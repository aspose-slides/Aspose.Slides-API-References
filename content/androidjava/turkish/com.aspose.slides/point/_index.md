---
title: Point
second_title: Aspose.Slides Android için Java API Referansı
description: Animasyon noktasını temsil eder.
type: docs
url: /tr/com.aspose.slides/point/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Animasyon noktasını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Point()](#Point--) | Varsayılan yapıcı. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Zaman, değer ve formülle animasyon noktası oluşturur. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getTime()](#getTime--) | Zaman değerini temsil eder. |
| [setTime(float value)](#setTime-float-) | Zaman değerini temsil eder. |
| [getValue()](#getValue--) | Nokta değerini temsil eder. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Nokta değerini temsil eder. |
| [getFormula()](#getFormula--) | Değerler, from, to, by öznitelikleri içindeki formüller şunlardan oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host supported properties) örnek: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Okunabilir/Yazılabilir String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Değerler, from, to, by öznitelikleri içindeki formüller şunlardan oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host supported properties) örnek: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Okunabilir/Yazılabilir String. |
### Point() {#Point--}
```
public Point()
```


Varsayılan yapıcı.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Zaman, değer ve formülle animasyon noktası oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| time | float | Zaman değeri. |
| value | java.lang.Object | Nokta değeri. |
| formula | java.lang.String | Formül. |

### getTime() {#getTime--}
```
public final float getTime()
```


Zaman değerini temsil eder. Okunabilir/Yazılabilir float.

**Döndürür:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Zaman değerini temsil eder. Okunabilir/Yazılabilir float.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunabilir/Yazılabilir Object.

**Döndürür:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Nokta değerini temsil eder. Yalnızca: bool, ColorFormat, float, int, string. Okunabilir/Yazılabilir Object.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Değerler, from, to, by öznitelikleri içindeki formüller şunlardan oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host supported properties) örnek: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Okunabilir/Yazılabilir String.

**Döndürür:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Değerler, from, to, by öznitelikleri içindeki formüller şunlardan oluşabilir: Standart aritmetik operatörler: '+', '-', '*', '/', '^', '%' (mod) Sabitler: 'pi' 'e' Koşullu operatörler: 'abs', 'min', 'max', '?' (if) Karşılaştırma operatörleri: '==', '>=', '', '!=', '!' Trigonometrik operatörler: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Doğal logaritma 'ln()' Özellik referansları (host supported properties) örnek: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Okunabilir/Yazılabilir String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |