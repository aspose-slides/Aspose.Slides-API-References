---
title: Point
second_title: Aspose.Slides Java API-referencia
description: Animációs pontot képvisel.
type: docs
url: /hu/com.aspose.slides/point/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Animációs pontot képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Point()](#Point--) | Alapértelmezett konstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Animációs pont létrehozása idővel, értékkel és formulával. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTime()](#getTime--) | Az időértéket képviseli. |
| [setTime(float value)](#setTime-float-) | Az időértéket képviseli. |
| [getValue()](#getValue--) | A pontértéket képviseli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | A pontértéket képviseli. |
| [getFormula()](#getFormula--) | Az értékeken, from, to, by attribútumokban használt képletek a következőkből állhatnak: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Az értékeken, from, to, by attribútumokban használt képletek a következőkből állhatnak: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
### Point() {#Point--}
```
public Point()
```

Alapértelmezett konstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Animációs pont létrehozása idővel, értékkel és formulával.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| time | float | Időérték. |
| value | java.lang.Object | Pontérték. |
| formula | java.lang.String | Formula. |

### getTime() {#getTime--}
```
public final float getTime()
```

Az időértéket képviseli. Olvasás/írás float.

**Visszatér:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Az időértéket képviseli. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

A pontértéket képviseli. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Visszatér:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

A pontértéket képviseli. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Az értékeken, from, to, by attribútumokban használt képletek a következőkből állhatnak: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Visszatér:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Az értékeken, from, to, by attribútumokban használt képletek a következőkből állhatnak: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |