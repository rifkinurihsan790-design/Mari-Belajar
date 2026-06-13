<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mari Belajar</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial,sans-serif;
    background:linear-gradient(135deg,#4f46e5,#06b6d4);
    color:white;
    min-height:100vh;
}

.hero{
    text-align:center;
    padding:120px 20px;
}

.hero h1{
    font-size:60px;
}

.hero p{
    margin-top:20px;
    font-size:22px;
}

button{
    margin-top:30px;
    padding:15px 30px;
    border:none;
    border-radius:10px;
    cursor:pointer;
    font-size:18px;
}
</style>
</head>

<body>

<div class="hero">
    <h1>🚀 Mari Belajar</h1>
    <p>Belajar HTML, CSS dan JavaScript bersama saya</p>

    <button onclick="halo()">
        Mulai Belajar
    </button>
</div>

<script>
function halo(){
    alert("Selamat datang di website Mari Belajar!");
}
</script>

</body>
</html>
