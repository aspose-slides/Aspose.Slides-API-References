---
title: TextFrameFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 包含 TextFrames 的 formatTextFrameFormatting 属性。
type: docs
url: /zh/com.aspose.slides/textframeformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

包含 TextFrame 的 formatTextFrameFormatting 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | 初始化 [TextFrameFormat](../../com.aspose.slides/textframeformat) 类的一个新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | 返回文本的样式。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回表示文本 3D 效果属性的 ThreeDFormat 对象。 |
| [getMarginLeft()](#getMarginLeft--) | 获取或设置 TextFrame 中左边距（点）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 获取或设置 TextFrame 中左边距（点）。 |
| [getMarginRight()](#getMarginRight--) | 获取或设置 TextFrame 中右边距（点）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 获取或设置 TextFrame 中右边距（点）。 |
| [getMarginTop()](#getMarginTop--) | 获取或设置 TextFrame 中上边距（点）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 获取或设置 TextFrame 中上边距（点）。 |
| [getMarginBottom()](#getMarginBottom--) | 获取或设置 TextFrame 中下边距（点）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 获取或设置 TextFrame 中下边距（点）。 |
| [getWrapText()](#getWrapText--) | 如果文本在 TextFrame 的边距处换行，则返回 true。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文本在 TextFrame 的边距处换行，则返回 true。 |
| [getAnchoringType()](#getAnchoringType--) | 获取或设置 TextFrame 中的垂直锚点文本。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 获取或设置 TextFrame 中的垂直锚点文本。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，则文本应在框中水平居中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，则文本应在框中水平居中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 确定文本方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 确定文本方向。 |
| [getAutofitType()](#getAutofitType--) | 获取或设置文本的自动适应模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 获取或设置文本的自动适应模式。 |
| [getColumnCount()](#getColumnCount--) | 获取或设置文本区域的列数。 |
| [setColumnCount(int value)](#setColumnCount-int-) | 获取或设置文本区域的列数。 |
| [getColumnSpacing()](#getColumnSpacing--) | 获取或设置文本列之间的间距（点）。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 获取或设置文本列之间的间距（点）。 |
| [getRotationAngle()](#getRotationAngle--) | 指定自定义的文本在边框内的旋转角度。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定自定义的文本在边框内的旋转角度。 |
| [getTransform()](#getTransform--) | 获取或设置文本换行形状。 |
| [setTransform(byte value)](#setTransform-byte-) | 获取或设置文本换行形状。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 获取或设置即使已应用 3-D 旋转效果也保持文本平坦。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 获取或设置即使已应用 3-D 旋转效果也保持文本平坦。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效文本框格式化数据。 |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

初始化 [TextFrameFormat](../../com.aspose.slides/textframeformat) 类的一个新实例。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

返回文本的样式。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回：**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

返回表示文本 3D 效果属性的 ThreeDFormat 对象。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ``` 
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // 设置文本转换
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
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Returns or sets the left margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Returns or sets the left margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Returns or sets the right margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Returns or sets the right margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Returns or sets the top margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Returns or sets the top margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Returns or sets the bottom margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Returns or sets the bottom margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True if text is wrapped at TextFrame's margins. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True if text is wrapped at TextFrame's margins. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Returns or sets vertical anchor text in a TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

返回或设置 TextFrame 中的垂直锚点文本。可读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final byte getCenterText()
```

If NullableBool.True then text should be centered in box horizontally. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

If NullableBool.True then text should be centered in box horizontally. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Returns or sets text's autofit mode. Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Returns or sets text's autofit mode. Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```
Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double.

**Returns:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Returns:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Specifies custom the rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float.

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
public final byte getTransform()
```

Gets or sets text wrapping shape. Read/write [TextShapeType](../../com.aspose.slides/textshapetype).

**Returns:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Gets or sets text wrapping shape. Read/write [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean.

**Returns:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```
 
Gets or sets keeping text flat even if a 3-D Rotation effect was applied. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
Gets effective text frame formatting data with the inheritance applied.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回：**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).