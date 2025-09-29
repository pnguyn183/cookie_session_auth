Cookie Session Auth
Giới thiệu

Dự án này sử dụng session + cookie để xác thực và lưu trạng thái người dùng trong NodeJS. Người dùng có thể đăng ký, đăng nhập, truy cập profile, đăng xuất và quản lý session trong MongoDB.

Cách chạy

Cài dependency:

npm install


Chạy project:

node cookie_auth.js

Hướng dẫn test

Register → tạo user mới, kiểm tra trong database.

Login → đăng nhập, server tạo session và trả cookie.

Profile → truy cập thông tin user bằng session cookie.

Logout → đăng xuất, cookie/session bị xóa.

Kiểm tra DB → xác minh user và session trong MongoDB.

Kết quả test:
### 1. Register
![Register](img/register.png)

### 2. Login
![Login](img/login.png)

### 3. Login Session Cookie
![Login Session Cookie](img/loginsessioncookie.png)

### 4. Profile
![Profile](img/profile.png)

### 5. Logout
![Logout](img/logout.png)

### 6. Logout Session Cookie
![Logout Session Cookie](img/logoutsessioncookie.png)

### 7. User trong MongoDB
![User MongoDB](img/usermongodb.png)