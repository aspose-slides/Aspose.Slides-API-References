---
title: DataLabel
second_title: Aspose.Slides Java API 参考
description: 表示系列标签。
type: docs
url: /zh/com.aspose.slides/datalabel/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IDataLabel](../../com.aspose.slides/idatalabel), com.aspose.slides.IDOMObject
```
public class DataLabel implements IDataLabel, IDOMObject
```

表示系列标签。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DataLabel(IChartDataPoint parentImmediate)](#DataLabel-com.aspose.slides.IChartDataPoint-) | 创建 DataLabel 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父图表。 |
| [isVisible()](#isVisible--) | False 表示数据标签不可见（因此所有 Show*-flags（如 ShowValue 等）均为 false）。 |
| [hide()](#hide--) | 通过将所有 Show*-flags（如 ShowValue 等）设置为 false，使数据标签隐藏。 |
| [getActualLabelText()](#getActualLabelText--) | 返回基于 DataLabelFormat 设置或 TextFrameForOverriding.Text 值的实际标签文本。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式文本。 |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getX()](#getX--) | 返回或设置标题的 X 坐标，以图表宽度的比例表示。 |
| [setX(float value)](#setX-float-) | 返回或设置标题的 X 坐标，以图表宽度的比例表示。 |
| [getY()](#getY--) | 返回或设置标题的 Y 坐标，以图表高度的比例表示。 |
| [setY(float value)](#setY-float-) | 返回或设置标题的 Y 坐标，以图表高度的比例表示。 |
| [getWidth()](#getWidth--) | 返回或设置标题的宽度，以图表宽度的比例表示。 |
| [setWidth(float value)](#setWidth-float-) | 返回或设置标题的宽度，以图表宽度的比例表示。 |
| [getHeight()](#getHeight--) | 返回或设置标题的高度，以图表高度的比例表示。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置标题的高度，以图表高度的比例表示。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getDataLabelFormat()](#getDataLabelFormat--) | 返回数据标签格式。 |
| [getValueFromCell()](#getValueFromCell--) | 获取或设置工作簿数据单元格。 |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | 获取或设置工作簿数据单元格。 |
| [getLabelShapeType()](#getLabelShapeType--) | 获取或设置数据标签的形状类型。 |
| [setLabelShapeType(int value)](#setLabelShapeType-int-) | 获取或设置数据标签的形状类型。 |
| [getActualX()](#getActualX--) | 指定图表元素相对于图表左上角的实际 X 位置（左）。 |
| [getActualY()](#getActualY--) | 指定图表元素相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |
### DataLabel(IChartDataPoint parentImmediate) {#DataLabel-com.aspose.slides.IChartDataPoint-}
```
public DataLabel(IChartDataPoint parentImmediate)
```


创建 DataLabel 类的新实例。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| parentImmediate | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 父 ChartDataPoint。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


返回 Parent_Immediate 对象。只读 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```


返回父图表。只读 [IChart](../../com.aspose.slides/ichart)。

**返回：**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


False 表示数据标签不可见（因此所有 Show*-flags（如 ShowValue 等）均为 false）。只读 boolean 。

**返回：**
boolean
### hide() {#hide--}
```
public final void hide()
```


通过将所有 Show*-flags（如 ShowValue 等）设置为 false，使数据标签隐藏。执行后 IsVisible 将为 false。

### getActualLabelText() {#getActualLabelText--}
```
public final String getActualLabelText()
```


返回基于 DataLabelFormat 设置或 TextFrameForOverriding.Text 值的实际标签文本。

**返回：**
java.lang.String - java.lang.String 对象。
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```


使用参数 "text" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则直接更改其文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文本。 |

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```


可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖数据标签的自动生成文本。数据标签的自动生成文本指由 ShowSeriesName、ShowValue 等属性管理并使用 TextFormatManager.TextFormat 属性格式化的文本。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getX() {#getX--}
```
public final float getX()
```


返回或设置标题的 X 坐标，以图表宽度的比例表示。读写 float 。

**返回：**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


返回或设置标题的 X 坐标，以图表宽度的比例表示。读写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getY() {#getY--}
```
public final float getY()
```


返回或设置标题的 Y 坐标，以图表高度的比例表示。读写 float 。

**返回：**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


返回或设置标题的 Y 坐标，以图表高度的比例表示。读写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getWidth() {#getWidth--}
```
public final float getWidth()
```


返回或设置标题的宽度，以图表宽度的比例表示。读写 float 。

**返回：**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


返回或设置标题的宽度，以图表宽度的比例表示。读写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getHeight() {#getHeight--}
```
public final float getHeight()
```


返回或设置标题的高度，以图表高度的比例表示。读写 float 。

**返回：**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


返回或设置标题的高度，以图表高度的比例表示。读写 float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getRight() {#getRight--}
```
public final float getRight()
```


右。只读 float 。

**返回：**
float
### getBottom() {#getBottom--}
```
public final float getBottom()
```


底部。只读 float 。

**返回：**
float
### getDataLabelFormat() {#getDataLabelFormat--}
```
public final IDataLabelFormat getDataLabelFormat()
```


返回数据标签格式。只读 [IDataLabelFormat](../../com.aspose.slides/idatalabelformat)。

**返回：**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public final IChartDataCell getValueFromCell()
```


获取或设置工作簿数据单元格。仅在 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时应用。

**返回：**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public final void setValueFromCell(IChartDataCell value)
```


获取或设置工作簿数据单元格。仅在 IDataLabelFormat.ShowLabelValueFromCell 属性为 true 时应用。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getLabelShapeType() {#getLabelShapeType--}
```
public final int getLabelShapeType()
```


获取或设置数据标签的形状类型。如果未定义形状，则返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

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
public final void setLabelShapeType(int value)
```


获取或设置数据标签的形状类型。如果未定义形状，则返回 [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined)。

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
### getActualX() {#getActualX--}
```
public final float getActualX()
```


指定图表元素相对于图表左上角的实际 X 位置（左）。在获取实际值之前请调用 IChart.ValidateChartLayout() 方法。只读 float 。

**返回：**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


指定图表元素相对于图表左上角的实际顶部位置。在获取实际值之前请调用 IChart.ValidateChartLayout() 方法。只读 float 。

**返回：**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


指定图表元素的实际宽度。在获取实际值之前请调用 IChart.ValidateChartLayout() 方法。只读 float 。

**返回：**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


指定图表元素的实际高度。在获取实际值之前请调用 IChart.ValidateChartLayout() 方法。只读 float 。

**返回：**
float
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


返回 FillFormat 的父幻灯片。只读 [BaseSlide](../../com.aspose.slides/baseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


返回 FillFormat 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)