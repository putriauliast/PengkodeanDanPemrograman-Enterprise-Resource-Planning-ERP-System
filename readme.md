## PENJELASAN APLIKASI
Sales ERP is a Modern and responsive small business management system. Developed by PHP and Laravel, JQery, Ajax, Bootstrap. It is Designed and Develop for thinking shop, small business, company and any types of business. Here has accounting,management, invoice user and Data analysis.

## FITUR APLIKASI
1. Invoice Management
2. Category
3. Product Management
4. Tax Management
5. Unit
6. Supplier
7. Purchase
8. Customer Update


## DATABASE APLIKASI
![alt text](https://github.com/putriauliast/Sistem-Informasi-Akuntansi---Enterprise-Resource-Planning-ERP-System/blob/main/Screenshot%202023-12-14%20095709.png?raw=true)


## RELASI DATABASE APLIKASI
![alt text](https://github.com/putriauliast/Sistem-Informasi-Akuntansi---Enterprise-Resource-Planning-ERP-System/blob/main/Screenshot%202023-12-14%20102031.png?raw=true)


## TAMPILAN APLIKASI

![saleserp](https://user-images.githubusercontent.com/25568503/65633659-6b83d580-dffe-11e9-90f4-a1083e094165.png)

![erp2](https://user-images.githubusercontent.com/25568503/65633750-9e2dce00-dffe-11e9-9653-6a65086e284e.png)

![erp23](https://user-images.githubusercontent.com/25568503/65633890-e816b400-dffe-11e9-8442-fb977552d5e6.png)

![admin](https://user-images.githubusercontent.com/25568503/65634018-28763200-dfff-11e9-967b-b6ec401147df.png)

![login](https://user-images.githubusercontent.com/25568503/65634125-5fe4de80-dfff-11e9-9639-18255ce948b1.png)


## FLOWCHART SISTEM
Flowchart Login
![alt text](https://github.com/putriauliast/Sistem-Informasi-Akuntansi---Enterprise-Resource-Planning-ERP-System/blob/main/flowchart%20login%201.drawio.png?raw=true)

Flowchart Menu Utama
![alt text](https://github.com/putriauliast/Sistem-Informasi-Akuntansi---Enterprise-Resource-Planning-ERP-System/blob/main/flowchart%20halaman%20utama.drawio.png?raw=true)

Flowchart Logout
![alt text](https://github.com/putriauliast/Sistem-Informasi-Akuntansi---Enterprise-Resource-Planning-ERP-System/blob/main/flowchart%20logout.drawio.png?raw=true)

## INSTALASI DAN PENJELASAN STEP

Follow these steps to set up the Sales ERP Laravel project on your local machine:
**Requirements:**
Composer, PHP version >5 and <8.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/naufalrandika/ERPLaravel.git

2. **Navigate to the Project Directory:**
   ```bash
   cd ERPLaravel

3. **Copy .env:**
   ```bash
   cp .env.example .env

4. **Install Dependencies:**
   ```bash
   composer install

5. **Make Database:**
   Open on browser ***https://localhost/phpmyadmin***
   , Create New Database dan Name it
   ```laravel
   laravel

6. **Run Migrations:**
   ```bash
   php artisan migrate:fresh

7. **Seed the Database:**
   ```bash
   php artisan db:seed

8. **Generate Application Key:**
   ```bash
   php artisan key:generate

9. **Start the Development Server:**
   ```bash
   php artisan serve



