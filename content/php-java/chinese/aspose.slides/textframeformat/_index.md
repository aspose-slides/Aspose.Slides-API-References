---
title: TextFrameFormat
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/textframeformat/
---
## TextFrameFormat 类

  包含 TextFrame 的 formatTextFrameFormatting 属性。
 
### TextFrameFormat {#TextFrameFormat}

| 名称 | 描述 |
| --- | --- |
| TextFrameFormat() | 初始化 TextFrameFormat 类的新实例。 |

 **返回：**
TextFrameFormat


---


### getAnchoringType {#getAnchoringType}

| 名称 | 描述 |
| --- | --- |
| getAnchoringType () | 返回或设置 TextFrame 中垂直锚点文本。读/写 TextAnchorType。 |

 **返回：**
byte


---


### getAutofitType {#getAutofitType}

| 名称 | 描述 |
| --- | --- |
| getAutofitType () | 返回或设置文本的自动适配模式。读/写 TextAutofitType。 |

 **返回：**
byte


---


### getCenterText {#getCenterText}

| 名称 | 描述 |
| --- | --- |
| getCenterText () | 如果 NullableBool.True，则文本应水平居中于框内。读/写 NullableBool。 |

 **返回：**
byte


---


### getColumnCount {#getColumnCount}

| 名称 | 描述 |
| --- | --- |
| getColumnCount () | 返回或设置文本区域的列数。此值必须为正数。否则，该值将被设为 0。值 0 表示未定义。读/写 int。 |

 **返回：**
int


---


### getColumnSpacing {#getColumnSpacing}

| 名称 | 描述 |
| --- | --- |
| getColumnSpacing () | 返回或设置文本区域中列之间的间距（以点为单位）。仅在存在超过 1 列时适用。此值必须为正数。否则，该值将被设为 0。读/写 double。 |

 **返回：**
double


---


### getEffective {#getEffective}

| 名称 | 描述 |
| --- | --- |
| getEffective () | 获取应用继承后的有效文本框格式数据。 |

 **返回：**
TextFrameFormatEffectiveData


---


### getKeepTextFlat {#getKeepTextFlat}

| 名称 | 描述 |
| --- | --- |
| getKeepTextFlat () | 获取或设置即使应用了 3-D 旋转效果仍保持文本平面。读/写 boolean。 |

 **返回：**
boolean


---


### getMarginBottom {#getMarginBottom}

| 名称 | 描述 |
| --- | --- |
| getMarginBottom () | 返回或设置 TextFrame 底部边距（点）。读/写 double。 |

 **返回：**
double


---


### getMarginLeft {#getMarginLeft}

| 名称 | 描述 |
| --- | --- |
| getMarginLeft () | 返回或设置 TextFrame 左侧边距（点）。读/写 double。 |

 **返回：**
double


---


### getMarginRight {#getMarginRight}

| 名称 | 描述 |
| --- | --- |
| getMarginRight () | 返回或设置 TextFrame 右侧边距（点）。读/写 double。 |

 **返回：**
double


---


### getMarginTop {#getMarginTop}

| 名称 | 描述 |
| --- | --- |
| getMarginTop () | 返回或设置 TextFrame 顶部边距（点）。读/写 double。 |

 **返回：**
double


---


### getRotationAngle {#getRotationAngle}

| 名称 | 描述 |
| --- | --- |
| getRotationAngle () | 指定针对边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。即形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。读/写 float。 |

 **返回：**
float


---


### getTextStyle {#getTextStyle}

| 名称 | 描述 |
| --- | --- |
| getTextStyle () | 返回文本的样式。只读 ITextStyle。 |

 **返回：**
[TextStyle](../textstyle)


---


### getTextVerticalType {#getTextVerticalType}

| 名称 | 描述 |
| --- | --- |
| getTextVerticalType () | 确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。读/写 TextVerticalType。 |

 **返回：**
byte


---


### getThreeDFormat {#getThreeDFormat}

| 名称 | 描述 |
| --- | --- |
| getThreeDFormat () | 返回表示文本 3D 效果属性的 ThreeDFormat 对象。只读 IThreeDFormat。 |

 **返回：**
[ThreeDFormat](../threedformat)


---


### getTransform {#getTransform}

| 名称 | 描述 |
| --- | --- |
| getTransform () | 获取或设置文本换行形状。读/写 TextShapeType。 |

 **返回：**
byte


---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |

 **返回：**
long


---


### getWrapText {#getWrapText}

| 名称 | 描述 |
| --- | --- |
| getWrapText () | 如果在 TextFrame 边距处换行则为 True。读/写 NullableBool。 |

 **返回：**
byte


---


### setAnchoringType {#setAnchoringType}

| 名称 | 描述 |
| --- | --- |
| setAnchoringType (byte) | 返回或设置 TextFrame 中垂直锚点文本。读/写 TextAnchorType。 |

 **返回：**
void


---


### setAutofitType {#setAutofitType}

| 名称 | 描述 |
| --- | --- |
| setAutofitType (byte) | 返回或设置文本的自动适配模式。读/写 TextAutofitType。 |

 **返回：**
void


---


### setCenterText {#setCenterText}

| 名称 | 描述 |
| --- | --- |
| setCenterText (byte) | 如果 NullableBool.True，则文本应水平居中于框内。读/写 NullableBool。 |

 **返回：**
void


---


### setColumnCount {#setColumnCount}

| 名称 | 描述 |
| --- | --- |
| setColumnCount (int) | 返回或设置文本区域的列数。此值必须为正数。否则，该值将被设为 0。值 0 表示未定义。读/写 int。 |

 **返回：**
void


---


### setColumnSpacing {#setColumnSpacing}

| 名称 | 描述 |
| --- | --- |
| setColumnSpacing (double) | 返回或设置文本区域中列之间的间距（以点为单位）。仅在存在超过 1 列时适用。此值必须为正数。否则，该值将被设为 0。读/写 double。 |

 **返回：**
void


---


### setKeepTextFlat {#setKeepTextFlat}

| 名称 | 描述 |
| --- | --- |
| setKeepTextFlat (boolean) | 获取或设置即使应用了 3-D 旋转效果仍保持文本平面。读/写 boolean。 |

 **返回：**
void


---


### setMarginBottom {#setMarginBottom}

| 名称 | 描述 |
| --- | --- |
| setMarginBottom (double) | 返回或设置 TextFrame 底部边距（点）。读/写 double。 |

 **返回：**
void


---


### setMarginLeft {#setMarginLeft}

| 名称 | 描述 |
| --- | --- |
| setMarginLeft (double) | 返回或设置 TextFrame 左侧边距（点）。读/写 double。 |

 **返回：**
void


---


### setMarginRight {#setMarginRight}

| 名称 | 描述 |
| --- | --- |
| setMarginRight (double) | 返回或设置 TextFrame 右侧边距（点）。读/写 double。 |

 **返回：**
void


---


### setMarginTop {#setMarginTop}

| 名称 | 描述 |
| --- | --- |
| setMarginTop (double) | 返回或设置 TextFrame 顶部边距（点）。读/写 double。 |

 **返回：**
void


---


### setRotationAngle {#setRotationAngle}

| 名称 | 描述 |
| --- | --- |
| setRotationAngle (float) | 指定针对边界框内文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果已指定，则该旋转独立于形状应用。即形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的最终值。读/写 float。 |

 **返回：**
void


---


### setTextVerticalType {#setTextVerticalType}

| 名称 | 描述 |
| --- | --- |
| setTextVerticalType (byte) | 确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。读/写 TextVerticalType。 |

 **返回：**
void


---


### setTransform {#setTransform}

| 名称 | 描述 |
| --- | --- |
| setTransform (byte) | 获取或设置文本换行形状。读/写 TextShapeType。 |

 **返回：**
void


---


### setWrapText {#setWrapText}

| 名称 | 描述 |
| --- | --- |
| setWrapText (byte) | 如果在 TextFrame 边距处换行则为 True。读/写 NullableBool。 |

 **返回：**
void


---