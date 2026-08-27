---
title: Trendline
second_title: Aspose.Slides for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/trendline/
---
## Trendline 类

 类表示图表系列的趋势线

### addTextFrameForOverriding {#addTextFrameForOverriding}

| 名称 | 描述 |
| --- | --- |
| addTextFrameForOverriding (String) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 新 TextFrameForOverriding 的文本。 |

**返回值：**
[TextFrame](../textframe)

---

### getBackward {#getBackward}

| 名称 | 描述 |
| --- | --- |
| getBackward () | 指定趋势线在被趋势化系列的数据之前向前延伸的类别数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读/写 double。 |

**返回值：**
double

---

### getChart {#getChart}

| 名称 | 描述 |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

**返回值：**
[Chart](../chart)

---

### getDisplayEquation {#getDisplayEquation}

| 名称 | 描述 |
| --- | --- |
| getDisplayEquation () | 指定趋势线的方程式在图表上显示（与 Rsquaredvalue 同标签）。读/写 boolean。 |

**返回值：**
boolean

---

### getDisplayRSquaredValue {#getDisplayRSquaredValue}

| 名称 | 描述 |
| --- | --- |
| getDisplayRSquaredValue () | 指定趋势线的 R 平方值在图表上显示（与方程式同标签）。读/写 boolean。 |

**返回值：**
boolean

---

### getFormat {#getFormat}

| 名称 | 描述 |
| --- | --- |
| getFormat () | 表示趋势线的格式。读/写 IFormat。 |

**返回值：**
[Format](../format)

---

### getForward {#getForward}

| 名称 | 描述 |
| --- | --- |
| getForward () | 指定趋势线在被趋势化系列的数据之后向后延伸的类别数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读/写 double。 |

**返回值：**
double

---

### getIntercept {#getIntercept}

| 名称 | 描述 |
| --- | --- |
| getIntercept () | 指定趋势线交叉 y 轴的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。 |

**返回值：**
double

---

### getOrder {#getOrder}

| 名称 | 描述 |
| --- | --- |
| getOrder () | 指定多项式趋势线的阶数。对其他趋势线类型忽略此设置。取值必须在 2 到 6 之间。读/写 byte。 |

**返回值：**
byte

---

### getPeriod {#getPeriod}

| 名称 | 描述 |
| --- | --- |
| getPeriod () | 指定移动平均趋势线的周期。对其他趋势线变体忽略此设置。取值必须在 2 到 255 之间。读/写 byte。 |

**返回值：**
byte

---

### getPresentation {#getPresentation}

| 名称 | 描述 |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回值：**
[Presentation](../presentation)

---

### getRelatedLegendEntry {#getRelatedLegendEntry}

| 名称 | 描述 |
| --- | --- |
| getRelatedLegendEntry () | 表示与此趋势线相关的图例条目。只读 ILegendEntryProperties。 |

**返回值：**
[LegendEntryProperties](../legendentryproperties)

---

### getSlide {#getSlide}

| 名称 | 描述 |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回值：**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getTextFormat {#getTextFormat}

| 名称 | 描述 |
| --- | --- |
| getTextFormat () | 返回文本格式。只读 IChartTextFormat。 |

**返回值：**
[ChartTextFormat](../charttextformat)

---

### getTextFrameForOverriding {#getTextFrameForOverriding}

| 名称 | 描述 |
| --- | --- |
| getTextFrameForOverriding () | 可以包含富格式化文本。如果此属性不为 null，则此格式化文本值将覆盖数据标签的自动生成文本。自动生成的数据显示标签文本是指由 ShowSeriesName、ShowValue 等属性管理并使用 TextFormatManager.TextFormat 属性格式化的文本。只读 ITextFrame。 |

**返回值：**
[TextFrame](../textframe)

---

### getTrendlineName {#getTrendlineName}

| 名称 | 描述 |
| --- | --- |
| getTrendlineName () | 获取或设置趋势线的名称。读/写 String。 |

**返回值：**
String

---

### getTrendlineType {#getTrendlineType}

| 名称 | 描述 |
| --- | --- |
| getTrendlineType () | 获取或设置趋势线的类型。读/写 TrendlineType。 |

**返回值：**
int

---

### setBackward {#setBackward}

| 名称 | 描述 |
| --- | --- |
| setBackward (double) | 指定趋势线在被趋势化系列的数据之前向前延伸的类别数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读/写 double。 |

**返回值：**
void

---

### setDisplayEquation {#setDisplayEquation}

| 名称 | 描述 |
| --- | --- |
| setDisplayEquation (boolean) | 指定趋势线的方程式在图表上显示（与 Rsquaredvalue 同标签）。读/写 boolean。 |

**返回值：**
void

---

### setDisplayRSquaredValue {#setDisplayRSquaredValue}

| 名称 | 描述 |
| --- | --- |
| setDisplayRSquaredValue (boolean) | 指定趋势线的 R 平方值在图表上显示（与方程式同标签）。读/写 boolean。 |

**返回值：**
void

---

### setFormat {#setFormat}

| 名称 | 描述 |
| --- | --- |
| setFormat ([Format](../format)) | 表示趋势线的格式。读/写 IFormat。 |

**返回值：**
void

---

### setForward {#setForward}

| 名称 | 描述 |
| --- | --- |
| setForward (double) | 指定趋势线在被趋势化系列的数据之后向后延伸的类别数（或散点图上的单位数）。在散点图和非散点图上，该值应为任意非负值。读/写 double。 |

**返回值：**
void

---

### setIntercept {#setIntercept}

| 名称 | 描述 |
| --- | --- |
| setIntercept (double) | 指定趋势线交叉 y 轴的值。仅在趋势线类型为 exp、linear 或 poly 时支持此属性。读/写 double。 |

**返回值：**
void

---

### setOrder {#setOrder}

| 名称 | 描述 |
| --- | --- |
| setOrder (byte) | 指定多项式趋势线的阶数。对其他趋势线类型忽略此设置。取值必须在 2 到 6 之间。读/写 byte。 |

**返回值：**
void

---

### setPeriod {#setPeriod}

| 名称 | 描述 |
| --- | --- |
| setPeriod (byte) | 指定移动平均趋势线的周期。对其他趋势线变体忽略此设置。取值必须在 2 到 255 之间。读/写 byte。 |

**返回值：**
void

---

### setTrendlineName {#setTrendlineName}

| 名称 | 描述 |
| --- | --- |
| setTrendlineName (String) | 获取或设置趋势线的名称。读/写 String。 |

**返回值：**
void

---

### setTrendlineType {#setTrendlineType}

| 名称 | 描述 |
| --- | --- |
| setTrendlineType (int) | 获取或设置趋势线的类型。读/写 TrendlineType。 |

**返回值：**
void