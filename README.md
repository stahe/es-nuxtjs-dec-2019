# Introducción al marco NUXT.JS con ejemplos

📘 **Accede a la documentación del curso:** [https://stahe.github.io/es-nuxtjs-dec-2019/](https://stahe.github.io/es-nuxtjs-dec-2019/)

---

Este documento presenta ejemplos de cómo utilizar el marco NUXT.JS.

El marco [Nuxt.js](https://fr.nuxtjs.org/) nos permitirá implementar la siguiente funcionalidad:

- La primera página de la aplicación web es servida, por ejemplo, por un servidor [Node.js](https://fr.nuxtjs.org/). Además, las demás páginas de la aplicación también están alojadas en este mismo servidor. Se sirven cuando el usuario escribe manualmente su URL en el navegador. Estas páginas incorporan una aplicación [Vue.js] (aproximadamente).
- Una vez que la primera página se carga en el navegador, la aplicación se comporta como una aplicación [Vue.js] estándar.

En definitiva, la aplicación se comporta como una aplicación [Vue.js], salvo en la primera página y cuando el usuario escribe manualmente las URL. En estos casos, la página se recupera del servidor.

Cuando un motor de búsqueda solicita las distintas páginas de la aplicación, recibe las páginas del servidor. Es posible que estas páginas hayan sido optimizadas para SEO (optimización para motores de búsqueda). En una aplicación clásica de [Vue.js], el motor de búsqueda recibe una página con escaso valor de SEO.

## Metodología

Los scripts del documento se comentan y se reproduce su ejecución. En ocasiones se proporcionan explicaciones adicionales. El documento requiere una lectura activa: para comprender un script, es necesario leer su código, sus comentarios y los resultados de su ejecución.

Serge Tahé, diciembre de 2019