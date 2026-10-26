---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje punkt animacji.
type: docs
url: /pl/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Reprezentuje punkt animacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTime()](#getTime--) | Reprezentuje wartość czasu. |
| [setTime(float value)](#setTime-float-) | Reprezentuje wartość czasu. |
| [getValue()](#getValue--) | Reprezentuje wartość punktu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Reprezentuje wartość punktu. |
| [getFormula()](#getFormula--) | Formuły w wartościach, atrybutach from, to, by mogą być tworzone z następujących: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odniesienia do właściwości (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Odczyt/zapis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formuły w wartościach, atrybutach from, to, by mogą być tworzone z następujących: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odniesienia do właściwości (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Odczyt/zapis String. |

### getTime() {#getTime--}
```
public abstract float getTime()
```

Reprezentuje wartość czasu. Odczyt/zapis float.

**Zwraca:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Reprezentuje wartość czasu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Reprezentuje wartość punktu. Tylko: bool, ColorFormat, float, int, string. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Reprezentuje wartość punktu. Tylko: bool, ColorFormat, float, int, string. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formuły w wartościach, atrybutach from, to, by mogą być tworzone z następujących: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odniesienia do właściwości (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formuły w wartościach, atrybutach from, to, by mogą być tworzone z następujących: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odniesienia do właściwości (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |