
## Book Review 📚
A simple and clean Laravel application for managing and reviewing books.
Users can browse, review, and rate books easily.


## Features ✨

- [User registration and login.
- [Book listing and detailed view.
- [Add new books.
- [Add and edit book reviews
- [Rating system for books
- [Admin panel to manage books and reviews.
- [Responsive and user-friendly design


## Tech Stack 🛠
- [Backend: Laravel

- [Database: MySQL

- [Frontend: Blade Templates, Bootstrap

- [Authentication: Laravel Breeze (or built-in auth scaffolding)

## Installation 🚀
Follow these steps to run the project locally:</br>
# 1. Clone the repository
<pre> ```bash 
    git clone https://github.com/palashkumer/book-review.git
 ```</pre>

# 2. Navigate into the project directory
cd book-review

# 3. Install PHP dependencies
composer install

# 4. Install JavaScript dependencies (optional if using frontend assets)
npm install && npm run dev

# 5. Create a copy of .env file
cp .env.example .env

# 6. Generate the application key
php artisan key:generate

# 7. Set up your database credentials in the .env file

# 8. Run migrations to create tables
php artisan migrate

# 9. Start the development server
php artisan serve

