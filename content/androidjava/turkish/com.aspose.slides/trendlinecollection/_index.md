---
title: TrendlineCollection
second_title: Aspose.Slides for Android Java API Referansı
description: Trendline koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/trendlinecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline koleksiyonunu temsil eder
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(int trendlineType)](#add-int-) | Yeni Trendline'ı koleksiyonun sonuna ekler ve döndürür. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Belirtilen değeri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getCount()](#getCount--) | Koleksiyon içinde gerçek anlamda tutulan öğe sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Yalnızca okuma [Trendline](../../com.aspose.slides/trendline).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

Yeni Trendline'ı koleksiyonun sonuna ekler ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| trendlineType | int |  |

**Döndürür:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyon içinde gerçek anlamda tutulan öğe sayısını alır. Yalnızca okuma int.

**Döndürür:**
int