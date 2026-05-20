<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For sindhu ❤️</title>

<style>
body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ff4e8a, #ff758c, #ff9a9e);
    font-family: 'Georgia', serif;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

/* FIRST SCREEN */
.start {
    background: rgba(255, 255, 255, 0.15);
    padding: 35px 25px;
    border-radius: 25px;
    text-align: center;
    box-shadow: 0 0 35px rgba(0,0,0,0.35);
    animation: pulse 2s infinite;
    cursor: pointer;
}

.start h1 {
    font-size: 26px;
    margin-bottom: 10px;
}

.start p {
    font-size: 18px;
    opacity: 0.9;
}

/* SURPRISE CARD */
.card {
    display: none;
    background: rgba(255, 255, 255, 0.18);
    padding: 26px;
    border-radius: 25px;
    max-width: 92%;
    text-align: center;
    box-shadow: 0 0 40px rgba(0,0,0,0.4);
    animation: fadeIn 1.6s ease;
}

.photo {
    width: 100%;
    max-height: 380px;
    object-fit: cover;
    border-radius: 20px;
    margin-bottom: 18px;
    border: 3px solid rgba(255,255,255,0.6);
}

h2 {
    font-size: 26px;
    margin-bottom: 12px;
}

p {
    font-size: 18px;
    line-height: 1.75;
}

.signature {
    margin-top: 22px;
    font-size: 20px;
    font-style: italic;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(25px); }
    to { opacity: 1; transform: translateY(0); }
}

@keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.06); }
    100% { transform: scale(1); }
}
</style>
</head>

<body>

<!-- TAP SCREEN -->
<div class="start" onclick="openSurprise()">
    <h1>💖 Tap to open your surprise 💖</h1>
    <p>This is made only for you…</p>
</div>

<!-- SURPRISE CONTENT -->
<div class="card" id="surprise">
    <img src="sindhu .jpg" alt="sindhu" class="photo">

    <h2>💙 sindhu 💙</h2>

    <p>
        You are always and always my best place to be.<br><br>

        My life is never the same from the day I loved you.<br>
        I saw my <b>peace</b> in you,<br>
        which I can never ever put into words.<br><br>

        If I had to live my life all over again,<br>
        I would find you sooner,<br>
        so I could love you longer ❤️
    </p>

    <div class="signature">
        — Yours, Sindhu
    </div>
</div>

<script>
function openSurprise() {
    document.querySelector('.start').style.display = 'none';
    document.getElementById('surprise').style.display = 'block';
}
</script>

</body>
</html>
