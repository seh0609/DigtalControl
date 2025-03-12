# Modelamiento de sistemas
En la clase se vio que un modelamiento define como la obtención de funciones matematicas, las cuales premiten representar los difenentes comportamientos que tienen las variables de interes en el sistema bajo estudio, con respecto a esta definicion se plantearon varios modelamientos como lo son: Mecánico, Hidráulico, Neumático, Térmico, Combinaciones. Cada uno de estos cuenta con un principio general para el modelamiento el cual es: 

![image](https://github.com/user-attachments/assets/1e70ffd0-83ba-450c-97b2-7adee228efdd)

Figura 1. Principio del modelamiento

## 1. Modelo dinamico
Variables de interes con respecto al tiempo F(t)

Tambien es necesario saber cuando las variables cambian con respecto al tiempo $\frac{df(t)}{dt}$

Como luce un modelo de ecuacion diferencial 

![image](https://github.com/user-attachments/assets/6589b5c7-2869-45f7-8a0f-87ca88f51830)

Figura 2. modelo de una ecuacion diferencial

>🔑 *F:* salida sistema
>
>🔑 *U:* entrada del sistema
>
>🔑 la solucion siempre va a ser una funcion
>


## 2. Sistemas Mecanicos
Este es un sistema el cual cumple una tarea especifica mediante la manipulación de fuerzas y movimientos. En estos sistemas se encuentran mecanismos que transforman la energía, ya sea para aumentar la velocidad, alterar la dirección del movimiento o generar un cambio deseado en la fuerza aplicada

### 2.1. Ecuaciones fundamentales 

$$Fr={K2}x{X}$$ -- Ley de Hooke

$$Ff={K1}x{Vm}$$ -- 𝐹𝑟𝑖𝑐𝑐𝑖ó𝑛 𝑣𝑖𝑠𝑐𝑜𝑠𝑎

$$F={m}x{a}$$ -- 𝐿𝑒𝑦𝑒𝑠 𝑑𝑒 𝑁𝑒𝑤𝑡𝑜𝑛

### 2.2. Ejemplo
💡**Ejemplo 1:** Sistemas masa-resorte-amortiguador

![image](https://github.com/user-attachments/assets/37a4bbfb-d056-45f2-bc5a-9ceb2ddcaf51)

Figura 3. Desarrollo del ejemplo, este ekemplo se saco de https://www.studocu.com/pe/document/universidad-nacional-de-san-agustin-de-arequipa/fisica/ejemplo-masa-resorte-amortiguador/30445000

### 2.3. Tabla
En caso de necesitar la inclusión de tablas para organizar información se recomienda el uso de la herramienta del siguiente enlace https://www.tablesgenerator.com/markdown_tables , la cual permite organizar la información dentro de la tabla y genera el código markdown automáticamente:

## 2.4. Ejercicios
📚 **Ejercicio mecanico**

![image](https://github.com/user-attachments/assets/19d2dd78-a7e2-4ee1-a64e-09c0b15871b7)

Figura 4. Ejercicio 1

![image](https://github.com/user-attachments/assets/5ac06f2f-fe6d-4aa8-b058-7b03d5d7cde7)

Figura 5. Diagrama de cuerpo libre

![Imagen de WhatsApp 2025-03-11 a las 20 37 50_3db0ac34](https://github.com/user-attachments/assets/9eb2b32f-3b6a-454a-9641-2d542b8333bb)

Figura 6. Desarrollo del ejercicio 

cambio

## 3. Sistemas Rotacional
Se entiende por un sistema rotacional a un modelo que gira en torno de un eje interno a este movimiento se le conoce como "rotacion"
>🔑 *Rotacion:* movimiento en el que los distintos puntos del cuerpo presentan velocidades que son proporcionales a su distancia al eje.

El rotacional o rotor es un operador vectorial que muestra la tendencia de un campo vectorial a inducir rotación alrededor de un punto.

### 3.1. Ecuaciones fundamentales 

$$Fr={K}x{φ}$$ -- Angulo de torsion

$$Ff=b x \frac{dφ}{dt}$$ -- V𝑒𝑙𝑜𝑐𝑖𝑑𝑎𝑑 𝑎𝑛𝑔𝑢𝑙𝑎𝑟

$$T=J x \frac{dφ^2}{dt^2}$$ -- M𝑜𝑚𝑒𝑛𝑡𝑜 𝑑𝑒 𝑖𝑛𝑒𝑟𝑐𝑖𝑎

### 3.2. Ejemplo
💡**Ejemplo 1:** 

![image](https://github.com/user-attachments/assets/b61d2c92-58a8-4873-a851-522f96376599)

Figura 7 Desarrollo del ejemplo, este ekemplo se saco de https://dademuchconnection.wordpress.com/2018/09/22/funcion-de-transferencia-de-sistema-mecanico-rotacional-masa-resorte-amortiguador/

![image](https://github.com/user-attachments/assets/d88d1486-e911-4082-900b-ed0aea6fd051)

Figura 8 Desarrollo del ejemplo, este ekemplo se saco de https://dademuchconnection.wordpress.com/2018/09/22/funcion-de-transferencia-de-sistema-mecanico-rotacional-masa-resorte-amortiguador/


![image](https://github.com/user-attachments/assets/9cd335f7-d883-4480-a896-d21db1bce4a4)

Figura 9 Desarrollo del ejemplo, este ekemplo se saco de https://dademuchconnection.wordpress.com/2018/09/22/funcion-de-transferencia-de-sistema-mecanico-rotacional-masa-resorte-amortiguador/

![image](https://github.com/user-attachments/assets/309a12ac-0ce0-4204-917c-fdcc9f222520)

Figura 10 Desarrollo del ejemplo, este ekemplo se saco de https://dademuchconnection.wordpress.com/2018/09/22/funcion-de-transferencia-de-sistema-mecanico-rotacional-masa-resorte-amortiguador/

## 3.3. Ejercicios
📚 **Ejercicio rotacional**

![image](https://github.com/user-attachments/assets/c283e99e-ffd9-4e6d-9189-bcc6598aaa15)

Figura 11. Ejercicio 2

![image](https://github.com/user-attachments/assets/7d95bb4d-a755-4306-a945-f803a46418ea)

Figura 12. Diagrama de cuerpo libre

![Imagen de WhatsApp 2025-03-11 a las 20 38 38_b53a63da](https://github.com/user-attachments/assets/cf8c19f1-0451-496b-b436-af6c8e7f0577)

Figura 13. Desarrollo del ejercicio 

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
https://sdindustrial.com.mx/blog/introduccion-a-los-sistemas-mecanicos/

https://www.studocu.com/pe/document/universidad-nacional-de-san-agustin-de-arequipa/fisica/ejemplo-masa-resorte-amortiguador/30445000

https://ocw.unican.es/pluginfile.php/1829/course/section/1438/capitulo_1.pdf

https://www.scribd.com/document/217568833/sistemas-rotacionales


