<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>ATOZ Zone — Online Store</title>
  <style>
    :root{
      --primary:#1e88e5;
      --bg:#f6f8fb;
      --card:#ffffff;
      --text:#17212b;
      --muted:#6b7280;
    }
    *{box-sizing:border-box;font-family:Inter,Arial,sans-serif;}
    body{margin:0;background:var(--bg);color:var(--text);}
    header{
      background:linear-gradient(90deg,var(--primary),#2196f3);
      color:#fff;
      padding:12px 18px;
      display:flex;
      align-items:center;
      justify-content:space-between;
    }
    .brand{font-size:20px;font-weight:bold;}
    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
      gap:18px;
      padding:20px;
    }
    .card{
      background:var(--card);
      border-radius:10px;
      box-shadow:0 2px 8px rgba(0,0,0,0.08);
      overflow:hidden;
      text-align:center;
      transition:transform .2s;
    }
    .card:hover{transform:scale(1.03);}
    .card img{width:100%;height:160px;object-fit:cover;}
    .card h3{margin:10px 0 5px;}
    .card p{margin:0 0 10px;color:var(--muted);}
    .btn{
      background:var(--primary);
      color:#fff;
      border:none;
      padding:8px 14px;
      border-radius:6px;
      cursor:pointer;
    }
  </style>
</head>
<body>
  <header>
    <div class="brand">🛍️ ATOZ Zone</div>
  </header>
  <main>
    <div class="grid">
      <div class="card">
        <img src="https://via.placeholder.com/300x200" alt="Product 1">
        <h3>Smart Watch</h3>
        <p>৳1200</p>
        <button class="btn">Add to Cart</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x200" alt="Product 2">
        <h3>Bluetooth Speaker</h3>
        <p>৳950</p>
        <button class="btn">Add to Cart</button>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/300x200" alt="Product 3">
        <h3>Wireless Earbuds</h3>
        <p>৳1150</p>
        <button class="btn">Add to Cart</button>
      </div>
    </div>
  </main>
</body>
</html>
