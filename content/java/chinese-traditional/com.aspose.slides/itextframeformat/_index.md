---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: 包含 TextFrames 的格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

包含 TextFrame 的格式屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 返回文字樣式。 |
| [getMarginLeft()](#getMarginLeft--) | 返回或設定 TextFrame 中的左邊距（點）。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | 返回或設定 TextFrame 中的左邊距（點）。 |
| [getMarginRight()](#getMarginRight--) | 返回或設定 TextFrame 中的右邊距（點）。 |
| [setMarginRight(double value)](#setMarginRight-double-) | 返回或設定 TextFrame 中的右邊距（點）。 |
| [getMarginTop()](#getMarginTop--) | 返回或設定 TextFrame 中的上邊距（點）。 |
| [setMarginTop(double value)](#setMarginTop-double-) | 返回或設定 TextFrame 中的上邊距（點）。 |
| [getMarginBottom()](#getMarginBottom--) | 返回或設定 TextFrame 中的下邊距（點）。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | 返回或設定 TextFrame 中的下邊距（點）。 |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | 返回或設定 TextFrame 中的垂直錨點文字。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | 返回或設定 TextFrame 中的垂直錨點文字。 |
| [getCenterText()](#getCenterText--) | 如果 NullableBool.True，則文字應在框內水平置中。 |
| [setCenterText(byte value)](#setCenterText-byte-) | 如果 NullableBool.True，則文字應在框內水平置中。 |
| [getTextVerticalType()](#getTextVerticalType--) | 判斷文字方向。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 判斷文字方向。 |
| [getAutofitType()](#getAutofitType--) | 返回或設定文字的自動調整模式。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | 返回或設定文字的自動調整模式。 |
| [getColumnCount()](#getColumnCount--) | 返回或設定文字區域中的列數。 |
| [setColumnCount(int value)](#setColumnCount-int-) | 返回或設定文字區域中的列數。 |
| [getColumnSpacing()](#getColumnSpacing--) | 返回或設定文字區域中列之間的間距（點）。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | 返回或設定文字區域中列之間的間距（點）。 |
| [getThreeDFormat()](#getThreeDFormat--) | 返回表示文字 3D 效果屬性的 ThreeDFormat 物件。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 返回或設定將文字完全保留在 3D 場景之外。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 返回或設定將文字完全保留在 3D 場景之外。 |
| [getRotationAngle()](#getRotationAngle--) | 指定套用於文字於邊界框內的自訂旋轉。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | 指定套用於文字於邊界框內的自訂旋轉。 |
| [getTransform()](#getTransform--) | 取得或設定文字換行形狀。 |
| [setTransform(byte value)](#setTransform-byte-) | 取得或設定文字換行形狀。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效文字框格式資料。 |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

返回文字樣式。唯讀 [ITextStyle](../../com.aspose.slides/itextstyle).

**返回值:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

返回或設定 TextFrame 中的左邊距（點）。讀寫 double.

**返回值:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

返回或設定 TextFrame 中的左邊距（點）。讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

返回或設定 TextFrame 中的右邊距（點）。讀寫 double.

**返回值:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

返回或設定 TextFrame 中的右邊距（點）。讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

返回或設定 TextFrame 中的上邊距（點）。讀寫 double.

**返回值:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

返回或設定 TextFrame 中的上邊距（點）。讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

返回或設定 TextFrame 中的下邊距（點）。讀寫 double.

**返回值:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

返回或設定 TextFrame 中的下邊距（點）。讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True if text is wrapped at TextFrame's margins. 讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**返回值:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True if text is wrapped at TextFrame's margins. 讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

返回或設定 TextFrame 中的垂直錨點文字。讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**返回值:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

返回或設定 TextFrame 中的垂直錨點文字。讀寫 [TextAnchorType](../../com.aspose.slides/textanchortype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

如果 NullableBool.True，則文字應在框內水平置中。讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**返回值:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

如果 NullableBool.True，則文字應在框內水平置中。讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

判斷文字方向。此屬性與 RotationAngle 中的自訂角度共同決定最終的視覺文字旋轉值。讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**返回值:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

判斷文字方向。此屬性與 RotationAngle 中的自訂角度共同決定最終的視覺文字旋轉值。讀寫 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

返回或設定文字的自動調整模式。讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype).

**返回值:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

返回或設定文字的自動調整模式。讀寫 [TextAutofitType](../../com.aspose.slides/textautofittype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

返回或設定文字區域中的列數。此值必須為正數，否則會被設定為 0。值 0 表示未定義。讀寫 int.

**返回值:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

返回或設定文字區域中的列數。此值必須為正數，否則會被設定為 0。值 0 表示未定義。讀寫 int.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

返回或設定文字區域中列之間的間距（點）。僅在存在多於 1 列時適用。此值必須為正數，否則會被設定為 0。讀寫 double.

**返回值:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

返回或設定文字區域中列之間的間距（點）。僅在存在多於 1 列時適用。此值必須為正數，否則會被設定為 0。讀寫 double.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

返回表示文字 3D 效果屬性的 ThreeDFormat 物件。唯讀 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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


**返回值:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

返回或設定將文字完全保留在 3D 場景之外。讀寫 boolean.

**返回值:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

返回或設定將文字完全保留在 3D 場景之外。讀寫 boolean.

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

指定套用於文字於邊界框內的自訂旋轉。若未指定，則使用伴隨形狀的旋轉。若已指定，則獨立於形狀套用旋轉。此屬性與 TextVerticalType 中的預定義垂直類型共同決定最終的視覺文字旋轉值。讀寫 float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**返回值:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

指定套用於文字於邊界框內的自訂旋轉。若未指定，則使用伴隨形狀的旋轉。若已指定，則獨立於形狀套用旋轉。此屬性與 TextVerticalType 中的預定義垂直類型共同決定最終的視覺文字旋轉值。讀寫 float.

--------------------

> ```
> 考慮一個形狀已套用 90 度順時針旋轉的情況。 
>  此外，文字本身還套用了 -90 度逆時針旋轉。 
>  逆時針旋轉。然後，結果形狀會顯示為已旋轉，但其中的文字會看起來彷彿根本沒有被旋轉。 
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

取得或設定文字換行形狀。讀寫 [TextShapeType](../../com.aspose.slides/textshapetype).

**返回值:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

取得或設定文字換行形狀。讀寫 [TextShapeType](../../com.aspose.slides/textshapetype).

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

取得套用繼承後的有效文字框格式資料。

**返回值:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).