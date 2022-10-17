# Practica Velazquez
En esta práctica lo primero que he hecho ha sido crear un repositorio
con el siguiente comando:
>git init

Después añadiremos las carpetas al repositorio con el comando:
>git add .

Despues de hacer el repositorio y añadir las carpetas lo que he hecho ha
sido crear un archivo html y un archivo css, despues de ello les he 
enlazado con un link de esta manera.
```HTML
    <link rel="stylesheet" href="...">
```
En la parte de href ponemos el nombre del archivos de css que tengamos.

Una vez cerado los archivos he empezado a hacer la pagina la cual la he
dividido en 3 secciones:

* Un encabezado
* Las imagenes laterales
* Las imágenes centrales
* La informacion de las imagenes centrales

El encabezado es un header, despues dentro de un main estan las imagenes
laterales dentro de un section, las imagenes centrales en un aside y las
descripciones en un div.

He usado un tipo de letra para toda la página cogiendo el codigo de Google 
Fonts y copiandolo arriba de todo del css de esta manera:
```CSS
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap');
body{
    font-family: 'Montserrat', sans-serif;
}
```

En esta practica he tenido problemas de codigo repetido e innecesario
por lo que he tenido que actualizarlo varias veces quitando el código
repetido.

Aqui un ejemplo de código repetido:

```CSS
    .foto{
    margin: auto;
    display: block;
    padding-top: 15px;
    width: 150px;
    height: 188px;
    filter: grayscale(100%);
}
```

Entonces lo que he hecho ha sido borrar los repetidos y dejar uno solo.

He creado tambien varios index para tener cada imagen con su descripción
correspondiente al pinchar en cada foto lateral, los cuales he enlazado con el siguiente codigo.

````HTML
    <a href="..."></a>
````
Dentro del href pondremos la página a la que queramos ir al pinchar en
ese enlace.

A medida que he ido haciendo este trabajo he ido haciendo commit aunque
lo he hecho mal porque se me ha olvidado hacer el push el cual he hecho
tarde.

Esto se deberia haber hecho antes pero como se me olvido lo hare ahora.

Subire el repositorio a git hub con el comando 
> git push

o con el commit and push que tenemos aqui en el phpstorm.

Y básicamente esto seria todo lo que he hecho, he tenido problemas en la 
maquetación porque no controlo muy bien lo de los porcentajes y la 
parte del java script tampoco se muy bien ya que no lo dimos mucho el 
año pasado.