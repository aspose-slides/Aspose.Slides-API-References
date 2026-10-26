---
title: IShape
second_title: Java APIリファレンスによるAndroid向けAspose.Slides
description: スライド上のシェイプを表します。
type: docs
url: /ja/com.aspose.slides/ishape/
---
**実装されているすべてのインターフェイス：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

スライド上のシェイプを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | シェイプが TextHolder かどうかを判定します。 |
| [getPlaceholder()](#getPlaceholder--) | シェイプのプレースホルダーを返します。 |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | プレースホルダーが無い場合は新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [removePlaceholder()](#removePlaceholder--) | このシェイプがプレースホルダーでないことを定義します。 |
| [getCustomData()](#getCustomData--) | シェイプのカスタムデータを返します。 |
| [getRawFrame()](#getRawFrame--) | 生のシェイプフレームのプロパティを取得または設定します。 |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | 生のシェイプフレームのプロパティを取得または設定します。 |
| [getFrame()](#getFrame--) | シェイプフレームのプロパティを取得または設定します。 |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | シェイプフレームのプロパティを取得または設定します。 |
| [getLineFormat()](#getLineFormat--) | シェイプの線形書式プロパティを含む LineFormat オブジェクトを返します。 |
| [getThreeDFormat()](#getThreeDFormat--) | シェイプの線形書式プロパティを含む ThreeDFormat オブジェクトを返します。 |
| [getEffectFormat()](#getEffectFormat--) | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。 |
| [getFillFormat()](#getFillFormat--) | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 |
| [getImage()](#getImage--) | シェイプのサムネイルを返します。 |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | シェイプのサムネイルを返します。 |
| [getHidden()](#getHidden--) | シェイプが非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | シェイプが非表示かどうかを判定します。 |
| [getZOrderPosition()](#getZOrderPosition--) | シェイプの Z 順序での位置を返します。 |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | シェイプ上の接続ポイントの数を返します。 |
| [getRotation()](#getRotation--) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。 |
| [setRotation(float value)](#setRotation-float-) | 指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。 |
| [getX()](#getX--) | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。 |
| [setX(float value)](#setX-float-) | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。 |
| [getY()](#getY--) | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。 |
| [setY(float value)](#setY-float-) | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。 |
| [getWidth()](#getWidth--) | シェイプの幅（ポイント単位）を取得または設定します。 |
| [setWidth(float value)](#setWidth-float-) | シェイプの幅（ポイント単位）を取得または設定します。 |
| [getHeight()](#getHeight--) | シェイプの高さ（ポイント単位）を取得または設定します。 |
| [setHeight(float value)](#setHeight-float-) | シェイプの高さ（ポイント単位）を取得または設定します。 |
| [getAlternativeText()](#getAlternativeText--) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | シェイプに関連付けられた代替テキストを取得または設定します。 |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。 |
| [getName()](#getName--) | シェイプの名前を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | シェイプの名前を取得または設定します。 |
| [isDecorative()](#isDecorative--) | 「装飾としてマーク」オプションを取得または設定します（読み取り/書き込み ブール型）。 |
| [setDecorative(boolean value)](#setDecorative-boolean-) | 「装飾としてマーク」オプションを取得または設定します（読み取り/書き込み ブール型）。 |
| [getShapeLock()](#getShapeLock--) | シェイプのロック状態を返します。 |
| [getUniqueId()](#getUniqueId--) | アドインや他のコードで使用することを想定した、プレゼンテーションスコープの内部識別子を返します。 |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | シェイプの存続期間中一定で、PowerPoint やインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を返します。 |
| [isGrouped()](#isGrouped--) | シェイプがグループ化されているかどうかを判定します。 |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | このプロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。 |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | このプロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。 |
| [getParentGroup()](#getParentGroup--) | シェイプがグループ化されている場合、親の GroupShape オブジェクトを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | シェイプの内容を SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | シェイプの内容を SVG ファイルとして保存します。 |
| [getBasePlaceholder()](#getBasePlaceholder--) | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。 |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

シェイプが TextHolder かどうかを判定します。読み取り専用 ブール型。

**戻り値:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../../com.aspose.slides/iplaceholder)。

**戻り値:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

プレースホルダーが無い場合は新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | プレースホルダーの内容をコピーする元。 |

**戻り値:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - 新しい [IPlaceholder](../../com.aspose.slides/iplaceholder)。

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

このシェイプがプレースホルダーでないことを定義します。

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../com.aspose.slides/icustomdata)。

**戻り値:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //または
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //このようなコードは不明確な状況を招く可能性があります。そのため、IShape.getFrame() で未定義の値を使用することに制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されている必要があります（Float.NaN または NullableBool.NotDefined ではいけません）。上記の例コードは現在 ArgumentException 例外をスローします。
>  //これは以下の使用例に適用されます：
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // シェイプはプレースホルダーにリンクされています
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // これによりシェイプはプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。
```

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //または
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //このようなコードは不明確な状況を生む可能性があります。そのため、IShape.getFrame() で未定義の値を使用することに制限が追加されました。x、y、width、height、flipH、flipV、rotationAngle の値は定義されている必要があります（Float.NaN または NullableBool.NotDefined ではいけません）。上記の例コードは現在 ArgumentException 例外をスローします。
>  //これは以下の使用例に適用されます：
>  IShape shape = ...;
>  shape.setFrame(...); // 未定義にできません
>  IShapeCollection shapes = ...;
>  //x、y、width、height パラメータは Float.NaN にできません：
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // シェイプはプレースホルダーにリンクされています
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // これでシェイプはプレースホルダーから x、y、height、flipH、flipV の値を継承し、width=100 と rotationAngle=0 を上書きします。
> ```


**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

シェイプフレームのプロパティを取得または設定します。読み取り/書き込み [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返される IShapeFrame インスタンスの各プロパティは未定義ではありません（NaN または NotDefined ではない）。割り当てられる IShapeFrame インスタンスの各プロパティも未定義であってはなりません（NaN または NotDefined ではない）。RawFrame インスタンスのプロパティに未定義値を設定できます。

**戻り値:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

シェイプフレームのプロパティを取得または設定します。読み取り/書き込み [IShapeFrame](../../com.aspose.slides/ishapeframe)。

--------------------

返される IShapeFrame インスタンスの各プロパティは未定義ではありません（NaN または NotDefined ではない）。割り当てられる IShapeFrame インスタンスの各プロパティも未定義であってはなりません（NaN または NotDefined ではない）。RawFrame インスタンスのプロパティに未定義値を設定できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

シェイプの線形書式プロパティを含む LineFormat オブジェクトを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

シェイプの線形書式プロパティを含む ThreeDFormat オブジェクトを返します。読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**戻り値:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

シェイプのサムネイルを返します。ShapeThumbnailBounds.Shape シェイプサムネイル境界タイプがデフォルトで使用されます。

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - シェイプのサムネイル。

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

シェイプのサムネイルを返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | シェイプサムネイル境界タイプ。 |
| scaleX | float | X スケール |
| scaleY | float | Y スケール |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - シェイプのサムネイル。ShapeThumbnailBounds.Appearance が使用され、シェイプに可視要素がない場合は null。

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

シェイプが非表示かどうかを判定します。読み取り/書き込み ブール型。

**戻り値:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

シェイプが非表示かどうかを判定します。読み取り/書き込み ブール型。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

シェイプの Z 順序での位置を返します。Shapes[0] は Z 順序の最背面、Shapes[Shapes.Count - 1] は最前面を示します。読み取り専用 int。

**戻り値:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

シェイプ上の接続ポイントの数を返します。読み取り専用 int。

**戻り値:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み float。

--------------------

返される値は常に定義済み（Float.NaN ではない）。割り当てる値も定義済みでなければなりません（Float.NaN ではない）。RawFrame インスタンスのプロパティに未定義値を設定できます。

**戻り値:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

指定されたシェイプが Z 軸周りに回転している角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み float。

--------------------

返される値は常に定義済み（Float.NaN ではない）。割り当てる値も定義済みでなければなりません（Float.NaN ではない）。RawFrame インスタンスのプロパティに未定義値を設定できます。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**戻り値:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**戻り値:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**戻り値:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**戻り値:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み float。

--------------------

返される値は常に定義済みで、Float.NaN ではありません。割り当てる値も定義済みである必要があります。RawFrame インスタンスのプロパティにのみ Float.NaN を割り当ててください。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

シェイプの名前を取得または設定します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

シェイプの名前を取得または設定します。読み取り/書き込み String。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

「装飾としてマーク」オプションを取得または設定します（読み取り/書き込み ブール型）。

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
public abstract void setDecorative(boolean value)
```

「装飾としてマーク」オプションを取得または設定します（読み取り/書き込み ブール型）。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

シェイプのロック状態を返します。読み取り専用 [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)。

**戻り値:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

プレゼンテーションスコープの内部識別子を返します。ユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 long。#getOfficeInteropShapeId.getOfficeInteropShapeId も参照。

**戻り値:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

スライドスコープの一意識別子を返します。シェイプの存続期間中一定で、PowerPoint やインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようになります。読み取り専用 long。#getUniqueId.getUniqueId も参照。

**戻り値:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

シェイプがグループ化されているかどうかを判定します。読み取り専用 ブール型。

--------------------

プロパティ #getParentGroup.getParentGroup は、シェイプがグループ化されている場合に親 GroupShape オブジェクトを返します。

**戻り値:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

このプロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み取り/書き込み [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**戻り値:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

このプロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み取り/書き込み [BlackWhiteMode](../../com.aspose.slides/blackwhitemode)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

シェイプがグループ化されている場合、親の GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../../com.aspose.slides/igroupshape)。

--------------------

プロパティ #isGrouped.isGrouped はシェイプがグループ化されているかどうかを判定します。

**戻り値:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

シェイプの内容を SVG ファイルとして保存します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。

--------------------

> ```
> // プレースホルダーシェイプのすべての（マスター/レイアウト/スライド）アニメーション効果を取得
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