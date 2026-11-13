---
title: DataLabelCollection
second_title: Aspose.Slides for Java API 參考
description: 代表系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/datalabelcollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

代表系列標籤。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getChart()](#getChart--) | 返回父圖表。 |
| [iterator()](#iterator--) | 返回一個遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [isVisible()](#isVisible--) | False 表示資料標籤預設不顯示（因此 DefaultDataLabelFormat 屬性的所有 Show\*-旗標 (ShowValue, ...) 為 false）。 |
| [hide()](#hide--) | 透過將 DefaultDataLabelFormat 屬性的所有 Show\*-旗標 (ShowValue, ...) 設為 false，使資料標籤預設隱藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 取得集合中可見資料標籤的數量。 |
| [getCount()](#getCount--) | 取得集合中所有資料標籤的數量。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 取得預設資料標籤格式。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 代表資料標籤引導線格式。 |
| [getParentSeries()](#getParentSeries--) | 取得父系列。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 返回集合中指定 DataLabel 的索引。 |
| [get_Item(int index)](#get-Item-int-) | 取得具有指定索引之資料點的資料標籤。 |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | 取得或設定資料標籤的預設形狀類型。 |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | 取得或設定資料標籤的預設形狀類型。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |

### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**傳回值:**  
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

返回可遍歷集合的列舉器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 可用來遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

返回整個集合的 java 迭代器。

**傳回值:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 可用來遍歷集合的 IGenericEnumerator。

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False 表示資料標籤預設不可見（因此 DefaultDataLabelFormat 屬性的所有 Show\*-旗標 (ShowValue, ...) 為 false）。唯讀 boolean.

--------------------

如果資料標籤預設可見，您可以使用 Hide() 方法將其預設設定為隱藏。但若資料標籤預設不可見（IsVisible 為 false），則可透過將 DefaultDataLabelFormat 屬性的 Show\*-旗標 (ShowValue, ...) 設為 true，將資料標籤「預設可見」。

**傳回值:**  
boolean

### hide() {#hide--}
```
public final void hide()
```

透過將 DefaultDataLabelFormat 屬性的所有 Show\*-旗標 (ShowValue, ...) 設為 false，使資料標籤預設隱藏。此後 IsVisible 將為 false。

--------------------

如果資料標籤預設不可見（IsVisible 為 false），則可透過將 DefaultDataLabelFormat 屬性的 Show\*-旗標 (ShowValue, ...) 設為 true，將資料標籤「預設可見」。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

取得集合中可見資料標籤的數量。唯讀 int。

**傳回值:**  
int

### getCount() {#getCount--}
```
public final int getCount()
```

取得集合中所有資料標籤的數量。唯讀 int。

**傳回值:**  
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

取得預設資料標籤格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**傳回值:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

代表資料標籤引導線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**傳回值:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

取得父系列。唯讀 [IChartSeries](../../com.aspose.slides/ichartseries)。

**傳回值:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

返回集合中指定 DataLabel 的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 要尋找的 DataLabel。 |

**傳回值:**
int - DataLabel 的索引，若 DataLabel 不屬於此集合則返回 -1。

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

取得具有指定索引之資料點的資料標籤。

--------------------

存取資料標籤的其他方式為：- series.getDataPoints().get_Item(i).getLabel() - 管理標籤屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

取得或設定資料標籤的預設形狀類型。若未定義形狀，則返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 將第一系列中所有資料標籤的形狀類型設定為 Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

設定此屬性亦會將集合中所有資料標籤的 IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) 屬性設為相同的值。

**傳回值:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

取得或設定資料標籤的預設形狀類型。若未定義形狀，則返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 將第一系列中所有資料標籤的形狀類型設定為 Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

設定此屬性亦會將集合中所有資料標籤的 IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) 屬性設為相同的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**傳回值:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值:**
[IPresentation](../../com.aspose.slides/ipresentation)