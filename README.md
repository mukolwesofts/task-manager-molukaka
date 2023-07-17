# Task Management System

A simple task management app

Basic Functionality

* Create/Edit/Delete Projects
* Create/Edit/View Tasks per project
* Reorder priority of the tasks


## Getting Started

These instructions will cover usage information and for the docker container


Clone the project repository by running the command below if you use SSH


```bash
git clone git@github.com:codeaamirkalimi/Task-Management-System-Laravel.git
```

After cloning, run:

```bash
cd task-manager-molukaka && ./vendor/bin/sail up
```

In case you are having port issues after running the above command please update the following port variables in your **.env** file

```bash
APP_PORT=8080
FORWARD_DB_PORT=33066
```

If you are not using docker, after cloning the app, run:

```bash
composer install
```

```bash
npm install
```

Duplicate `.env.example` and rename it .env

Then, run:

```bash
php artisan key:generate
```

Create your database, update the name in the `.env` file, run:
```bash
php artisan migrate
```

And finally, start the application:


```bash
php artisan serve
```

and visit http://localhost:8000 to see the application in action.


## Built With

* [Laravel](https://laravel.com/) - The PHP Framework For Web Artisans
* [VueJs](https://vuejs.org/) - A JavaScript library for building user interfaces
* [TailwindCss](https://tailwindcss.com/) - A CSS Frameworks that's utility-first.

## License

[MIT](https://choosealicense.com/licenses/mit/)
