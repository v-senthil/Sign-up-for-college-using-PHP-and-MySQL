# College Sign-Up Form (PHP + MySQL)

A registration form for a college sign-up flow, backed by raw PHP and MySQL.

## How it works
- `form.php` / `form1.php` render the sign-up form (name, address, email, phone, DOB, age, gender, department, college, password).
- On submit, `form.php` checks the password/confirm-password match and inserts the row via `mysqli_connect`.
- `admin.php` / `show.php` / `show1.php` list submitted entries; `edit.php` and `delete*.php` handle updates and removal.

## Use
1. Serve the files with a PHP + MySQL stack (e.g. XAMPP).
2. Create a `test` database matching the columns the scripts insert into.
3. Open `form.php` (or `home.html`) in the browser.

College project, 2019–2021.
