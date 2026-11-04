# HourFlow

HourFlow is a web-based time tracking and work-hours management application built with Laravel and Vue.js.

This application aims to help users manage their work schedules, record daily working hours, track overtime, and manage time off earned through additional work.

## Tech Stack

- **Backend:** Laravel 12 (PHP)
- **Frontend:** Vue 3 with TypeScript

## Features (Planned)


## Requirements

- PHP 8.2 or higher
- Composer
- Node.js and npm
- MySQL or MariaDB

## Local Installation

**1. Clone the repository**

`git clone https://github.com/rvs1212/hourFlow.git`

`cd hourFlow`

**2. Install dependencies**

`composer install`

`npm install`

**3. Configure the environment**

`cp .env.example .env`

`php artisan key:generate`

Update the database configuration in `.env` with your local database credentials.

**4. Run database migrations**

`php artisan migrate`

**5. Start the application**

For Laravel Herd users, ensure the site is linked in Herd, then run:

`npm run dev`

Alternatively, use:

`composer run dev`

## Development

- `npm run dev` — Start the Vite development server
- `npm run build` — Generate production frontend assets
- `php artisan test` — Run Laravel tests


