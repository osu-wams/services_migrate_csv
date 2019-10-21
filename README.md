# Services Migrate CSV
This is a Drupal 8 module to provide a CSV migration of services.

## Installation
Use composer to add this module to a Drupal site.
```shell script
composer require --dev osu-wams/services_migrate_csv
```
Either using Drush or the UI install the this module and it's dependencies
```shell script
drush en services_migrate_csv
```

## Usage
### Drush
```shell script
drush  migrate:import osu_services_csv
```
To limit the the amount processed 
```shell script
drush migrate:import osu_services_csv --limit=10
```
### Drupal UI
To be able to run the migrations from the web interface you will need to enable the module Migrate Drupal UI.
