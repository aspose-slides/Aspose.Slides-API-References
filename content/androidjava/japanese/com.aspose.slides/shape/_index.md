---
title: Shape
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: スライド上のシェイプを表します。
type: docs
url: /ja/com.aspose.slides/shape/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

スライド上のシェイプを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | シェイプが TextHolder_PPT かどうかを判定します。 |
| [getPlaceholder()](#getPlaceholder--) | シェイプのプレースホルダーを返します。 |
| [removePlaceholder()](#removePlaceholder--) | このシェイプがプレースホルダーではないことを定義します。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 基本的なプレースホルダー シェイプを返します（レイアウトまたはマスタースライドから継承されたシェイプ）。 |
| [getCustomData()](#getCustomData--) | シェイプのカスタム データを返します。 |
| [getRawFrame()](#getRawFrame--) | 生のシェイプ フレームのプロパティを取得または設定します。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 生のシェイプ フレームのプロパティを取得または設定します。 |
| [getFrame()](#getFrame--) | シェイプ フレームのプロパティを取得または設定します。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | シェイプ フレームのプロパティを取得または設定します。 |
| [getLineFormat()](#getLineFormat--) | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。 |
| [getThreeDFormat()](#getThreeDFormat--) | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。 |
| [getEffectFormat()](#getEffectFormat--) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。 |
| [getFillFormat()](#getFillFormat--) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 |
| [getImage()](#getImage--) | シェイプのサムネイルを返します。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | シェイプのサムネイルを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | シェイプの内容を SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | シェイプの内容を SVG ファイルとして保存します。 |
| [getHyperlinkClick()](#getHyperlinkClick--) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | マウスクリック用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 |
| [getHyperlinkManager()](#getHyperlinkManager--) | ハイパーリンク マネージャーを返します。 |
| [getHidden()](#getHidden--) | シェイプが非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | シェイプが非表示かどうかを判定します。 |
| [getZOrderPosition()](#getZOrderPosition--) | シェイプの Z 順序内での位置を返します。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | シェイプ上の接続ポイントの数を返します。 |
| [getRotation()](#getRotation--) | 指定されたシェイプが Z 軸周りに回転する度数を取得または設定します。 |
| [setRotation(float value)](#setRotation-float-) | 指定されたシェイプが Z 軸周りに回転する度数を取得または設定します。 |
| [getX()](#getX--) | ポイントで測定したシェイプ左上隅の X 座標を取得または設定します。 |
| [setX(float value)](#setX-float-) | ポイントで測定したシェイプ左上隅の X 座標を取得または設定します。 |
| [getY()](#getY--) | ポイントで測定したシェイプ左上隅の Y 座標を取得または設定します。 |
| [setY(float value)](#setY-float-) | ポイントで測定したシェイプ左上隅の Y 座標を取得または設定します。 |
| [getWidth()](#getWidth--) | ポイントで測定したシェイプの幅を取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | ポイントで測定したシェイプの幅を取得または設定します。 |
| [getHeight()](#getHeight--) | ポイントで測定したシェイプの高さを取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | ポイントで測定したシェイプの高さを取得または設定します。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。 |
| [getUniqueId()](#getUniqueId--) | アドインやその他のコードで使用することを想定した、プレゼンテーション スコープの内部識別子を返します。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | スライド スコープの一意の識別子を返します。この識別子はシェイプの存続期間中は一定で、PowerPoint やインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できます。 |
| [getAlternativeText()](#getAlternativeText--) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [getName()](#getName--) | シェイプの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | シェイプの名前を取得または設定します。 |
| [isDecorative()](#isDecorative--) | 「装飾としてマーク」オプションの取得/設定（読み書き）ブール値です。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 「装飾としてマーク」オプションの取得/設定（読み書き）ブール値です。 |
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

シェイプが TextHolder_PPT かどうかを判定します。**読み取り専用** boolean .

**戻り値:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

シェイプのプレースホルダーを返します。シェイプにプレースホルダーがない場合は null を返します。**読み取り専用** [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Presentation クラスのインスタンスを作成します
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // 最初のスライドにアクセスします
>      ISlide sld = pres.getSlides().get_Item(0);
>      // プレースホルダーを見つけるためにシェイプを反復処理します
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // 各プレースホルダーのテキストを変更します
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // プレゼンテーションをディスクに保存します
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
>      for (IShape shape : slide.getSlide().getShapes()) // スライドを反復処理します
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint は "Click to add title" と表示します
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // サブタイトルを追加します
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

このシェイプがプレースホルダーではないことを定義します。

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | 内容をコピーするプレースホルダー。 |

**戻り値:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新しい #getPlaceholder.getPlaceholder。

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

基本的なプレースホルダー シェイプを返します（レイアウトまたはマスタースライドから継承されたシェイプ）。

--------------------

> ```
> // プレースホルダー シェイプの (マスター/レイアウト/スライド) のすべてのアニメーション効果を取得します
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

シェイプのカスタム データを返します。**読み取り専用** [ICustomData](../../com.aspose.slides/icustomdata).

**戻り値:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

生のシェイプ フレームのプロパティを取得または設定します。**読み書き** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //または
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //このようなコードは不明瞭な状況を招く可能性があります。そのため IShape.getFrame() に未定義の値を使用することに制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されている必要があります（Float.NaN または NullableBool.NotDefined ではいけません）。上記のサンプルコードは現在 ArgumentException をスローします。
>  //これは以下の使用例に適用されます:
>  IShape shape = ...;
>  shape.setFrame(...); // 未定義にできません
>  IShapeCollection shapes = ...;
>  // x、y、width、height パラメータは Float.NaN にできません:
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
>  //ただし IShape.RawFrame のフレーム プロパティは未定義にできる場合があります。これはシェイプがプレースホルダーにリンクされているときに意味があります。その場合、未定義のシェイプ フレーム値は親プレースホルダー シェイプから上書きされます。該当シェイプに親プレースホルダーが存在しない場合、シェイプは IShape.RawFrame に基づいて有効フレームを評価する際にデフォルト値を使用します。デフォルト値は x、y、width、height、flipH、flipV、rotationAngle に対して 0 と NullableBool.False です。例:
>  IShape shape = ...; // シェイプはプレースホルダーにリンクされています
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在シェイプはプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。{code}
> ```


**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

生のシェイプ フレームのプロパティを取得または設定します。**読み書き** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //または
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //このようなコードは不明瞭な状況を招く可能性があります。そのため IShape.getFrame() に未定義の値を使用することに制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されている必要があります（Float.NaN または NullableBool.NotDefined ではいけません）。上記の例コードは現在 ArgumentException をスローします。
>  //これらの使用例に適用されます：
>  IShape shape = ...;
>  shape.setFrame(...); // 未定義にできません
>  IShapeCollection shapes = ...;
>  // x、y、width、height パラメータは Float.NaN にできません：
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
>  //ただし IShape.RawFrame のフレーム プロパティは未定義にできます。これはシェイプがプレースホルダーにリンクされている場合に意味があります。その場合、未定義のシェイプ フレーム値は親プレースホルダー シェイプから上書きされます。該当シェイプに親プレースホルダーが存在しない場合、シェイプは IShape.RawFrame に基づいて有効フレームを評価する際にデフォルト値を使用します。デフォルト値は x、y、width、height、flipH、flipV、rotationAngle に対して 0 と NullableBool.False です。例：
>  IShape shape = ...; // シェイプはプレースホルダーにリンクされています
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // 現在シェイプはプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。{code}
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

シェイプ フレームのプロパティを取得または設定します。**読み書き** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

返される IShapeFrame インスタンスの各プロパティは未定義ではありません（NaN または NotDefined ではない）。割り当てられた IShapeFrame インスタンスの各プロパティも未定義であってはなりません（NaN または NotDefined ではない）。RawFrame インスタンスのプロパティに未定義の値を設定することはできます。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

シェイプ フレームのプロパティを取得または設定します。**読み書き** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

返される IShapeFrame インスタンスの各プロパティは未定義ではありません（NaN または NotDefined ではない）。割り当てられた IShapeFrame インスタンスの各プロパティも未定義であってはなりません（NaN または NotDefined ではない）。RawFrame インスタンスのプロパティに未定義の値を設定することはできます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定のシェイプの場合、null が返されることがあります。**読み取り専用** [ILineFormat](../../com.aspose.slides/ilineformat).

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプの場合、null が返されることがあります。**読み取り専用** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**戻り値:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注: エフェクトプロパティを持たない特定のシェイプの場合、null が返されることがあります。**読み取り専用** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプの場合、null が返されることがあります。**読み取り専用** [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // アクセント4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // アクセント4、明るさ80%増
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // アクセント4、明るさ60%増
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // アクセント4、明るさ40%増
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // アクセント4、暗さ25%増
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // アクセント4、暗さ50%増
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

シェイプのサムネイルを返します。デフォルトで ShapeThumbnailBounds.Shape が使用されます。

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - シェイプ サムネイル。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

シェイプのサムネイルを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| bounds | int | シェイプ サムネイルの境界タイプ。 |
| scaleX | float | X スケール |
| scaleY | float | Y スケール |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - シェイプ サムネイル。ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は null が返されます。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲット ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲット ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。**読み書き** [IHyperlink](../../com.aspose.slides/ihyperlink).

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

マウスクリック用に定義されたハイパーリンクを取得または設定します。**読み書き** [IHyperlink](../../com.aspose.slides/ihyperlink).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。**読み書き** [IHyperlink](../../com.aspose.slides/ihyperlink).

**戻り値:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

マウスオーバー用に定義されたハイパーリンクを取得または設定します。**読み書き** [IHyperlink](../../com.aspose.slides/ihyperlink).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

ハイパーリンク マネージャーを返します。**読み取り専用** [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**戻り値:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

シェイプが非表示かどうかを判定します。**読み書き**  boolean .

**戻り値:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

シェイプが非表示かどうかを判定します。**読み書き**  boolean .

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

シェイプの Z 順序内での位置を返します。Shapes[0] は Z 順序の最背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。**読み取り専用**  int .

**戻り値:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

シェイプ上の接続ポイントの数を返します。**読み取り専用**  int .

**戻り値:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

指定されたシェイプが Z 軸周りに回転する度数を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。**読み書き** float.

--------------------

返される値は常に定義されています（Float.NaN ではありません）。割り当てられた値も定義されている必要があります（Float.NaN ではない）。RawFrame インスタンスのプロパティに未定義の値を設定できます。

**戻り値:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

指定されたシェイプが Z 軸周りに回転する度数を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。**読み書き** float.

--------------------

返される値は常に定義されています（Float.NaN ではありません）。割り当てられた値も定義されている必要があります（Float.NaN ではない）。RawFrame インスタンスのプロパティに未定義の値を設定できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

シェイプ左上隅の X 座標をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**戻り値:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

シェイプ左上隅の X 座標をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

シェイプ左上隅の Y 座標をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**戻り値:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

シェイプ左上隅の Y 座標をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

シェイプの幅をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**戻り値:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

シェイプの幅をポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

シェイプの高さをポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**戻り値:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

シェイプの高さをポイント単位で取得または設定します。**読み書き** float.

--------------------

返される値は常に定義されており、Float.NaN ではありません。割り当てられた値も定義されている必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を設定できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。**読み書き** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**戻り値:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。**読み書き** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

アドインやその他のコードで使用することを想定した、プレゼンテーション スコープの内部識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。**読み取り専用** long。#getOfficeInteropShapeId.getOfficeInteropShapeId も参照してください。

**戻り値:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

スライド スコープの一意の識別子を返します。この識別子はシェイプの存続期間中は一定で、PowerPoint やインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できます。**読み取り専用** long。#getUniqueId.getUniqueId も参照してください。

**戻り値:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

シェイプに関連付けられた代替テキストを取得または設定します。**読み書き** String.

**戻り値:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

シェイプに関連付けられた代替テキストを取得または設定します。**読み書き** String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

シェイプに関連付けられた代替テキストのタイトルを取得または設定します。**読み書き** String.

**戻り値:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

シェイプに関連付けられた代替テキストのタイトルを取得または設定します。**読み書き** String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。**読み書き** String.

**戻り値:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。**読み書き** String.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

「装飾としてマーク」オプションの取得/設定（読み書き）ブール値です。

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

「装飾としてマーク」オプションの取得/設定（読み書き）ブール値です。

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

シェイプのロック情報を返します。**読み取り専用** [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**戻り値:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

シェイプがグループ化されているかどうかを判定します。**読み取り専用** boolean.

--------------------

プロパティ #getParentGroup.getParentGroup はシェイプがグループ化されている場合に親の GroupShape オブジェクトを返します。

**戻り値:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

シェイプがグループ化されている場合、親の GroupShape オブジェクトを返します。そうでない場合は null を返します。**読み取り専用** [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

プロパティ #isGrouped.isGrouped はシェイプがグループ化されているかどうかを判定します。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。**読み取り専用** IDOMObject.

**戻り値:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。

**戻り値:**
android.graphics.RectF - スライド座標系でシェイプの視覚的境界を表す android.graphics.RectF。

--------------------

返される矩形は、スライド座標空間でシェイプがレンダリング中に生成するすべてのコンテンツの軸揃え境界を表します。これらの境界は、シェイプのモデル境界 #getX.getX/#setX(float)、#getY.getY/#setY(float)、#getWidth.getWidth/#setWidth(float)、#getHeight.getHeight/#setHeight(float) と異なる場合があり、レンダリングされたコンテンツがスライドの原点を超える場合は負の座標を含むことがあります。視覚的境界は、変換（例: 回転）、ストローク幅とジョイン、テキストレイアウトとオーバーフロー、SmartArt のジオメトリ、その他のレイアウト効果など、最終的な描画外観に影響を与える要素を考慮します。返される境界はスライド矩形にクリップされません。

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

シェイプの親スライドを返します。**読み取り専用** [IBaseSlide](../../com.aspose.slides/ibaseslide).

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

スライドの親プレゼンテーションを返します。**読み取り専用** [IPresentation](../../com.aspose.slides/ipresentation).

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)