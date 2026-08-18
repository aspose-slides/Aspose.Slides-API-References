---
title: ChartSeriesCollection
second_title: Aspose.Slides for Java API Referansı
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/chartseriescollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

[ChartSeries](../../com.aspose.slides/chartseries) koleksiyonunu temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki öğeyi alır. |
| [size()](#size--) | Koleksiyondaki nesne sayısını döndürür. |
| [add(int type)](#add-int-) | Yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [insert(int index, int type)](#insert-int-int-) | Yeni bir grafik serisi oluşturur ve koleksiyona yerleştirir. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) kaynaklı yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | [ChartCellCollection](../../com.aspose.slides/chartcellcollection) kaynaklı yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [add(String name, int type)](#add-java.lang.String-int-) | Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Belirtilen [ChartSeries](../../com.aspose.slides/chartseries)'yi arar ve tüm Koleksiyon içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen konumda saklanan bir ActiveX kontrolünü koleksiyondan kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm kontrolleri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumeratörü döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator'ı döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Senkronizasyon kökünü döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Belirtilen indeksdeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Belirtilen indeksteki öğe.

### size() {#size--}
```
public final int size()
```

Koleksiyondaki nesne sayısını döndürür. Salt-okunur int.

**Dönüş Değeri:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Seri tipi |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Yeni grafik serisi.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Yeni bir grafik serisi oluşturur ve koleksiyona yerleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

[ChartDataCell](../../com.aspose.slides/chartdatacell) kaynaklı yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Seri adını içeren hücre. |
| type | int | Seri tipini ayarlayan tip

--------------------

Aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa, yöntem hiçbir şey eklemez ve indeksini döndürür. |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi veya zaten koleksiyonda olan seri.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

[ChartCellCollection](../../com.aspose.slides/chartcellcollection) kaynaklı yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Seri adını içeren hücreler. |
| type | int | Seri tipini ayarlayan tip

--------------------

Aynı hücreden oluşturulan grafik serisi zaten koleksiyonda varsa, yöntem hiçbir şey eklemez ve indeksini döndürür. |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi veya zaten koleksiyonda olan seri.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Değerden yeni bir grafik serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Seri adı. |
| type | int | Seri tipini ayarlayan tip |

**Dönüş Değeri:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen grafik serisi.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Belirtilen [ChartSeries](../../com.aspose.slides/chartseries)'yi arar ve tüm Koleksiyon içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Grafik serisi değeri. |

**Dönüş Değeri:**
int - Değerin tüm CollectionBase içinde ilk oluşumunun sıfır tabanlı indeksi, bulunursa; aksi takdirde -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Belirtilen değeri kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Değer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Belirtilen konumda saklanan bir ActiveX kontrolünü koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak kontrolün indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm kontrolleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Koleksiyon içinde yineleme yapan bir enumeratörü döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Tüm koleksiyon için bir java iterator'ı döndürür.

**Dönüş Değeri:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Tüm koleksiyonu belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi |
| index | int | Hedef dizideki indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt-okunur boolean.

**Dönüş Değeri:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Senkronizasyon kökünü döndürür. Salt-okunur Object.

**Dönüş Değeri:**
java.lang.Object