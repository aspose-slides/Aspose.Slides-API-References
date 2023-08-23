---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Contains the TextFrame's formatting properties.
## Methods

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getColumnCount()](#getColumnCount--) | Returns or sets number of columns in the text area. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returns or sets number of columns in the text area. |
| [getColumnSpacing()](#getColumnSpacing--) | Returns or sets the space between text columns in the text area (in points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returns or sets the space between text columns in the text area (in points). |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that represents 3d effect properties for a text. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Returns or set keeping text out of 3D scene entirely. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Returns or set keeping text out of 3D scene entirely. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [getTransform()](#getTransform--) | Gets or sets text wrapping shape. |
| [setTransform(byte value)](#setTransform-byte-) | Gets or sets text wrapping shape. |
| [getEffective()](#getEffective--) | Gets effective text frame formatting data with the inheritance applied. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Returns text's style. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Returns or sets the left margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Returns or sets the left margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Returns or sets the right margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Returns or sets the right margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Returns or sets the top margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Returns or sets the top margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Returns or sets the bottom margin (points) in a TextFrame. Read/write double.

**Returns:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Returns or sets the bottom margin (points) in a TextFrame. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


True if text is wrapped at TextFrame's margins. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


True if text is wrapped at TextFrame's margins. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Returns or sets vertical anchor text in a TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returns:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Returns or sets vertical anchor text in a TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


If NullableBool.True then text should be centered in box horizontally. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


If NullableBool.True then text should be centered in box horizontally. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returns:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Determines text orientation. The resulted value of visual text rotation summarized from this property and custom angle in property RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Returns or sets text's autofit mode. Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returns:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Returns or sets text's autofit mode. Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int.

**Returns:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Returns or sets number of columns in the text area. This value must be a positive number. Otherwise, the value will be set to zero. Value 0 means undefined value. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double.

**Returns:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Returns or sets the space between text columns in the text area (in points). This should only apply when there is more than 1 column present. This value must be a positive number. Otherwise, the value will be set to zero. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Returns the ThreeDFormat object that represents 3d effect properties for a text. Read-only [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Set text transformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Set Extrusion
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Set Contour
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Set Depth
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Set Material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Set Lighting
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Set camera type
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


Specifies the custom rotation that is being applied to the text within the bounding box. If it not specified, the rotation of the accompanying shape is used. If it is specified, then this is applied independently from the shape. That is the shape can have a rotation applied in addition to the text itself having a rotation applied to it. The resulted value of visual text rotation summarized from this property and predefined vertical type in property TextVerticalType. Read/write float.

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
```


Gets effective text frame formatting data with the inheritance applied.

**Returns:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).
