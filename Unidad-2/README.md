<div align="center">

<img src="https://github.com/user-attachments/assets/0249b6fe-8642-4ea1-ba56-dd3e713088fc" width="180"/>

# UNIVERSIDAD NACIONAL DE LOJA

### Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables

## Carrera de Computación

# Unidad 2

## Estructuras Condicionales y Repetitivas

### Portafolio Académico - Teoría de Programación

</div>

---

## Información General

| Información | Detalle |
|:------------|:--------|
| **Asignatura** | Teoría de Programación |
| **Unidad** | Unidad 2 |
| **Tema General** | Estructuras Condicionales y Repetitivas |
| **Ciclo** | Primer Ciclo |
| **Período Académico** | Abril – Agosto 2026 |
| **Docente** | Ing. Lissette Geoconda López Faicán |
| **Estudiante** | Sdier Emanuel Roblez Roblez |

---

<div align="center">

### 📁 Navegación

<p align="center">

<a href="https://github.com/roblezsdier02-alt/Portafolio-Digital-de-Aprendizaje-Teor-a-de-la-Programaci-n.">
  <img src="https://img.shields.io/badge/⬅️%20Regresar%20al%20Portafolio%20Principal-0A66C2?style=for-the-badge" alt="Regresar al Portafolio Principal">
</a>

</p>
</div>

---

<a id="indice"></a>

# 📑 Índice

- [Introducción](#introducción)
- [Objetivos](#objetivos)
- [Contenidos de la Unidad](#contenidos-de-la-unidad)
  - [1. Estructuras Condicionales](#1-estructuras-condicionales)
  - [2. Estructuras Repetitivas](#2-estructuras-repetitivas)
- [Actividad Práctica](#actividad-práctica)
- [Reflexión Crítica](#reflexión-crítica)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Declaración de uso de IA](#declaración-de-uso-de-la-ia-generativa)

---

# Introducción

Las estructuras de control de flujo constituyen uno de los fundamentos más importantes de la programación, ya que permiten modificar el orden de ejecución de las instrucciones según determinadas condiciones o repetir procesos de manera controlada. Gracias a estas estructuras es posible desarrollar programas capaces de tomar decisiones, validar información y automatizar tareas repetitivas de forma eficiente.

Durante esta unidad se estudiaron las **estructuras condicionales** y las **estructuras repetitivas**, analizando su funcionamiento mediante algoritmos, pseudocódigo, diagramas de flujo y su implementación en lenguaje C. Estos conocimientos fortalecen el pensamiento lógico y preparan al estudiante para resolver problemas computacionales de mayor complejidad.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Objetivos

## Objetivo General

Comprender el funcionamiento de las estructuras condicionales y repetitivas para desarrollar algoritmos capaces de tomar decisiones y ejecutar procesos iterativos en la resolución de problemas computacionales.

## Objetivos Específicos

- Identificar los diferentes tipos de estructuras condicionales.
- Comprender el funcionamiento de los ciclos repetitivos.
- Representar algoritmos mediante pseudocódigo y diagramas de flujo.
- Aplicar estructuras de decisión y repetición en programas escritos en lenguaje C.
- Analizar y validar algoritmos utilizando pruebas de escritorio.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Contenidos de la Unidad

Durante esta unidad se abordaron los principales mecanismos que permiten controlar el flujo de ejecución de un programa. Estos mecanismos hacen posible que un algoritmo pueda tomar decisiones en función de determinadas condiciones o repetir un conjunto de instrucciones hasta cumplir un objetivo específico.

Los contenidos desarrollados proporcionan las bases necesarias para construir programas dinámicos, eficientes y capaces de resolver problemas reales mediante estructuras de control.

## Temas desarrollados

| Tema | Descripción |
|:------|:------------|
| **Estructuras Condicionales** | Permiten ejecutar diferentes acciones dependiendo del resultado de una condición lógica. |
| **Estructuras Repetitivas** | Permiten repetir instrucciones mientras se cumpla una condición o durante un número determinado de iteraciones. |
| **Diagramas de Flujo** | Representación gráfica de la lógica utilizada en estructuras condicionales y repetitivas. |
| **Pseudocódigo** | Diseño estructurado del algoritmo antes de la implementación. |
| **Aplicación Práctica** | Desarrollo de un programa utilizando estructuras condicionales y ciclos para resolver un problema real. |

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---
# 1. Estructuras Condicionales

Las **estructuras condicionales** permiten modificar el flujo normal de ejecución de un programa mediante la evaluación de una condición lógica. Dependiendo del resultado (verdadero o falso), el algoritmo ejecutará un bloque específico de instrucciones.

Estas estructuras son fundamentales porque permiten que un programa pueda tomar decisiones y responder de manera diferente según los datos ingresados por el usuario o las condiciones del problema.

---

## Características

- Evalúan expresiones lógicas.
- Permiten tomar decisiones.
- Organizan diferentes caminos de ejecución.
- Mejoran la flexibilidad del algoritmo.
- Son indispensables en cualquier lenguaje de programación.

---

## Tipos de Estructuras Condicionales

### 1. Condicional Simple (if)

La estructura **if** ejecuta un bloque de instrucciones únicamente cuando la condición evaluada es verdadera.

### Pseudocódigo

```text
Si (condición) Entonces

    Instrucciones

FinSi
```

### Diagrama de Flujo

<p align="center">

<img src="https://github.com/user-attachments/assets/836e445c-1e7c-4068-82df-ed370dd2694e" width="420">

</p>

### Ejemplo

```c
if (edad >= 18){

    printf("Mayor de edad");

}
```

---

### 2. Condicional Doble (if - else)

Permite ejecutar un bloque cuando la condición es verdadera y otro diferente cuando la condición es falsa.

### Pseudocódigo

```text
Si (condición) Entonces

    Instrucciones

Sino

    Instrucciones

FinSi
```

### Ejemplo

```c
if (nota >= 7){

    printf("Aprobado");

}
else{

    printf("Reprobado");

}
```

---

### 3. Condicional Múltiple (if - else if)

Se utiliza cuando existen varias condiciones posibles.

### Pseudocódigo

```text
Si (condición1)

    ...

Sino Si(condición2)

    ...

Sino

    ...

FinSi
```

### Ejemplo

```c
if(promedio >= 9){

    printf("Excelente");

}
else if(promedio >= 7){

    printf("Bueno");

}
else{

    printf("Debe mejorar");

}
```

---

### 4. Selección Múltiple (switch)

La estructura **switch** permite seleccionar una opción entre varios casos posibles.

### Ejemplo

```c
switch(opcion){

case 1:

    printf("Registrar");

break;

case 2:

    printf("Consultar");

break;

default:

    printf("Opción incorrecta");

}
```

---

## Comparación entre estructuras condicionales

| Estructura | Uso principal |
|------------|---------------|
| **if** | Ejecuta acciones cuando una condición es verdadera. |
| **if - else** | Permite elegir entre dos alternativas. |
| **if - else if** | Evalúa varias condiciones diferentes. |
| **switch** | Selecciona una opción entre varios casos. |

---

## Aplicaciones

Las estructuras condicionales son utilizadas para:

- Validar datos.
- Verificar usuarios.
- Controlar accesos.
- Clasificar información.
- Crear menús.
- Automatizar decisiones.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# 2. Estructuras Repetitivas

Las **estructuras repetitivas**, también conocidas como **ciclos o bucles**, permiten ejecutar un conjunto de instrucciones varias veces sin necesidad de escribir el mismo código repetidamente.

Su utilización reduce la cantidad de instrucciones escritas y facilita el desarrollo de programas más eficientes.

---

## Características

- Automatizan procesos repetitivos.
- Reducen código duplicado.
- Facilitan cálculos masivos.
- Mejoran la eficiencia del programa.
- Permiten recorrer arreglos y colecciones de datos.

---

## Tipos de ciclos

### 1. Ciclo While

El ciclo **while** evalúa primero una condición lógica.

Si la condición es verdadera, ejecuta las instrucciones.

Cuando deja de cumplirse, el ciclo termina.

### Pseudocódigo

```text
Mientras(condición)

    Instrucciones

FinMientras
```

### Diagrama de Flujo

<p align="center">

<img src="https://github.com/user-attachments/assets/f02092cb-1ebe-4b6c-865d-655f92c80e7e" width="520">

</p>

### Ejemplo

```c
int i = 1;

while(i <= 5){

    printf("%d\n", i);

    i++;

}
```

---

### 2. Ciclo Do - While

Este ciclo ejecuta las instrucciones al menos una vez, ya que la condición se evalúa al final.

### Pseudocódigo

```text
Repetir

    Instrucciones

Hasta Que(condición)
```

### Ejemplo

```c
int i = 1;

do{

    printf("%d\n", i);

    i++;

}while(i<=5);
```

---

### 3. Ciclo For

Se utiliza cuando se conoce previamente el número de repeticiones.

### Pseudocódigo

```text
Para i ← 1 Hasta 10

    Instrucciones

FinPara
```

### Ejemplo

```c
for(int i=1;i<=10;i++){

    printf("%d\n",i);

}
```

---

## Comparación entre ciclos

| Ciclo | Característica |
|--------|----------------|
| **while** | Evalúa primero la condición. |
| **do-while** | Ejecuta al menos una vez. |
| **for** | Ideal cuando se conoce el número de repeticiones. |

---

## Aplicaciones

Los ciclos son utilizados para:

- Mostrar listas.
- Recorrer arreglos.
- Validar información.
- Realizar cálculos repetitivos.
- Generar tablas.
- Procesar grandes cantidades de datos.

---

# 📌 Importancia de la Unidad

Las estructuras condicionales y repetitivas constituyen uno de los pilares fundamentales de la programación. Gracias a ellas es posible desarrollar aplicaciones capaces de tomar decisiones, controlar procesos y automatizar tareas de manera eficiente.

El dominio de estas estructuras permite construir algoritmos más dinámicos, optimizar recursos computacionales y resolver problemas de mayor complejidad. Además, representan la base para el aprendizaje de estructuras de datos, programación orientada a objetos y desarrollo de software en niveles más avanzados.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---
# Actividad Práctica

En esta práctica se aplican las estructuras condicionales y repetitivas estudiadas durante la unidad para desarrollar un programa en lenguaje C que calcule la sucesión de Fibonacci. Además, se emplean herramientas como el análisis del problema, el diagrama de flujo, el pseudocódigo y la prueba de escritorio para validar la solución propuesta.

---

# Ejercicio Integrador

## 📝 Planteamiento del Problema

Desarrollar un programa en lenguaje C que solicite al usuario un número entero positivo **n** y muestre la sucesión de Fibonacci hasta el término indicado. El programa deberá validar que el valor ingresado sea mayor o igual a cero utilizando una estructura repetitiva.

---

# 🔍 Análisis del Problema

## Entradas

- Número entero **n**.

## Procesos

1. Solicitar el valor de **n**.
2. Validar que el número sea mayor o igual a cero mediante un ciclo **do-while**.
3. Analizar los casos especiales utilizando una estructura **if - else if - else**.
4. Si el valor ingresado es mayor que 1, generar la sucesión utilizando un ciclo **for**.
5. Mostrar los términos de la sucesión de Fibonacci.

## Salidas

- Serie de Fibonacci hasta el término solicitado.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Diseño del Algoritmo

## 📊 Diagrama de Flujo

<p align="center">

<img src="https://github.com/user-attachments/assets/401558ce-d9a5-439e-b000-ef492d6be256" width="700">

</p>

---

## 🧠 Pseudocódigo

```text
Inicio

Leer n

Mientras n < 0 Hacer

    Leer n

FinMientras

Si n = 0 Entonces

    Mostrar 0

Sino Si n = 1 Entonces

    Mostrar 1

Sino

    anta ← 0

    antb ← 1

    Para contador ← 2 Hasta n

        suma ← anta + antb

        Mostrar suma

        anta ← antb

        antb ← suma

    FinPara

FinSi

Fin
```

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Prueba de Escritorio

## Datos de prueba

| n | Salida esperada |
|---:|----------------|
| 0 | 0 |
| 1 | 1 |
| 2 | 1 |
| 5 | 1 2 3 5 |
| 8 | 1 2 3 5 8 13 21 |

---

## Seguimiento de Variables

Para el caso **n = 5**

| Iteración | anta | antb | suma |
|-----------:|------:|------:|------:|
| Inicial | 0 | 1 | - |
| 2 | 0 | 1 | 1 |
| 3 | 1 | 1 | 2 |
| 4 | 1 | 2 | 3 |
| 5 | 2 | 3 | 5 |

### Interpretación

La prueba de escritorio demuestra que en cada iteración el programa calcula correctamente el nuevo término de la sucesión utilizando la suma de los dos valores anteriores.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Implementación en Lenguaje C

```c
#include <stdio.h>

int main() {

    int n;
    int anta = 0;
    int antb = 1;
    int suma;
    int cont;

    do {

        printf("Ingrese un numero mayor o igual a cero: ");
        scanf("%d",&n);

    } while(n < 0);

    if(n == 0){

        printf("%d\n",0);

    }

    else if(n == 1){

        printf("%d\n",1);

    }

    else{

        printf("%d\n",anta);
        printf("%d\n",antb);

        for(cont=2; cont<=n; cont++){

            suma = anta + antb;

            printf("%d\n",suma);

            anta = antb;

            antb = suma;

        }

    }

    return 0;

}
```

---

# Explicación del Código

| Instrucción | Función |
|--------------|---------|
| `do-while` | Valida que el usuario ingrese un número mayor o igual a cero. |
| `if` | Comprueba si el número ingresado es 0. |
| `else if` | Comprueba si el número ingresado es 1. |
| `else` | Ejecuta el cálculo de la sucesión para cualquier otro valor. |
| `for` | Genera cada término de Fibonacci mediante iteraciones. |
| `anta` | Guarda el término anterior de la serie. |
| `antb` | Guarda el término actual de la serie. |
| `suma` | Calcula el nuevo término de Fibonacci. |

---

# Resultado Esperado

```
Ingrese un numero mayor o igual a cero: 8

0
1
1
2
3
5
8
13
21
```

---

# Competencias Desarrolladas

Durante la realización de esta práctica se fortalecieron las siguientes competencias:

- Diseño de algoritmos.
- Aplicación de estructuras condicionales.
- Uso de estructuras repetitivas.
- Implementación de programas en lenguaje C.
- Validación mediante pruebas de escritorio.
- Resolución de problemas utilizando pensamiento lógico.
- Comprensión del funcionamiento de la sucesión de Fibonacci.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---
# Reflexión Crítica

## Dificultades Encontradas

Durante el desarrollo de esta unidad, una de las principales dificultades fue comprender la diferencia entre las distintas estructuras de control de flujo y determinar cuál era la más adecuada para cada situación. Inicialmente resultó complejo identificar cuándo utilizar una estructura condicional simple, doble o múltiple, así como diferenciar los escenarios en los que era conveniente aplicar los ciclos `while`, `do-while` y `for`.

Otra dificultad importante fue el análisis de problemas que requerían combinar estructuras condicionales y repetitivas dentro de un mismo algoritmo, especialmente en ejercicios donde era necesario validar datos y realizar cálculos iterativos, como el caso de la sucesión de Fibonacci.

---

## Estrategias Aplicadas

Para superar estas dificultades se realizaron diversas actividades de práctica y análisis:

- Elaboración de algoritmos paso a paso antes de programar.
- Diseño de diagramas de flujo para visualizar el comportamiento del algoritmo.
- Desarrollo de pseudocódigos utilizando estructuras condicionales y repetitivas.
- Resolución de ejercicios progresivos para fortalecer la lógica de programación.
- Aplicación de pruebas de escritorio para verificar resultados.
- Implementación y depuración de programas en lenguaje C.

Estas estrategias permitieron comprender mejor el comportamiento de las estructuras de control y mejorar la capacidad para resolver problemas computacionales.

---

## Aprendizajes Adquiridos

Al finalizar esta unidad se fortalecieron conocimientos relacionados con:

- La toma de decisiones mediante estructuras condicionales.
- La automatización de procesos utilizando ciclos repetitivos.
- La validación de datos mediante estructuras de control.
- El diseño y análisis de algoritmos más complejos.
- La implementación de programas utilizando lenguaje C.
- La combinación de estructuras de decisión y repetición para resolver problemas reales.

Los conocimientos adquiridos constituyen una base fundamental para el estudio de estructuras de datos, funciones y programación modular en unidades posteriores.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Conclusiones

1. Las estructuras condicionales permiten que los programas puedan tomar decisiones y ejecutar diferentes acciones dependiendo de las condiciones establecidas.

2. Las estructuras repetitivas facilitan la automatización de tareas mediante la ejecución controlada de bloques de instrucciones, reduciendo la cantidad de código necesario para resolver problemas.

3. La aplicación conjunta de estructuras condicionales y repetitivas permitió desarrollar soluciones más dinámicas y eficientes, fortaleciendo las habilidades de análisis lógico y programación.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Bibliografía

> **Formato IEEE**

[1] L. Joyanes Aguilar, *Fundamentos de Programación: Algoritmos, Estructuras de Datos y Objetos*, 5.ª ed. Madrid, España: McGraw-Hill Education, 2020.

[2] P. Deitel y H. Deitel, *C How to Program*, 9th ed. Boston, MA, USA: Pearson Education, 2022.

[3] B. W. Kernighan y D. M. Ritchie, *The C Programming Language*, 2nd ed. Upper Saddle River, NJ, USA: Prentice Hall, 1988.

[4] Oracle Corporation, *Java Documentation*, Oracle, 2023. Disponible en: https://docs.oracle.com

[5] Free Software Foundation, *GNU C Library Documentation*, GNU Project. Disponible en: https://www.gnu.org/software/libc/

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

# Declaración de uso de la IA generativa

Durante la elaboración de este portafolio académico se utilizó Inteligencia Artificial generativa como herramienta de apoyo para mejorar la organización de contenidos, estructurar documentos en formato Markdown, sugerir ejemplos base de programación y optimizar aspectos de redacción y presentación.

Todo el material presentado fue revisado, comprendido y validado por el estudiante antes de su incorporación al portafolio. Los ejercicios, algoritmos, diagramas, códigos fuente, análisis, reflexiones y conclusiones reflejan el proceso de aprendizaje desarrollado durante la asignatura y cumplen con los principios de honestidad y probidad académica establecidos por la Universidad Nacional de Loja.

<div align="right">

[⬆ Volver al índice](#indice)

</div>

---

<div align="center">

# ✅ Unidad 2 Finalizada

### Universidad Nacional de Loja

### Carrera de Computación

### Portafolio Académico - Teoría de Programación

📘 **Unidad 2: Estructuras Condicionales y Repetitivas**

---

### Navegación

🏠 [Portafolio Principal](../README.md)

📂 [Unidad 1](../Unidad-1/)

📂 [Unidad 3](../Unidad-3/)

</div>
