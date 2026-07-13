---
title: Point
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un punto di animazione.
type: docs
url: /it/com.aspose.slides/point/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Rappresenta un punto di animazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Point()](#Point--) | Costruttore predefinito. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Crea un punto di animazione con tempo, valore e formula. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTime()](#getTime--) | Rappresenta il valore del tempo. |
| [setTime(float value)](#setTime-float-) | Rappresenta il valore del tempo. |
| [getValue()](#getValue--) | Rappresenta il valore del punto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Rappresenta il valore del punto. |
| [getFormula()](#getFormula--) | Le formule nei valori, negli attributi from, to, by, possono essere composte da questi: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/scrittura String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Le formule nei valori, negli attributi from, to, by, possono essere composte da questi: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/scrittura String. |
### Point() {#Point--}
```
public Point()
```


Costruttore predefinito.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Crea un punto di animazione con tempo, valore e formula.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| time | float | Valore del tempo. |
| value | java.lang.Object | Valore del punto. |
| formula | java.lang.String | Formula. |

### getTime() {#getTime--}
```
public final float getTime()
```


Rappresenta il valore del tempo. Lettura/scrittura float.

**Restituisce:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Rappresenta il valore del tempo. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Rappresenta il valore del punto. Solo: bool, ColorFormat, float, int, string. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Rappresenta il valore del punto. Solo: bool, ColorFormat, float, int, string. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Le formule nei valori, negli attributi from, to, by, possono essere composte da questi: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Le formule nei valori, negli attributi from, to, by, possono essere composte da questi: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |