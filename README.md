<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kejutan Untuk Bububbbbb</title>
  <style>
    body {
      background: #ffe6f2;
      color: #b30059;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding: 40px 20px;
      margin: 0;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      animation: fadeIn 2s ease-in;
    }
    h1 {
      font-size: 2.2rem;
      margin-bottom: 1rem;
      animation: slideDown 1.5s ease forwards;
    }
    p {
      font-size: 1.25rem;
      max-width: 600px;
      margin: 0 auto 2rem auto;
      line-height: 1.5;
      animation: fadeInText 3s ease forwards;
    }
    img {
      max-width: 300px;
      border-radius: 15px;
      margin: 0 auto 2rem;
      box-shadow: 0 8px 15px rgba(179, 0, 89, 0.4);
      animation: bounce 2s infinite;
    }
    button {
      background-color: #b30059;
      color: white;
      border: none;
      padding: 15px 30px;
      border-radius: 30px;
      font-size: 1.2rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
      animation: pulse 2s infinite;
    }
    button:hover {
      background-color: #d62873;
    }

    /* Animations */
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    @keyframes slideDown {
      from {opacity: 0; transform: translateY(-30px);}
      to {opacity: 1; transform: translateY(0);}
    }
    @keyframes fadeInText {
      from {opacity: 0;}
      to {opacity: 1;}
    }
    @keyframes bounce {
      0%, 100% {transform: translateY(0);}
      50% {transform: translateY(-15px);}
    }
    @keyframes pulse {
      0%, 100% {transform: scale(1);}
      50% {transform: scale(1.05);}
    }

  </style>
</head>
<body>

  <!-- Ganti 'foto-kamu.jpg' dengan nama file foto Anda -->
  <img src="foto-kamu.jpg" alt="Foto Bububbbb" />

  <h1>Haloooo bububbbbb ku yang paling cantik, imut, menggemaskan se duniaaaaaa iniiiiii</h1>
  <p>
    Kenalin aku Apip asisten Rapip ahayyy, aku di sini cuma mau nyampein pesan dari Rapip kalo Rapip tuh sayangg banget sama kamu,<br>
    kamu jangan nakal ya di sana ☺☺☺
  </p>

  <button onclick="alert('Semangat ya bububbbb, aku sayang kamu! ❤️')">Klik Aku, Bububbbb!</button>

</body>
</html>
