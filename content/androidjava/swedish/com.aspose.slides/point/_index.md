---
title: Point
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar animationspunkt.
type: docs
url: /sv/com.aspose.slides/point/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Representerar animationspunkt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Point()](#Point--) | Standardkonstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Skapa en animationspunkt med tid, värde och formel. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTime()](#getTime--) | Representerar tidsvärde. |
| [setTime(float value)](#setTime-float-) | Representerar tidsvärde. |
| [getValue()](#getValue--) | Representerar punktvärde. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representerar punktvärde. |
| [getFormula()](#getFormula--) | Formler inom värden, från-, till- och by-attribut kan bestå av följande: Standardaritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (if) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (värdar som stöds) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formler inom värden, från-, till- och by-attribut kan bestå av följande: Standardaritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (if) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (värdar som stöds) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String. |
### Point() {#Point--}
```
public Point()
```

Standardkonstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Skapa en animationspunkt med tid, värde och formel.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| time | float | Tidsvärde. |
| value | java.lang.Object | Punktvärde. |
| formula | java.lang.String | Formel. |

### getTime() {#getTime--}
```
public final float getTime()
```

Representerar tidsvärde. Läs/skriv float.

**Returnerar:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Representerar tidsvärde. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Representerar punktvärde. Endast: bool, ColorFormat, float, int, string. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Representerar punktvärde. Endast: bool, ColorFormat, float, int, string. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formler inom värden, från-, till- och by-attribut kan bestå av följande: Standardaritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (if) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logarithm 'ln()' Egendomsreferenser (värdar som stöds) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String.

**Returnerar:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formler inom värden, från-, till- och by-attribut kan bestå av följande: Standardaritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (if) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logarithm 'ln()' Egendomsreferenser (värdar som stöds) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |