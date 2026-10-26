---
title: Point
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Animationspunkt dar.
type: docs
url: /de/com.aspose.slides/point/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Stellt einen Animationspunkt dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Point()](#Point--) | Standardkonstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Erzeugt einen Animationspunkt mit Zeit, Wert und Formel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTime()](#getTime--) | Stellt den Zeitwert dar. |
| [setTime(float value)](#setTime-float-) | Stellt den Zeitwert dar. |
| [getValue()](#getValue--) | Stellt den Punktwert dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stellt den Punktwert dar. |
| [getFormula()](#getFormula--) | Formeln innerhalb von Werten, from, to, by-Attributen können aus folgenden Elementen bestehen: Standardarithmetikoperatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formeln innerhalb von Werten, from, to, by-Attributen können aus folgenden Elementen bestehen: Standardarithmetikoperatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String. |
### Point() {#Point--}
```
public Point()
```

Standardkonstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Erzeugt einen Animationspunkt mit Zeit, Wert und Formel.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| time | float | Zeitwert. |
| value | java.lang.Object | Punktwert. |
| formula | java.lang.String | Formel. |

### getTime() {#getTime--}
```
public final float getTime()
```

Stellt den Zeitwert dar. Lesen/Schreiben float.

**Rückgabe:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Stellt den Zeitwert dar. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Stellt den Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lesen/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Stellt den Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formeln innerhalb von Werten, from, to, by-Attributen können aus folgenden Elementen bestehen: Standardarithmetikoperatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formeln innerhalb von Werten, from, to, by-Attributen können aus folgenden Elementen bestehen: Standardarithmetikoperatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |