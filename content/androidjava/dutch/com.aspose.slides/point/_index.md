---
title: Point
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt animatiepunt.
type: docs
url: /nl/com.aspose.slides/point/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Vertegenwoordigt animatiepunt.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Point()](#Point--) | Standaardconstructor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Maak animatiepunt met tijd, waarde en formule. |

## Methods

| Methode | Beschrijving |
| --- | --- |
| [getTime()](#getTime--) | Stelt tijdwaarde voor. |
| [setTime(float value)](#setTime-float-) | Stelt tijdwaarde voor. |
| [getValue()](#getValue--) | Stelt puntwaarde voor. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stelt puntwaarde voor. |
| [getFormula()](#getFormula--) | Formules binnen waarden, van, tot, door attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formules binnen waarden, van, tot, door attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String. |

### Point() {#Point--}
```
public Point()
```

Standaardconstructor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Maak animatiepunt met tijd, waarde en formule.

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

Stelt tijdwaarde voor. Lezen/Schrijven float.

**Retourneert:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Stelt tijdwaarde voor. Lezen/Schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Stelt puntwaarde voor. Alleen: bool, ColorFormat, float, int, string. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Stelt puntwaarde voor. Alleen: bool, ColorFormat, float, int, string. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formules binnen waarden, van, tot, door attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String.

**Retourneert:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formules binnen waarden, van, tot, door attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |