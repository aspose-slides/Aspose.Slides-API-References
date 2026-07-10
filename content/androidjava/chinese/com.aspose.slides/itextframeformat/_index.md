---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /zh/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

包含 TextFrame 的格式属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 返回文本的样式。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置 TextFrame 中的左边距（点）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 返回或设置 TextFrame 中的左边距（点）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置 TextFrame 中的右边距（点）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 返回或设置 TextFrame 中的右边距（点）。 |
| [getMarginTop()](#getMarginTop--) | 返回或设置 TextFrame 中的上边距（点）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 返回或设置 TextFrame 中的上边距（点）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回或设置 TextFrame 中的下边距（点）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 返回或设置 TextFrame 中的下边距（点）。 |
| [getWrapText()](#getWrapText--) | 如果文本在 TextFrame 的边距处换行则为 True。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文本在 TextFrame 的边距处换行则为 True。 |
| [getAnchoringType()](#getAnchoringType--) | 返回或设置 TextFrame 中的垂直锚点文本。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 返回或设置 TextFrame 中的垂直锚点文本。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，则文本应在盒子中水平居中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，则文本应在盒子中水平居中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 确定文本方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 确定文本方向。 |
| [getAutofitType()](#getAutofitType--) | 返回或设置文本的自动适配模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 返回或设置文本的自动适配模式。 |
| [getColumnCount()](#getColumnCount--) | 返回或设置文本区域中的列数。 |
| [setColumnCount(int value)](#setColumnCount-int-) | 返回或设置文本区域中的列数。 |
| [getColumnSpacing()](#getColumnSpacing--) | 返回或设置文本区域中文本列之间的间距（以点为单位）。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 返回或设置文本区域中文本列之间的间距（以点为单位）。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回表示文本 3D 效果属性的 ThreeDFormat 对象。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 返回或设置完全将文本排除在 3D 场景之外。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 返回或设置完全将文本排除在 3D 场景之外。 |
| [getRotationAngle()](#getRotationAngle--) | 指定在边界框内应用于文本的自定义旋转。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定在边界框内应用于文本的自定义旋转。 |
| [getTransform()](#getTransform--) | 获取或设置文本换行形状。 |
| [setTransform(byte value)](#setTransform-byte-) | 获取或设置文本换行形状。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效文本框格式数据。 |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

返回文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

返回或设置 TextFrame 中的左边距（点）。读/写 double。

**返回：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

返回或设置 TextFrame 中的左边距（点）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

返回或设置 TextFrame 中的右边距（点）。读/写 double。

**返回：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

返回或设置 TextFrame 中的右边距（点）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

返回或设置 TextFrame 中的上边距（点）。读/写 double。

**返回：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

返回或设置 TextFrame 中的上边距（点）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

返回或设置 TextFrame 中的下边距（点）。读/写 double。

**返回：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

返回或设置 TextFrame 中的下边距（点）。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

如果文本在 TextFrame 的边距处换行则为 True。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

如果文本在 TextFrame 的边距处换行则为 True。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

返回或设置 TextFrame 中的垂直锚点文本。读/写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回：**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

返回或设置 TextFrame 中的垂直锚点文本。读/写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

如果 NullableBool.True，则文本应在盒子中水平居中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

如果 NullableBool.True，则文本应在盒子中水平居中。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的最终值。读/写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

返回或设置文本的自动适配模式。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**返回：**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

返回或设置文本的自动适配模式。读/写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

返回或设置文本区域中的列数。此值必须为正数，否则将被设置为 0。值 0 表示未定义。读/写 int。

**返回：**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

返回或设置文本区域中的列数。此值必须为正数，否则将被设置为 0。值 0 表示未定义。读/写 int。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

返回或设置文本区域中文本列之间的间距（以点为单位）。仅在存在多列时适用。此值必须为正数，否则将被设置为 0。读/写 double。

**返回：**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

返回或设置文本区域中文本列之间的间距（以点为单位）。仅在存在多列时适用。此值必须为正数，否则将被设置为 0。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

返回表示文本 3D 效果属性的 ThreeDFormat 对象。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ``` 
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // 设置文本变换
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 设置拉伸
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // 设置轮廓
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // 设置深度
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // 设置材质
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // 设置灯光
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // 设置相机类型
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Returns:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```


Returns or set keeping text out of 3D scene entirely. Read/write boolean.

**Returns:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Returns or set keeping text out of 3D scene entirely. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


指定在边界框内应用于文本的自定义旋转。如果未指定，则使用伴随形状的旋转。如果指定，则独立于形状应用。即形状可以有旋转，同时文本本身也可以有旋转。可视文本旋转的最终值由此属性与属性 TextVerticalType 中预定义的垂直类型汇总得出。读/写 float.

--------------------

> ```
> 考虑一种情况：一个形状被顺时针旋转了 90 度。 
> 在此基础上，文本主体本身被逆时针旋转了 -90 度。 
> 那么最终的形状看起来是旋转的，但其中的文本看起来好像根本没有旋转。
> ```

**返回：**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```
 


Gets or sets text wrapping shape. Read/write [TextShapeType](../../com.aspose.slides/textshapetype).

**Returns:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Gets or sets text wrapping shape. Read/write [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
Gets effective text frame formatting data with the inheritance applied.

**Returns:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).