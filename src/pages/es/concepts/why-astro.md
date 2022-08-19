---
layout: ~/layouts/MainLayout.astro
title: ¿Por qué usar Astro?
description: Astro es un framework web integral para construir sitios web rápidos y centrados en el contenido. ¡Aprende más!
i18nReady: true
---

Astro es un **framework web integral** para construir **sitios web rápidos** y **centrados en el contenido**. ¡Aprende más!

¿Por qué elegir Astro en lugar de otro framework web? Aquí hay cinco principios básicos de diseño para ayudar a explicar por qué construimos Astro, cuáles son los problemas que pretende resolver y por qué Astro puede ser la mejor opción para tu proyecto o equipo.

#### Astro es...

1. [Content-focused](#content-focused) (enfocado en el contenido): Astro fue diseñado para sitios web ricos en contenido.
2. [Server-first](#server-first) (servidor primero): Los sitios web se ejecutan más rápido cuando procesan HTML en el lado del servidor.
3. [Fast by default](#fast-by-default) (rápido por defecto): Debería ser imposible crear un sitio web lento en Astro.
4. [Easy to use](#easy-to-use) (fácil de usar): No hace falta ser un experto para construir algo en Astro.
5. [Fully-featured, but flexible](#fully-featured-but-flexible) (con plena funcionalidad y sin embargo flexible): Puedes optar entre más de 100 integraciones ofrecidas por Astro.

## Content-focused

Enfocado en el contenido. **Astro fue diseñado para crear sitios web ricos en contenido.** Esto incluye la mayoría de los sitios de marketing, edición de publicaciones, documentación, blogs, portfolios y hasta algunos sitios de comercio electrónico.

Por el contrario, la mayoría de los frameworks web modernos están diseñados para crear *aplicaciones web*. Estos frameworks funcionan mejor para crear experiencias más complejas similares a aplicaciones en el navegador: paneles de administración con inicio de sesión para usuarios registrados, bandejas de entrada, redes sociales, listas de tareas e incluso aplicaciones nativas como [Figma](https://figma.com/) y [Ping](https://ping.gg/).

Esta es una de las diferencias más importantes que hay que entender sobre Astro. El enfoque especial de Astro en el contenido le permite a Astro hacer compensaciones y ofrecer características de rendimiento inigualables que no tendrían sentido para implementar de parte de otros frameworks web centrados en aplicaciones.

:::tip
Si tu proyecto cae en el segundo campo de las "aplicaciones", es posible que Astro no sea la opción correcta para tu proyecto... **¡y está bien!** Consulta [Next.js](https://nextjs.org/) para una excelente alternativa de framework web centrado en aplicaciones.
:::

## Server-first

Servidor primero. **Astro aprovecha el renderizado del lado del servidor por encima del renderizado del lado del cliente tanto como sea posible.** Este es el mismo enfoque que los frameworks tradicionales del lado del servidor (PHP, WordPress, Laravel, Ruby on Rails, etc.) han estado usando durante décadas. Pero no necesitas aprender un segundo lenguaje del lado del servidor. Con Astro, todo sigue siendo solo HTML, CSS y JavaScript (o TypeScript, si lo prefieres).

Este enfoque entra en contraste con otros frameworks web JavaScript modernos como Next.js, SvelteKit, Nuxt, Remix y otros. Estos frameworks requieren el renderizado del lado del cliente de todo tu sitio web e incluyen el renderizado del lado del servidor principalmente para abordar los problemas de _performance_. Este enfoque se ha denominado **Aplicación de página única (SPA Single Page Application)**, en contraste con el enfoque de **Aplicación de varias páginas (MPA Multi Page App )** que tiene Astro.

El modelo SPA tiene sus ventajas. Sin embargo, esto se logra a expensas de una complejidad adicional y al final concesiones en la *performance*. Estas concesiones perjudican el rendimiento de la página, incluidas métricas críticas como [Time to Interactive (TTI Tiempo para interactuar)](https://web.dev/interactive/), lo que no tiene mucho sentido para los sitios web centrados en contenido, donde el rendimiento de la primera carga es esencial.

[Obtén más información sobre lo que hace que la arquitectura MPA de Astro sea única](/es/concepts/mpa-vs-spa/)


## Fast by default

Rápido por defecto. La *performance* siempre es importante, pero es *especialmente* crítica para los sitios web centrados en el contenido. Ha sido bien probado que un bajo rendimiento le hace perder participación, conversiones y dinero. Por ejemplo:

- Por cada 100ms más rápido → 1% más conversiones ([Mobify](https://web.dev/why-speed-matters/), ganando +$380,000/año)
- 50% más rápido → 12% más ventas ([AutoAnything](https://www.digitalcommerce360.com/2010/08/19/web-accelerator-revs-conversion-and-sales-autoanything/))
- 20% más rápido → 10% más conversiones ([Furniture Village](https://www.thinkwithgoogle.com/intl/en-gb/marketing-strategies/app-and-mobile/furniture-village-and-greenlight-slash-page-load-times-boosting-user-experience/))
- 40% más rapido → 15% más en registraciones de usuarios nuevos ([Pinterest](https://medium.com/pinterest-engineering/driving-user-growth-with-performance-improvements-cfc50dafadd7))
- 850ms más rapido → 7% más conversiones ([COOK](https://web.dev/why-speed-matters/))
- Cada segondo más lento → 10% menos usuarios ([BBC](https://www.creativebloq.com/features/how-the-bbc-builds-websites-that-scale))

En muchos frameworks web, es fácil crear un sitio web que se vea muy bien durante el desarrollo pero que carga dolorosamente lento en producción. JavaScript suele ser el culpable, ya que los celulares de los usuarios y los dispositivos de menor potencia rara vez alcanzan la velocidad de la computadora portátil de un desarrollador.

La magia de Astro está en cómo combina los dos valores explicados anteriormente, un enfoque en contenido con una arquitectura MPA que prioriza el servidor, para buscar soluciones de compensación y ofrecer funciones que otros frameworks no pueden. El resultado es un rendimiento web sorprendente para cada sitio web, sin esfuerzo adicional. Nuestro objetivo: **Debería ser casi imposible construir un sitio web lento con Astro.**

Un sitio web Astro puede [cargar un 40% más rápido con un 90% menos de JavaScript](https://twitter.com/t3dotgg/status/1437195415439360003) comparado con el mismo sitio creado con el framework de React más popular. Pero no confíes en nuestra palabra: mira cómo Astro deja a Ryan Carniato (creador de Solid.js y Marko) [sin palabras](https://youtu.be/2ZEMb_H-LYE?t=8163).

## Easy to use

Fácil de usar. **El objetivo de Astro es ser accesible para todos los desarrolladores web.** Astro fue diseñado para sentirse familiar y alcanzable, independientemente del nivel de habilidad o experiencia previa con el desarrollo web.

Comenzamos asegurándonos de que pudieras usar cualquier lenguaje de componente de interfaz de usuario favorito que ya conozcas. Hay soporte para React, Preact, Svelte, Vue, Solid, Lit y ​​muchos otros para crear nuevos componentes de interfaz de usuario en un proyecto de Astro.

También queríamos asegurarnos de que Astro también tuviera un excelente lenguaje de componentes integrado. Para hacer eso, creamos nuestro propio lenguaje de interfaz de usuario `.astro`. Está fuertemente influenciado por HTML: ¡cualquier fragmento válido de HTML ya es un componente válido de Astro! Pero también combina algunas de nuestras funciones favoritas prestadas de otros lenguajes de componentes, como expresiones JSX (React) y tiene soporte para el scoping CSS por defecto (Svelte y Vue).

Astro fue diseñado para ser menos complejo que otros lenguajes y frameworks de interfaz de usuario. Una gran razón para esto es que Astro fue diseñado para renderizarse en el servidor, no en el navegador. Eso significa que no necesitas preocuparte por: hooks (React), closures expirados (también React), refs (Vue), observables (Svelte), átomos, selectores, reacciones o derivaciones. No hay reactividad en el servidor, por lo que toda esa complejidad se desvanece.

Uno de nuestros dichos favoritos es: **Complejidad como opción.** Diseñamos Astro para eliminar la mayor cantidad posible de "complejidad requerida" de la experiencia del desarrollador, especialmente cuando lo utilizas por primera vez. Puedes crear un sitio web de ejemplo "Hello World" en Astro con solo HTML y CSS. Luego, cuando necesites crear algo más poderoso, puedes buscar nuevas funciones y APIs de manera incremental a medida que avances.

## Fully-featured, but flexible

Con plena funcionalidad y sin embargo flexible. **Astro es un framework web todo en uno que viene con todo lo que necesitas para construir un sitio web.** Astro incluye sintaxis de componentes, enrutamiento basado en archivos, manejo de activos (imágenes, fuentes), proceso de construcción, empaquetado, optimizaciones, obtención de datos (data fetching), y más. Puedes crear excelentes sitios web sin tener que salir del conjunto de funciones principales de Astro.

Si necesitas más control, puedes extender Astro con más de [100+ integraciones](https://astro.build/integrations/) como [React](https://www.npmjs.com/package/@astrojs/react), [Svelte](https://www.npmjs.com/package/@astrojs/svelte), [Vue](https://www.npmjs.com/package/@astrojs/vue), [Tailwind CSS](https://www.npmjs.com/package/@astrojs/tailwind), [MDX](https://www.npmjs.com/package/@astrojs/mdx), [optimizaciones de imágenes](https://www.npmjs.com/package/@astrojs/images), y más. [Conectar tu CMS favorito](https://astro.build/integrations/) o [desplegar en tu host favorito](/es/guides/deploy/) con un solo comando.

Astro es independiente de la interfaz de usuario, lo que significa que puede **traer su propio framework de interfaces de usuario (BYOF Bring your own framework/Trae tu propio framework)**. React, Preact, Solid, Svelte, Vue y Lit son oficialmente compatibles con Astro. Incluso puedes mezclar y combinar diferentes frameworks en la misma página, lo que facilita las migraciones futuras y evita el encierre del proyecto en un solo framework.
