---
title: DataLabelCollection
second_title: Aspose.Slides for Java API 参考
description: 表示系列标签。
type: docs
url: /zh/com.aspose.slides/datalabelcollection/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**全部实现的接口:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

表示系列标签。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getChart()](#getChart--) | 返回父级图表。 |
| [iterator()](#iterator--) | 返回一个用于遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
| [isVisible()](#isVisible--) | False 表示默认情况下数据标签不可见（并且 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue，...）均为 false）。 |
| [hide()](#hide--) | 通过将 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue，...）设置为 false 状态，使数据标签默认隐藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 获取集合中可见数据标签的数量。 |
| [getCount()](#getCount--) | 获取集合中所有数据标签的数量。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 获取默认数据标签格式。 |
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

返回父级图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回:**  
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

返回一个用于遍历集合的枚举器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False 表示默认情况下数据标签不可见（因此 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue，...）均为 false）。只读 boolean。

--------------------

如果数据标签默认可见，您可以使用 Hide() 方法将其默认隐藏。但如果数据标签默认不可见（IsVisible 为 false），您可以通过将 DefaultDataLabelFormat 属性的 Show*-标志（ShowValue，...）设为 true 状态，使数据标签“默认可见”。

**返回:**  
boolean

### hide() {#hide--}
```
public final void hide()
```

通过将 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue，...）设置为 false 状态，使数据标签默认隐藏。之后 IsVisible 将为 false。

--------------------

如果数据标签默认不可见（IsVisible 为 false），您可以通过将 DefaultDataLabelFormat 属性的 Show*-标志（ShowValue，...）设置为 true 状态，使数据标签“默认可见”。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

获取集合中可见数据标签的数量。只读 int。

**返回:**  
int

### getCount() {#getCount--}
```
public final int getCount()
```

获取集合中所有数据标签的数量。只读 int。

**返回:**  
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

获取默认数据标签格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回:**  
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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

获取父系列。只读 [IChartSeries](../../com.aspose.slides/ichartseries)。

**返回:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

返回集合中指定 DataLabel 的索引。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 要查找的 DataLabel。 |

**返回:**  
int - DataLabel 的索引，如果 DataLabel 不属于此集合则返回 -1。

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

获取具有指定索引的数据点的数据标签。

--------------------

访问数据标签的另一种方式是：- series.getDataPoints().get_Item(i).getLabel() - 管理标签属性。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)