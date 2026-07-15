---
title: TextFrameFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 包含 TextFrames 的 formatTextFrameFormatting 屬性。
type: docs
url: /zh-hant/com.aspose.slides/textframeformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**已實作的介面：**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

包含 TextFrame 的 formatTextFrameFormatting 屬性。

## 建構式

| 建構式 | 說明 |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | 初始設定 [TextFrameFormat](../../com.aspose.slides/textframeformat) 類別的新執行個體。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | 傳回文字的樣式。 |
| [getThreeDFormat()](#getThreeDFormat--) | 傳回 ThreeDFormat 物件，該物件表示文字的 3D 效果屬性。 |
| [getMarginLeft()](#getMarginLeft--) | 傳回或設定 TextFrame 中的左邊距（點）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 傳回或設定 TextFrame 中的左邊距（點）。 |
| [getMarginRight()](#getMarginRight--) | 傳回或設定 TextFrame 中的右邊距（點）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 傳回或設定 TextFrame 中的右邊距（點）。 |
| [getMarginTop()](#getMarginTop--) | 傳回或設定 TextFrame 中的上邊距（點）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 傳回或設定 TextFrame 中的上邊距（點）。 |
| [getMarginBottom()](#getMarginBottom--) | 傳回或設定 TextFrame 中的下邊距（點）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 傳回或設定 TextFrame 中的下邊距（點）。 |
| [getWrapText()](#getWrapText--) | 如果文字在 TextFrame 的邊界換行則為 True。 |
| [setWrapText(byte value)](#setWrapText-byte-) | 如果文字在 TextFrame 的邊界換行則為 True。 |
| [getAnchoringType()](#getAnchoringType--) | 傳回或設定 TextFrame 中的垂直錨定文字。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 傳回或設定 TextFrame 中的垂直錨定文字。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，則文字應在水平上置中於方框內。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，則文字應在水平上置中於方框內。 |
| [getTextVerticalType()](#getTextVerticalType--) | 決定文字方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 決定文字方向。 |
| [getAutofitType()](#getAutofitType--) | 傳回或設定文字的自動調整模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 傳回或設定文字的自動調整模式。 |
| [getColumnCount()](#getColumnCount--) | 傳回或設定文字區域的欄位數。 |
| [setColumnCount(int value)](#setColumnCount-int-) | 傳回或設定文字區域的欄位數。 |
| [getColumnSpacing()](#getColumnSpacing--) | 傳回或設定文字區域中欄位的間距（點）。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 傳回或設定文字區域中欄位的間距（點）。 |
| [getRotationAngle()](#getRotationAngle--) | 指定自訂的旋轉角度，套用於邊界框內的文字。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定自訂的旋轉角度，套用於邊界框內的文字。 |
| [getTransform()](#getTransform--) | 取得或設定文字換行形狀。 |
| [setTransform(byte value)](#setTransform-byte-) | 取得或設定文字換行形狀。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 取得或設定即使套用 3-D 旋轉效果，仍保持文字平面。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 取得或設定即使套用 3-D 旋轉效果，仍保持文字平面。 |
| [getEffective()](#getEffective--) | 取得套用繼承的有效文字框格式資料。 |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

初始設定 [TextFrameFormat](../../com.aspose.slides/textframeformat) 類別的新執行個體。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回值：**
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

傳回文字的樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle)。

**傳回值：**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

傳回 ThreeDFormat 物件，該物件表示文字的 3D 效果屬性。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // 設定文字變形
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 設定擠出
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // 設定輪廓
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // 設定深度
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // 設定材質
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // 設定光照
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // 設定相機類型
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值：**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

傳回或設定 TextFrame 中的左邊距（點）。可讀寫 double。

**傳回值：**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

傳回或設定 TextFrame 中的左邊距（點）。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

傳回或設定 TextFrame 中的右邊距（點）。可讀寫 double。

**傳回值：**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

傳回或設定 TextFrame 中的右邊距（點）。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

傳回或設定 TextFrame 中的上邊距（點）。可讀寫 double。

**傳回值：**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

傳回或設定 TextFrame 中的上邊距（點）。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

傳回或設定 TextFrame 中的下邊距（點）。可讀寫 double。

**傳回值：**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

傳回或設定 TextFrame 中的下邊距（點）。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

如果文字在 TextFrame 的邊界換行則為 True。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

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

**傳回值：**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

如果文字在 TextFrame 的邊界換行則為 True。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

傳回或設定 TextFrame 中的垂直錨定文字。可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**傳回值：**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

傳回或設定 TextFrame 中的垂直錨定文字。可讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

如果 NullableBool.True，則文字應在水平上置中於方框內。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**傳回值：**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

如果 NullableBool.True，則文字應在水平上置中於方框內。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

決定文字方向。此屬性與 RotationAngle 的自訂角度彙總為視覺文字旋轉值。可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**傳回值：**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

決定文字方向。此屬性與 RotationAngle 的自訂角度彙總為視覺文字旋轉值。可讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

傳回或設定文字的自動調整模式。可讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype)。

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

**傳回值：**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

傳回或設定文字的自動調整模式。可讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype)。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

傳回或設定文字區域的欄位數。此數值必須為正數。否則，該值將被設定為 0。值 0 代表未定義的數值。可讀寫 int。

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

**傳回值：**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

傳回或設定文字區域的欄位數。此數值必須為正數。否則，該值將被設定為 0。值 0 代表未定義的數值。可讀寫 int。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

傳回或設定文字區域中欄位的間距（點）。僅在存在多於 1 個欄位時適用。此數值必須為正數。否則，該值將被設定為 0。可讀寫 double。

**傳回值：**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

傳回或設定文字區域中欄位的間距（點）。僅在存在多於 1 個欄位時適用。此數值必須為正數。否則，該值將被設定為 0。可讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

指定自訂的旋轉角度，套用於邊界框內的文字。若未指定，則使用隨附圖形的旋轉。如果指定，則獨立於圖形套用旋轉。也就是說，圖形可以有旋轉，文字本身亦可有旋轉。此屬性與 TextVerticalType 的預定義垂直類型彙總為視覺文字旋轉值。可讀寫 float。

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**傳回值：**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

指定自訂的旋轉角度，套用於邊界框內的文字。若未指定，則使用隨附圖形的旋轉。如果指定，則獨立於圖形套用旋轉。也就是說，圖形可以有旋轉，文字本身亦可有旋轉。此屬性與 TextVerticalType 的預定義垂直類型彙總為視覺文字旋轉值。可讀寫 float。

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

取得或設定文字換行形狀。可讀寫 [TextShapeType](../../com.aspose.slides/textshapetype)。

**傳回值：**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

取得或設定文字換行形狀。可讀寫 [TextShapeType](../../com.aspose.slides/textshapetype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

取得或設定即使套用 3-D 旋轉效果，仍保持文字平面。可讀寫 boolean。

**傳回值：**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

取得或設定即使套用 3-D 旋轉效果，仍保持文字平面。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

取得套用繼承的有效文字框格式資料。

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


**傳回值：**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).