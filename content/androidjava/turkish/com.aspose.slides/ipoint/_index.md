---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Animasyon noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Animasyon noktasını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTime()](#getTime--) | Zaman değerini temsil eder. |
| [setTime(float value)](#setTime-float-) | Zaman değerini temsil eder. |
| [getValue()](#getValue--) | Nokta değerini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Nokta değerini temsil eder. |
| [getFormula()](#getFormula--) | Değerlerdeki, from, to, by özniteliklerinde formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host destekli özellikler) örnek: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Okunur/yazılabilir String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Değerlerdeki, from, to, by özniteliklerinde formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host destekli özellikler) örnek: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Okunur/yazılabilir String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Zaman değerini temsil eder. Okunur/yazılabilir float.

**Döndürür:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Zaman değerini temsil eder. Okunur/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunur/yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunur/yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Değerlerdeki, from, to, by özniteliklerinde formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host destekli özellikler) örnek: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Okunur/yazılabilir String.

**Döndürür:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Değerlerdeki, from, to, by özniteliklerinde formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host destekli özellikler) örnek: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Okunur/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |