---
title: Point
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Erstellt einen Animationspunkt mit Zeit, Wert und Formel. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTime()](#getTime--) | Stellt den Zeitwert dar. |
| [setTime(float value)](#setTime-float-) | Stellt den Zeitwert dar. |
| [getValue()](#getValue--) | Stellt den Punktwert dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stellt den Punktwert dar. |
| [getFormula()](#getFormula--) | Formeln innerhalb von Werten, den Attributen from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lese/Schreib String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formeln innerhalb von Werten, den Attributen from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lese/Schreib String. |
### Point() {#Point--}
```
public Point()
```

Standardkonstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Erstellt einen Animationspunkt mit Zeit, Wert und Formel.

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

Stellt den Zeitwert dar. Lese/Schreib float.

**Rückgabewert:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Stellt den Zeitwert dar. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Stellt den Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lese/Schreib Object.

**Rückgabewert:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Stellt den Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lese/Schreib Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formeln innerhalb von Werten, den Attributen from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lese/Schreib String.

**Rückgabewert:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formeln innerhalb von Werten, den Attributen from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |