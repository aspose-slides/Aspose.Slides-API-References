---
title: Point
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un punto de animación.
type: docs
url: /es/com.aspose.slides/point/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Representa un punto de animación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Point()](#Point--) | Constructor predeterminado. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Crear punto de animación con tiempo, valor y fórmula. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getTime()](#getTime--) | Representa el valor de tiempo. |
| [setTime(float value)](#setTime-float-) | Representa el valor de tiempo. |
| [getValue()](#getValue--) | Representa el valor del punto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representa el valor del punto. |
| [getFormula()](#getFormula--) | Las fórmulas dentro de los valores, atributos from, to, by, pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lectura/escritura String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Las fórmulas dentro de los valores, atributos from, to, by, pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lectura/escritura String. |
### Point() {#Point--}
```
public Point()
```


Constructor predeterminado.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Crear punto de animación con tiempo, valor y fórmula.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| time | float | Valor de tiempo. |
| value | java.lang.Object | Valor del punto. |
| formula | java.lang.String | Fórmula. |

### getTime() {#getTime--}
```
public final float getTime()
```


Representa el valor de tiempo. Lectura/escritura float.

**Devuelve:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Representa el valor de tiempo. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Representa el valor del punto. Solo: bool, ColorFormat, float, int, string. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Representa el valor del punto. Solo: bool, ColorFormat, float, int, string. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Las fórmulas dentro de los valores, atributos from, to, by, pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lectura/escritura String.

**Devuelve:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Las fórmulas dentro de los valores, atributos from, to, by, pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |