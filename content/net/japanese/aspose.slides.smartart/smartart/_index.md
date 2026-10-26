---
title: SmartArt
second_title: Aspose.Sildes for .NET API リファレンス
description: SmartArt ダイアグラムを表します
type: docs
weight: 10600
url: /ja/aspose.slides.smartart/smartart/
---
## SmartArt クラス

SmartArt ダイアグラムを表します

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | SmartArt オブジェクト内のすべてのノードのコレクションを返します。読み取り専用 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 形状に関連付けられた代替テキストを取得または設定します。読み書き String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 形状に関連付けられた代替テキストのタイトルを取得または設定します。読み書き String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、形状が白黒表示モードでどのように描画されるかを指定します。読み書き [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | SmartArt オブジェクトのカラー スタイルを取得または設定します。読み書き [`SmartArtColorType`](../smartartcolortype)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 形状上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 形状のカスタム データを返します。読み取り専用 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 形状に適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注: エフェクト プロパティを持たない特定の形状の場合、null を返すことがあります。読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 形状の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定の形状の場合、null を返すことがあります。読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 形状フレームのプロパティを取得または設定します。読み書き [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 形状のロックを返します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 形状の高さ（ポイント単位）を取得または設定します。読み書き Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 形状が非表示かどうかを決定します。読み書き Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' オプションを取得または設定します。読み書き Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 形状がグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | 図が反転をサポートしている場合、SmartArt ダイアグラムの左から右 (LTR) または右から左 (RTL) の状態を取得または設定します。読み書き Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 形状が TextHolder_PPT かどうかを判断します。読み取り専用 Boolean。 |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | SmartArt オブジェクトのレイアウトを取得または設定します。読み書き [`SmartArtLayoutType`](../smartartlayouttype)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 形状の線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定の形状の場合、null を返すことがあります。読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 形状の名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み書き String。 |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | SmartArt オブジェクトのルート ノードのコレクションを返します。読み取り専用 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 形状のライフタイム中一定で、ドキュメント内の任意の場所から PowerPoint またはインタープコードが形状を確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 UInt32。参照: [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 形状がグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 形状のプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | SmartArt オブジェクトのクイック スタイルを取得または設定します。読み書き [`SmartArtQuickStyleType`](../smartartquickstyletype)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 未加工の形状フレームのプロパティを取得または設定します。読み書き [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された形状が Z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。読み書き Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 形状のロックを返します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。(2 プロパティ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 形状の親スライドを返します。読み取り専用 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 形状の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定の形状の場合、null を返すことがあります。読み取り専用 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを目的とした、プレゼンテーションスコープの内部識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。参照: [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 形状の幅（ポイント単位）を取得または設定します。読み書き Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 形状の左上隅の X 座標（ポイント単位）を取得または設定します。読み書き Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 形状の左上隅の Y 座標（ポイント単位）を取得または設定します。読み書き Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z オーダー内における形状の位置を返します。Shapes[0] は z オーダーの最背面にある形状を返し、Shapes[Shapes.Count - 1] は最前面にある形状を返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー形状（現在の形状が継承元となるレイアウトまたはマスタースライドの形状）を返します。継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 形状のサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 形状のサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされた内容から計算された形状の視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この形状がプレースホルダーでないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 形状の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 形状の内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject)
* インターフェイス [ISmartArt](../ismartart)
* 名前空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->