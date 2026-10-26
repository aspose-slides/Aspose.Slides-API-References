---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Represent animation point.
type: docs
url: /tr/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Animasyon noktasını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTime()](#getTime--) | Zaman değerini temsil eder. |
| [setTime(float value)](#setTime-float-) | Zaman değerini temsil eder. |
| [getValue()](#getValue--) | Nokta değerini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Nokta değerini temsil eder. |
| [getFormula()](#getFormula--) | Değerler, from, to, by özniteliklerinde kullanılan formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörleri: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host desteklenen özellikler) örneğin: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Okunabilir/yazılabilir String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Değerler, from, to, by özniteliklerinde kullanılan formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörleri: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host desteklenen özellikler) örneğin: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Okunabilir/yazılabilir String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Zaman değerini temsil eder. Okunabilir/yazılabilir float.

**Döndürür:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Zaman değerini temsil eder. Okunabilir/yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunabilir/yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunabilir/yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Değerler, from, to, by özniteliklerinde kullanılan formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörleri: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host desteklenen özellikler) örneğin: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Okunabilir/yazılabilir String.

**Döndürür:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Değerler, from, to, by özniteliklerinde kullanılan formüller şu bileşenlerden oluşabilir: Standart aritmetik operatörleri: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host desteklenen özellikler) örneğin: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Okunabilir/yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |