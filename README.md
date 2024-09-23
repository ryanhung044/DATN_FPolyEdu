# FPOLY EDU

## Description
Đây là dự án tốt nghiệp với đề tài `quản lý sinh viên`, chủ yếu với laravel và react, được xây dựng bởi `Hưng`, `Hải`, `Hoàng Anh`, `Lộc`, `An`, `Huy`, `Trung`

## Technologies Used
- Backend: Laravel 
- Frontend: React
- Database: MySQL 
- Other tools: Composer, npm

---

## Setup Instructions

### Prerequisites
Make sure you have the following installed:
- PHP >= 8.0
- Composer
- Node.js (npm)
- MySQL 

### 1. Backend Setup (Laravel)
1. Clone the repository:
    ```bash
    git clone <git remote add origin https://github.com/ryanhung044/DATN_FPolyEdu.git>
    cd <repository-folder>/BE
    ```

2. Create `.env` file:
    Copy `.env.example` to `.env`:
    ```bash
    cp .env.example .env
    ```

3. Install Composer dependencies:
    ```bash
    composer install
    ```

4. Generate the application key:
    ```bash
    php artisan key:generate
    ```

5. Set up your database:
    In the `.env` file, set your database credentials:
    ```env
    DB_CONNECTION=mysql
    DB_HOST=sql12.freemysqlhosting.net
    DB_PORT=3306
    DB_DATABASE=sql12733018
    DB_USERNAME=sql12733018
    DB_PASSWORD=IigiK3x4Wf
    ```

6. Run database migrations:
    ```bash
    php artisan migrate
    ```

7. Run the Laravel development server:
    ```bash
    php artisan serve
    ```

   The Laravel server should now be running at `http://127.0.0.1:8000`.

---

### 2. Frontend Setup (React)
1. Navigate to the frontend folder:
    ```bash
    cd ../FE
    ```

2. Install npm dependencies:
    ```bash
    npm install
    ```

3. Run the React development server:
    ```bash
    npm run dev
    ```

    The React frontend should now be running at `http://localhost:3000`.

---

## Additional Information

### Running Tests
To run tests for Laravel, you can use:
```bash
php artisan test
