# Laravel 10 DMS

## Install breeze package for Auth
composer require laravel/breeze --dev
php artisan breeze:install 

## Create database and Tables
php artisan migrate

## Create New migration file
php artisan make:migration

Description:
  Create a new migration file

Usage:
  make:migration [options] [--] <name>

Arguments:
  name                   The name of the migration

Options:
      --create[=CREATE]  The table to be created
      --table[=TABLE]    The table to migrate
      --path[=PATH]      The location where the migration file should be created
      --realpath         Indicate any provided migration file paths are pre-resolved absolute paths
      --fullpath         Output the full path of the migration (Deprecated)
  -h, --help             Display help for the given command. When no command is given display help for the list command
  -q, --quiet            Do not output any message
  -V, --version          Display this application version
      --ansi|--no-ansi   Force (or disable --no-ansi) ANSI output
  -n, --no-interaction   Do not ask any interactive question
      --env[=ENV]        The environment the command should run under
  -v|vv|vvv, --verbose   Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug