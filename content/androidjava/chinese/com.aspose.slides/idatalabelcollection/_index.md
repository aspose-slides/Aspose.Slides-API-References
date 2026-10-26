---
title: IDataLabelCollection
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示系列标签。
type: docs
url: /zh/com.aspose.slides/idatalabelcollection/
---
**已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

表示系列标签。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 获取具有指定索引的数据点的数据标签。 |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | 返回集合中所有数据标签的默认格式。 |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | 表示数据标签引导线的格式。 |
| [isVisible()](#isVisible--) | False 表示数据标签默认不可见（因此 DefaultDataLabelFormat 属性的所有 Show\*-标志（ShowValue 等）均为 false）。 |
| [hide()](#hide--) | 通过将 DefaultDataLabelFormat 属性的所有 Show\*-标志（ShowValue 等）设置为 false 状态，使数据标签默认隐藏。 |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | 获取集合中可见数据标签的数量。 |
| [getCount()](#getCount--) | 获取集合中所有数据标签的数量。 |
| [getParentSeries()](#getParentSeries--) | 返回父图表系列。 |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | 返回集合中指定 DataLabel 的索引。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

获取具有指定索引的数据点的数据标签。

--------------------

访问数据标签的另一种方式是：- getSeries().getDataPoints().get\_Item(i).getLabel() - 管理标签属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

返回集合中所有数据标签的默认格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回值:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

表示数据标签引导线的格式。只读 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False means that data label is not visible by default (and so all Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Read-only  boolean .

--------------------

If data label is visible by default you can make it hidden by default with Hide() method. But if data label is not visible by default (IsVisible is false) you can make data label "visible by default" with setting Show\*-flags (ShowValue, ...) of the DefaultDataLabelFormat property to true state.

**Returns:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```
通过将 DefaultDataLabelFormat 属性的所有 Show*-标志（ShowValue 等）设置为 false 状态，使数据标签默认隐藏。此后 IsVisible 将为 false。

--------------------

如果数据标签默认不可见（IsVisible 为 false），可以通过将 DefaultDataLabelFormat 属性的 Show*-标志（ShowValue 等）设置为 true 状态，使数据标签“默认可见”。

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

获取集合中可见数据标签的数量。只读  int .

**Returns:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gets the number of all data labels in the collection. Read-only  int .

**Returns:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Returns parent chart series. Read-only [IChartSeries](../../com.aspose.slides/ichartseries).

**Returns:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)

返回集合中指定 DataLabel 的索引。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | 要查找的 DataLabel。 |

**返回值:**
int - DataLabel 的索引；如果 DataLabel 不属于此集合，则返回 -1。