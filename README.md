<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>安全第一むじなグループ｜荒野行動アカウント販売・買取</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", system-ui, sans-serif;
      background: #fdfdfd;
      color: #2c3e50;
    }

    /* ゴージャスな金色グラデーション背景 */
    .gold-bg {
      background: linear-gradient(135deg, #f7e9c5, #e8c77b, #d9b45d);
    }

    header {
      position: fixed;
      top: 0;
      left: 0;
      right: 0;
      height: 70px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 40px;
      background: rgba(255,255,255,0.85);
      backdrop-filter: blur(10px);
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
      z-index: 100;
    }

    .logo {
      font-weight: 700;
      font-size: 18px;
      letter-spacing: 0.12em;
      color: #b8860b;
    }

    nav a {
      margin-left: 24px;
      text-decoration: none;
      color: #2c3e50;
      font-size: 14px;
      font-weight: 600;
    }

    nav a:hover {
      color: #b8860b;
    }

    /* ゴージャスなヒーロー背景 */
    .hero {
      margin-top: 70px;
      min-height: 75vh;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }

    .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background-image: url("gold-hero.jpg"); /* ←豪華な背景画像に差し替え */
      background-size: cover;
      background-position: center;
      filter: brightness(0.65) saturate(1.2);
    }

    .hero-title {
      font-size: 42px;
      letter-spacing: 0.15em;
      margin-bottom: 12px;
      position: relative;
      z-index: 1;
      text-shadow: 0 0 12px rgba(0,0,0,0.4);
    }

    .hero-sub {
      font-size: 18px;
      opacity: 0.95;
      margin-bottom: 32px;
      position: relative;
      z-index: 1;
      text-shadow: 0 0 10px rgba(0,0,0,0.4);
    }

    .hero-cta {
      position: relative;
      z-index: 1;
      display: inline-block;
      padding: 14px 36px;
      border-radius: 999px;
      background: rgba(255,255,255,0.9);
      color: #b8860b;
      font-weight: 700;
      text-decoration: none;
      font-size: 15px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.25);
    }

    main {
      padding: 60px 8vw 80px;
      background: #fff8e6; /* 柔らかい金色の背景 */
    }

    .section-title {
      text-align: center;
      font-size: 24px;
      letter-spacing: 0.15em;
      margin-bottom: 32px;
      color: #b8860b;
      font-weight: 700;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 24px;
      margin-bottom: 60px;
    }

    .card {
      background: #ffffff;
      border-radius: 16px;
      overflow: hidden;
      box-shadow: 0 6px 20px rgba(0,0,0,0.12);
      border: 2px solid #f0d89c;
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-body {
      padding: 18px 20px;
    }

    .card-label {
      font-size: 12px;
      color: #b8860b;
      letter-spacing: 0.15em;
      margin-bottom: 6px;
      font-weight: 700;
    }

    .card-title {
      font-size: 17px;
      margin-bottom: 10px;
      font-weight: 600;
    }

    .news-list {
      max-width: 720px;
      margin: 0 auto 60px;
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.12);
      padding: 20px 24px;
      border: 2px solid #f0d89c;
    }

    .news-item {
      padding: 10px 0;
      border-bottom: 1px solid #f0e3c0;
      font-size: 14px;
    }

    .video-placeholder {
      max-width: 720px;
      margin: 0 auto 60px;
      padding: 24px;
      border-radius: 16px;
      border: 2px dashed #d9b45d;
      background: #fff9e9;
      text-align: center;
      font-size: 14px;
      color: #6b7c88;
    }

    .cta-bottom {
      max-width: 720px;
      margin: 0 auto;
      text-align: center;
      padding: 40px 24px;
      border-radius: 20px;
      color: #fff;
      position: relative;
      overflow: hidden;
    }

    .cta-bottom::before {
      content: "";
      position: absolute;
      inset: 0;
      background-image: url("gold-cta.jpg"); /* ←豪華な背景画像に差し替え */
      background-size: cover;
      background-position: center;
      filter: brightness(0.7);
    }

    .cta-inner {
      position: relative;
      z-index: 1;
    }

    footer {
      margin-top: 40px;
      padding: 20px 8vw 30px;
      font-size: 12px;
      color: #6b7c88;
      text-align: center;
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">安全第一むじなグループ</div>
    <nav>
      <a href="#service">Service</a>
      <a href="#news">News</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero gold-bg">
    <div>
      <div class="hero-title">安全第一むじなグループ</div>
      <div class="hero-sub">荒野行動アカウント販売・買取サービス</div>
      <a href="#service" class="hero-cta">サービスを見る</a>
    </div>
  </section>

  <main>
    <h2 class="section-title" id="service">サービス内容</h2>

    <div class="cards">
      <article class="card">
        <img src="sell.jpg" alt="">
        <div class="card-body">
          <div class="card-label">SELL</div>
          <div class="card-title">アカウント販売</div>
          <p>安全な手順で荒野行動アカウントを販売できます。詐欺ゼロを継続中。</p>
        </div>
      </article>

      <article class="card">
        <img src="buy.jpg" alt="">
        <div class="card-body">
          <div class="card-label">BUY</div>
          <div class="card-title">アカウント買取</div>
          <p>高ランク・限定アイテム所持アカウントを適正価格で買取します。</p>
        </div>
      </article>

      <article class="card">
        <img src="safe.jpg" alt="">
        <div class="card-body">
          <div class="card-label">SAFETY</div>
          <div class="card-title">安全な取引</div>
          <p>本人確認・情報確認を徹底し、トラブルのない取引を実現しています。</p>
        </div>
      </article>
    </div>

    <h2 class="section-title" id="news">NEWS</h2>
    <div class="news-list">
      <div class="news-item">2024.04.15 安全取引ガイドを更新しました。</div>
      <div class="news-item">2024.03.28 新しい販売ラインナップを追加しました。</div>
      <div class="news-item">2024.03.10 取引トラブルゼロを継続達成。</div>
    </div>

    <div class="video-placeholder">
      ここに動画を追加できます（YouTube / mp4）
    </div>

    <div class="cta-bottom" id="contact">
      <div class="cta-inner">
        <h3>お問い合わせ</h3>
        <p>販売・買取の相談はこちらから</p>
        <a href="mailto:contact@example.com"
           style="background:#fff; padding:10px 28px; border-radius:999px; color:#b8860b; text-decoration:none;">
          メールで問い合わせる
        </a>
      </div>
    </div>
  </main>

  <footer>
    &copy; 安全第一むじなグループ
  </footer>
</body>
</html>
