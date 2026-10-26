---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /sv/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Representerar animeringspunkt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTime()](#getTime--) | Representerar tidsvärde. |
| [setTime(float value)](#setTime-float-) | Representerar tidsvärde. |
| [getValue()](#getValue--) | Representerar punktvärde. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representerar punktvärde. |
| [getFormula()](#getFormula--) | Formler inom värden, från, till, av attribut kan bestå av följande: Standard aritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (om) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (host stödda egenskaper) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formler inom värden, från, till, av attribut kan bestå av följande: Standard aritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (om) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (host stödda egenskaper) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Representerar tidsvärde. Läs/skriv float.

**Returnerar:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Representerar tidsvärde. Läs/skriv float.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Representerar punktvärde. Endast: bool, ColorFormat, float, int, string. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Representerar punktvärde. Endast: bool, ColorFormat, float, int, string. Läs/skriv Object.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formler inom värden, från, till, av attribut kan bestå av följande: Standard aritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (om) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (host stödda egenskaper) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String.

**Returnerar:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formler inom värden, från, till, av attribut kan bestå av följande: Standard aritmetiska operatorer: '+', '-', '*', '/', '^', '%' (mod) Konstanter: 'pi' 'e' Villkorsoperatorer: 'abs', 'min', 'max', '?' (om) Jämförelseoperatorer: '==', '>=', '', '!=', '!' Trigonometriska operatorer: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Naturlig logaritm 'ln()' Egendomsreferenser (host stödda egenskaper) till exempel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Läs/skriv String.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |