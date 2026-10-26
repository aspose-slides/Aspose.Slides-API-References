---
title: ITrendlineCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: TrendlineEx öğelerinin bir koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/itrendlinecollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx öğelerinin bir koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekte bulunan öğe sayısını alır. |
| [add(int trendlineType)](#add-int-) | Yeni Trendline'ı bir koleksiyonun sonuna ekler ve döndürür. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Belirtilen değeri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Belirtilen indeksteki öğeyi alır. Yalnızca okuma [ITrendline](../../com.aspose.slides/itrendline).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonda gerçekte bulunan öğe sayısını alır. Yalnızca okuma int.

**Döndürür:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Yeni Trendline'ı bir koleksiyonun sonuna ekler ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| trendlineType | int | Trendline türü [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Döndürür:**
[ITrendline](../../com.aspose.slides/itrendline) - Yeni Trendline [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Kaldırılacak Trendline [ITrendline](../../com.aspose.slides/itrendline) |