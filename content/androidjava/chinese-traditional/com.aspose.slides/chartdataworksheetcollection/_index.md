---
title: ChartDataWorksheetCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示圖表資料工作簿的工作表集合。
type: docs
url: /zh-hant/com.aspose.slides/chartdataworksheetcollection/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection), com.aspose.slides.IDOMObject  
```
public final class ChartDataWorksheetCollection implements IChartDataWorksheetCollection, IDOMObject
```

代表圖表資料工作簿的工作表集合。

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
## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回依索引的工作表。 |
| [size()](#size--) | 傳回計數。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iteratorJava()](#iteratorJava--) | 傳回用於整個集合的 java 迭代器。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | 複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataWorksheet get_Item(int index)
```

傳回依索引的工作表。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 集合中工作表的索引。 |

**傳回:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet 的實例。
### size() {#size--}
```
public final int size()
```

傳回計數。唯讀 int。

**傳回:**
int
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回:**
com.aspose.slides.IDOMObject
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iteratorJava()
```

傳回用於整個集合的 java 迭代器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - 可用於遍歷集合的 IGenericEnumerator。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataWorksheet> iterator()
```

傳回遍歷集合的列舉器。

**傳回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataWorksheet> - 可用於遍歷集合的 IGenericEnumerator。
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

複製到指定的陣列。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要複製至的陣列。 |
| arrayIndex | int | 開始複製的索引。 |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**傳回:** 
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**傳回:**
java.lang.Object