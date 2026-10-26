---
title: TextFrameFormat
second_title: Aspose.Slides for Java API 参考
description: 包含 TextFrames 的 formatTextFrameFormatting 属性。
type: docs
url: /zh/com.aspose.slides/textframeformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**实现的所有接口:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

包含 TextFrame 的 formatTextFrameFormatting 属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | 初始化 [TextFrameFormat](../../com.aspose.slides/textframeformat) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | 返回文本的 style。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回 ThreeDFormat 对象，表示文本的 3d 效果属性。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或设置 TextFrame 中的左边距（点）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 返回或设置 TextFrame 中的左边距（点）。 |
| [getMarginRight()](#getMarginRight--) | 返回或设置 TextFrame 中的右边距（点）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 返回或设置 TextFrame 中的右边距（点）。 |
| [getMarginTop()](#getMarginTop--) | 返回或设置 TextFrame 中的上边距（点）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 返回或设置 TextFrame 中的上边距（点）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回或设置 TextFrame 中的下边距（点）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 返回或设置 TextFrame 中的下边距（点）。 |
| [getWrapText()](#getWrapText--) | 如果文本在 TextFrame 的边距处换行，则为 true。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文本在 TextFrame 的边距处换行，则为 true。 |
| [getAnchoringType()](#getAnchoringType--) | 返回或设置 TextFrame 中的垂直锚定文本。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 返回或设置 TextFrame 中的垂直锚定文本。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，则文本应水平居中于框中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，则文本应水平居中于框中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 确定文本方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 确定文本方向。 |
| [getAutofitType()](#getAutofitType--) | 返回或设置文本的 autofit 模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 返回或设置文本的 autofit 模式。 |
| [getColumnCount()](#getColumnCount--) | 返回或设置文本区域中的列数。 |
| [setColumnCount(int value)](#setColumnCount-int-) | 返回或设置文本区域中的列数。 |
| [getColumnSpacing()](#getColumnSpacing--) | 返回或设置文本区域中文本列之间的间距（点）。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 返回或设置文本区域中文本列之间的间距（点）。 |
| [getRotationAngle()](#getRotationAngle--) | 指定在边界框内应用于文本的自定义旋转。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定在边界框内应用于文本的自定义旋转。 |
| [getTransform()](#getTransform--) | 获取或设置文本换行形状。 |
| [setTransform(byte value)](#setTransform-byte-) | 获取或设置文本换行形状。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 获取或设置即使应用了 3-D 旋转效果也保持文本平面。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 获取或设置即使应用了 3-D 旋转效果也保持文本平面。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效文本框格式化数据。 |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

初始化 [TextFrameFormat](../../com.aspose.slides/textframeformat) 类的新实例。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

返回文本的 style。只读 [ITextStyle](../../com.aspose.slides/itextstyle)。

**返回:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

返回 ThreeDFormat 对象，表示文本的 3d 效果属性。只读 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // 设置文本变换
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 设置挤压
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


**返回:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

返回或设置 TextFrame 中的左边距（点）。读写 double。

**返回:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

返回或设置 TextFrame 中的左边距（点）。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

返回或设置 TextFrame 中的右边距（点）。读写 double。

**返回:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

返回或设置 TextFrame 中的右边距（点）。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

返回或设置 TextFrame 中的上边距（点）。读写 double。

**返回:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

返回或设置 TextFrame 中的上边距（点）。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

返回或设置 TextFrame 中的下边距（点）。读写 double。

**返回:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

返回或设置 TextFrame 中的下边距（点）。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

如果文本在 TextFrame 的边距处换行，则为 true。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

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


**返回:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

如果文本在 TextFrame 的边距处换行，则为 true。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

返回或设置 TextFrame 中的垂直锚定文本。读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**返回:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

返回或设置 TextFrame 中的垂直锚定文本。读写 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

如果 NullableBool.True，则文本应水平居中于框中。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

如果 NullableBool.True，则文本应水平居中于框中。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的结果值。读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**返回:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

确定文本方向。该属性与属性 RotationAngle 中的自定义角度共同决定可视文本旋转的结果值。读写 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

返回或设置文本的 autofit 模式。读写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

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


**返回:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

返回或设置文本的 autofit 模式。读写 [TextAutofitType](../../com.aspose.slides/textautofittype)。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

返回或设置文本区域中的列数。此值必须为正数。否则，该值将被设为零。值 0 表示未定义。读写 int。

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


**返回:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

返回或设置文本区域中的列数。此值必须为正数。否则，该值将被设为零。值 0 表示未定义。读写 int。

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


**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

返回或设置文本区域中文本列之间的间距（点）。仅在存在多于 1 列时适用。此值必须为正数。否则，该值将被设为零。读写 double。

**返回:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

返回或设置文本区域中文本列之间的间距（点）。仅在存在多于 1 列时适用。此值必须为正数。否则，该值将被设为零。读写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用随附形状的旋转。如果指定，则独立于形状应用旋转，即形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的结果值。读写 float。

--------------------

> ```
> 考虑一种情况，形状已应用顺时针 90 度的旋转。 
>  此外，文本本身已应用逆时针 -90 度的旋转。 
>  然后，结果形状看起来被旋转， 
>  但其中的文本看起来好像根本没有被旋转。 
```

**返回:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

指定在边界框内应用于文本的自定义旋转。如果未指定，则使用随附形状的旋转。如果指定，则独立于形状应用旋转，即形状可以有旋转，同时文本本身也可以有旋转。该属性与属性 TextVerticalType 中的预定义垂直类型共同决定可视文本旋转的结果值。读写 float。

--------------------

> ```
> 考虑一种情况，形状已应用顺时针 90 度的旋转。 
>  此外，文本本身已应用 -90 度的 
>  逆时针旋转。然后，结果形状会看起来被 
>  被旋转，但其中的文本看起来好像根本没有被旋转。 
```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

获取或设置文本换行形状。读写 [TextShapeType](../../com.aspose.slides/textshapetype)。

**返回:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

获取或设置文本换行形状。读写 [TextShapeType](../../com.aspose.slides/textshapetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

获取或设置即使应用了 3-D 旋转效果也保持文本平面。读写 boolean。

**返回:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public           



```

获取或设置即使应用了 3-D 旋转效果也保持文本平面。读写 boolean。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

获取应用继承后的有效文本框格式化数据。

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


**返回:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).