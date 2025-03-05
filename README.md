# RD_Cuaderno-de-Ejercicios-1a-Parte
**1. Para un sistema de comunicaciones con 17 niveles de señal, que funciona en banda base, calcular el máximo ancho de banda si el ruido es despreciable y la tasa de transmisión es de 10 Mbits/s. ¿Qué tipo de medio guiado se podría utilizar para el sistema?**
<br>Para calcular el ancho de banda máximo aplicamos la formula de Nyquist:<br>
<br>B=R/2log2M;<br>
<br>Donde: R=10Mbits (tasa de transmision) y M=17 (niveles de señal)<br>
<br>Sustituyendo: B=10x10^6/2x4,09= **1,22MHz**
<br>Como el ancho de banda es bajo se pueden utilizar varios tipos de medios guiados: **par trenzado, cable coaxial o fibra óptica**

**2. ¿Cuál es la tasa de transmisión máxima en un canal óptico con fibra de ancho de banda de 1 THz y conversores optoeléctricos de 100 Gbaudios, si la relación SNR es de 15 dB y la modulación utilizada en los conversores es de 4 símbolos en cuadratura?**

**3. Si en el sistema anterior se introduce un conector de fibra con un 20% de pérdidas, responder a las siguientes cuestiones:**
**a) ¿Se verá afectada la tasa de transmisión máxima?**
**b) ¿Qué velocidad máxima se tendrá en la salida?**

**4. Indicar el tipo de modulación que se está utilizando y los problemas que plantea en los casos b y c.**
![{3B3300A8-C3A2-4445-A00F-EB6A940D2CD1}](https://github.com/user-attachments/assets/b2439270-8324-4818-9908-0866d912048c)

**5. Sabiendo que se transmiten dos señales de forma simultánea y que se aplican dos modulaciones diferentes:**
**a) Indicar qué dos modulaciones se están aplicando.**
**b) Recuperar la información de ambas señales.**
![{55E1271B-F16F-4C5B-BECD-41E8C796F344}](https://github.com/user-attachments/assets/186957c9-3776-4bf8-b608-98ff0fd31d56)

**6. Indicar las longitudes de onda que se transmiten en cada uno de los puntos marcados en el esquema.**
![{145FD890-1568-4D2C-A607-450C82F66462}](https://github.com/user-attachments/assets/b418b29a-18d4-4bb6-852d-29e81fc23de2)

**7. Se considera una pila de protocolos de 4 capas. La capa 4 envía un bloque de 1 Kbyte.La capa 3 añade cabeceras de 256 bits y cada paquete es de 512 bytes. La capa 2 añade cabeceras de 512 bits y el campo de datos de las tramas son de 128 bytes. La capa 1 añade a cada 30 bytes de datos, 32 bits de comienzo, un byte de parada, y 16 bits de CRC. Dibujar todo el proceso de encapsulamiento del sistema transmisor y calcular la eficiencia del sistema.**

**8. Un sistema satélite divide la información de la capa 3 en bloques de 1904 bits, a los que añade una cabecera de 64 bits. Si cada trama tarda en transmitirse 20 ms y la latencia del satélite es de 85 ms, ¿cuánto tiempo tardará en realizar la transmisión de 5 Mbytes de información?**

**9. Calcular el resultado de un paquete de datos “1111011101010101” en un sistema de enlace de datos con las siguientes especificaciones:**
**• Secuencia de inicio de trama “010101010”.**
**• Protección frente a errores H(7,4).**
**• Tamaño máximo por trama de 4 bytes.**

**10. Un fabricante indica que su sistema integra un CRC-8 con el siguiente polinomio generador: 𝐺𝐺(𝑥𝑥) = 𝑥𝑥8 + 𝑥𝑥7 + 𝑥𝑥2 + 1. Plantear los pasos que se deben realizar para calcular la trama resultante, considerando que el CRC se aplica al final de la trama 2 del ejercicio anterior.**

**11. ¿Cuántos errores pueden llegar a corregir la codificación H(15,11) y el CRC-32?**

**12. Se recibe la trama “1111111101011010101011” y se conoce que el protocolo está constituido por una cabecera “11111111” y que los datos están codificados con H(14,10), ¿cuáles son los datos útiles que se han transmitido?**

**13. ¿A qué protocolo de la capa de enlace de datos corresponde el siguiente esquema temporal?**
![{978403F4-7BE2-48B7-BF96-3AA334517ACF}](https://github.com/user-attachments/assets/be6d4dcf-8fd1-4db7-909c-1b4f2f769b4b)

**14. ¿Se puede aplicar el protocolo del ejercicio anterior en el siguiente escenario?**
![{2942A3A6-926C-47C5-85DD-B2286D80FBD2}](https://github.com/user-attachments/assets/9c9be10c-6fe6-4e56-a81b-99cbf0cfd6dd)

**15. Dibujar un diagrama de ventana deslizante con un receptor con buffer para tres tramas y un transmisor que dispone de 5 tramas desordenadas que llegan en el orden 0, 3, 2, 4, 1.**

**16. Un canal coaxial con FDM con una tasa de transmisión de 500 Mbits/s con una longitud media de trama de 1/𝜇𝜇 = 12584 bits y una tasa de llegada de trama 𝜆𝜆 = 20000 trama/s:**
**a) ¿Qué retardo tendrá?**
**b) Si lo comparten entre 256 usuarios ¿cuántas portadoras serán necesarias?**
**c) ¿Cuánto tiempo tardará un nodo en detectar una colisión?**

**17. Representar la trama “1111111101011010101011” con codificación Manchester y Manchester diferencial. Indicar las unidades y magnitudes en los ejes.**

**18. Diseñar una red Bluetooth que pueda mantener 15 nodos esclavos activos de manera simultánea.**

**19. Cuál será el rutado entre los siguientes switches si utilizan para su conexión un árbol de expansión con raíz B5.**
![{6F3072EF-2B63-4A25-A226-EF20052F7212}](https://github.com/user-attachments/assets/438a2042-3f07-4e40-a1d5-5b379d7793e5)

**20. Conociendo el rutado del ejercicio anterior, realizar de nuevo el árbol de expansión que se produciría si el switch B3 dejara de estar activo**
![{C85AD36B-1E8D-457E-8718-907B14C486F4}](https://github.com/user-attachments/assets/3f55e143-84bb-4b4d-8420-2c6ada551a9c)
