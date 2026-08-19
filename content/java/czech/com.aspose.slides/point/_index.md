---
title: Point
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje bod animace.
type: docs
url: /cs/com.aspose.slides/point/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Reprezentuje bod animace.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Point()](#Point--) | Výchozí konstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Vytvoří bod animace s časem, hodnotou a vzorcem. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getTime()](#getTime--) | Reprezentuje časovou hodnotu. |
| [setTime(float value)](#setTime-float-) | Reprezentuje časovou hodnotu. |
| [getValue()](#getValue--) | Reprezentuje hodnotu bodu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Reprezentuje hodnotu bodu. |
| [getFormula()](#getFormula--) | Vzorce v hodnotách, atributech from, to, by mohou být složeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Vzorce v hodnotách, atributech from, to, by mohou být složeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String. |
### Point() {#Point--}
```
public Point()
```


Výchozí konstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Vytvoří bod animace s časem, hodnotou a vzorcem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| time | float | Časová hodnota. |
| value | java.lang.Object | Hodnota bodu. |
| formula | java.lang.String | Vzor. |

### getTime() {#getTime--}
```
public final float getTime()
```


Reprezentuje časovou hodnotu. Čtení/zápis float.

**Návratová hodnota:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Reprezentuje časovou hodnotu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Reprezentuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/zápis Object.

**Návratová hodnota:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Reprezentuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Vzorce v hodnotách, atributech from, to, by mohou být složeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String.

**Návratová hodnota:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Vzorce v hodnotách, atributech from, to, by mohou být složeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |