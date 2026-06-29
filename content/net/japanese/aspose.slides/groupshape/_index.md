---
title: GroupShape
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のシェイプのグループを表します。
type: docs
weight: 5070
url: /ja/aspose.slides/groupshape/
---
## GroupShape クラス

スライド上のシェイプのグループを表します。

```csharp
public class GroupShape : Shape, IGroupShape
```

## プロパティ

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き可能 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能 String。 |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | 基本 IShape インターフェイスを取得できます。読み取り専用 [`IShape`](../ishape)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定します。読み書き可能 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | エフェクトプロパティがないシェイプの場合、null を返すことがあります。エフェクト フォーマット オブジェクトを返します。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 塗りつぶしプロパティがないシェイプの場合、null を返すことがあります。塗りつぶしフォーマット オブジェクトを返します。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | シェイプのロック情報を返します。読み取り専用 [`IGroupShapeLock`](../igroupshapelock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | ポイント単位でシェイプの高さを取得または設定します。読み書き可能 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み書き可能 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック時に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー時に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み書き可能 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT であるかどうかを判定します。読み取り専用 Boolean。 |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | GroupShape オブジェクトはライン プロパティを持たないため、null を返します。ライン フォーマット オブジェクトを返します。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み書き可能 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を返します。形状の存続期間中は一定で、PowerPoint やインタープコードが文書内の任意の場所から確実に参照できます。読み取り専用 UInt32。[`UniqueId`](../shape/uniqueid) も参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプ フレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Z 軸周りの回転角度（度数）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き可能 Single。 |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | シェイプのロック情報を返します。読み取り専用 [`IGroupShapeLock`](../igroupshapelock)。 (2 properties) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | グループ内のシェイプ コレクションを返します。読み取り専用 [`IShapeCollection`](../ishapecollection)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 3D プロパティがないシェイプの場合、null を返すことがあります。ThreeDFormat オブジェクトを返します。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用するための内部プレゼンテーション スコープ識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid) も参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅をポイント単位で取得または設定します。読み書き可能 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標をポイント単位で取得または設定します。読み書き可能 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標をポイント単位で取得または設定します。読み書き可能 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z オーダー内でのシェイプ位置を返します。Shapes[0] は Z オーダーの最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 Int32。 |

## メソッド

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。現在のシェイプが継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape がサムネイルの境界タイプとして使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [Shape](../shape)
* インターフェイス [IGroupShape](../igroupshape)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->