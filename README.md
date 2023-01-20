<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog </title>
    <link rel="icon" href="favicon.ico.ico">
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Blog</h1>
        <section class="principal">
            <div class="caja">
                <hr>
                <nav>
                   <pre>
                 Me llamo José Raúl tengo 17 años, actualmente no estudio pero en unos meses me prepararé para
                 presentar en alguna univeridad ya que por cuestiones de la vida tuve que regresarme a Puebla 
                 mientras estaba estudiando en México como foraneo en el Instituo Politecnico Nacional. </pre>
                </nav> 
             </div>

        </section>
   </header>
    <hr>
    <section class="di principal"> 
            <nav>
                <pre>
                     Poco a poco iré subiendo un video mientras mejoró el sitio, entreno, crezco mentalmente, 
                     aprendo más a programar y sobre todo preparme para mi examen en unos meses, me gustaría 
                     crecer también en este proyecto por el cual, si estas leyendo este sitio, agradezco y 
                     espero puedas acompañarme en cada episodio :) </pre>
            </nav>
            
    </section>
     <hr>
     <section class="tri principal">
        <div>
            <pre>
                Hace un año tuve como meta, prepararme para presentar mi examen de admisión en el IPN, 
                como en BUAP, y así fue, quede en ambas universidades por lo cual decidí irme a estudiar  
                a México y estuve ahí 3 meses, viviendo como foraneo en una ciudad muy grande como lo es
                CDMX,disfruté, sufrí, aprendí y sobre todo entendí muchas situaciones, una de ellas lo que
                es estar solo en una cuidad tan grande. </pre>
      </div>
  <hr>
      <div>
        <pre>
            Hasta el momento, hemos aprendido cosas báscicas de programación entrenamiento 
            ccs, html y algo de Javascript para esto será el sitio web para ejemplificar 
            todo lo que he aprendido a lo largo de este tiempo en lo qué me preparo para 
            volver a presentar mi examen de admisión y como extra el canal de Youtube que
            en cada uno de los links encontrará un video diferente titulados "Episodio". </pre>
    </div>
  <hr> 
  
     </section>
<nav>
   <ul>
       <li><a href="https://youtu.be/6AD18G3AQ_w": target="_blank"> Episodio 1 </a></li>
       <li><a href="https://youtu.be/ZUpKUmnaIFY": target="_blank"> Episodio 2 </a></li>
       <li><a href="https://youtu.be/6AQ8-Ut5LGw": target="_blank"> Episodio 3 </a></li>
       <li><a href="https://youtu.be/SvGfgv57i9g": target="_blank">Episodio 4 </a></li>
       <li><a href="productos.html" : target="_blank"> Inicio</a></li>
   </ul>
</nav>
<div class="video">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/O3T6-jsw124" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
<hr>
</body>
</html>
<canvas width="980" height="50"></canvas> 
<script>

 var pantalla = document.querySelector("canvas");
    var pincel = pantalla.getContext("2d");
    pincel.fillStyle= "Black";
    pincel.fillRect(0,0,1500,60);

    function disenarCirculo(x,y,radio){

    pincel.fillStyle="#ffa420";
    pincel.beginPath();
    pincel.arc(x,y,radio,0,2*Math.PI);
    pincel.fill();
    }

     function limpiarpantalla(){
       pincel.clearRect(0,0,1500,60);
     }

     var  x = 0 
         function actualizarPantalla(){

            disenarCirculo(x,20,8);
            x++;
         }


      setInterval(actualizarPantalla, 5);      

    function saltarLinea() {
        document.write("<br>");
    }   
 </script> 
