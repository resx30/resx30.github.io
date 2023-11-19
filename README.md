# resx30.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <link rel="stylesheet" href="style.css">
    <title>Variedades la ventanita</title>
</head>
<body>
    
    <div class="head">

       <div class="logo">
          <a href="#">VARIEDADES LA VENTANITA</a>
       </div>

       <nav class="navbar">
        <a href="#">Inicio</a>
        <a href="#">Nosotros</a>
        <a href="#">Contacto</a>
        <a href="#">Productos</a>
        <a href="#">Precio</a>
       </nav>

    </div>

    <header class="content header">
         <h2 class="title">Inicio</h2>
         <p>Nosotros somos Variedades La Ventanita, una tienda que fue creada en 2012 
            en el municipio de Envigado, en el barrio Uribe Ángel. Estamos ubicados en 
            una acogedora casa de primer piso, donde ofrecemos una amplia variedad de 
            productos para satisfacer las necesidades de nuestros clientes. 
            Nuestro objetivo es brindar un excelente servicio y productos de calidad, 
            para que cada visita a nuestra tienda sea una experiencia única. 
            ¡Te invitamos a conocernos y descubrir todo lo que tenemos para ofrecerte!"
         </p>

         <div class="btn-home">
            <a href="#" class="btn">Saber mas</a>
         </div>
    </header>

    <section class="content sau">

        <h2 class="title">Productos</h2>
         <p>En nuestra tienda, encontrarás una amplia variedad de productos
             para satisfacer tus necesidades. Ofrecemos dulces, helados, snacks, 
             bebidas, artículos de papelería, productos de higiene personal, 
             piñatería, servicio de fotocopias y recargas de datos. ¡Visítanos y 
             descubre todo lo que tenemos para ti!
         </p>


            <div class="box-container">

                <div class="box">
                <i class="fab fa-angular"></i>
                <h3>HarmonyOS</h3>
                <p>Podrás encontrar esta pagina 
                    en todo tipo de sistema operativo.
                </p>
            </div>
            <div class="box">
                <i class="fab fa-apple"></i>
                <h3>IPHONE</h3>
                 <p>Podrás encontrar esta pagina 
                    en todo tipo de sistema operativo.</p>
            </div>
             <div class="box-container">

                 <div class="box">
                 <i class="fab fa-android"></i>
                <h3>ANDROID</h3>
                <p>Podrás encontrar esta pagina 
                    en todo tipo de sistema operativo.</p>
            </div>
        </div>

    </section>

    <section class="content about">

        <h2 class="title">Nosotros</h2>
         <p>En nuestra tienda, cada día es una oportunidad para
            aprender y crecer juntos como familia. Nos enorgullece
            ser una empresa familiar, donde la enseñanza y el 
            crecimiento continuo son valores fundamentales. 
            Nos dedicamos a brindar las mejores experiencias a nuestros
            clientes, porque sabemos que cada interacción cuenta. 
            Nos enfocamos en ofrecer los mejores productos para la 
            comunidad envigadeña. Trabajamos de la mano con proveedores 
            confiables y seleccionamos cuidadosamente cada artículo que 
            ofrecemos en nuestro catálogo.
        </p>

        <a href="#" class="btn">Saber mas</a>

    </section>

    <section class="content price">

        <article class="contain">
           <h2 class="title">Precio</h2>
           <p>Nos enorgullece ofrecer precios accesibles para que
             puedas comprar los productos que más te gusten. Sabemos
            lo importante que es encontrar productos de calidad a 
            precios asequibles, y por eso nos esforzamos en brindarte
            la mejor experiencia de compra. Además de precios accesibles,
            nos destacamos por la calidad de nuestros productos. Trabajamos 
            con marcas reconocidas y confiables, asegurando que cada artículo 
            que adquieras cumpla con los más altos estándares de calidad.
        </p>

        <a href="#" class="btn">Saber precio</a>

        </article>

    </section>

    <section class="content contact">
      <h2 class="title">Contacto</h2>
      <p>3053847873</p>
      <figure class="map">
        <img src="img/mapa.png" height="250px" width="100%" alt="mapa">
      </figure>
    </section>


</body>
</html>
















*{
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    vertical-align: baseline;
}

body {
    text-align: center;
    font-family: sans-serif;
} 

.head {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 63px;
    background: #171717;
    position: fixed;
    width: 100%;
    z-index: 100;
}

.navbar {
    display: flex;
    margin-right: 10px;
}

.logo{
    margin-left: 30px;
}

.logo a{
    text-decoration: none;
    color: #fff;
    text-transform: uppercase;
    font-size: 20px;
}

.navbar a{
    display: block;
    padding: 20px 20px;
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    font-size: 20px;
}

.navbar a:hover{
    background: #3f3f3f;
}

.header {
    display: flex;
    justify-content: center;
    align-items: center;

}  

.header {
    height: 60vh !important;
    background: url(img/header.jpg) no-repeat center;
    background-size: cover;
}

.title {
    margin-bottom: 40px;
    font-size: 60px;
    font-weight: 600;
    text-transform: uppercase;
    color: #fff;
}

p {
    margin-bottom: 40px;
    font-size: 18px;
    color: #fff;
    padding: 0 100px;
}

.btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 40px;
    border: 2px solid #9c27b0;
    color: #fff;
    text-decoration: none;
    background: #9c27b0;
}

.btn:hover {
    background: none;
}

.btn-home {
    display: flex;
}

.btn-home a {
    margin: 0 10px;

}


.content {
    height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.sau {
    padding: 30px;
    background: #1f1d1d;
}

.box-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    text-align: center;

}

.box-container .box {
    height: 11rem;
    width: 17rem;
    background: #101010;
    text-align: center;
    border-radius: 1rem;
    box-shadow: 0 .3rem 5rem rgba(0, 0, 0, .5);
    margin: 2rem;
}

.box-container .box i {
    height: 3rem;
    width: 3rem;
    line-height: 3rem;
    text-align: center;
    border-radius: 50%;
    color: #fff;
    background: #9c27b0;
    font-size: 2rem;
    margin: 1rem 0;

}

.box-container .box h3 {
    font-size: 20px;
    color: #9c27b0;

}

.box-container .box p {
    padding: 0 15px;
    font-size: 16px;
}

.about {
    background: #171717;
}

.price {
    background: url(img/costos.jpg) no-repeat center;
    background-attachment: fixed;
    background-size: cover;
    text-align: center;
}

.contact {
    padding-top: 20px;
    background: #171717;
    padding-bottom: 0;
}



@media screen (max-width: 768px) {
    
    .title{
        margin-bottom: 0;
        font-size: 40px;
    }

    .sau {
        height: 120vh;
    }

    .navbar {
        display: none;
    }
}
