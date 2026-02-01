# VD
FOR MY DEAR SABS
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Valentine’s Day ❤️</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body {
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }
    .card {
      background: rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 40px 25px;
      max-width: 420px;
      width: 90%;
      box-shadow: 0 20px 40px rgba(0,0,0,0.2);
      animation: fadeIn 1.5s ease;
    }
    h1 {
      font-size: 2.2rem;
      margin-bottom: 15px;
    }
    h2 {
      font-size: 1.3rem;
      margin-bottom: 20px;
      font-weight: 400;
    }
    p {
      font-size: 1rem;
      line-height: 1.6;
      margin-bottom: 25px;
    }
    .heart {
      font-size: 3rem;
      animation: pulse 1.2s infinite;
      margin-bottom: 20px;
    }
    button {
      background: #fff;
      color: #ff4d6d;
      border: none;
      padding: 12px 24px;
      border-radius: 30px;
      font-size: 1rem;
      cursor: pointer;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    button:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }
    .hidden-message {
      display: none;
      margin-top: 20px;
      font-size: 1.05rem;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.2); }
      100% { transform: scale(1); }
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="heart">❤️</div>
    <h1>Happy Valentine’s Day</h1>
    <h2>My Love</h2>
    <p>
      From the moment you came into my life, everything became brighter.
      This little page is just a tiny way of saying how much you mean to me.
    </p>
    <button onclick="showMessage()">Tap for a Surprise 💌</button>
    <div class="hidden-message" id="message">
      You are my favorite person, my safe place, and my forever Valentine.
      I’m so lucky to have you. 💕
      <br /><br />
      — Yours ❤️
    </div>
  </div>  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script></body>
</html>
