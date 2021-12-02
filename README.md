# INFORME DE LABORATORIO 3

**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

Nombres : Martin Coronel, Jefferson Chicaiza, Tito Obando 

NRC: 10133

***Objetivo General***

- Analizar los voltajes en diferentes nodos de un circuito cerrado, mediante una práctica de laboratorio para comprender cómo se comportan las tensiones en los diferentes nodos. 

***Objetivo Especificos***
- Conocer los conceptos de nodos para identificar los principales y el de referencia.
- Realizar un circuito en un protoboard siguiendo la estructura dada por el docente para analizar las tensiones en los nodos 
- Medir  con el multimetro valores de las corrientes de las diferentes mallas. 
- Comparar los valores calculados por el método de tensiones en los nodos con los valores medidos para  determinar mayor validez a nuestro analisis.

**2.MARCO TEORICO**

![image](https://user-images.githubusercontent.com/94098157/144464391-88385fce-f778-4f80-901b-b5cd3bb08bca.png)

**3.MATERIAL Y EQUIPO REQUERIDO**

![image](https://user-images.githubusercontent.com/94098157/144358967-6f911d74-a0c2-4904-b3ad-606503253c1f.png)

**4.EXPLICACIÓN DEL PROCEDIMIENTO**

*1. Arme el circuito que se muestra en la figura 1.1*

![image](https://user-images.githubusercontent.com/94098157/144353613-8c45fbf6-3bd3-4abd-9c3c-e6510dded6f1.png)
![image](https://user-images.githubusercontent.com/94098157/144353930-5e5ff6b8-beef-4ff3-a225-027cebc17ee9.png)
Primeramente se muestra el circuito realizado en el simulador tinkercad en el que se observa todos los componentes que se especifican en el diagrama como son los resistores, cables, fuentes de voltaje  y además la inicialización de la simulación.    

*2. Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1.*

![image](https://user-images.githubusercontent.com/94098157/144355741-d050193a-d28a-4293-97d7-b8bb03d2ad27.png)
Aquí se muestra la respectiva medición del voltaje en el primer nodo principal  con respecto al nodo de referencia en el que marca  el valor de 2.82 voltios. 

![image](https://user-images.githubusercontent.com/94098157/144356285-3d10b28f-f045-4de1-98c8-a03c05758947.png)
De la misma manera, en la medición del  segundo nodo principal se marca un valor de 4.8 voltios, es importante mencionar que el nodo de referencia se lo puede conectar en cualquier parte en donde actúe dicho nodo.

*3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 3.1, obteniendo los valores de los voltajes de nodo. Anote los resultados en la tabla 3.1.*

![image](https://user-images.githubusercontent.com/94098157/144358169-9c5d6860-67fd-4110-b9c7-72249ab3a6f0.png)
En cuanto al circuito creado en multisim online se realizó la respectiva medición del primer nodo principal con respecto al nodo de referencia, dando como resultado 2.82 volteos 

![image](https://user-images.githubusercontent.com/94098157/144358346-766b1318-1ea0-4cdb-90c8-baa9e345edb3.png)
De la misma manera, la medición del voltaje en el  segundo nodo principal nos da un valor de 4.8 voltios con respecto al nodo de referencia.

*Calculos del voltaje por el método de tensiones en los nodos*

![image](https://user-images.githubusercontent.com/94098157/144363594-3c6ac633-346f-4614-92ce-ff9fc4a2c328.png)
Primeramente se identifican los nodos principales, el nodo de referencia y el sentido de la corriente, además se toma en cuenta que todas las corrientes de los nodos salen.    

![image](https://user-images.githubusercontent.com/94098157/144364085-a49e2ae1-ce34-4c7c-a3ec-2039b75cbce5.png)

Por lo tanto, la sumatoria de todas las corrientes que salen del nodo son iguales a cero. Al formarse una igualdad se debe establecer que dichas corrientes son iguales  al voltaje sobre la resistencia en base a la ley de ohm, por lo que se forman dos ecuaciones en función a los dos voltajes que quieren calcular. Dichas ecuaciones se las puede resolver mediante una calculadora de Sistemas ecuaciones lineales en este caso se utilizó symbolab en donde X=V 1 y Y=V2.

![image](https://user-images.githubusercontent.com/94098157/144435615-ceb2bf6c-98e6-4f39-8143-ba6d86046bda.png)

Como respuesta tenemos:

![image](https://user-images.githubusercontent.com/94098157/144435809-22500b55-c042-480e-91fe-de4d7b0ec3ce.png)

Pues si bien un resultado nos da negativo es importante mencionar que solo se tomó la  dirección de salida de la corriente para ambos nodos principales 

![image](https://user-images.githubusercontent.com/94098157/144467100-24171188-6a36-482f-af1e-00b204e7cac9.png)

*4. Compare los valores de la tabla 3.1 y realice sus conclusiones.*

![image](https://user-images.githubusercontent.com/94098157/144466989-63d82875-5353-4502-b9fc-2c16688e8c0f.png)

**5. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

La comprobación de todos los valores de voltaje en los nodos principales por medio de la práctica, el cálculo y una simulación nos arrojaron valores muy similares entre ellos, por lo que la tensión en los nodos del circuito fueron obtenidos de manera correcta.

![image](https://user-images.githubusercontent.com/94098157/144467896-246f4d05-639f-4a48-8596-bf17d823a3aa.png)


**6. VIDEO:**

https://www.youtube.com/watch?v=yifDJoK_LgQ

**7. CONCLUSIONES**
- Tener los conceptos claros en lo que ue se refiere a corriente y al definición de un nodo principal y de referencia nos ayudó a medir de forma precisa los diferentes voltajes que pasan por los nodos. 
- Se pudo observar que las leyes de kirchhoff son el camino para calcular los voltajes en los diferentes nodos. 
- Los valores analiticos, experimentales, simulados muestran una gran semejanza entre ellos, lo que signfica que los voltajes obtenidos en los nodos son precisos.
- Conocer el funcionamiento del multimetro nos ayudó a poder realizar de manera precisa las medicones en las mallas del circuito.

**8. BIBLIOGRAFÍA**

Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION.

Khan. (2015).*Khan Academy Las Leyes de Kirchhoff*. https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws

Link_Symbolab:https://es.symbolab.com
