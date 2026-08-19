---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Representatie van een animatiepunt.
type: docs
url: /nl/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Representatie van een animatiepunt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTime()](#getTime--) | Stelt tijdwaarde voor. |
| [setTime(float value)](#setTime-float-) | Stelt tijdwaarde voor. |
| [getValue()](#getValue--) | Stelt puntwaarde voor. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stelt puntwaarde voor. |
| [getFormula()](#getFormula--) | Formules binnen waarden, van-, tot- en door-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formules binnen waarden, van-, tot- en door-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Stelt tijdwaarde voor. Lezen/Schrijven float.

**Retourneert:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Stelt tijdwaarde voor. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Stelt puntwaarde voor. Alleen: bool, ColorFormat, float, int, string. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Stelt puntwaarde voor. Alleen: bool, ColorFormat, float, int, string. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formules binnen waarden, van-, tot- en door-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formules binnen waarden, van-, tot- en door-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |