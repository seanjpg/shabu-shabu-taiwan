<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>頂級鍋物餐廳</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Noto Serif TC", "Times New Roman", serif;
      background: #0b0b0b;
      color: #f5f0e8;
      letter-spacing: 1px;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      padding: 24px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(0, 0, 0, 0.65);
      z-index: 10;
    }

    .logo {
      font-size: 26px;
      letter-spacing: 4px;
      color: #d6b36a;
    }

    nav a {
      color: #f5f0e8;
      text-decoration: none;
      margin-left: 32px;
      font-size: 14px;
    }

    nav a:hover {
      color: #d6b36a;
    }

    .hero {
      height: 100vh;
      background:
        linear-gradient(rgba(0,0,0,.45), rgba(0,0,0,.75)),
        url("your-hero-image.jpg") center/cover no-repeat;
      display: flex;
      align-items: center;
      padding: 0 10%;
    }

    .hero-content {
      max-width: 620px;
    }

    .hero h1 {
      font-size: 56px;
      font-weight: 400;
      line-height: 1.4;
      margin-bottom: 24px;
      color: #fff;
    }

    .hero p {
      font-size: 18px;
      line-height: 2;
      color: #ddd;
      margin-bottom: 36px;
    }

    .btn {
      display: inline-block;
      padding: 14px 36px;
      border: 1px solid #d6b36a;
      color: #d6b36a;
      text-decoration: none;
      transition: .3s;
    }

    .btn:hover {
      background: #d6b36a;
      color: #111;
    }

    section {
      padding: 100px 10%;
    }

    .section-title {
      font-size: 34px;
      font-weight: 400;
      color: #d6b36a;
      margin-bottom: 40px;
      text-align: center;
    }

    .concept {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 28px;
      text-align: center;
    }

    .concept-card {
      border: 1px solid rgba(214,179,106,.35);
      padding: 40px 24px;
      background: rgba(255,255,255,.03);
    }

    .concept-card h3 {
      color: #d6b36a;
      margin-bottom: 16px;
      font-size: 22px;
      font-weight: 400;
    }

    .concept-card p {
      font-size: 15px;
      line-height: 1.8;
      color: #ccc;
    }

    .info {
      background: #151515;
      text-align: center;
    }

    .info p {
      line-height: 2;
      color: #ddd;
      font-size: 16px;
    }

    footer {
      padding: 40px 10%;
      text-align: center;
      color: #888;
      font-size: 13px;
      background: #050505;
    }

    @media (max-width: 768px) {
      header {
        flex-direction: column;
        gap: 16px;
      }

      nav a {
        margin: 0 10px;
      }

      .hero h1 {
        font-size: 36px;
      }

      .concept {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">SHABU</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">News</a>
      <a href="#">Menu</a>
      <a href="#">Location</a>
      <a href="#">About</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>四季美學<br>合而為一</h1>
      <p>
        嚴選新鮮食材，忠於原味料理，  
        以細膩服務與沉穩空間，打造一場高級鍋物體驗。
      </p>
      <a href="#" class="btn">線上訂位</a>
    </div>
  </section>

  <section>
    <h2 class="section-title">Brand Concept</h2>

    <div class="concept">
      <div class="concept-card">
        <h3>新鮮</h3>
        <p>讓食材的原味被看見，回到料理最純粹的狀態。</p>
      </div>

      <div class="concept-card">
        <h3>堅持</h3>
        <p>嚴選肉品、海鮮與湯底，呈現細緻而完整的餐桌層次。</p>
      </div>

      <div class="concept-card">
        <h3>空間</h3>
        <p>以低調奢華的設計語彙，營造安靜而舒適的用餐環境。</p>
      </div>

      <div class="concept-card">
        <h3>服務</h3>
        <p>從入席到餐後，每一個細節皆以溫度款待來訪賓客。</p>
      </div>
    </div>
  </section>

  <section class="info">
    <h2 class="section-title">Location</h2>
    <p>地址：台北市信義區松仁路 28 號 4 樓</p>
    <p>電話：02-2723-9222</p>
    <p>營業時間：週一至週五 12:00–14:30 / 17:30–22:00</p>
    <p>週六、週日 12:00–22:00</p>
    <br />
    <a href="#" class="btn">Call Us</a>
  </section>

  <footer>
    © 2026 SHABU Restaurant. All Rights Reserved.
  </footer>

</body>
</html>
