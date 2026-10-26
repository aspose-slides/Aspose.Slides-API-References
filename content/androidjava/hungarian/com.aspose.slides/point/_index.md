---
title: Point
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Animációs pontot ábrázol.
type: docs
url: /hu/com.aspose.slides/point/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Animációs pontot ábrázol.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Point()](#Point--) | Alapértelmezett konstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Animációs pont létrehozása idővel, értékkel és képlettel. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTime()](#getTime--) | Az időértéket jelöli. |
| [setTime(float value)](#setTime-float-) | Az időértéket jelöli. |
| [getValue()](#getValue--) | A pontértéket jelöli. |
| [setValue(Object value)](#setValue-java.lang.Object-) | A pontértéket jelöli. |
| [getFormula()](#getFormula--) | Képletek az értékekben, valamint a from, to, by attribútumokban ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürális logaritmus 'ln()' Tulajdonság hivatkozások (a gazda által támogatott tulajdonságok) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Képletek az értékekben, valamint a from, to, by attribútumokban ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürális logaritmus 'ln()' Tulajdonság hivatkozások (a gazda által támogatott tulajdonságok) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
### Point() {#Point--}
```
public Point()
```

Alapértelmezett konstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Animációs pont létrehozása idővel, értékkel és képlettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| time | float | Az időérték. |
| value | java.lang.Object | A pontérték. |
| formula | java.lang.String | Képlet. |

### getTime() {#getTime--}
```
public final float getTime()
```

Az időértéket jelöli. Olvasás/írás float.

**Visszatérési érték:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Az időértéket jelöli. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

A pontértéket jelöli. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Visszatérési érték:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

A pontértéket jelöli. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Képletek az értékekben, valamint a from, to, by attribútumokban ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürális logaritmus 'ln()' Tulajdonság hivatkozások (a gazda által támogatott tulajdonságok) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Képletek az értékekben, valamint a from, to, by attribútumokban ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natürális logaritmus 'ln()' Tulajdonság hivatkozások (a gazda által támogatott tulajdonságok) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |