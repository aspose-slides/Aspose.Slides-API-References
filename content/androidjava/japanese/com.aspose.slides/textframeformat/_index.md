---
title: TextFrameFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: TextFrames の formatTextFrameFormatting プロパティを含みます。
type: docs
url: /ja/com.aspose.slides/textframeformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

TextFrame の formatTextFrameFormatting プロパティを含みます。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | [TextFrameFormat](../../com.aspose.slides/textframeformat) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | テキストのスタイルを返します。 |
| [getThreeDFormat()](#getThreeDFormat--) | テキストの3D効果プロパティを表す ThreeDFormat オブジェクトを返します。 |
| [getMarginLeft()](#getMarginLeft--) | TextFrame の左余白 (ポイント) を取得または設定します。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame の左余白 (ポイント) を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | TextFrame の右余白 (ポイント) を取得または設定します。 |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame の右余白 (ポイント) を取得または設定します。 |
| [getMarginTop()](#getMarginTop--) | TextFrame の上余白 (ポイント) を取得または設定します。 |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame の上余白 (ポイント) を取得または設定します。 |
| [getMarginBottom()](#getMarginBottom--) | TextFrame の下余白 (ポイント) を取得または設定します。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame の下余白 (ポイント) を取得または設定します。 |
| [getWrapText()](#getWrapText--) | TextFrame の余白でテキストが折り返される場合は true。 |
| [setWrapText(byte value)](#setWrapText-byte-) | TextFrame の余白でテキストが折り返される場合は true。 |
| [getAnchoringType()](#getAnchoringType--) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | TextFrame の垂直アンカー テキストを取得または設定します。 |
| [getCenterText()](#getCenterText--) | NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されるべきです。 |
| [setCenterText(byte value)](#setCenterText-byte-) | NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されるべきです。 |
| [getTextVerticalType()](#getTextVerticalType--) | テキストの向きを決定します。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | テキストの向きを決定します。 |
| [getAutofitType()](#getAutofitType--) | テキストの自動フィットモードを取得または設定します。 |
| [setAutofitType(byte value)](#setAutofitType-byte-) | テキストの自動フィットモードを取得または設定します。 |
| [getColumnCount()](#getColumnCount--) | テキスト領域の列数を取得または設定します。 |
| [setColumnCount(int value)](#setColumnCount-int-) | テキスト領域の列数を取得または設定します。 |
| [getColumnSpacing()](#getColumnSpacing--) | テキスト領域の列間スペース (ポイント) を取得または設定します。 |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | テキスト領域の列間スペース (ポイント) を取得または設定します。 |
| [getRotationAngle()](#getRotationAngle--) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 |
| [setRotationAngle(float value)](#setRotationAngle-float-) | バウンディングボックス内のテキストに適用されるカスタム回転を指定します。 |
| [getTransform()](#getTransform--) | テキストの折り返し形状を取得または設定します。 |
| [setTransform(byte value)](#setTransform-byte-) | テキストの折り返し形状を取得または設定します。 |
| [getKeepTextFlat()](#getKeepTextFlat--) | 3D回転効果が適用されてもテキストを平面のままに保つかを取得または設定します。 |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | 3D回転効果が適用されてもテキストを平面のままに保つかを取得または設定します。 |
| [getEffective()](#getEffective--) | 継承が適用された有効なテキストフレーム書式設定データを取得します。 |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

[TextFrameFormat](../../com.aspose.slides/textframeformat) クラスの新しいインスタンスを初期化します。

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long。

**戻り値:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

テキストのスタイルを返します。読み取り専用 [ITextStyle](../../com.aspose.slides/itextstyle)。

**戻り値:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

テキストの3D効果プロパティを表す ThreeDFormat オブジェクトを返します。読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // テキスト変換を設定
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // 押し出しを設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // 輪郭を設定
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // 深さを設定
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
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

TextFrame の左余白 (ポイント) を取得または設定します。読み書き double。

**戻り値:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

TextFrame の左余白 (ポイント) を取得または設定します。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

TextFrame の右余白 (ポイント) を取得または設定します。読み書き double。

**戻り値:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

TextFrame の右余白 (ポイント) を取得または設定します。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

TextFrame の上余白 (ポイント) を取得または設定します。読み書き double。

**戻り値:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

TextFrame の上余白 (ポイント) を取得または設定します。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

TextFrame の下余白 (ポイント) を取得または設定します。読み書き double。

**戻り値:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

TextFrame の下余白 (ポイント) を取得または設定します。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

TextFrame の余白でテキストが折り返される場合は true。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

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


**戻り値:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

TextFrame の余白でテキストが折り返される場合は true。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

TextFrame の垂直アンカー テキストを取得または設定します。読み書き [TextAnchorType](../../com.aspose.slides/textanchortype)。

**戻り値:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

TextFrame の垂直アンカー テキストを取得または設定します。読み書き [TextAnchorType](../../com.aspose.slides/textanchortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されるべきです。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**戻り値:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

NullableBool.True の場合、テキストは水平方向にボックスの中央に配置されるべきです。読み書き [NullableBool](../../com.aspose.slides/nullablebool)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

テキストの向きを決定します。Visual なテキスト回転は本プロパティと RotationAngle のカスタム角度から合成されます。読み書き [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**戻り値:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

テキストの向きを決定します。Visual なテキスト回転は本プロパティと RotationAngle のカスタム角度から合成されます。読み書き [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

テキストの自動フィットモードを取得または設定します。読み書き [TextAutofitType](../../com.aspose.slides/textautofittype)。

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


**戻り値:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

テキストの自動フィットモードを取得または設定します。読み書き [TextAutofitType](../../com.aspose.slides/textautofittype)。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

テキスト領域の列数を取得または設定します。この値は正の数でなければなりません。そうでなければ 0 に設定されます。0 は未定義を意味します。読み書き int。

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


**戻り値:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

テキスト領域の列数を取得または設定します。この値は正の数でなければなりません。そうでなければ 0 に設定されます。0 は未定義を意味します。読み書き int。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

テキスト領域の列間スペース (ポイント) を取得または設定します。列が 1 つ以上ある場合にのみ適用されます。この値は正の数でなければなりません。そうでなければ 0 に設定されます。読み書き double。

**戻り値:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

テキスト領域の列間スペース (ポイント) を取得または設定します。列が 1 つ以上ある場合にのみ適用されます。この値は正の数でなければなりません。そうでなければ 0 に設定されます。読み書き double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、添付シェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。シェイプに回転が適用され、テキスト自体にも回転が適用されることがあります。Visual なテキスト回転は本プロパティと TextVerticalType の事前定義垂直タイプから合成されます。読み書き float。

--------------------

> ```
> シェイプに 90 度の時計回りの回転が適用されている場合を考えてみます。 
>  さらに、テキスト本体自体には -90 度の反時計回りの回転が適用されています。 
>  その結果、シェイプは回転したように見えますが、内部のテキストは全く回転していないかのように見えます。
> ```


**戻り値:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

バウンディングボックス内のテキストに適用されるカスタム回転を指定します。指定されていない場合は、添付シェイプの回転が使用されます。指定されている場合、シェイプとは独立して適用されます。シェイプに回転が適用され、テキスト自体にも回転が適用されることがあります。Visual なテキスト回転は本プロパティと TextVerticalType の事前定義垂直タイプから合成されます。読み書き float。

--------------------

> ```
> シェイプに 90 度の時計回りの回転が適用されている場合を考えてみます。 
>  さらに、テキスト本体自体には -90 度の反時計回りの回転が適用されています。 
>  その結果、シェイプは回転したように見えますが、内部のテキストは全く回転していないかのように見えます。
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public final byte getTransform()
```

テキストの折り返し形状を取得または設定します。読み書き [TextShapeType](../../com.aspose.slides/textshapetype)。

**戻り値:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

テキストの折り返し形状を取得または設定します。読み書き [TextShapeType](../../com.aspose.slides/textshapetype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

テキストを 3D 回転効果が適用されても平面のままに保つかを取得または設定します。読み書き boolean。

**戻り値:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

テキストを 3D 回転効果が適用されても平面のままに保つかを取得または設定します。読み書き boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

継承が適用された有効なテキストフレーム書式設定データを取得します。

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


**戻り値:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).