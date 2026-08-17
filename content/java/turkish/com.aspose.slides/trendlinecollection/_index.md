---
title: TrendlineCollection
second_title: Aspose.Slides for Java API Referansı
description: Trendline koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/trendlinecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Trendline koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [add(int trendlineType)](#add-int-) | Yeni Trendline'ı bir koleksiyonun sonuna ekler ve döndürür. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Belirtilen değeri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ı döndürür. |
| [getCount()](#getCount--) | Koleksiyonun içinde gerçekten bulunan öğe sayısını alır. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. Salt-okunur [Trendline](../../com.aspose.slides/trendline).

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

Yeni Trendline'ı bir koleksiyonun sonuna ekler ve döndürür.

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

Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Bir IGenericEnumerator, koleksiyon içinde yineleme için kullanılabilir.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

Tüm koleksiyon için bir java iterator'ı döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Tüm koleksiyon için bir java.util.Iterator.
### getCount() {#getCount--}
```
public final int getCount()
```

Koleksiyonun içinde gerçekten bulunan öğe sayısını alır. Salt-okunur int.

**Döndürür:**
int