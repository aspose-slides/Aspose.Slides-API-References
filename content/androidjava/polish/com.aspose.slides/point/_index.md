---
title: Point
second_title: Aspose.Slides dla Androida - referencja API Java
description: Reprezentuje punkt animacji.
type: docs
url: /pl/com.aspose.slides/point/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Reprezentuje punkt animacji.
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [Point()](#Point--) | Domyślny konstruktor. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Utwórz punkt animacji z czasem, wartością i formułą. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getTime()](#getTime--) | Reprezentuje wartość czasu. |
| [setTime(float value)](#setTime-float-) | Reprezentuje wartość czasu. |
| [getValue()](#getValue--) | Reprezentuje wartość punktu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Reprezentuje wartość punktu. |
| [getFormula()](#getFormula--) | Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odwołania do własności (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Odczyt/zapis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odwołania do własności (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Odczyt/zapis String. |
### Point() {#Point--}
```
public Point()
```

Domyślny konstruktor.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Utwórz punkt animacji z czasem, wartością i formułą.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| time | float | Wartość czasu. |
| value | java.lang.Object | Wartość punktu. |
| formula | java.lang.String | Formuła. |

### getTime() {#getTime--}
```
public final float getTime()
```

Reprezentuje wartość czasu. Odczyt/zapis float.

**Zwraca:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Reprezentuje wartość czasu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Reprezentuje wartość punktu. Dozwolone typy: bool, ColorFormat, float, int, string. Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Reprezentuje wartość punktu. Dozwolone typy: bool, ColorFormat, float, int, string. Odczyt/zapis Object.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odwołania do własności (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów: Standardowe operatory arytmetyczne: '+', '-', '*', '/', '^', '%' (mod) Stałe: 'pi' 'e' Operatory warunkowe: 'abs', 'min', 'max', '?' (if) Operatory porównania: '==', '>=', '', '!=', '!' Operatory trygonometryczne: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarytm naturalny 'ln()' Odwołania do własności (właściwości obsługiwane przez host) na przykład: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |