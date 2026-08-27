---
title: ChartTitle
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/charttitle/
---
## ChartTitle 类

表示图表标题属性。

### addTextFrameForOverriding {#addTextFrameForOverriding}

| Name | Description |
| --- | --- |
| addTextFrameForOverriding (String) | 使用参数 "text" 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。 |

**参数:**

| Name | Type | Description |
| --- | --- | --- |
| text | String | 新 TextFrameForOverriding 的文本。 |

**返回值:**
[TextFrame](../textframe)

---

### getActualHeight {#getActualHeight}

| Name | Description |
| --- | --- |
| getActualHeight () | 指定图表元素的实际高度。在获取实际值之前，请调用方法 IChart.validateChartLayout()。只读 float。 |

**返回值:**
float

---

### getActualWidth {#getActualWidth}

| Name | Description |
| --- | --- |
| getActualWidth () | 指定图表元素的实际宽度。在获取实际值之前，请调用方法 IChart.validateChartLayout()。只读 float。 |

**返回值:**
float

---

### getActualX {#getActualX}

| Name | Description |
| --- | --- |
| getActualX () | 指定图表元素相对于图表左上角的实际 x 位置（左）。在获取实际值之前，请调用方法 IChart.validateChartLayout()。只读 float。 |

**返回值:**
float

---

### getActualY {#getActualY}

| Name | Description |
| --- | --- |
| getActualY () | 指定图表元素相对于图表左上角的实际 y 位置（上）。在获取实际值之前，请调用方法 IChart.validateChartLayout()。只读 float。 |

**返回值:**
float

---

### getBottom {#getBottom}

| Name | Description |
| --- | --- |
| getBottom () | 底部。只读 float。 |

**返回值:**
float

---

### getChart {#getChart}

| Name | Description |
| --- | --- |
| getChart () | 返回父图表。只读 IChart。 |

**返回值:**
[Chart](../chart)

---

### getFormat {#getFormat}

| Name | Description |
| --- | --- |
| getFormat () | 返回标题的填充、线条、效果样式。只读 IFormat。 |

**返回值:**
[Format](../format)

---

### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | 返回或设置标题的高度，作为图表高度的比例。读/写 float。 |

**返回值:**
float

---

### getOverlay {#getOverlay}

| Name | Description |
| --- | --- |
| getOverlay () | 确定是否允许其他图表元素覆盖标题。读/写 boolean。 |

**返回值:**
boolean

---

### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | 返回 FillFormat 的父演示文稿。只读 IPresentation。 |

**返回值:**
[Presentation](../presentation)

---

### getRight {#getRight}

| Name | Description |
| --- | --- |
| getRight () | 右侧。只读 float。 |

**返回值:**
float

---

### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | 返回 FillFormat 的父幻灯片。只读 BaseSlide。 |

**返回值:**
[MasterHandoutSlide](../masterhandoutslide), [BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [Slide](../slide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [MasterNotesSlide](../masternotesslide)

---

### getTextFormat {#getTextFormat}

| Name | Description |
| --- | --- |
| getTextFormat () | 返回文本格式。只读 IChartTextFormat。 |

**返回值:**
[ChartTextFormat](../charttextformat)

---

### getTextFrameForOverriding {#getTextFrameForOverriding}

| Name | Description |
| --- | --- |
| getTextFrameForOverriding () | 可以包含富格式化文本。如果此属性不为 null，则该格式化文本值会覆盖自动生成的文本。自动生成的文本是数据标签、值轴的显示单位标签、轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 IFormattedTextContainer.TextFormat 属性进行格式化。只读 ITextFrame。 |

**返回值:**
[TextFrame](../textframe)

---

### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | 返回或设置标题的宽度，作为图表宽度的比例。读/写 float。 |

**返回值:**
float

---

### getX {#getX}

| Name | Description |
| --- | --- |
| getX () | 返回或设置标题的 x 坐标，作为图表宽度的比例。读/写 float。 |

**返回值:**
float

---

### getY {#getY}

| Name | Description |
| --- | --- |
| getY () | 返回或设置标题的 y 坐标，作为图表高度的比例。读/写 float。 |

**返回值:**
float

---

### setHeight {#setHeight}

| Name | Description |
| --- | --- |
| setHeight (float) | 返回或设置标题的高度，作为图表高度的比例。读/写 float。 |

**返回值:**
void

---

### setOverlay {#setOverlay}

| Name | Description |
| --- | --- |
| setOverlay (boolean) | 确定是否允许其他图表元素覆盖标题。读/写 boolean。 |

**返回值:**
void

---

### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth (float) | 返回或设置标题的宽度，作为图表宽度的比例。读/写 float。 |

**返回值:**
void

---

### setX {#setX}

| Name | Description |
| --- | --- |
| setX (float) | 返回或设置标题的 x 坐标，作为图表宽度的比例。读/写 float。 |

**返回值:**
void

---

### setY {#setY}

| Name | Description |
| --- | --- |
| setY (float) | 返回或设置标题的 y 坐标，作为图表高度的比例。读/写 float。 |

**返回值:**
void

---