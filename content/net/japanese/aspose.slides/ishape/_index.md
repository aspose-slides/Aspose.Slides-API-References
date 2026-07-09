---
title: IShape
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上の図形を表します。
type: docs
weight: 6950
url: /ja/aspose.slides/ishape/
---
## IShape インターフェイス

スライド上の図形を表します。

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | 図形に関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | 図形に関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | ベースの IHyperlinkContainer インターフェイスを取得できます。読み取り専用 [`IHyperlinkContainer`](../ihyperlinkcontainer)。 |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | ベースの ISlideComponent インターフェイスを取得できます。読み取り専用 [`ISlideComponent`](../islidecomponent)。 |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | 図形が白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | 図形上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | 図形のカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | 図形に適用されたピクセル効果を含む EffectFormat オブジェクトを返します。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | 図形の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | 図形フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/ishape/height) { get; set; } | ポイント単位で測定された図形の高さを取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | 図形が非表示かどうかを決定します。読み取り/書き込み Boolean。 |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | ‘Mark as decorative’ オプションを取得または設定します。Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | 図形がグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | 図形が TextHolder かどうかを判断します。読み取り専用 Boolean。 |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | 図形の線書式プロパティを含む LineFormat オブジェクトを返します。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/ishape/name) { get; set; } | 図形の名前を取得または設定します。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | 図形のライフタイム中に一定であり、PowerPoint やインタープコードがドキュメント内の任意の場所から確実に図形を参照できるスライドスコープの一意の識別子を返します。読み取り専用 UInt32。こちらも参照してください [`UniqueId`](./uniqueid)。 |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | 図形がグループ化されている場合、親の GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | 図形のプレースホルダーを返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | 生の図形フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | 指定された図形が z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | 図形のロック状態を返します。読み取り専用 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | 図形の 3D 書式プロパティを含む ThreeDFormat オブジェクトを返します。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | アドインやその他のコードが使用することを目的とした内部のプレゼンテーションスコープ識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。こちらも参照してください [`OfficeInteropShapeId`](./officeinteropshapeid)。 |
| [Width](../../aspose.slides/ishape/width) { get; set; } | ポイント単位で測定された図形の幅を取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/ishape/x) { get; set; } | ポイント単位で測定された図形の左上隅の x 座標を取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/ishape/y) { get; set; } | ポイント単位で測定された図形の左上隅の y 座標を取得または設定します。読み取り/書き込み Single。 |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | 図形の z オーダー内での位置を返します。Shapes[0] は z オーダーの最背面にある図形を返し、Shapes[Shapes.Count - 1] は最前面にある図形を返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | 現在の図形が継承元となるレイアウトまたはマスタースライドから取得された基本的なプレースホルダー形状を返します。継承元がない場合は null が返されます。 |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | 図形のサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | 図形のサムネイルを返します。 |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | この図形がプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 参照

* インターフェイス [IHyperlinkContainer](../ihyperlinkcontainer)
* インターフェイス [ISlideComponent](../islidecomponent)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->