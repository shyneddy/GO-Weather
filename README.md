<h1>CODE TEST: GO-WEATHER</h1>
<p><strong>Công nghệ sử dụng:</strong> Laravel 10.x</p>
<h2>Hướng dẫn chạy code trên localhost:</h2>
<ol>
    <li><strong>B1:</strong> Clone source code về máy.</li>
    <li><strong>B2:</strong> Tạo file <code>.env</code> và dán nội dung đã comment ở file <code>.env.example</code>.</li>
    <li><strong>B3:</strong> Chạy lệnh: <code>composer install</code> và <code>npm install</code> để cài đặt các phụ thuộc.</li>
    <li><strong>B4:</strong> Chạy lệnh: <code>php artisan migrate</code> để tạo database.</li>
    <li><strong>B5:</strong> Chạy lệnh: <code>php artisan serve</code> để khởi động máy chủ.</li>
    <li><strong>B6:</strong> Chạy lệnh: <code>npm run dev</code> để xây dựng, biên dịch frontend.</li>
    <li><strong>B7:</strong> Truy cập <code>http://127.0.0.1:8000</code> và sử dụng trang web.</li>
</ol>

<h2>Tính năng tự động gửi dự báo thời tiết hàng ngày:</h2>
<p>
    Để sử dụng tính năng này, chạy lệnh: <code>php artisan schedule:work</code> để chạy trình lập lịch.
</p>
<p>
    <strong>Lưu ý:</strong> Có thể chỉnh thời gian gửi tin nhắn cho người dùng trong hàm <code>schedule</code> của file <code>app\console\kernel.php</code>.
</p>
