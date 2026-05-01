<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kolam Pancing Pak Dhe</title>

<link rel="icon" href="https://i.ibb.co/rG6SdNr6/file-00000000f2c072089b3e11e29a07a7c9.png">

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f4f4f4;
}

/* HEADER */
header{
    background:
    linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
    url('https://i.ibb.co/qbdmr0Y/IMG-20260501-075601.jpg');
    background-size:cover;
    background-position:top;
    padding:100px 20px;
    text-align:center;
    color:white;
}

.logo{
    width:180px;
    margin-bottom:15px;
}

.container{
    width:90%;
    max-width:900px;
    margin:auto;
    margin-top:-40px;
}

/* CARD */
.card{
    background:white;
    padding:20px;
    margin:20px 0;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
}

h2{
    color:#008060;
}

/* GALERI */
.gallery{
    display:grid;
    gap:15px;
}

.gallery img{
    width:100%;
    border-radius:10px;
    object-fit:cover;
    max-height:350px;
}

/* BUTTON */
.btn{
    display:inline-block;
    padding:12px 20px;
    border-radius:8px;
    text-decoration:none;
    color:white;
    margin:5px;
}

.wa{
    background:#25D366;
}

.tiktok{
    background:black;
}

/* FLOAT WA */
.wa-float{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    color:white;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    font-size:22px;
}

iframe{
    width:100%;
    border:none;
    border-radius:10px;
}

footer{
    text-align:center;
    padding:20px;
    color:#666;
}
</style>
</head>
<body>

<header>
    <img 
        src="https://i.ibb.co/rG6SdNr6/file-00000000f2c072089b3e11e29a07a7c9.png" 
        class="logo"
        alt="Logo Kolam Pancing Pak Dhe">

    <h1>🎣 Kolam Pancing Pak Dhe</h1>
    <p>Tempat Mancing Nyaman & Seru</p>
</header>

<div class="container">

    <!-- GALERI -->
    <div class="card">
        <h2>📸 Galeri Kolam</h2>
        <div class="gallery">

            <img 
                src="https://i.ibb.co/qbdmr0Y/IMG-20260501-075601.jpg" 
                alt="Suasana Pagi">

            <img 
                src="https://i.ibb.co/PZSWMgDY/IMG-20260325-180958.jpg" 
                alt="Suasana Malam">

        </div>
    </div>

    <!-- LOKASI -->
    <div class="card">
        <h2>📍 Lokasi</h2>
        <p>Jabaran, Kedungpari, Mojowarno, Jombang, Jawa Timur</p>

        <iframe
        src="https://maps.google.com/maps?q=mojowarno%20jombang&t=&z=13&ie=UTF8&iwloc=&output=embed"
        height="250">
        </iframe>
    </div>

    <!-- JAM -->
    <div class="card">
        <h2>⏰ Jam Operasional</h2>
        <ul>
            <li>Senin - Jumat : 07.00 - 02.00</li>
            <li>Sabtu : 07.00 - 04.00</li>
            <li>Minggu : 07.00 - 02.00</li>
        </ul>
    </div>

    <!-- EVENT -->
    <div class="card">
        <h2>🎣 Info Mabar & Event</h2>
        <p>Jadwal mabar dan event terbaru bisa berubah sewaktu-waktu.</p>
        <p>Cek update terbaru di TikTok kami 👇</p>

        <a href="GANTI_LINK_TIKTOK" class="btn tiktok" target="_blank">
            TikTok Kami
        </a>
    </div>

    <!-- KONTAK -->
    <div class="card">
        <h2>📞 Kontak</h2>
        <p>WhatsApp: 0857-3552-4280</p>

        <a href="https://wa.me/6285735524280" class="btn wa" target="_blank">
            Chat WhatsApp
        </a>
    </div>

</div>

<a href="https://wa.me/6285735524280" class="wa-float">💬</a>

<footer>
© 2026 Kolam Pancing Pak Dhe
</footer>

</body>
</html>
