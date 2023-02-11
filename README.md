# laravue-weather-app
Weather app using Laravel as Backend and VueJS as Frontend

# Backend Requirements
```
- PHP >= 8.0
- [composer](https://getcomposer.org/)
```
# Setup backend
```bash
cd larave-backend
composer install
cp .env .env-example
php artisan key:generate
php artisan serve
```
You should be able to access the backend at [localhost:8000](localhost:8000)

# Frontend Requirements
- Node > 16.0

# Setup Frontend
```bash
cd vue-frontend
npm install
npm run dev
```
You should be able to access the frontend that will be outputed on your terminal
