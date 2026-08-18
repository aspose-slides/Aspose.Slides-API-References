---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides için Java API Referansı
description: Grafik veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartdataworksheetcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Chart veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndekse göre çalışma sayfasını döndürür. |
| [size()](#size--) | Sayımı döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java yineleyicisi döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde yineleme yapan bir enumerator döndürür. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

İndekse göre çalışma sayfasını döndürür.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Koleksiyondaki çalışma sayfasının indeksi. |

**Döndürür:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet örneği.

### size() {#size--}
```
public final int size()
```

Sayımı döndürür. Salt-okunur int.

**Döndürür:**
int

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Tüm koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Koleksiyon içinde yineleme yapmak için kullanılabilecek bir IGenericEnumerator.

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Belirtilen diziye kopyalar.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kopyalanacak dizi. |
| arrayIndex | int | Kopyalamaya başlanacak indeks. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (çok iş parçacıklı) olup olmadığını belirten bir değer döndürür. Salt-okunur boolean.

**Döndürür:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Salt-okunur Object.

**Döndürür:**
java.lang.Object