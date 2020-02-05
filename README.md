# Angular Universal SSR

Angular Universal permite renderizar el sitio web del lado del Servidor. Lo que permite obtener las siguientes ventajas:

- Mejoramiento del SEO
- Mejora en el rendimiento de dispositivos móviles
- Mejorar la velocidad en la primera carga

Generar proyecto:

`ng new seo-ssr`

Comando para implementarlo:

`ng add @nguniversal/express-engine --clientProject seo-ssr`

Levantar sevidor de prueba:

`npm run build:ssr && npm run serve:ssr`

App **sin** Angular Universal:

![Sin SSR](http://imgfz.com/i/0f2lexN.png)

App **con** Angular Universal:

![Con SSR](http://imgfz.com/i/0APZ9ew.png)

El contenido del componente se muestra sin problemas dentro de la etiqueta app-root, lo que permitirá una mejor interpretación de los robots de los buscadores.

[Documentación oficial](https://angular.io/guide/universal)

[Server Rendering](https://developers.google.com/web/updates/2019/02/rendering-on-the-web)
