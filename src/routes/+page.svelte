<svelte:head>
	<title>Inicio</title>
	<meta name="description" content="Bienvenidos al proyecto de planta RAEE de El calafate" />
</svelte:head>
<div class="Banner">
    <div>
        <img class="logo" src="logo.png" alt="Logo">
    </div>
    <div class="infobar">
        <a  class ="boton1" href="/">inicio</a>
        <a  class ="boton1" href="/esp">Sobre el Proyecto</a>
      

    </div>
</div>

<img src="proyecto_RAEE _00001.jpg" alt="">
<div class="video">
    <h2 class="tituloDoc">Documental sobre residuos electrónicos</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/25uIBlSVrnU?si=RqKuNTrw94nrqYeV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
   
</div>
<img src="proyecto_RAEE_00002.jpg" alt="">
<img src="proyecto_RAEE_00003.jpg" alt="">
<img src="proyecto_RAEE_00004.jpg" alt="">
<img src="proyecto_RAEE_00005.jpg" alt="">
<img src="proyecto_RAEE_00006.jpg" alt="">
<img src="proyecto_RAEE_00007.jpg" alt="">
<img src="proyecto_RAEE_00008.jpg" alt="">
<img src="proyecto_RAEE_00009.jpg" alt="">
<img src="proyecto_RAEE_00010.jpg" alt="">
<img src="proyecto_RAEE_00011.jpg" alt="">
<img src="proyecto_RAEE_00012.jpg" alt="">
<img src="proyecto_RAEE_00013.jpg" alt="">
<img src="proyecto_RAEE_00014.jpg" alt="">
<img src="proyecto_RAEE_00015.jpg" alt="">


<style>
    .video{
        display: grid;
        justify-content: center;
        gap: 1em;
        padding: 2em 0;
    }
    .tituloDoc{
        text-align: center;
        text-transform: uppercase;
        font-size: 1.5em;
    }
  
    a{
      text-decoration: none;
      
    }
  
    div{
      justify-content: center;
    align-content: center;
    }
    .Banner {
        display: flex;
        align-items: center;
        height: 70px;
        border-bottom: 1px solid #333; /* Línea sólida de 3 píxeles de ancho y color negro */
        width: 100%;
        z-index: 100;
        padding: 1em 0;
    }

 
    .logo{
        margin-top: 10px;
        margin-left: 2px;
        margin-right: 29px;
        width: 80px;
        margin-bottom: 19px;
        height: auto; 
        
    }





.info{
  padding-left: 12px;
      justify-content: center;
      display: flex;
      align-items: center;
      flex-direction: column;
    justify-content: center;
    align-content: center;
}

.tituloL{
  border-bottom: 1px solid #000; /* Línea sólida de 3 píxeles de ancho y color negro */
    display: inline-block; /* Asegura que la línea se extienda solo hasta el ancho del texto */
    padding-bottom: 5px;
    font-family: Georgia, 'Times New Roman', Times, serif;
}
.letrasN{
    text-align: center;
    display: flex;
}
.infobar .boton1{
    color: #333;
    padding : 8px 6px;
    border: 1px solid #333;
    transition: all .3s ease-in-out;
  }
  .infobar .boton1:hover{
    background-color: #333;
    color: #fff
  }
</style>
