**¿Qué es Git?**

Git es una herramienta que realiza una función del control de versiones
de código de forma distribuida, de la que destacamos varias
características:

⦁ Es muy potente

⦁ Fue diseñada por Linus Torvalds

⦁ No depende de un repositorio central

⦁ Es software libre

⦁ Con ella podemos mantener un historial completo de versiones

⦁ Podemos movernos, como si tuviéramos un puntero en el tiempo, por
todas las revisiones de código y desplazarnos una manera muy ágil.

⦁ Es muy rápida

⦁ Tiene un sistema de trabajo con ramas que lo hace especialmente
potente

⦁ En cuanto a la funcionalidad de las ramas, las mismas están destinadas
a provocar proyectos divergentes de un proyecto principal, para hacer
experimentos o para probar nuevas funcionalidades.

⦁ Las ramas pueden tener una línea de progreso diferente de la rama
principal donde está el core de nuestro desarrollo. En algún momento
podemos llegar a probar algunas de esas mejoras o cambios en el código y
hacer una fusión a nuestro proyecto principal, ya que todo esto lo
maneja Git de una forma muy eficiente

**¿Qué es Git Flow?**

Gitflow es un modelo alternativo de creación de ramas en Git en el que
se utilizan ramas de función y varias ramas principales. Según este
modelo, los desarrolladores crean una rama de función y retrasan su
fusión con la rama principal del tronco hasta que la función está
completa.

**¿Por qué utilizar Git Flow?**

Se utiliza Git Flow ya que permite dividir tu proyecto en varias ramas
de desarrollo dedicadas a tareas muy específicas de tu proyecto,
permitiendo que sean muchos los desarrolladores que puedan estar
integrados en el mismo proyecto al mismo tiempo.

**Parte práctica**

El usuario 1 implementa la estructura inicial utilizando el boilerplate
y modificándolo acorde a lo que se pide en la práctica.

![](./capturas_proceso/24a399d26ba62ac64b42df862c22281a9352e0e2.png){width="6.86698709536308in"
height="1.9102559055118111in"}

![](./capturas_proceso/4112a0429f5b473be379c24d451f4a12b7fce539.png){width="6.875in"
height="1.8012817147856517in"}

![](./capturas_proceso/1f68972f8d2e2e801e0d4e96fa8789c19484f141.png){width="6.850962379702537in"
height="3.7235575240594927in"}

El usuario 1 inicia el proyecto

![](./capturas_proceso/68e1b93153fbd55a82d6e7910885427330e6b5c4.png){width="6.8171522309711285in"
height="0.9644433508311461in"}

El usuario 1 realiza los pasos para tener el proyecto en GitHub

![](./capturas_proceso/a8bdf6ceb1b2ad9b9f03e0faf53869ee6d67551a.png){width="6.5536854768153985in"
height="6.274037620297463in"}El usuario 1 crea la rama de desarrollo
para utilizar la metodología Git Flow

![](./capturas_proceso/cf909e6316b7060cef2d998df3e107305152fd00.png){width="5.0in"
height="1.2708333333333333in"}

El usuario 2 crea las ramas feature/contenidoHTML y
feature/atributosHTML basadas en la rama de desarrollo

![](./capturas_proceso/d67f0d640e842385bd2c45e4fc950ed18099ed6a.png){width="6.338529090113735in"
height="2.997596237970254in"}El usuario 2 completa la feature
contenidoHTML

![](./capturas_proceso/2ddb5479f555e268bb2e1c8b51c7117ac9a2a743.png){width="6.338140857392826in"
height="3.6708398950131236in"}

El usuario 2 fusiona la rama de feature/contenidoHTML con la de
desarrollo

![](./capturas_proceso/46b4cd6f792a21f91f1a49787573d4d590b1742d.png){width="6.538462379702537in"
height="1.2564107611548556in"}

![](./capturas_proceso/d81f46a6e8b252b5c63dea62f2b26a1ca959cc03.png){width="6.579861111111111in"
height="0.6354166666666666in"}

El usuario 2 completa la feature atributosHTML

![](./capturas_proceso/ed42d1eb2351359a8b68e11b312bfedafe2debda.png){width="6.498396762904637in"
height="3.8305621172353455in"}El usuario 2 fusiona la rama de
feature/atributosHTML con la de desarrollo

![](./capturas_proceso/4e3a12bb32828c85a1ff3299afc5366a0eaeea30.png){width="6.482372047244095in"
height="1.0803958880139983in"}

![](./capturas_proceso/c3d6517f013cff606a901dd58a4d4ddb1df9a340.png){width="6.469907042869641in"
height="1.2708333333333333in"}

El usuario 3 crea la rama feature/estilosCSS basada en la rama de
desarrollo

![](./capturas_proceso/6994190ecdb4cae5bd10ca475e0b55ac9a2f6b0d.png){width="6.39423009623797in"
height="0.8259219160104987in"}

El usuario 3 completa la feature estilosCSS

![](./capturas_proceso/091462d658a2819d284884af869435d973b28777.png){width="6.39423009623797in"
height="4.18169072615923in"}

El usuario 3 fusiona la rama feature/estilosCSS con la de desarrollo

![](./capturas_proceso/f3aca13e9483255cd14a44c461caf79b51c20176.png){width="6.421809930008749in"
height="1.1505741469816273in"}![](./capturas_proceso/4c2650f2bbac7db171952a24d9c4ef3cad009eed.png){width="6.446758530183727in"
height="0.5833333333333334in"}El usuario 1 da el visto bueno así que
fusiona la rama de desarrollo con la master

![](./capturas_proceso/9a3de1e471646f44d9bd72375a62cc15f716660a.png){width="6.568287401574803in"
height="2.0104166666666665in"}El usuario 1 etiqueta la versión como 1.0

![](./capturas_proceso/51ca6739db3d3dac89fe5e0f58aa8522a5446042.png){width="6.603009623797026in"
height="0.9375in"}El usuario 1 crea la rama test para la realización de
pruebas

![](./capturas_proceso/78cbdf93f59487386d1350dd03e5920dba8cdb44.png){width="6.6232633420822395in"
height="1.2708333333333333in"}

**El usuario 1 crea los hooks:**

Para la creación de un hook que se active cuando se haga un clonado o un
checkout del proyecto hay que ir a la ruta
**carpeta_proyecto/.git/hooks/** y crear un fichero llamado
**post-checkout**

En este caso, utilizará el entorno bash para que se recree la carpeta
node_modules

![](./capturas_proceso/65fda92989ec99afcefbdacbb72a2081cbcc5b16.png){width="6.819083552055993in"
height="4.009785651793526in"}Finalmente, se añaden permisos de ejecución
al fichero

![](./capturas_proceso/b37f3410560621a36f06db73027351120d666045.png){width="6.685605861767279in"
height="1.8892038495188102in"}

Para la verificación del texto de un commit, en la carpeta anterior se
renombra el archivo existente **commit-msg.sample** a **commit-msg.**

Una vez realizado esto, se modifica el archivo para conseguir lo que se
quiere, en este caso:

![](./capturas_proceso/d1000853c3099ba75ca257030150c8a61f5da7f6.png){width="6.666666666666667in"
height="3.3494313210848645in"}

También se le dan permisos de ejecución al fichero:

![](./capturas_proceso/89f3a4b15f166893305bf3e66b27e5540ff86ff7.png){width="6.590908792650919in"
height="0.5738637357830271in"}

Ahora se crea el hook para la verificación de caracteres extraños y
utilizar el plugin eslint html:

En primer lugar, se instala eslint y eslint-plugin-html en el proyecto
con npm install

También se utiliza el comando npm init \@eslint/config para completar su
configuración

Por último, se modifica el fichero .eslintrc.js para añadir el plugin
eslint-html

![img](./capturas_proceso/6cef77f7376dd89cb28f7186b78b9cf786686543.png)

**pre-commit.sample** a **pre-commit**

Se modifica el fichero para obtener los resultados deseados:

![img](./capturas_proceso/c632e80652216f31ab05ac584742d2e9c32371aa.png)

![img](./capturas_proceso/11922e7c6eab8e8d4c7d46f7a9ca3eea8ee2e1eb.png)

El usuario 1 hace un commit para implementar eslint y su complemento,
además, hay que realizar unos cambios en los ficheros HTML para poder
validarlos debido a problemas con el script de google analytics, así que
todos estos cambios los realiza el usuario 1 en la rama de test

![img](./capturas_proceso/ad81462bf442d021fa03aa1306e1423399b8cda7.png)
rama master

![img](./capturas_proceso/ca2329563de12442a2e98ce63b24b025c61bbda2.png)

Ahora, copiará los hooks para que todos los usuarios los tengan
disponibles

![img](./capturas_proceso/a4c5b05244cf4c67672126f9d44439447afbee28.png)
![img](./capturas_proceso/9b2b4f06515c4c38baa852dfbf2b503d4a9a6929.png)

![img](./capturas_proceso/3617ad17782bdf14eba82089bb60c8529e573e47.png)

Finalmente, el usuario 1 creará una rama llamada gh-pages e incluirá la
documentación de todo el proceso en el fichero README.md

![img](./capturas_proceso/87f2ffac0cbc4540472f63b0e47127469fe95c23.png)
![img](./capturas_proceso/38fda92f76ec18fba755d60da2b00636870986bd.png)


Se activará la opción de GitHub Pages en GitHub:

![img](./capturas_proceso/20c51321c517817a95d015d754dd7828afa29d12.png)
