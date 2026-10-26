---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides için Java API Referansı
description: Özel bir bölme ile bar-pie veya pie-of-pie grafiğinde bölme noktası için bir nokta koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/piesplitcustompointcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Özel bir bölme ile çubuk-pie veya pie-of-pie grafiğinde bölme noktası için bir nokta koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeks için grafik veri noktasını döndürür. |
| [add(int dataPointIndex)](#add-int-) | Üst serinin nokta koleksiyonundaki indeksiyle veri noktasını ekler. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Veri noktasını koleksiyona ekler. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Koleksiyondan öğeyi kaldırır. |
| [remove(int dataPointIndex)](#remove-int-) | Üst serinin nokta koleksiyonundaki indeksiyle koleksiyondan öğeyi kaldırır. |
| [clear()](#clear--) | Tüm öğeleri [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kaldırır. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerinin bir Dizine (Array) belirli bir dizi indeksinden başlayarak kopyalar. |
| [size()](#size--) | Grafik veri noktalarının sayısını döndürür veya ayarlar. |
| [isReadOnly()](#isReadOnly--) | [IGenericCollection](../../com.aspose.slides/igenericcollection)'un salt okunur olup olmadığını gösteren bir değeri alır. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Belirtilen indeks için grafik veri noktasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İndeks. |

**Dönüş:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Grafik veri noktası.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Üst serinin nokta koleksiyonundaki indeksiyle veri noktasını ekler.

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

Koleksiyondan öğeyi kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Kaldırılacak veri noktası. |

**Dönüş:**
boolean - öğe başarılı bir şekilde kaldırıldıysa true; aksi takdirde false. Bu metod ayrıca öğe System.Collections.Generic.List\{T\}'de bulunamazsa false döndürür.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Üst serinin nokta koleksiyonundaki indeksiyle koleksiyondan öğeyi kaldırır.

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

Belirli bir değerin [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde konumlandırılacak nesne. |

**Dönüş:**
boolean - öğe [IGenericCollection](../../com.aspose.slides/igenericcollection) içinde bulunursa true; aksi takdirde false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) öğelerinin bir Dizine (Array) belirli bir dizi indeksinden başlayarak kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Elemanların kopyalanacağı tek boyutlu Dizi. [IGenericCollection](../../com.aspose.slides/igenericcollection)'den kopyalanan öğelerin hedefidir. Dizi sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex | int | Kopyalamanın başlayacağı dizideki sıfır tabanlı indeks. |
### size() {#size--}
```
public final int size()
```

Grafik veri noktalarının sayısını döndürür veya ayarlar. Salt okunur int.

**Dönüş:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection)'un salt okunur olup olmadığını gösteren bir değeri alır. Salt okunur boolean.

**Dönüş:**
boolean - [IGenericCollection](../../com.aspose.slides/igenericcollection)'un salt okunur olması durumunda true; aksi takdirde false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değeri döndürür. Salt okunur boolean.

**Dönüş:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt okunur Object.

**Dönüş:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Dönüş:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Koleksiyon içinde yinelemek için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Dönüş:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - tüm koleksiyon için bir java.util.Iterator.