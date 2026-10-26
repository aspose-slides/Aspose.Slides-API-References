---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /ja/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

TextFrame の書式設定プロパティを含みます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | テキストのスタイルを返します。 |
| [getMarginLeft()](#getMarginLeft--) | TextFrame の左余白（ポイント）を取得または設定します。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame の左余白（ポイント）を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | TextFrame の右余白（ポイント）を取得または設定します。 |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame の右余白（ポイント）を取得または設定します。 |
| [getMarginTop()](#getMarginTop--) | TextFrame の上余白（ポイント）を取得または設定します。 |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame の上余白（ポイント）を取得または設定します。 |
| [getMarginBottom()](#getMarginBottom--) | TextFrame の下余白（ポイント）を取得または設定します。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame の下余白（ポイント）を取得または設定します。 |
| [getWrapText()](#getWrapText--) | テキストが TextFrame の余白で折り返される場合は true。 |
| [setWrapText(byte value)](#setWrapText-byte-) | テキストが TextFrame の余白で折り返される場合は true。 |
| [getAnchoringType()](#getAnchoringType--) | TextFrame の垂直アンカーテキストを取得または設定します。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame の垂直アンカーテキストを取得または設定します。 |
| [getCenterText()](#getCenterText--) | NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されます。 |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されます。 |
| [getTextVerticalType()](#getTextVerticalType--) | テキストの向きを決定します。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | テキストの向きを決定します。 |
| [getAutofitType()](#getAutofitType--) | テキストの自動調整モードを取得または設定します。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | テキストの自動調整モードを取得または設定します。 |
| [getColumnCount()](#getColumnCount--) | テキスト領域の列数を取得または設定します。 |
| [setColumnCount(int value)](#setColumnCount-int-) | テキスト領域の列数を取得または設定します。 |
| [getColumnSpacing()](#getColumnSpacing--) | テキスト領域の列間のスペース（ポイント）を取得または設定します。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | テキスト領域の列間のスペース（ポイント）を取得または設定します。 |
| [getThreeDFormat()](#getThreeDFormat--) | テキストの 3D 効果プロパティを表す ThreeDFormat オブジェクトを返します。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | テキストを 3D シーンから完全に除外するかどうかを取得または設定します。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | テキストを 3D シーンから完全に除外するかどうかを取得または設定します。 |
| [getRotationAngle()](#getRotationAngle--) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 |
| [getTransform()](#getTransform--) | テキストの折り返し形状を取得または設定します。 |
| [setTransform(byte value)](#setTransform-byte-) | テキストの折り返し形状を取得または設定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテキストフレームの書式設定データを取得します。 |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

テキストのスタイルを返します。 読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame の左余白（ポイント）を取得または設定します。 読み書き double。

**戻り値:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

TextFrame の左余白（ポイント）を取得または設定します。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame の右余白（ポイント）を取得または設定します。 読み書き double。

**戻り値:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

TextFrame の右余白（ポイント）を取得または設定します。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame の上余白（ポイント）を取得または設定します。 読み書き double。

**戻り値:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

TextFrame の上余白（ポイント）を取得または設定します。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame の下余白（ポイント）を取得または設定します。 読み書き double。

**戻り値:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

TextFrame の下余白（ポイント）を取得または設定します。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

テキストが TextFrame の余白で折り返される場合は true。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

テキストが TextFrame の余白で折り返される場合は true。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame の垂直アンカーテキストを取得または設定します。 読み書き [TextAnchorType](../../com.aspose.slides/textanchortype)。

**戻り値:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

TextFrame の垂直アンカーテキストを取得または設定します。 読み書き [TextAnchorType](../../com.aspose.slides/textanchortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されます。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されます。 読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

テキストの向きを決定します。 このプロパティと RotationAngle のカスタム角度から総合された視覚的テキスト回転値が結果となります。 読み書き [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**戻り値:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

テキストの向きを決定します。 このプロパティと RotationAngle のカスタム角度から総合された視覚的テキスト回転値が結果となります。 読み書き [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

テキストの自動調整モードを取得または設定します。 読み書き [TextAutofitType](../../com.aspose.slides/textautofittype)。

**戻り値:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

テキストの自動調整モードを取得または設定します。 読み書き [TextAutofitType](../../com.aspose.slides/textautofittype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

テキスト領域の列数を取得または設定します。 この値は正の数でなければなりません。そうでない場合、0 に設定されます。0 は未定義を意味します。 読み書き int。

**戻り値:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

テキスト領域の列数を取得または設定します。 この値は正の数でなければなりません。そうでない場合、0 に設定されます。0 は未定義を意味します。 読み書き int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

テキスト領域の列間のスペース（ポイント）を取得または設定します。 1 列以上が存在する場合にのみ適用されます。 この値は正の数でなければなりません。そうでない場合、0 に設定されます。 読み書き double。

**戻り値:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

テキスト領域の列間のスペース（ポイント）を取得または設定します。 1 列以上が存在する場合にのみ適用されます。 この値は正の数でなければなりません。そうでない場合、0 に設定されます。 読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

テキストの 3D 効果プロパティを表す ThreeDFormat オブジェクトを返します。 読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // テキストの変形を設定
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 押し出しを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // 輪郭を設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // 奥行きを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // マテリアルを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // ライティングを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // カメラタイプを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

テキストを 3D シーンから完全に除外するかどうかを取得または設定します。 読み書き boolean。

**戻り値:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

テキストを 3D シーンから完全に除外するかどうかを取得または設定します。 読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 指定されていない場合は、同伴するシェイプの回転が使用されます。 指定された場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上に、テキスト自体にも回転が適用されることがあります。 このプロパティと TextVerticalType の事前定義された垂直タイプから総合された視覚的テキスト回転値が結果となります。 読み書き float。

--------------------

> ```
> 形状に 90 度の時計回りの回転が適用されたケースを考えてみましょう。 
>   さらに、テキスト本体自体にも -90 度の反時計回りの回転が適用されています。 
>   すると、結果として得られる形状は回転したように見えますが
>   テキストは回転していないかのように見えます。
```

**戻り値:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 指定されていない場合は、同伴するシェイプの回転が使用されます。 指定された場合、シェイプとは独立して適用されます。つまり、シェイプに回転が適用されている上に、テキスト自体にも回転が適用されることがあります。 このプロパティと TextVerticalType の事前定義された垂直タイプから総合された視覚的テキスト回転値が結果となります。 読み書き float。

--------------------

> ```
> 形状に 90 度の時計回りの回転が適用された場合を考えてみましょう。 
>  さらに、テキスト本体自体にも -90 度の反時計回りの回転が適用されています。 
>  すると、結果として得られる形状は回転したように見えますが
>  テキストは回転していないかのように見えます。 
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

テキストの折り返し形状を取得または設定します。 読み書き [TextShapeType](../../com.aspose.slides/textshapetype)。

**戻り値:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

テキストの折り返し形状を取得または設定します。 読み書き [TextShapeType](../../com.aspose.slides/textshapetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

継承が適用された有効なテキストフレームの書式設定データを取得します。

**戻り値:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).