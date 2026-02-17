<!doctype html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Harmonia Music - Công ty Âm nhạc</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700;800&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header class="site-header">
      <div class="container nav-wrap">
        <a class="logo" href="#">Harmonia<span>Music</span></a>
        <nav>
          <ul class="nav-links">
            <li><a href="#ve-chung-toi">Về chúng tôi</a></li>
            <li><a href="#nghe-si">Nghệ sĩ</a></li>
            <li><a href="#dich-vu">Dịch vụ</a></li>
            <li><a href="#lien-he">Liên hệ</a></li>
          </ul>
        </nav>
        <button class="btn btn-outline">Đặt lịch tư vấn</button>
      </div>
    </header>

    <main>
      <section class="hero">
        <div class="container hero-grid">
          <div>
            <p class="tag">CÔNG TY SẢN XUẤT ÂM NHẠC</p>
            <h1>Nâng tầm nghệ sĩ Việt với âm thanh đẳng cấp quốc tế</h1>
            <p class="hero-copy">
              Harmonia Music đồng hành từ sáng tác, sản xuất, truyền thông đến tổ chức biểu diễn,
              giúp thương hiệu nghệ thuật của bạn chạm tới hàng triệu khán giả.
            </p>
            <div class="hero-actions">
              <button class="btn btn-primary">Khởi tạo dự án</button>
              <button class="btn btn-ghost">Xem hồ sơ năng lực</button>
            </div>
          </div>
          <div class="hero-card">
            <h2>03 Studio chuẩn phòng thu</h2>
            <ul>
              <li>Phòng thu vocal cách âm chuyên sâu</li>
              <li>Hệ thống mixing & mastering hiện đại</li>
              <li>Đội ngũ producer và kỹ sư âm thanh giàu kinh nghiệm</li>
            </ul>
          </div>
        </div>
      </section>

      <section id="ve-chung-toi" class="section">
        <div class="container">
          <h2>Về Harmonia Music</h2>
          <p>
            Thành lập từ năm 2018, chúng tôi là đơn vị sáng tạo âm nhạc tích hợp, kết nối nghệ sĩ,
            nhãn hàng và người yêu nhạc qua các sản phẩm chất lượng cao.
          </p>
        </div>
      </section>

      <section id="nghe-si" class="section section-alt">
        <div class="container">
          <h2>Nghệ sĩ tiêu biểu</h2>
          <div class="cards">
            <article class="card">
              <h3>Luna V</h3>
              <p>Pop / R&B · 12M lượt nghe</p>
            </article>
            <article class="card">
              <h3>RhyMatic</h3>
              <p>Hip-hop / Rap · 8M lượt nghe</p>
            </article>
            <article class="card">
              <h3>Nguyên Khải</h3>
              <p>Ballad / Acoustic · 5M lượt nghe</p>
            </article>
          </div>
        </div>
      </section>

      <section id="dich-vu" class="section">
        <div class="container">
          <h2>Dịch vụ</h2>
          <div class="cards">
            <article class="card">
              <h3>Sản xuất âm nhạc</h3>
              <p>Thu âm, phối khí, mixing và mastering trọn gói.</p>
            </article>
            <article class="card">
              <h3>Phát hành & phân phối</h3>
              <p>Đưa nhạc lên Spotify, Apple Music, YouTube và TikTok.</p>
            </article>
            <article class="card">
              <h3>Booking & sự kiện</h3>
              <p>Tổ chức mini show, concert và activation cho thương hiệu.</p>
            </article>
          </div>
        </div>
      </section>

      <section id="lien-he" class="section section-alt">
        <div class="container contact">
          <div>
            <h2>Liên hệ hợp tác</h2>
            <p>Email: hello@harmoniamusic.vn</p>
            <p>Hotline: 0909 123 456</p>
          </div>
          <form class="contact-form">
            <label>
              Họ và tên
              <input type="text" placeholder="Nhập họ tên" />
            </label>
            <label>
              Email
              <input type="email" placeholder="email@domain.com" />
            </label>
            <label>
              Nhu cầu
              <textarea rows="4" placeholder="Mô tả dự án của bạn"></textarea>
            </label>
            <button type="button" class="btn btn-primary">Gửi thông tin</button>
          </form>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <div class="container">
        <p>© 2026 Harmonia Music. All rights reserved.</p>
      </div>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
