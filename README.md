<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>transition</title>
</head>
<h1>GALERIA DE FOTOS :v </h1>

<body>
    <div class="kodfun-galeri">
       
      <div style="background-image: url('https://i.pinimg.com/564x/bb/9c/f6/bb9cf6aa2f252e0421e579de0b4d717b.jpg');"></div>
      <div style="background-image: url('https://i.pinimg.com/564x/e3/44/4b/e3444bbe625f997bf91b9a63c18cd464.jpg');"></div>
      <div style="background-image: url('https://i.pinimg.com/564x/0c/bb/e1/0cbbe1679e763ca62ed5b1f37e5c7484.jpg');"></div>
      <div style="background-image: url('https://i.pinimg.com/564x/6b/2b/12/6b2b12838a7746ea7c1bd1403ae1a2d3.jpg');"></div>
      <div style="background-image: url('https://i.pinimg.com/564x/74/06/c4/7406c424b08ad26a88468af0ab2ee489.jpg');"></div>
      <div style="background-image: url('https://i.pinimg.com/564x/83/1c/90/831c90ed405da67b37c785188c43a5e2.jpg');"></div>

    </div>

    <style>
        h1 {
            color:rgb(0, 0, 0)
        }
      body {
        background-color: rgb(202, 17, 17)
      
    }
    .kodfun-galeri {
        display: flex;
        height: 17rem;
        gap: 3rem;
    }
    .kodfun-galeri > div {
        flex: auto;
        border-radius: 2rem;
        background-position: center ;
        background-repeat: no-repeat;
        background-size: auto 100%;
        transition: all .8s cubic-bezier(.25, .3, .45, 1.4);
        box-shadow: 5px 8px 10px rgb(255, 255, 255);
    }

  
    .kodfun-galeri > div:hover {
        flex: 4;
    }
 
    
    </style>
</body>
</html>


