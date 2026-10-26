---
title: ErrorBarsFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/errorbarsformat/
---
## ErrorBarsFormat 类

 表示图表系列的误差线。ErrorBars 的自定义值位于 IChartDataPointCollection（在 ( IChartDataPoint#getErrorBarsCustomValues) 属性中）。

### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

 **返回：**
[Chart](../chart)


---


### getFormat {#getFormat}

| 名称 | 描述 |
| --- | --- |
| getFormat () | 表示误差线的格式。读写 IFormat。 |

 **返回：**
[Format](../format)


---


### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 所属的父演示文稿。只读 IPresentation。 |

 **返回：**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 所属的父幻灯片。只读 BaseSlide。 |

 **返回：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)


---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 获取或设置误差线的类型。读写 ErrorBarType。 |

 **返回：**
int


---


### getValue {#getValue}

| 名称 | 描述 |
| --- | --- |
| getValue () | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。其他情况下将返回 NaN。读写 float。 |

 **返回：**
float


---


### getValueType {#getValueType}

| 名称 | 描述 |
| --- | --- |
| getValueType () | 表示确定误差线长度的可能方式。对于自定义值类型，请使用系列 DataPoints 集合中特定数据点的 ( IChartDataPoint#getErrorBarsCustomValues) 属性来指定值。对于 Fixed、Percentage 或 StandardDeviation 值类型，请使用 Value 属性来指定值。读写 ErrorBarValueType。 |

 **返回：**
int


---


### hasEndCap {#hasEndCap}

| 名称 | 描述 |
| --- | --- |
| hasEndCap () | 指定在误差线上不绘制端帽。读写 boolean。 |

 **返回：**
boolean


---


### isVisible {#isVisible}

| 名称 | 描述 |
| --- | --- |
| isVisible () | 获取或设置误差线的可见性。读写 boolean。 |

 **返回：**
boolean


---


### setEndCap {#setEndCap}

| 名称 | 描述 |
| --- | --- |
| setEndCap (boolean) | 指定在误差线上不绘制端帽。读写 boolean。 |

 **返回：**
void


---


### setFormat {#setFormat}

| 名称 | 描述 |
| --- | --- |
| setFormat ([Format](../format)) | 表示误差线的格式。读写 IFormat。 |

 **返回：**
void


---


### setType {#setType}

| 名称 | 描述 |
| --- | --- |
| setType (int) | 获取或设置误差线的类型。读写 ErrorBarType。 |

 **返回：**
void


---


### setValue {#setValue}

| 名称 | 描述 |
| --- | --- |
| setValue (float) | 获取或设置用于 Fixed、Percentage 和 StandardDeviation 值类型以确定误差线长度的值。其他情况下将返回 NaN。读写 float。 |

 **返回：**
void


---


### setValueType {#setValueType}

| 名称 | 描述 |
| --- | --- |
| setValueType (int) | 表示确定误差线长度的可能方式。对于自定义值类型，请使用系列 DataPoints 集合中特定数据点的 ( IChartDataPoint#getErrorBarsCustomValues) 属性来指定值。对于 Fixed、Percentage 或 StandardDeviation 值类型，请使用 Value 属性来指定值。读写 ErrorBarValueType。 |

 **返回：**
void


---


### setVisible {#setVisible}

| 名称 | 描述 |
| --- | --- |
| setVisible (boolean) | 获取或设置误差线的可见性。读写 boolean。 |

 **返回：**
void


---