<!DOCTYPE HTML>
<html>
<head>
    <link rel="stylesheet"
          href="c.css">
    <style>
        * {
            #border: 1px solid blue;
    
        }
        .row {
            display: flex;
        }

    </style></head>    
    
 <body> 
     <h1>item</h1>
    
     <div class="row">
         <div>height</div>
         <div id="height"></div>
     </div>
     <div class="row">
     <div>weight</div>
     <div id="weight"></div>
     </div>
     <div class="row">
         <div>color</div>
         <div id="color"></div>
     </div>
     
    </body>
<script>
   function prece(height,weight,color) {
            this.height = height;
       this.weight = weight;
       this.color = color;
        }

        var prece1 = new prece(2"m",1"kg",red);
        var prece2 = new prece(30"cm",300"gr",blue);


        document.getElementById("height").innerHTML = prece1.cena;
        var b = document.getElementById("color");
        b.innerHTML = prece1.color;
        var c = document.getElementById("weight");
        c.innerHTML = prece1.weight;
    </script>  
        
     
   
     </html>
