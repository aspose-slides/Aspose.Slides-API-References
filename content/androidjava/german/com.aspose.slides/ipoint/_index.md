---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt einen Animationspunkt dar.
type: docs
url: /de/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Stellt einen Animationspunkt dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTime()](#getTime--) | Stellt einen Zeitwert dar. |
| [setTime(float value)](#setTime-float-) | Stellt einen Zeitwert dar. |
| [getValue()](#getValue--) | Stellt einen Punktwert dar. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Stellt einen Punktwert dar. |
| [getFormula()](#getFormula--) | Formeln innerhalb von Werten, von-, bis- und Schritt-Attributen können aus den folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formeln innerhalb von Werten, von-, bis- und Schritt-Attributen können aus den folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Stellt einen Zeitwert dar. Lesen/Schreiben float.

**Rückgabe:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Stellt einen Zeitwert dar. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Stellt einen Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lesen/Schreiben Object.

**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Stellt einen Punktwert dar. Nur: bool, ColorFormat, float, int, string. Lesen/Schreiben Object.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formeln innerhalb von Werten, von-, bis- und Schritt-Attributen können aus den folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formeln innerhalb von Werten, von-, bis- und Schritt-Attributen können aus den folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: '+', '-', '*', '/', '^', '%' (mod) Konstanten: 'pi' 'e' Bedingungsoperatoren: 'abs', 'min', 'max', '?' (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürlicher Logarithmus 'ln()' Property-Referenzen (vom Host unterstützte Eigenschaften) zum Beispiel: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |