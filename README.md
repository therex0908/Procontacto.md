![ProContactoLogo](https://user-images.githubusercontent.com/121767595/211174228-9907b7f7-8057-447d-ab3d-690eecbdb2ff.png)

# Evaluación Práctica :computer:

#### Edgar Juan Pablo Pichardo Barragan

## Lista de ejercicios:

- [x] :small_blue_diamond: [**Ejercicio 1**](#ejercicio-1) 
- [x] :small_blue_diamond: [**Ejercicio 2**](#ejercicio-2) 
- [x] :small_blue_diamond: [**Ejercicio 3**](#ejercicio-3) 
- [x] :small_blue_diamond: [**Ejercicio 4**](#ejercicio-4) 
- [x] :small_blue_diamond: [**Ejercicio 5**](#ejercicio-5) 
- [x] :small_blue_diamond: [**Ejercicio 6**](#ejercicio-6) 
- [x] :small_blue_diamond: [**Ejercicio 7**](#ejercicio-7) 


## Ejercicio 1

1. Instalar el IDE Visual Studio Code

<img width="90" alt="visual" src="https://user-images.githubusercontent.com/121767595/211175815-c116b12c-7730-46fc-8c60-9f6376270afe.png">

2. Instalar GIT y GIT Bash

<img width="90" alt="visual" src="https://user-images.githubusercontent.com/121767595/211175847-cdf75ef8-5485-44bc-902d-c38e64684fbf.png">


## Ejercicio 2

1. **¿Qué es un servidor HTTP?**

Es el protocolo de transmisión de información, es cual se establece para que un computador solicitante y otro que contiene la información puedan comunicarse de         manera correcta a la hora de transmitir información por la red.

2. **¿Qué son los verbos HTTP? Mencionar los más conocidos** 

Son peticiones que usamos para indicar que queremos realizar sobre el servidor, y las mas conocidas son get, post, patch, put y delete.

3. **¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?** 

Un request es la petición que el cliente hace y esta llegara al servidor. </br>
Un response es la solución que da el servidor después de hacer lo que necesita para brindarle una respuesta.</br>
Los headers son la parte central de los request y response y contienen información de autentificación de seguridad, el agente que se esta utilizando y metadatos de control del cache.

4. **¿Qué es un queryString? (En el contexto de una url)** 

Es la parte de una URL que contiene los datos que deben pasar a aplicaciones web como los programas CGI.

5 **¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?** 

Indican si se ha completado satisfactoriamente una solicitud HTTP específica. Como la respuesta satisfactoria 200 que es uno de los HTTP responseCode. Son el tipo de comunicación web que se utiliza para indicar situaciones o problemas de los sitios y páginas que se dan por parte del cliente o del servidor.

6 **¿Cómo se envía la data en un Get y cómo en un POST?** 

El método get envía la información codificada del usuario en el header del HTTP request, directamente en la url. </br>
Un ejemplo es:</br>
www.ejercicio2.com/index.htm?key1=value1&key2=value2&key3=value3 </br>
En el método HTTP post también se codifica la información, pero ésta se envía a través del body del HTTP request, entonces no aparece en la URL.

7 **¿Qué verbo http utiliza el navegador cuando accedemos a una página?** 

Utiliza el verbo get.

8 **Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.** 

En XML la estructura de datos estándar esta basada en texto para representar información estructurada como: datos, listas, configuración, documentos, etc. </br>
Aquí un ejemplo muy simple de una estructura en XML: </br>

```XML
<nota>
<para>Procontacto</para>
<de>Edgar</de>
<titulo>Ejercicio2</titulo>
<contenido>Estructura de datos</contenido>
</nota>
```
En JSON el formato de intercambio de información es mas legible y por lo tanto mas entendible por el ser humano y de igual manera es igual de eficiente que XML. </br>
Aquí el mismo ejemplo de XML pero en JSON: </br>

```JSON
{
    "nota": {
        "para": "Procontacto",
        "de": "Edgar",
        "titulo": "Ejercicio2",
        "contenido": "Estructura de datos"
    }
}
```
9 **Explicar brevemente el estándar SOAP** 

El estándar SOAP está basado en XML y sirve  para la transmisión de mensajes en HTTP y otros protocolos de Internet.

10.	**Explicar brevemente el estándar REST Full**

Es una técnica de la arquitectura de software, es decir, un conjunto de principios y patrones de comunicación que ayudan a crear APIs.

11.	**¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?**

Los headers transmiten información acerca del navegador del cliente a la página solicitada. </br>
El key Content-type indica el media type del recurso y dice al cliente que tipo de contenido será retornado. </br>


## Ejercicio 3

**Descargar el POSTMAN (aplicación para realizar request como cliente), adjuntando un screen de resolución para cada ítem:** </br>

1. **Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json** </br>

![image](https://user-images.githubusercontent.com/121767595/211177893-d555368a-ad31-431f-bd74-8f76d58caa95.png)

2. **Realizar un request POST a la URL anterior, y con body:** </br>

```
{
"name":"Tu nombre",
"email":tunombre.tuapellido@procontacto.com.mx
}
```
Tip: (Marcar la opción “raw” como body)

![image](https://user-images.githubusercontent.com/121767595/211177951-24eea36d-889f-43b9-86bb-306977e7dea6.png)

3. **Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json**

![image](https://user-images.githubusercontent.com/121767595/211177964-87a81d5d-d33a-47a0-9c58-bb85cfec13a7.png)

4. **¿Qué diferencias se observan entre las llamadas el punto 1 y 3?** </br>

En el primer GET nos arrojó los datos que se encuentran en la URL, en cambio en el segundo GET podemos observar los datos de la URL más los datos que se dieron de alta en el POST del punto 2. 


## Ejercicio 4

**Realizar los siguientes módulos de Trailhead:** </br>
https://trailhead.salesforce.com/users/norozco3/trailmixes/introduccion


## Ejercicio 5
## Ejercicio 6
## Ejercicio 7

