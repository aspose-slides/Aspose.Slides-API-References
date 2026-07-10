---
title: ChartTitle
second_title: Aspose.Slides for Android via Java API 参考
description: 表示图表标题属性。
type: docs
url: /zh/com.aspose.slides/charttitle/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.IChartTitle](../../com.aspose.slides/icharttitle), com.aspose.slides.IDOMObject
```
public class ChartTitle implements IChartTitle, IDOMObject
```

表示图表标题属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getX()](#getX--) | 返回或设置标题的 x 坐标，作为图表宽度的分数。 |
| [setX(float value)](#setX-float-) | 返回或设置标题的 x 坐标，作为图表宽度的分数。 |
| [getY()](#getY--) | 返回或设置标题的 y 坐标，作为图表高度的分数。 |
| [setY(float value)](#setY-float-) | 返回或设置标题的 y 坐标，作为图表高度的分数。 |
| [getWidth()](#getWidth--) | 返回或设置标题的宽度，作为图表宽度的分数。 |
| [setWidth(float value)](#setWidth-float-) | 返回或设置标题的宽度，作为图表宽度的分数。 |
| [getHeight()](#getHeight--) | 返回或设置标题的高度，作为图表高度的分数。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置标题的高度，作为图表高度的分数。 |
| [getRight()](#getRight--) | 右。 |
| [getBottom()](#getBottom--) | 底部。 |
| [getOverlay()](#getOverlay--) | 确定是否允许其他图表元素覆盖标题。 |
| [setOverlay(boolean value)](#setOverlay-boolean-) | 确定是否允许其他图表元素覆盖标题。 |
| [getFormat()](#getFormat--) | 返回标题的填充、线条、效果样式。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用参数 “text” 中的文本初始化 TextFrameForOverriding。 |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含富格式化文本。 |
| [getTextFormat()](#getTextFormat--) | 返回文本格式。 |
| [getActualX()](#getActualX--) | 指定相对于图表左上角的实际 x 位置（左）。 |
| [getActualY()](#getActualY--) | 指定相对于图表左上角的实际顶部位置。 |
| [getActualWidth()](#getActualWidth--) | 指定图表元素的实际宽度。 |
| [getActualHeight()](#getActualHeight--) | 指定图表元素的实际高度。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 返回父图表。 |
| [getSlide()](#getSlide--) | 返回 FillFormat 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 FillFormat 的父演示文稿。 |

### getX() {#getX--}
```
public final float getX()
```

返回或设置标题的 x 坐标，作为图表宽度的分数。读/写 float。

**返回：**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

返回或设置标题的 x 坐标，作为图表宽度的分数。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

返回或设置标题的 y 坐标，作为图表高度的分数。读/写 float。

**返回：**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

返回或设置标题的 y 坐标，作为图表高度的分数。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

返回或设置标题的宽度，作为图表宽度的分数。读/写 float。

**返回：**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

返回或设置标题的宽度，作为图表宽度的分数。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或设置标题的高度，作为图表高度的分数。读/写 float。

**返回：**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或设置标题的高度，作为图表高度的分数。读/写 float。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getRight() {#getRight--}
```
public final float getRight()
```

右。只读 float。

**返回：**
float

### getBottom() {#getBottom--}
```
public final float getBottom()
```

底部。只读 float。

**返回：**
float

### getOverlay() {#getOverlay--}
```
public final boolean getOverlay()
```

确定是否允许其他图表元素覆盖标题。读/写 boolean。

**返回：**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public final void setOverlay(boolean value)
```

确定是否允许其他图表元素覆盖标题。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

返回标题的填充、线条、效果样式。只读 [IFormat](../../com.aspose.slides/iformat)。

**返回：**
[IFormat](../../com.aspose.slides/iformat)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

使用参数 “text” 中的文本初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已经初始化，则仅更改其文本。

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

可以包含富格式化文本。如果此属性不为 null，则该格式化文本会覆盖自动生成的文本。自动生成的文本是数据标签、数值轴显示单元标签、轴标题、图表标题、趋势线标签的隐式属性。自动生成的文本使用 IFormattedTextContainer.TextFormat 属性进行格式化。只读 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

返回文本格式。只读 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**返回：**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

指定相对于图表左上角的实际 x 位置（左）。在获取实际值之前请调用 IChart.validateChartLayout() 方法。读取 float。

**返回：**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

指定相对于图表左上角的实际顶部位置。在获取实际值之前请调用 IChart.validateChartLayout() 方法。读取 float。

**返回：**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

指定图表元素的实际宽度。在获取实际值之前请调用 IChart.validateChartLayout() 方法。读取 float。

**返回：**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

指定图表元素的实际高度。在获取实际值之前请调用 IChart.validateChartLayout() 方法。读取 float。

**返回：**
float

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