---
title: Point
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje animační bod.
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

Reprezentuje animační bod.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Point()](#Point--) | Výchozí konstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Vytvoří animační bod s časem, hodnotou a vzorcem. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getTime()](#getTime--) | Representuje časovou hodnotu. |
| [setTime(float value)](#setTime-float-) | Representuje časovou hodnotu. |
| [getValue()](#getValue--) | Representuje hodnotu bodu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representuje hodnotu bodu. |
| [getFormula()](#getFormula--) | Vzorce v hodnotách, atributech from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (host podporované vlastnosti) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Číst/zapisovat String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Vzorce v hodnotách, atributech from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (host podporované vlastnosti) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Číst/zapisovat String. |
### Point() {#Point--}
```
public Point()
```

Výchozí konstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Vytvoří animační bod s časem, hodnotou a vzorcem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| time | float | Časová hodnota. |
| value | java.lang.Object | Hodnota bodu. |
| formula | java.lang.String | Vzorec. |

### getTime() {#getTime--}
```
public final float getTime()
```

Representuje časovou hodnotu. Číst/zapisovat float.

**Návratová hodnota:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Representuje časovou hodnotu. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Representuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Číst/zapisovat Object.

**Návratová hodnota:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Representuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Číst/zapisovat Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Vzorce v hodnotách, atributech from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (host podporované vlastnosti) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Číst/zapisovat String.

**Návratová hodnota:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Vzorce v hodnotách, atributech from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (host podporované vlastnosti) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |