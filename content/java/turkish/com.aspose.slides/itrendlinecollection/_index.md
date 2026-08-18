---
title: ITrendlineCollection
second_title: Aspose.Slides için Java API Referansı
description: TrendlineEx koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/itrendlinecollection/
---
**Tüm Uygulanan Arabirimler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

TrendlineEx koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [getCount()](#getCount--) | Koleksiyonda gerçekten bulunan öğe sayısını alır. |
| [add(int trendlineType)](#add-int-) | Yeni Trendline'ı koleksiyonun sonuna ekler ve döndürür. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Belirtilen değeri kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Belirtilen indeksdeki öğeyi alır. Salt okunur [ITrendline](../../com.aspose.slides/itrendline).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Koleksiyonda gerçekten bulunan öğe sayısını alır. Salt okunur int.

**Dönüş:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Yeni Trendline'ı koleksiyonun sonuna ekler ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| trendlineType | int | Trendline türü [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Dönüş:**
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