---
title: DataLabelCollection
second_title: Aspose.Slides for Java API 參考
description: 表示系列標籤。
type: docs
url: /zh-hant/com.aspose.slides/datalabelcollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

代表系列標籤。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getChart()](#getChart--) | 返回父圖表。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [isVisible()](#isVisible--) | false 表示資料標籤預設不可見（因此 DefaultDataLabelFormat 屬性的所有 Show\*-旗標（ShowValue 等）皆為 false）。 |
| [hide()](#hide--) | 透過將 DefaultDataLabelFormat 屬性的所有 Show\*-旗標（ShowValue 等）設為 false 來使資料標籤預設隱藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 獲取集合中可見資料標籤的數量。 |
| [getCount()](#getCount--) | 獲取集合中所有資料標籤的數量。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 獲取預設資料標籤格式。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 代表資料標籤的引線格式。 |
| [getParentSeries()](#getParentSeries--) | 獲取父序列。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 返回指定 DataLabel 在集合中的索引。 |
| [get_Item(int index)](#get-Item-int-) | 獲取具有指定索引的資料點的資料標籤。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父簡報。 |
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父圖表。唯讀 [IChart](../../com.aspose.slides/ichart)。

**返回值：**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

返回一個可遍歷集合的列舉器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

返回整個集合的 java 迭代器。

**返回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 整個集合的 java.util.Iterator。
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

false 表示資料標籤預設不可見（因此 DefaultDataLabelFormat 屬性的所有 Show\*-旗標（ShowValue 等）皆為 false）。唯讀 boolean。

--------------------

如果資料標籤預設可見，您可以使用 Hide() 方法將其預設隱藏。但若資料標籤預設不可見（IsVisible 為 false），則可透過將 DefaultDataLabelFormat 屬性的 Show\*-旗標（ShowValue 等）設為 true，將資料標籤設為「預設可見」。

**返回值：**
boolean
### hide() {#hide--}
```
public final void hide()
```

透過將 DefaultDataLabelFormat 屬性的所有 Show\*-旗標（ShowValue 等）設為 false，將資料標籤預設隱藏。執行後 IsVisible 會為 false。

--------------------

若資料標籤預設不可見（IsVisible 為 false），可透過將 DefaultDataLabelFormat 屬性的 Show\*-旗標（ShowValue 等）設為 true，將資料標籤設為「預設可見」。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

獲取集合中可見資料標籤的數量。唯讀 int。

**返回值：**
int
### getCount() {#getCount--}
```
public final int getCount()
```

獲取集合中所有資料標籤的數量。唯讀 int。

**返回值：**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

獲取預設資料標籤格式。唯讀 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回值：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

代表資料標籤的引線格式。唯讀 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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

**返回值：**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

獲取父序列。唯讀 [IChartSeries](../../com.aspose.slides/ichartseries)。

**返回值：**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

返回指定 DataLabel 在集合中的索引。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 要查找的 DataLabel。 |

**返回值：**
int - DataLabel 的索引，若 DataLabel 不屬於此集合則為 -1。
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

獲取具有指定索引的資料點的資料標籤。

--------------------

存取資料標籤的另一種方式：- series.getDataPoints().get_Item(i).getLabel() - 管理標籤屬性。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父投影片。唯讀 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回值：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值：**
[IPresentation](../../com.aspose.slides/ipresentation)