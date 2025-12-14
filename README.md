<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Halloween Party</title>
<style>
  body{
    margin:0;
    font-family:Arial;
    background:linear-gradient(#0b0b1f,#2c0b3d);
    color:#fff;
    overflow-x:hidden;
  }
  header{
    text-align:center;
    padding:60px 20px;
    background:url('https://images.unsplash.com/photo-1509551388413-e18d33b7c0d7?auto=format&fit=crop&w=1600&q=80') center/cover no-repeat;
  }
  header h1{
    font-size:48px;
    color:#ff9f1c;
    text-shadow:0 0 10px #ff6f00;
  }
  header p{ font-size:20px; }

  nav{
    background:#1a0628;
    padding:10px;
    text-align:center;
  }
  nav a{
    color:#ff9f1c;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
  }

  section{
    padding:40px 20px;
    max-width:1000px;
    margin:auto;
  }
  h2{
    color:#ff9f1c;
    text-align:center;
    margin-bottom:30px;
  }

  .cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
  }
  .card{
    background:#2b0b3f;
    padding:20px;
    border-radius:15px;
    box-shadow:0 0 15px rgba(255,159,28,0.4);
    text-align:center;
  }
  .card img{
    width:100%;
    border-radius:10px;
  }

  /* Form */
  form{
    background:#2b0b3f;
    padding:25px;
    border-radius:15px;
    max-width:500px;
    margin:30px auto;
    box-shadow:0 0 15px rgba(255,159,28,0.4);
  }
  input, textarea{
    width:100%;
    padding:10px;
    margin:10px 0;
    border-radius:8px;
    border:none;
  }
  button{
    background:#ff9f1c;
    color:#000;
    padding:10px 20px;
    border:none;
    border-radius:8px;
    font-weight:bold;
    cursor:pointer;
  }

  footer{
    text-align:center;
    padding:20px;
    background:#1a0628;
    margin-top:40px;
  }

  /* Hiệu ứng ma bay */
  .ghost{
    position:fixed;
    top:20%;
    left:-100px;
    width:80px;
    animation: ghostFly 15s linear infinite;
    opacity:0.8;
  }
  @keyframes ghostFly{
    0%{ left:-100px; }
    100%{ left:110%; }
  }
</style>
</head>
<body>

<img class="ghost" src="https://pngimg.com/uploads/ghost/gho">

<header>
  <h1>🎃 Halloween Party 🎃</h1>
  <p>Chào mừng bạn đến với lễ hội Halloween huyền bí!</p>
</header>

<nav>
  <a href="#home">Trang chủ</a>
  <a href="#event">Sự kiện</a>
  <a href="#gallery">Hình ảnh</a>
  <a href="#contact">Liên hệ</a>
</nav>

<section id="event">
  <h2>Sự kiện Halloween</h2>
  <div class="cards">
    <div class="card">
      <img src="https://tse4.mm.bing.net/th/id/OIP.y7jQRX_3k2Js4znfOEC3NwHaD4?cb=ucfimg2&ucfimg=1&rs=1&pid=ImgDetMain&o=7&rm=3">
      <h3>Hóa trang</h3>
      <p>Tham gia hóa trang rùng rợn và nhận quà.</p>
    </div>
    <div class="card">
      <img src="https://cdn.tgdd.vn/Files/2022/09/08/1466173/12-cach-trang-tri-banh-keo-halloween-dep-doc-dao-an-tuong-202209081633414057.jpg">
      <h3>Trick or Treat</h3>
      <p>Thu thập kẹo ngọt cùng bạn bè.</p>
    </div>
    <div class="card">
      <img src="https://dep.com.vn/wp-content/uploads/2020/07/ngoi-nha-ma-am-4.jpg">
      <h3>Nhà ma</h3>
      <p>Trải nghiệm cảm giác mạnh đầy hồi hộp.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Đăng ký tham gia</h2>
  <form>
    <input type="text" placeholder="Họ và tên">
    <input type="email" placeholder="Email">
    <textarea rows="4" placeholder="Lời nhắn..."></textarea>
    <button>Gửi đăng ký</button>
  </form>
</section>



</body>
</html>
