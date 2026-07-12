---
title: IPoint
second_title: Aspose.Slides Androidra a Java API hivatkozása
description: Animációs pontot jelöl.
type: docs
url: /hu/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Animációs pontot jelöl.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTime()](#getTime--) | Időértéket jelöl. |
| [setTime(float value)](#setTime-float-) | Időértéket jelöl. |
| [getValue()](#getValue--) | Pontértéket jelöl. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Pontértéket jelöl. |
| [getFormula()](#getFormula--) | A values, from, to, by attribútumokban lévő képletek ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometriai operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natúrlogaritmus 'ln()' Tulajdonság hivatkozások (host által támogatott tulajdonságok), például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | A values, from, to, by attribútumokban lévő képletek ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometriai operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natúrlogaritmus 'ln()' Tulajdonság hivatkozások (host által támogatott tulajdonságok), például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Időértéket jelöl. Olvasás/írás float.

**Visszatér:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Időértéket jelöl. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Pontértéket jelöl. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Visszatér:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Pontértéket jelöl. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

A values, from, to, by attribútumokban lévő képletek ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometriai operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natúrlogaritmus 'ln()' Tulajdonság hivatkozások (host által támogatott tulajdonságok), például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Visszatér:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

A values, from, to, by attribútumokban lévő képletek ezekből állhatnak: Standard aritmetikai operátorok: '+', '-', '*', '/', '^', '%' (mod) Állandók: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometriai operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natúrlogaritmus 'ln()' Tulajdonság hivatkozások (host által támogatott tulajdonságok), például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |