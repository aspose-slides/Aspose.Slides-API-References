---
title: Shape
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のシェイプを表します。
type: docs
url: /ja/com.aspose.slides/shape/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

スライド上のシェイプを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | 形状が TextHolder_PPT かどうかを判定します。 |
| [getPlaceholder()](#getPlaceholder--) | シェイプのプレースホルダーを返します。 |
| [removePlaceholder()](#removePlaceholder--) | このシェイプがプレースホルダーでないことを定義します。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたものにプレースホルダーのプロパティを設定します。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 基本的なプレースホルダーシェイプを返します（レイアウトやマスタースライドから継承されたシェイプ）。 |
| [getCustomData()](#getCustomData--) | シェイプのカスタムデータを返します。 |
| [getRawFrame()](#getRawFrame--) | 生のシェイプフレームのプロパティを取得または設定します。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 生のシェイプフレームのプロパティを取得または設定します。 |
| [getFrame()](#getFrame--) | シェイプフレームのプロパティを取得または設定します。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | シェイプフレームのプロパティを取得または設定します。 |
| [getLineFormat()](#getLineFormat--) | シェイプの線フォーマットプロパティを含む LineFormat オブジェクトを返します。 |
| [getThreeDFormat()](#getThreeDFormat--) | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。 |
| [getEffectFormat()](#getEffectFormat--) | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。 |
| [getFillFormat()](#getFillFormat--) | シェイプの塗りつぶしフォーマットプロパティを含む FillFormat オブジェクトを返します。 |
| [getImage()](#getImage--) | シェイプのサムネイルを返します。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | シェイプのサムネイルを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | シェイプの内容を SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | シェイプの内容を SVG ファイルとして保存します。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | ハイパーリンクマネージャーを返します。 |
| [getHidden()](#getHidden--) | シェイプが非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | シェイプが非表示かどうかを判定します。 |
| [getZOrderPosition()](#getZOrderPosition--) | z 順序におけるシェイプの位置を返します。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | シェイプ上の接続ポイントの数を返します。 |
| [getRotation()](#getRotation--) | 指定されたシェイプが z 軸を中心に回転した角度（度）を取得または設定します。 |
| [setRotation(float value)](#setRotation-float-) | 指定されたシェイプが z 軸を中心に回転した角度（度）を取得または設定します。 |
| [getX()](#getX--) | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。 |
| [setX(float value)](#setX-float-) | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。 |
| [getY()](#getY--) | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。 |
| [setY(float value)](#setY-float-) | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。 |
| [getWidth()](#getWidth--) | シェイプの幅（ポイント単位）を取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | シェイプの幅（ポイント単位）を取得または設定します。 |
| [getHeight()](#getHeight--) | シェイプの高さ（ポイント単位）を取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | シェイプの高さ（ポイント単位）を取得または設定します。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。 |
| [getUniqueId()](#getUniqueId--) | アドインや他のコードで使用することを想定した、プレゼンテーション内部スコープの識別子を返します。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | シェイプの存続期間中一定であり、PowerPoint やインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにする、スライドスコープの一意な識別子を返します。 |
| [getAlternativeText()](#getAlternativeText--) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [getName()](#getName--) | シェイプの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | シェイプの名前を取得または設定します。 |
| [isDecorative()](#isDecorative--) | 'Mark as decorative' オプションを取得または設定します。読み書き boolean。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 'Mark as decorative' オプションを取得または設定します。読み書き boolean。 |
| [getShapeLock()](#getShapeLock--) | シェイプのロック情報を返します。 |
| [isGrouped()](#isGrouped--) | シェイプがグループ化されているかどうかを判定します。 |
| [getParentGroup()](#getParentGroup--) | シェイプがグループ化されている場合、親の GroupShape オブジェクトを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [getSlide()](#getSlide--) | シェイプの親スライドを返します。 |
| [getPresentation()](#getPresentation--) | スライドの親プレゼンテーションを返します。 |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

形状が TextHolder_PPT かどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

シェイプのプレースホルダーを返します。シェイプにプレースホルダーが無い場合は null を返します。読み取り専用 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantiates a Presentation class
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterates through shapes to find the placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Changes the text in each placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Saves the presentation to disk
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // Iterates through the slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint displays "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adds subtitle
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

このシェイプがプレースホルダーでないことを定義します。

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたものにプレースホルダーのプロパティを設定します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | コピー元のプレースホルダー。 |

**戻り値:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新しい \#getPlaceholder.getPlaceholder。

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

基本的なプレースホルダーシェイプを返します（レイアウトやマスタースライドから継承されたシェイプ）。

--------------------

> ```
> // プレースホルダーシェイプの (マスター/レイアウト/スライド) すべてのアニメーション効果を取得します
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

現在のシェイプが継承されていない場合は null が返されます。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../com.aspose.slides/icustomdata)。

**戻り値:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

生のシェイプフレームのプロパティを取得または設定します。読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //または
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //このようなコードは不明瞭な状況を引き起こす可能性があります。そのため、IShape.getFrame() で未定義の値を使用することに制限が追加されました。x、y、幅、高さ、flipH、flipV、rotationAngle の値は必ず定義されている必要があります（Float.NaN または NullableBool.NotDefined ではいけません）。上記のサンプルコードは現在 ArgumentException 例外をスローします。
>  //これは以下の使用例に適用されます:
>  IShape shape = ...;
>  shape.setFrame(...); // 未定義にできません
>  IShapeCollection shapes = ...;
>  // x、y、幅、高さ のパラメータは Float.NaN にできません:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //ただし、IShape.RawFrame のフレームプロパティは未定義にすることができます。これはシェイプがプレースホルダーにリンクされている場合に意味があります。その場合、未定義のシェイプフレーム値は親プレースホルダーシェイプから上書きされます。シェイプに親プレースホルダーが存在しない場合、IShape.RawFrame を基に有効フレームを評価するときにデフォルト値が使用されます。デフォルト値は x、y、幅、高さ、flipH、flipV、rotationAngle に対して 0 と NullableBool.False です。例:
>  IShape shape = ...; // シェイプはプレースホルダーにリンクされています
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // これでシェイプはプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします.{code}
> ```


**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

生のシェイプフレームのプロパティを取得または設定します。読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

シェイプフレームのプロパティを取得または設定します。読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返された IShapeFrame インスタンスの各プロパティの値は undefined ではありません（NaN でも NotDefined でもありません）。割り当てられた IShapeFrame インスタンスの各プロパティの値は undefined であってはなりません（NaN でも NotDefined でもありません）。RawFrame インスタンスのプロパティに undefined 値を設定することができます。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

シェイプフレームのプロパティを取得または設定します。読み書き [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返された IShapeFrame インスタンスの各プロパティの値は undefined ではありません（NaN でも NotDefined でもありません）。割り当てられた IShapeFrame インスタンスの各プロパティの値は undefined であってはなりません（NaN でも NotDefined でもありません）。RawFrame インスタンスのプロパティに undefined 値を設定することができます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

シェイプの線フォーマットプロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**戻り値:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。注: エフェクトプロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

シェイプの塗りつぶしフォーマットプロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - シェイプのサムネイル。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

シェイプのサムネイルを返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | シェイプサムネイルの境界タイプ。 |
| scaleX | float | X スケール |
| scaleY | float | Y スケール |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - ShapeThumbnailBounds.Appearance が使用され、シェイプに表示要素がない場合は null を返します。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き [IHyperlink](../../com.aspose.slides/ihyperlink)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き [IHyperlink](../../com.aspose.slides/ihyperlink)。

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き [IHyperlink](../../com.aspose.slides/ihyperlink)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)。

**戻り値:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

シェイプが非表示かどうかを判定します。読み書き boolean。

**戻り値:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

シェイプが非表示かどうかを判定します。読み書き boolean。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

z 順序におけるシェイプの位置を返します。Shapes[0] は z 順序の背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 int。

**戻り値:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

シェイプ上の接続ポイントの数を返します。読み取り専用 int。

**戻り値:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

指定されたシェイプが z 軸を中心に回転した角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き float。

--------------------

返される値は常に定義されており（Float.NaN ではありません）。割り当てる値も定義されていなければなりません（Float.NaN ではありません）。RawFrame インスタンスのプロパティに undefined 値を設定することができます。

**戻り値:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write float.

--------------------

Returned value is always defined (is not Float.NaN). Assigned value must be defined (not Float.NaN). You can set undefined values for RawFrame instance properties.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**戻り値:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**戻り値:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**戻り値:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

Gets or sets the width of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**戻り値:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Gets or sets the height of the shape, measured in points. Read/write float.

--------------------

The value returned is always defined and never Float.NaN. The value assigned must also be defined; assign Float.NaN only to properties of a RawFrame instance.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**戻り値:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

Property specifies how a shape will render in black-and-white display mode.. Read/write [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. Because this value can be reassigned by the user or programmatically, it must not be treated as a persistent unique key. Read-only long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**戻り値:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. Read-only long. See also \#getUniqueId.getUniqueId.

**戻り値:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

Returns or sets the alternative text associated with a shape. Read/write String.

**戻り値:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

Returns or sets the alternative text associated with a shape. Read/write String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**戻り値:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

Returns or sets the title of alternative text associated with a shape. Read/write String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

Gets or sets 'Mark as decorative' option Reed/write boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

Returns shape's locks. Read-only [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**戻り値:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

Determines whether the shape is grouped. Read-only boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**戻り値:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returns Parent\_Immediate object. Read-only IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

Gets the visual bounds of the shape calculated from its rendered content.

**戻り値:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

The returned rectangle represents the axis-aligned bounds of all content produced by the shape during rendering in slide coordinate space. These bounds may differ from the shape's model bounds \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) and may contain negative coordinates if the rendered content extends beyond the slide origin. The visual bounds take into account rendering-related aspects such as transformations (for example, rotation), stroke width and joins, text layout and overflow, SmartArt geometry, and other layout effects that influence the final rendered appearance of the shape. The returned bounds are not clipped to the slide rectangle.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a shape. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a slide. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)