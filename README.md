# Laravel 6 Appointments System with Roles and Permissions Management

Simple project to manage appointments for companies like beauty salon, medical clinic or car repair shop. You can manage your Services, Employees, Clients and Appointments, viewing them in a calendar.

![Laravel Appointments calendar](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-appointments-calendar.png)

![Laravel Appointments form](https://laraveldaily.com/wp-content/uploads/2019/09/laravel-appointments-form.png)

System is mostly generated with [QuickAdminPanel](https://2019.quickadminpanel.com), with some small tweaks afterwards.

Other assets used:

- [CoreUI Free theme](https://coreui.io/demo/#main.html) (Bootstrap 4)
- [FullCalendar library](https://fullcalendar.io/) (version 3)

## How to use

- Clone the repository with `git clone`
- Create database by `mysql -u root -p`
- Copy `.env.example` file to `.env` and configure database credentials there
- Run `php artisan key:generate`
- Run `php artisan config:cache`
- Run `composer update`
- Run `php artisan migrate --seed` (it has some seeded data for your testing)
- That's it: launch the main URL. 
- You can login to admin panel with default credentials;
    - `admin@admin.com` - `password`
    - `user@user.com` - `password`
    - `registrar@registrar.com` - `password`

## License

Basically, feel free to use and re-use any way you want.

## Credit

This project is modified from original source by [LaravelDaily](https://github.com/LaravelDaily).
