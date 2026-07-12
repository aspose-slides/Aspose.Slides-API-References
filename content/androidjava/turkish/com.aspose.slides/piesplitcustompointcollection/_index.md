---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Özel bir bölme ile bar-of-pie veya pie-of-pie grafiğinde bölme noktası için bir nokta koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/piesplitcustompointcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm uygulanmış arabirimler:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Özel bir bölme ile bar-of-pie veya pie-of-pie grafiğinde bölme noktası için bir nokta koleksiyonunu temsil eder.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizin için grafik veri noktasını döndürür. |
| [add(int dataPointIndex)](#add-int-) | Üst serinin nokta koleksiyonundaki indeksine göre veri noktasını ekler. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Veri noktasını koleksiyona ekler. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Öğeyi koleksiyondan kaldırır. |
| [remove(int dataPointIndex)](#remove-int-) | Üst serinin nokta koleksiyonundaki indeksine göre öğeyi koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm öğeleri [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kaldırır. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin olup olmadığını belirler. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini belirli bir dizi indeksinden başlayarak bir Array'e kopyalar. |
| [size()](#size--) | Grafik veri noktalarının sayısını döndürür veya ayarlar. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okunabilir olup olmadığını gösteren bir değer alır. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Belirtilen dizin için grafik veri noktasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Dizin. |

**Döndürür:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Grafik veri noktası.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Üst serinin nokta koleksiyonundaki indeksine göre veri noktasını ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPointIndex | int | Üst serinin nokta koleksiyonundaki veri noktasının indeksi. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Veri noktasını koleksiyona ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Eklenecek veri noktası. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Öğeyi koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Kaldırılacak veri noktası. |

**Döndürür:**
boolean - öğe başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem aynı zamanda öğe System.Collections.Generic.List{T} içinde bulunamazsa false döndürür.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Üst serinin nokta koleksiyonundaki indeksine göre öğeyi koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPointIndex | int | Üst serinin nokta koleksiyonundaki veri noktasının indeksi. |

### clear() {#clear--}
```
public final void clear()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'deki tüm öğeleri kaldırır.

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) içinde belirli bir değerin olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde aranacak nesne. |

**Döndürür:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerini belirli bir dizi indeksinden başlayarak bir Array'e kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan öğelerin hedefi olan tek boyutlu dizi. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizi indeksi (sıfır tabanlı). |

### size() {#size--}
```
public final int size()
```

Grafik veri noktalarının sayısını döndürür veya ayarlar. Salt okunur int.

**Döndürür:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'in yalnızca okunabilir olup olmadığını gösteren bir değer alır. Salt okunur boolean.

**Döndürür:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection) yalnızca okunabilir ise true; aksi takdirde false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Salt okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Döndürür:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Koleksiyon üzerinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Koleksiyon üzerinde yineleme yapılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Tüm koleksiyon için bir java.util.Iterator.