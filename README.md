
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Giới thiệu bản thân</title>
    <style>
        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, sans-serif;
            background: linear-gradient(135deg, #e0f7fa, #fce4ec);
            color: #333;
        }

        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            overflow: hidden;
        }

        /* Ảnh trên cùng */
        .header {
            background: linear-gradient(135deg, #81d4fa, #f8bbd0);
            text-align: center;
            padding: 40px 20px;
        }

        .header img {
            width: 160px;
            height: 160px;
            object-fit: cover;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 15px;
        }

        .header h1 {
            margin: 10px 0 5px;
            color: #fff;
        }

        .header p {
            color: #fefefe;
            font-size: 18px;
        }

        .content {
            padding: 30px 40px;
        }

        .section {
            margin-bottom: 25px;
        }

        .section h2 {
            color: #4db6ac;
            border-left: 6px solid #4db6ac;
            padding-left: 10px;
            margin-bottom: 10px;
        }

        .section p, .section li {
            line-height: 1.7;
            font-size: 16px;
        }

        ul {
            padding-left: 20px;
        }

        .highlight {
            background: #f1f8e9;
            padding: 15px;
            border-radius: 10px;
        }

        .footer {
            text-align: center;
            padding: 15px;
            background: #e0f2f1;
            font-size: 14px;
            color: #555;
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Phần đầu có ảnh -->
    <div class="header">
        <img src="avatar.jpg" alt="Ảnh cá nhân">
        <h1>Xin chào! Mình là học sinh lớp 12B3</h1>
        <p>THPT Hòn Gai – Hạ Long</p>
    </div>

    <div class="content">
        <!-- Thông tin cá nhân -->
        <div class="section">
            <h2>📌 Thông tin cá nhân</h2>
            <p>
                Mình hiện <b>17 tuổi</b>, quê quán tại <b>Móng Cái</b>.  
                Hiện đang sinh sống và học tập tại <b>Hạ Long</b>, là học sinh lớp <b>12B3 – Trường THPT Hòn Gai</b>.
            </p>
        </div>

        <!-- Tính cách -->
        <div class="section">
            <h2>🌟 Tính cách</h2>
            <p class="highlight">
                Mình là người <b>vui vẻ, thân thiện, hiền lành</b> và luôn sống có <b>trách nhiệm</b>.  
                Mình dễ hòa đồng, biết lắng nghe và sẵn sàng giúp đỡ mọi người xung quanh.
            </p>
        </div>

        <!-- Sở thích -->
        <div class="section">
            <h2>🎯 Sở thích</h2>
            <ul>
                <li>Tham gia các hoạt động của trường và lớp</li>
                <li>Nghe nhạc để thư giãn tinh thần</li>
                <li>Đánh cầu lông để rèn luyện sức khỏe</li>
            </ul>
        </div>

        <!-- Lúc rảnh -->
        <div class="section">
            <h2>⏰ Lúc rảnh mình thường</h2>
            <ul>
                <li>Hát và nghe nhạc</li>
                <li>Lướt Facebook hoặc TikTok</li>
                <li>Xem phim để giải trí</li>
            </ul>
        </div>

        <!-- Gu âm nhạc -->
        <div class="section">
            <h2>🎵 Gu âm nhạc</h2>
            <p>
                Mình yêu thích các dòng nhạc <b>lofi & chill</b>, nhẹ nhàng – thư giãn.  
                Ngoài ra mình cũng thường nghe <b>nhạc Việt, nhạc Trung và US-UK</b>.
            </p>
        </div>

        <!-- Thế mạnh -->
        <div class="section">
            <h2>💪 Thế mạnh</h2>
            <ul>
                <li>Học ngoại ngữ tốt, đặc biệt là <b>tiếng Trung</b></li>
                <li>Làm việc nhóm khá ổn</li>
                <li>Có khả năng tự lập tốt</li>
            </ul>
        </div>

        <!-- Mục tiêu -->
        <div class="section">
            <h2>🚀 Mục tiêu trong tương lai</h2>
            <p class="highlight">
                Mục tiêu của mình là <b>hoàn thiện bản thân hơn mỗi ngày</b>,  
                có cơ hội <b>đi du học</b>, được <b>du lịch nhiều nơi</b> trong Việt Nam và các nước lân cận.  
                Trong tương lai, mình mong muốn trở thành <b>giáo viên ngoại ngữ</b>.
            </p>
        </div>
    </div>

    <div class="footer">
        © 2025 | Trang web giới thiệu bản thân
    </div>
</div>

</body>
</html>
