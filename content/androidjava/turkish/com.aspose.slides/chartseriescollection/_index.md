---
title: ChartSeriesCollection
second_title: Aspose.Slides Android için Java API Referansı
description: Koleksiyonunu temsil eder
type: docs
url: /tr/com.aspose.slides/chartseriescollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
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
| [add(int type)](#add-int-) | Yeni bir çizelge serisi oluşturur ve koleksiyona ekler. |
| [insert(int index, int type)](#insert-int-int-) | Yeni bir çizelge serisi oluşturur ve koleksiyona ekler. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Yeni bir çizelge serisini [ChartDataCell](../../com.aspose.slides/chartdatacell)'den oluşturur ve koleksiyona ekler. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Yeni bir çizelge serisini [ChartCellCollection](../../com.aspose.slides/chartcellcollection)'den oluşturur ve koleksiyona ekler. |
| [add(String name, int type)](#add-java.lang.String-int-) | Yeni bir çizelge serisini değerden oluşturur ve koleksiyona ekler. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Belirtilen [ChartSeries](../../com.aspose.slides/chartseries)'yi arar ve tüm koleksiyondaki ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Belirtilen değeri kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen konumda saklanan bir ActiveX denetimini koleksiyondan kaldırır. |
| [clear()](#clear--) | Koleksiyondaki tüm denetimleri kaldırır. |
| [iterator()](#iterator--) | Koleksiyon üzerinden yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm koleksiyonu belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Eşzamanlama kökü döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Belirtilen indeksdeki öğeyi alır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Belirtilen indeksdeki öğe.

### size() {#size--}
```
public final int size()
```

Koleksiyondaki nesne sayısını döndürür. Salt okunur int.

**Döndürür:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Yeni bir çizelge serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Seri tipi |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Yeni çizelge serisi.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Yeni bir çizelge serisi oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Yeni bir çizelge serisini [ChartDataCell](../../com.aspose.slides/chartdatacell)'den oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Seri adını içeren hücre. |
| type | int | Seri tipini ayarlar. |

--------------------

Eğer aynı hücreden oluşturulmuş bir çizelge serisi zaten koleksiyonda varsa, yöntem hiçbir şey eklemez ve dizinini döndürür.

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen çizelge serisi ya da zaten koleksiyonda olan seri.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Yeni bir çizelge serisini [ChartCellCollection](../../com.aspose.slides/chartcellcollection)'den oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Seri adını içeren hücreler. |
| type | int | Seri tipini ayarlar. |

--------------------

Eğer aynı hücreden oluşturulmuş bir çizelge serisi zaten koleksiyonda varsa, yöntem hiçbir şey eklemez ve dizinini döndürür.

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen çizelge serisi ya da zaten koleksiyonda olan seri.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Yeni bir çizelge serisini isimden oluşturur ve koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| name | java.lang.String | Seri adı. |
| type | int | Seri tipini ayarlar. |

**Döndürür:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Eklenen çizelge serisi.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Belirtilen [ChartSeries](../../com.aspose.slides/chartseries)'yi arar ve tüm Koleksiyon içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Çizelge serisi değeri. |

**Döndürür:**
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

Belirtilen konumda saklanan bir ActiveX denetimini koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak denetimin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Koleksiyondaki tüm denetimleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Koleksiyon üzerinden yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Koleksiyon üzerinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - Tüm koleksiyon için bir java.util.Iterator.

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

Koleksiyona erişimin eşzamanlı (thread-safe) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Eşzamanlama kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object