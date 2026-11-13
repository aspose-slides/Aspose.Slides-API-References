---
title: CachedChartValue
second_title: Aspose.Slides için Java API Referansı
description: Önbelleğe alınmış bir grafik değerini temsil eder (ör. X, Y, balon boyutu veya ana değer).
type: docs
url: /tr/com.aspose.slides/cachedchartvalue/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Önbelleğe alınmış bir grafik değeri temsil eder (ör. X, Y, balon boyutu veya ana değer).
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [toString()](#toString--) | Önbelleğe alınmış değerin dize temsili döndürür. |
| [toDouble()](#toDouble--) | Önbelleğe alınmış değeri bir double'a dönüştürür. |
| [getData()](#getData--) | Önbelleğe alınmış veri nesnesini alır. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Önbelleğe alınmış değerin dize temsili döndürür.

**Döndürür:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Önbelleğe alınmış değeri bir double'a dönüştürür.

**Döndürür:**
double - Sayısal temsil, ya da Data (\#getData.getData/\#setData(Object).setData(Object)) null ise veya bir double'a dönüştürülemezse Double.NaN.
### getData() {#getData--}
```
public final Object getData()
```


Önbelleğe alınmış veri nesnesini alır.  Salt okunur  Object .

**Döndürür:**
java.lang.Object