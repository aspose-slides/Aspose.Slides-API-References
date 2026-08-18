---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Az animációs pontot ábrázolja.
type: docs
url: /hu/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Az animációs pontot ábrázolja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTime()](#getTime--) | Az időértéket jelenti. |
| [setTime(float value)](#setTime-float-) | Az időértéket jelenti. |
| [getValue()](#getValue--) | Az pontértéket jelenti. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Az pontértéket jelenti. |
| [getFormula()](#getFormula--) | A képletek az értékekben, a from, to, by attribútumokban a következő elemekből állhatnak: Standard aritmetikai operátorok: '+', '-', '\*', '/', '^', '%' (mod) Konstansok: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Természetes logaritmus 'ln()' Tulajdonság-hivatkozások (a tárgyaló támogatott tulajdonságai) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | A képletek az értékekben, a from, to, by attribútumokban a következő elemekből állhatnak: Standard aritmetikai operátorok: '+', '-', '\*', '/', '^', '%' (mod) Konstansok: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Termész

és logaritmus 'ln()' Tulajdonság-hivatkozások (a tárgyaló támogatott tulajdonságai) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Az időértéket jelenti. Olvasás/írás float.

**Visszatér:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Az időértéket jelenti. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Az pontértéket jelenti. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Visszatér:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Az pontértéket jelenti. Csak: bool, ColorFormat, float, int, string. Olvasás/írás Object.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

A képletek az értékekben, a from, to, by attribútumokban a következő elemekből állhatnak: Standard aritmetikai operátorok: '+', '-', '\*', '/', '^', '%' (mod) Konstansok: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Termész

és logaritmus 'ln()' Tulajdonság-hivatkozások (a tárgyaló támogatott tulajdonságai) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Visszatér:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

A képletek az értékekben, a from, to, by attribútumokban a következő elemekből állhatnak: Standard aritmetikai operátorok: '+', '-', '\*', '/', '^', '%' (mod) Konstansok: 'pi' 'e' Feltételes operátorok: 'abs', 'min', 'max', '?' (if) Összehasonlító operátorok: '==', '>=', '', '!=', '!' Trigonometrikus operátorok: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Termész

és logaritmus 'ln()' Tulajdonság-hivatkozások (a tárgyaló támogatott tulajdonságai) például: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |