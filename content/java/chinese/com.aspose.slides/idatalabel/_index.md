---
title: IDataLabel
second_title: Aspose.Slides Java API 参考
description: 表示一系列标签。
type: docs
url: /zh/com.aspose.slides/idatalabel/
---
**所有实现的接口：**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

表示一系列标签。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isVisible()](#isVisible--) | False 表示数据标签不可见（因此所有 Show\*-flags（ShowValue，...）均为 false）。 |
| [hide()](#hide--) | 通过将所有 Show\*-flags（ShowValue，...）设置为 false 状态来隐藏数据标签。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 返回数据标签的格式。 |
| [getValueFromCell()](#getValueFromCell--) | 获取或设置工作簿数据单元格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 获取或设置工作簿数据单元格。 |
| [getActualLabelText()](#getActualLabelText--) | 根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |
| [getLabelShapeType()](#getLabelShapeType--) | 获取或设置数据标签的形状类型。 |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 获取或设置数据标签的形状类型。 |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False 表示数据标签不可见（因此所有 Show\*-flags（ShowValue，...）均为 false）。只读布尔值。

--------------------

如果数据标签可见，您可以使用 Hide() 方法将其隐藏。但如果数据标签不可见（IsVisible 为 false），可以通过将 Show\*-flags（ShowValue，...）设置为 true 状态来使数据标签可见。

**返回：**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

通过将所有 Show\*-flags（ShowValue，...）设置为 false 状态来隐藏数据标签。此后 IsVisible 将为 false。

--------------------

如果数据标签不可见（IsVisible 为 false），可以通过将 Show\*-flags（ShowValue，...）设置为 true 状态来使数据标签可见。

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

返回数据标签的格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

获取或设置工作簿数据单元格。仅当 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时适用。

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

获取或设置工作簿数据单元格。仅当 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时适用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。

**返回：**
java.lang.String - 实际标签文本字符串
### getLabelShapeType() {#getLabelShapeType--}
```
public abstract int getLabelShapeType()
```

获取或设置数据标签的形状类型。如果未定义形状，则返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 将第一个数据标签的形状类型设置为 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
int
### setLabelShapeType(int value) {#setLabelShapeType-int-}
```
public abstract void setLabelShapeType(int value)
```

获取或设置数据标签的形状类型。如果未定义形状，则返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // 将第一个数据标签的形状类型设置为 Ellipse.
>      firstSeries.getLabels().get_Item(0).setLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |