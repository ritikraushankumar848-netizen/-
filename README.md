<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MISSION INCOME 💸💸</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background: radial-gradient(circle at center, #ffe6f0 0%, #ffd6e3 50%, #ffe6f0 100%);
    font-size: 18px;
    position: relative;
    overflow-x: hidden;
  }

  body::before {
    content: '';
    position: fixed;
    top: 0; left: 0; right: 0; bottom: 0;
    pointer-events: none;
    box-shadow:
      0 0 20px #ff66cc inset,
      0 0 20px #ff33aa inset,
      0 0 30px #ff00cc inset,
      0 0 40px #ff66ff inset;
    z-index: 1;
    animation: frameGlow 4s ease-in-out infinite alternate;
  }

  @keyframes frameGlow {
    0% { box-shadow: 0 0 20px #ff66cc inset, 0 0 20px #ff33aa inset, 0 0 30px #ff00cc inset, 0 0 40px #ff66ff inset; }
    50% { box-shadow: 0 0 30px #ff99cc inset, 0 0 30px #ff66aa inset, 0 0 40px #ff33ff inset, 0 0 50px #ff33cc inset; }
    100% { box-shadow: 0 0 20px #ff66cc inset, 0 0 20px #ff33aa inset, 0 0 30px #ff00cc inset, 0 0 40px #ff66ff inset; }
  }

  main { position: relative; z-index: 2; padding: 40px; }

  .glow-header {
    background: #ffe6f0;
    color: #ff0066;
    padding: 30px;
    font-size: 36px;
    font-weight: bold;
    text-align: center;
    text-shadow: 0 0 5px #ff66aa, 0 0 10px #ff66aa, 0 0 15px #ff33aa, 0 0 20px #ff00cc;
    border-radius: 12px;
    margin: 20px auto;
    width: fit-content;
  }

  .marquee-box { width: 100%; overflow: hidden; white-space: nowrap; margin-bottom: 30px; position: relative; z-index: 2; }
  .marquee-track { display: inline-block; padding-left: 100%; animation: slide 12s linear infinite; }
  .marquee-text { display: inline-block; font-size: 26px; font-weight: bold; margin-right: 20px; animation: colorchange 3s linear infinite; }
  .marquee-btn { display: inline-block; background: linear-gradient(45deg, #ff5722, #ff9800, #ffc107, #ff5722); color: white; padding: 16px 36px; font-size: 24px; border-radius: 12px; text-decoration: none; margin-left: 10px; font-weight: bold; box-shadow: 0 0 8px rgba(255,87,34,0.7), 0 0 15px rgba(255,152,0,0.5); }

  @keyframes slide { 0% { transform: translateX(0%); } 100% { transform: translateX(-100%); } }
  @keyframes colorchange { 0% { color: red; } 25% { color: orange; } 50% { color: green; } 75% { color: blue; } 100% { color: purple; } }

  .btn { display: block; background: #28a745; color: white; padding: 18px 36px; margin: 20px auto; border: none; border-radius: 10px; font-size: 22px; cursor: pointer; text-decoration: none; transition: background 0.3s; position: relative; z-index: 2; }
  .btn:hover { background: #218838; }

  .tg-btn, .note-btn { display: block; margin: 15px auto; text-align: center; text-decoration: none; cursor: pointer; transition: background 0.3s; position: relative; z-index: 2; }
  .tg-btn { background: #0088cc; color: white; padding: 14px 28px; border-radius: 10px; font-size: 20px; }
  .tg-btn img { width: 24px; height: 24px; margin-right: 10px; vertical-align: middle; }
  .tg-btn:hover { background: #006fa1; }

  .note-btn { background: #ff9800; color: white; padding: 14px 24px; border-radius: 10px; font-size: 20px; font-weight: bold; border: 3px solid #ff5722; }
  .note-btn:hover { background: #ffb74d; }

  .task-list { margin-top: 40px; font-size: 20px; font-weight: bold; color: #333; text-align: left; display: inline-block; background: #fff0f5; padding: 20px 30px; border-radius: 12px; box-shadow: 0 0 8px rgba(0,0,0,0.1); position: relative; z-index: 2; }
  .task-list li { margin: 10px 0; }

  /* Welcome popup */
  #welcome-popup {
    position: fixed;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scale(0);
    background: linear-gradient(45deg, #ffe6f0, #ffccf2, #ffe6f0);
    color: #ff0066;
    padding: 25px 50px;
    font-size: 28px;
    font-weight: bold;
    text-align: center;
    border-radius: 15px;
    box-shadow: 0 0 20px #ff66cc, 0 0 30px #ff33aa, 0 0 40px #ff00cc;
    z-index: 9999;
    opacity: 0;
    transition: all 0.6s ease-in-out;
    text-shadow: 0 0 10px #ff66aa, 0 0 20px #ff33aa;
  }

  #welcome-popup.show {
    transform: translate(-50%, -50%) scale(1);
    opacity: 1;
    animation: sparkleBounce 1.5s linear infinite;
  }

  @keyframes sparkleBounce {
    0% { transform: translate(-50%, -50%) scale(0.95); }
    50% { transform: translate(-50%, -50%) scale(1.05); }
    100% { transform: translate(-50%, -50%) scale(0.95); }
  }
</style>
</head>
<body>

<!-- Welcome popup -->
<div id="welcome-popup">✨ Welcome to MISSION INCOME 💸💸 ✨</div>

<header class="glow-header">𝐌𝐈𝐒𝐒𝐈𝐎𝐍 𝐈𝐍𝐂𝐎𝐌𝐄 💸💸</header>
<main>
  <div class="marquee-box">
    <div class="marquee-track">
      <span class="marquee-text">EARN UNLIMITED UPI 3₹ 💸💲 INSTANT</span>
      <a href="#" class="marquee-btn">EARN UNLIMITED UPI 3₹</a>
    </div>
  </div>

  <!-- Buttons with working links -->
  <a href="https://mrewards.app/?uid=HHLMOFHzG2" target="_blank" class="btn">CLICK TO CLAIM REWARD</a>
  <a href="https://t.me/+Rq2hPYI99341NGVl" target="_blank" class="tg-btn">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram">Join Telegram Group
  </a>
  <a href="https://t.me/ROYAL_KING004" target="_blank" class="note-btn note-label">Send Task Complete Proof</a>

  <ul class="task-list">
    <li>1. Click to claim reward</li>
    <li>2. Download app</li>
    <li>3. Open/signup</li>
    <li>4. Complete your fast task</li>
    <li>5. Good to reward and make 3₹ UPI withdrawal Instant</li>
  </ul>
</main>

<script>
  window.addEventListener('load', () => {
    const popup = document.getElementById('welcome-popup');
    popup.classList.add('show');

    setTimeout(() => {
      popup.style.opacity = '0';
      popup.style.transform = 'translate(-50%, -50%) scale(0.5)';
    }, 3500);
  });
</script>

</body>
</html>
