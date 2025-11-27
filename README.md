<!doctype html>
<html lang="bn">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Profile Links</title>
<style>
  :root{--bg:#eef1f6;--card:#fff;--accent:#1155ff;--muted:#60708a}
  body{font-family:system-ui,-apple-system,Segoe UI,Roboto,"Noto Sans",sans-serif;
       margin:0;background:var(--bg);color:#0b1a2b;display:flex;align-items:flex-start;justify-content:center;padding:24px;}
  .wrap{width:100%;max-width:520px}
  .profile{background:var(--card);border-radius:14px;padding:22px;text-align:center;box-shadow:0 6px 22px rgba(6,30,63,0.08)}
  .avatar{width:92px;height:92px;border-radius:50%;overflow:hidden;margin:0 auto 12px;border:4px solid rgba(17,85,255,0.08)}
  .avatar img{width:100%;height:100%;object-fit:cover;display:block}
  h1{margin:6px 0 2px;font-size:20px;color:var(--accent)}
  p.bio{margin:0 0 14px;color:var(--muted);font-size:14px}
  .icons{display:flex;gap:12px;justify-content:center;margin-bottom:12px}
  .icons a{width:36px;height:36px;border-radius:8px;background:#f3f7ff;display:inline-flex;align-items:center;justify-content:center;text-decoration:none}
  .card-list{margin-top:14px;display:grid;gap:12px}
  .btn{background:var(--card);padding:14px;border-radius:14px;display:flex;align-items:center;justify-content:space-between;text-decoration:none;color:var(--accent);box-shadow:0 3px 12px rgba(8,30,63,0.04)}
  .btn .left{display:flex;align-items:center;gap:12px}
  .thumb{width:56px;height:36px;border-radius:8px;overflow:hidden;background:#0002;display:inline-block}
  .btn small{display:block;color:var(--muted);font-size:12px}
  footer{margin-top:14px;text-align:center;color:var(--muted);font-size:12px}
  @media (max-width:420px){.wrap{padding:0 6px}}
</style>
</head>
<body>
  <div class="wrap">
    <div class="profile">
      <div class="avatar"><img src="https://via.placeholder.com/300x300.png?text=Shafi" alt="avatar"></div>
      <h1>xshafi_1</h1>
      <p class="bio">Alhamdulillah for everything ❤️🌸</p>
      <div class="icons">
        <a href="#" title="YouTube">▶</a>
        <a href="#" title="TikTok">♪</a>
        <a href="#" title="Facebook">f</a>
        <a href="#" title="Instagram">ⓘ</a>
        <a href="#" title="X">X</a>
        <a href="#" title="WhatsApp">✆</a>
      </div>
      <div class="card-list">
        <a class="btn" href="https://youtube.com" target="_blank">
          <div class="left"><div class="thumb"><img src="https://via.placeholder.com/200x120.png?text=YT" style="width:100%;height:100%;object-fit:cover"></div>
          <div><strong>YouTube</strong><small>My channel</small></div></div>
          <div>›</div>
        </a>

        <a class="btn" href="https://www.tiktok.com" target="_blank">
          <div class="left"><div class="thumb"><img src="https://via.placeholder.com/200x120.png?text=TT" style="width:100%;height:100%;object-fit:cover"></div>
          <div><strong>TikTok</strong><small>Follow me</small></div></div>
          <div>›</div>
        </a>

        <a class="btn" href="https://facebook.com" target="_blank">
          <div class="left"><div class="thumb"><img src="https://via.placeholder.com/200x120.png?text=FB" style="width:100%;height:100%;object-fit:cover"></div>
          <div><strong>Facebook</strong><small>Page</small></div></div>
          <div>›</div>
        </a>

        <a class="btn" href="https://instagram.com" target="_blank">
          <div class="left"><div class="thumb"><img src="https://via.placeholder.com/200x120.png?text=IG" style="width:100%;height:100%;object-fit:cover"></div>
          <div><strong>Instagram</strong><small>Profile</small></div></div>
          <div>›</div>
        </a>
      </div>
      <footer>Made with ❤️ — Example</footer>
    </div>
  </div>
</body>
</html>
