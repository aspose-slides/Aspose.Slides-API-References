---
title: DataLabelCollection
second_title: Aspose.Slides for Android via Java API 参考
description: 表示系列标签。
type: docs
url: /zh/com.aspose.slides/datalabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

表示系列标签。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChart()](#getChart--) | 返回父图表。 |
| [iterator()](#iterator--) | 返回一个枚举器，用于遍历集合。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [isVisible()](#isVisible--) | False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-标志 (ShowValue, ...) 均为 false）。 |
| [hide()](#hide--) | 通过将 DefaultDataLabelFormat 属性的所有 Show*-标志 (ShowValue, ...) 设置为 false 状态，使数据标签默认隐藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 获取集合中可见数据标签的数量。 |
| [getCount()](#getCount--) | 获取集合中所有数据标签的数量。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 获取默认的数据标签格式。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 表示数据标签引导线格式。 |
| [getParentSeries()](#getParentSeries--) | 获取父系列。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 返回集合中指定 DataLabel 的索引。 |
| [get_Item(int index)](#get-Item-int-) | 获取具有指定索引的数据点的数据标签。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### getChart() {#getChart--}
```
public final IChart getChart()
```

返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回值:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

返回一个枚举器，用于遍历集合。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - 整个集合的 java.util.Iterator。
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-标志 (ShowValue, ...) 均为 false）。只读 boolean。

--------------------

如果数据标签默认可见，您可以使用 Hide() 方法将其默认隐藏。但如果数据标签默认不可见（IsVisible 为 false），您可以通过将 DefaultDataLabelFormat 属性的 Show*-标志 (ShowValue, ...) 设置为 true 状态，使数据标签“默认可见”。

**返回值:**
boolean
### hide() {#hide--}
```
public final void hide()
```

通过将 DefaultDataLabelFormat 属性的所有 Show*-标志 (ShowValue, ...) 设置为 false 状态，使数据标签默认隐藏。执行后 IsVisible 将为 false。

--------------------

如果数据标签默认不可见（IsVisible 为 false），您可以通过将 DefaultDataLabelFormat 属性的 Show*-标志 (ShowValue, ...) 设置为 true 状态，使数据标签“默认可见”。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

获取集合中可见数据标签的数量。只读 int。

**返回值:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中所有数据标签的数量。只读 int。

**返回值:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

获取默认的数据标签格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回值:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

表示数据标签引导线格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Gets the parent series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Returns an index of the specified DataLabel in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel to find. |

**Returns:**
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Gets the data label for the data point with the specified index.

--------------------

Alternate way to access data label is: - series.getDataPoints().get_Item(i).getLabel() - manage label properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回值:**
[IPresentation](../../com.aspose.slides/ipresentation)