---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides Java API Referansı
description: Özel bir bölünme ile bar-of-pie veya pie-of-pie grafiğinde ikinci pasta veya çubukta çizilecek nokta koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ipiesplitcustompointcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Özel bir bölünme ile bar-of-pie veya pie-of-pie grafiklerinde ikinci pasta veya çubukta çizilecek nokta koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndex'e göre grafik veri noktasını döndürür. |
| [add(int dataPointIndex)](#add-int-) | Üst serinin nokta koleksiyonundaki indeksine göre veri noktasını ekler. |
| [remove(int dataPointIndex)](#remove-int-) | Üst serinin nokta koleksiyonundaki indeksine göre öğeyi koleksiyondan kaldırır. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


İndex'e göre grafik veri noktasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Veri noktasının indeksi. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Grafik veri noktası.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Üst serinin nokta koleksiyonundaki indeksine göre veri noktasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPointIndex | int | Üst serinin nokta koleksiyonundaki veri noktasının indeksi. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Üst serinin nokta koleksiyonundaki indeksine göre öğeyi koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPointIndex | int | Üst serinin nokta koleksiyonundaki veri noktasının indeksi.. |