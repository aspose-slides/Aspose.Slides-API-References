---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides for Android via Java API Referansı
description: Grafik veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/chartdataworksheetcollection/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

Grafik veri çalışma kitabının çalışma sayfalarının koleksiyonunu temsil eder.

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

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | İndeks ile çalışma sayfasını döndürür. |
| [size()](#size--) | Sayacı döndürür. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | Tam koleksiyon için bir java yineleyicisi döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde dolaşan bir enumerator döndürür. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

İndeks ile çalışma sayfasını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Koleksiyondaki çalışma sayfasının indeksi. |

**Döndürür:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet örneği.
### size() {#size--}
```
public final int size()
```

Sayacı döndürür. Yalnızca okunabilir int.

**Döndürür:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Yalnızca okunabilir IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

Tam koleksiyon için bir java yineleyicisi döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Koleksiyon içinde dolaşmak için kullanılabilen bir IGenericEnumerator.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

Koleksiyon içinde dolaşan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - Koleksiyon içinde dolaşmak için kullanılabilen bir IGenericEnumerator.
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

Belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Kopyalanacak dizi. |
| arrayIndex | int | Kopyalamaya başlanacak indeks. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okunabilir boolean.

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Bir senkronizasyon kökü döndürür. Yalnızca okunabilir Object.

**Döndürür:**
java.lang.Object