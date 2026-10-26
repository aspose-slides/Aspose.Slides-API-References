---
title: Point
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt animatiepunt.
type: docs
url: /nl/com.aspose.slides/point/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Represent animation point.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Point()](#Point--) | Standaardconstructor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Maak een animatiepunt met tijd, waarde en formule. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getTime()](#getTime--) | Vertegenwoordigt tijdwaarde. |
| [setTime(float value)](#setTime-float-) | Vertegenwoordigt tijdwaarde. |
| [getValue()](#getValue--) | Vertegenwoordigt puntwaarde. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Vertegenwoordigt puntwaarde. |
| [getFormula()](#getFormula--) | Formules binnen waarden, van, naar, stap-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Lezen/schrijven String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formules binnen waarden, van, naar, stap-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Lezen/schrijven String. |
### Point() {#Point--}
```
public Point()
```


Standaardconstructor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Maak een animatiepunt met tijd, waarde en formule.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| time | float | Tijdwaarde. |
| value | java.lang.Object | Puntwaarde. |
| formula | java.lang.String | Formule. |

### getTime() {#getTime--}
```
public final float getTime()
```


Vertegenwoordigt tijdwaarde. Lezen/schrijven float.

**Retourwaarde:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Vertegenwoordigt tijdwaarde. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Vertegenwoordigt puntwaarde. Alleen: bool, ColorFormat, float, int, string. Lezen/schrijven Object.

**Retourwaarde:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Vertegenwoordigt puntwaarde. Alleen: bool, ColorFormat, float, int, string. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Formules binnen waarden, van, naar, stap-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Lezen/schrijven String.

**Retourwaarde:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Formules binnen waarden, van, naar, stap-attributen kunnen bestaan uit deze: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Conditionele operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (host-ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |