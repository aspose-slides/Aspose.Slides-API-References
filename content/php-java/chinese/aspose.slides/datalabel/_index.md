---
title: DataLabel
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/datalabel/
---
## DataLabel 类

 表示系列标签。

### DataLabel {#DataLabel}

| 名称 | 描述 |
| --- | --- |
| DataLabel([ChartDataPoint](../chartdatapoint)) | 创建 DataLabel 类的新实例。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| parentImmediate | [ChartDataPoint](../chartdatapoint) | 父 ChartDataPoint。 |

**返回：**
DataLabel


---


### addTextFrameForOverriding {#addTextFrameForOverriding}

| 名称 | 描述 |
| --- | --- |
| addTextFrameForOverriding (String) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 用于新 TextFrameForOverriding 的文本。 |

**返回：**
[TextFrame](../textframe)


---


### getActualHeight {#getActualHeight}

| 名称 | 描述 |
| --- | --- |
| getActualHeight () | 指定图表元素的实际高度。调用 IChart.ValidateChartLayout() 方法以获取实际值。只读 float。 |

**返回：**
float


---


### getActualLabelText {#getActualLabelText}

| 名称 | 描述 |
| --- | --- |
| getActualLabelText () | 根据 DataLabelFormat 设置或 TextFrameForOverriding.Text 值返回实际标签文本。 |

**返回：**
String


---


### getActualWidth {#getActualWidth}

| 名称 | 描述 |
| --- | --- |
| getActualWidth () | 指定图表元素的实际宽度。调用 IChart.ValidateChartLayout() 方法以获取实际值。只读 float。 |

**返回：**
float


---


### getActualX {#getActualX}

| 名称 | 描述 |
| --- | --- |
| getActualX () | 指定图表元素相对于图表左上角的实际 x 位置（左）。调用 IChart.ValidateChartLayout() 方法以获取实际值。只读 float。 |

**返回：**
float


---


### getActualY {#getActualY}

| 名称 | 描述 |
| --- | --- |
| getActualY () | 指定图表元素相对于图表左上角的实际顶部位置。调用 IChart.ValidateChartLayout() 方法以获取实际值。只读 float。 |

**返回：**
float


---


### getBottom {#getBottom}

| 名称 | 描述 |
| --- | --- |
| getBottom () | 底部。只读 float。 |

**返回：**
float


---


### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

**返回：**
[Chart](../chart)


---


### getDataLabelFormat {#getDataLabelFormat}

| 名称 | 描述 |
| --- | --- |
| getDataLabelFormat () | 返回数据标签格式。只读 IDataLabelFormat。 |

**返回：**
[DataLabelFormat](../datalabelformat)


---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 返回或设置标题的高度，作为图表高度的比例。读写 float。 |

**返回：**
float


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回：**
[Presentation](../presentation)


---


### getRight {#getRight}

| 名称 | 描述 |
| --- | --- |
| getRight () | 右侧。只读 float。 |

**返回：**
float


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getTextFormat {#getTextFormat}

| 名称 | 描述 |
| --- | --- |
| getTextFormat () | 返回文本格式。只读 IChartTextFormat。 |

**返回：**
[ChartTextFormat](../charttextformat)


---


### getTextFrameForOverriding {#getTextFrameForOverriding}

| 名称 | 描述 |
| --- | --- |
| getTextFrameForOverriding () | 可以包含富格式文本。如果此属性不为 null，则该格式化文本值会覆盖数据标签的自动生成文本。自动生成的文本指的是由 ShowSeriesName、ShowValue 等属性管理并使用 TextFormatManager.TextFormat 属性格式化的文本。只读 ITextFrame。 |

**返回：**
[TextFrame](../textframe)


---


### getValueFromCell {#getValueFromCell}

| 名称 | 描述 |
| --- | --- |
| getValueFromCell () | 获取或设置工作簿数据单元格。如果 IDataLabelFormat.ShowLabelValueFromCell 属性为 true，则适用。 |

**返回：**
[ChartDataCell](../chartdatacell)


---


### getWidth {#getWidth}

| 名称 | 描述 |
| --- | --- |
| getWidth () | 返回或设置标题的宽度，作为图表宽度的比例。读写 float。 |

**返回：**
float


---


### getX {#getX}

| 名称 | 描述 |
| --- | --- |
| getX () | 返回或设置标题的 x 坐标，作为图表宽度的比例。读写 float。 |

**返回：**
float


---


### getY {#getY}

| 名称 | 描述 |
| --- | --- |
| getY () | 返回或设置标题的 y 坐标，作为图表高度的比例。读写 float。 |

**返回：**
float


---


### hide {#hide}

| 名称 | 描述 |
| --- | --- |
| hide () | 通过将所有 Show* 标志（ShowValue 等）设为 false，使数据标签隐藏。此后 IsVisible 为 false。如果数据标签不可见（IsVisible 为 false），可以通过将 Show* 标志设为 true 使其可见。 |

**返回：**
void


---


### isVisible {#isVisible}

| 名称 | 描述 |
| --- | --- |
| isVisible () | false 表示数据标签不可见（所有 Show* 标志均为 false）。只读 boolean。如果数据标签可见，可以使用 Hide() 方法将其隐藏。但如果数据标签不可见（IsVisible 为 false），可以通过将 Show* 标志设为 true 使其可见。 |

**返回：**
boolean


---


### setHeight {#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight (float) | 返回或设置标题的高度，作为图表高度的比例。读写 float。 |

**返回：**
void


---


### setValueFromCell {#setValueFromCell}

| 名称 | 描述 |
| --- | --- |
| setValueFromCell ([ChartDataCell](../chartdatacell)) | 获取或设置工作簿数据单元格。如果 IDataLabelFormat.ShowLabelValueFromCell 属性为 true，则适用。 |

**返回：**
void


---


### setWidth {#setWidth}

| 名称 | 描述 |
| --- | --- |
| setWidth (float) | 返回或设置标题的宽度，作为图表宽度的比例。读写 float。 |

**返回：**
void


---


### setX {#setX}

| 名称 | 描述 |
| --- | --- |
| setX (float) | 返回或设置标题的 x 坐标，作为图表宽度的比例。读写 float。 |

**返回：**
void


---


### setY {#setY}

| 名称 | 描述 |
| --- | --- |
| setY (float) | 返回或设置标题的 y 坐标，作为图表高度的比例。读写 float。 |

**返回：**
void


---