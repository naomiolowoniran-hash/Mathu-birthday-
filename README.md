# Mathu-birthday-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday Mathu 🎀</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- effects -->
  <div class="confetti-container" id="confetti"></div>
  <div class="sparkle-container" id="sparkles"></div>

  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content center">
        <h1>Happy Birthday, Mathu! 🎂</h1>
        <p class="tagline">A tiny pastel corner of the internet made just for you.</p>

        <div class="polaroid" style="margin: 0 auto;">
          <!-- replace with real photo file -->
          <img src="mathu-photo.jpg" alt="Mathu's cute smile">
          <span>the cutest braces smile ever ✨</span>
        </div>

        <p>
          Dear Mathu, this whole website is my little love letter to your laugh,
          your chaos, and your Sri Lankan queen energy.
        </p>
        <p>
          Click below to enter your birthday world—filled with reasons I adore you,
          a BTS corner, and a few surprises.
        </p>

        <a href="about.html" class="btn-primary">Enter the Birthday World 🎀</a>

        <div class="footer">
          Made with so much love by Naomi ♡
        </div>
      </div>
    </div>
  </div>

  <script>
    // pastel confetti
    const confettiContainer = document.getElementById("confetti");
    const colors = ["#f7b7d4", "#c7b5ff", "#c9a27b", "#ffe3f2"];

    for (let i = 0; i < 70; i++) {
      const piece = document.createElement("div");
      piece.classList.add("confetti-piece");
      piece.style.left = Math.random() * 100 + "vw";
      piece.style.animationDelay = Math.random() * 4 + "s";
      piece.style.backgroundColor = colors[Math.floor(Math.random() * colors.length)];
      confettiContainer.appendChild(piece);
    }

    // sparkles
    const sparkleContainer = document.getElementById("sparkles");
    for (let i = 0; i < 35; i++) {
      const s = document.createElement("div");
      s.classList.add("sparkle");
      s.style.left = Math.random() * 100 + "vw";
      s.style.top = Math.random() * 100 + "vh";
      s.style.animationDelay = Math.random() * 3 + "s";
      sparkleContainer.appendChild(s);
    }
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>About Mathu 🌸</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content">
        <h1>Who is Mathu? 💕</h1>
        <p class="tagline">Sri Lankan sunshine with the cutest braces smile and the loudest laugh.</p>

        <div style="display:flex; flex-wrap:wrap; gap:18px; align-items:flex-start;">
          <div class="polaroid">
            <!-- replace with real photo -->
            <img src="mathu-laugh.jpg" alt="Mathu laughing">
            <span>laughing at something probably not that funny</span>
          </div>

          <div style="flex:1; min-width:220px;">
            <h2>Quick facts</h2>
            <ul class="list">
              <li>Has a <strong>braces smile</strong> that could literally light up a whole city.</li>
              <li>Laughs at everything—and somehow makes everyone else laugh too.</li>
              <li>Proud <strong>Sri Lankan queen</strong> with main‑character energy.</li>
              <li>Can turn the most boring day into a chaotic fun story.</li>
              <li>Certified “I will hype you up no matter what” friend.</li>
            </ul>

            <div class="scrap-note">
              If you’re here, you’re lucky—you’ve met Mathu in this lifetime.
              Please appreciate her laugh responsibly.
            </div>

            <div style="margin-top:10px;">
              <span class="chip">funny</span>
              <span class="chip">soft but chaotic</span>
              <span class="chip">braces icon</span>
              <span class="chip">Sri Lankan baddie</span>
            </div>
          </div>
        </div>

        <div class="footer">
          Next stop: <a href="reasons.html">20 reasons I love you →</a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Reasons I Love You 💗</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content">
        <h1>20 Reasons You’re Amazing ✨</h1>
        <p class="tagline">This is not even the full list, just the starter pack.</p>

        <ol class="list">
          <li>Your laugh could cure global sadness.</li>
          <li>Your braces smile is actually elite—no one is competing.</li>
          <li>You make every boring day fun just by existing.</li>
          <li>You understand my chaos better than anyone else.</li>
          <li>You hype me up even when I look like a potato.</li>
          <li>You’re the safest person I know to be my full self with.</li>
          <li>You remember the tiny details I say and bring them up later.</li>
          <li>You turn our inside jokes into full‑on sagas.</li>
          <li>You’re so kind without even trying.</li>
          <li>You always find a way to make me laugh when I need it most.</li>
          <li>You’re basically my sister at this point.</li>
          <li>You somehow make chaos feel comforting.</li>
          <li>You’re honest with me, even when it’s hard.</li>
          <li>You never make me feel alone in anything.</li>
          <li>You’re the first person I want to tell everything to.</li>
          <li>You’re beautiful in every single version of yourself.</li>
          <li>You support my delusions and dreams equally.</li>
          <li>You make growing up a little less scary.</li>
          <li>You’re proof that soulmates can be best friends.</li>
          <li>Simply put: life is better with you in it.</li>
        </ol>

        <div class="scrap-note">
          If you ever forget how loved you are, please come back to this page.
        </div>

        <div class="footer">
          BTS time? <a href="bts.html">Let’s go →</a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>BTS Corner for Mathu 💜</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content">
        <h1>For the BTS Princess 💜</h1>
        <p class="tagline">Because obviously your birthday website needed a BTS section.</p>

        <p>
          If BTS ever met you, I’m convinced they’d write a whole album about your smile,
          your laugh, and your main‑character energy.
        </p>

        <h2>Little BTS playlist for you</h2>
        <ul class="list">
          <li><a href="#" target="_blank">Song 1 – your comfort song</a></li>
          <li><a href="#" target="_blank">Song 2 – the one that makes you scream‑sing</a></li>
          <li><a href="#" target="_blank">Song 3 – the one that feels like a hug</a></li>
        </ul>
        <p style="font-size:0.9rem; color:#7a5f5f;">
          (You can replace these links with your actual favourite BTS songs on Spotify/YouTube.)
        </p>

        <div class="scrap-note">
          Reminder: you deserve the same love and softness you give to your favourite idols.
        </div>

        <div class="footer">
          Ready for a surprise? <a href="surprise.html">Click here →</a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Surprise for Mathu 🎁</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content center">
        <h1>Click for a Surprise 👀</h1>
        <p class="tagline">Because obviously I had to make this dramatic.</p>

        <div class="surprise-box">
          <button class="btn-primary" onclick="showSurprise()">Press me gently 🎀</button>
          <div id="surprise-text" class="surprise-text" style="display:none;"></div>
        </div>

        <div class="footer">
          After this, read your letter → <a href="letter.html">here</a>
        </div>
      </div>
    </div>
  </div>

  <script>
    const messages = [
      "Plot twist: you are actually the main character of this whole universe.",
      "Your laugh is my favourite sound. Please never stop using it.",
      "You are way more beautiful, loved, and important than you realise.",
      "If life was a K‑drama, you’d be the chaotic best friend everyone falls in love with.",
      "Thank you for existing exactly the way you are."
    ];

    function showSurprise() {
      const box = document.getElementById("surprise-text");
      const msg = messages[Math.floor(Math.random() * messages.length)];
      box.textContent = msg;
      box.style.display = "block";
    }
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Letter to Mathu 💌</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="wrapper page">
    <nav class="nav">
      <a href="index.html">Home</a>
      <a href="about.html">About Mathu</a>
      <a href="reasons.html">Reasons I Love You</a>
      <a href="bts.html">BTS Page</a>
      <a href="surprise.html">Surprise</a>
      <a href="letter.html">Letter</a>
    </nav>

    <div class="card">
      <div class="card-content">
        <h1>Dear Mathu, 💌</h1>
        <p>
          I made this little website because “happy birthday” didn’t feel big enough for what
          you mean to me.
        </p>
        <p>
          You’re not just my best friend—you’re my safe place, my chaos partner, my emotional
          support clown, and my favourite person to grow up with. Your laugh makes everything
          lighter, your smile (yes, including the braces) makes everything softer, and your
          presence makes everything feel less scary.
        </p>
        <p>
          I hope when you click through these pages, you feel even a tiny bit of the love
          and gratitude I have for you. You deserve softness, joy, and people who choose you
          the way you always choose them.
        </p>
        <p>
          Thank you for being my person. For every late‑night chat, every unhinged joke,
          every “are you awake?” message, every time you stayed when you didn’t have to.
        </p>
        <p>
          I don’t know what the future looks like, but I know I want you in it—laughing,
          screaming over songs, and turning normal days into core memories with me.
        </p>
        <p style="margin-top:14px; font-weight:500;">
          Happy birthday, Mathu. I love you more than this website can say. ♡
        </p>

        <div class="scrap-note">
          From: Naomi, your forever best friend.<br>
          P.S. Come back to this site whenever you forget how special you are.
        </div>

        <div class="footer">
          Back to the start → <a href="index.html">Home</a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>

