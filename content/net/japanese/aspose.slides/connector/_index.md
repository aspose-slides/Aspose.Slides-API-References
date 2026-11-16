---
title: Connector
second_title: Aspose.Sildes for .NET API リファレンス
description: コネクタを表します。
type: docs
weight: 2690
url: /ja/aspose.slides/connector/
---
## Connector クラス

コネクタを表します。

```csharp
public class Connector : GeometryShape, IConnector
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | shape の調整値のコレクションを返します。 読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape に関連付けられた代替テキストを取得または設定します。 読み書き String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape に関連付けられた代替テキストのタイトルを取得または設定します。 読み書き String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、shape が白黒表示モードでどのように描画されるかを指定します。 読み書き [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape の接続ポイントの数を返します。 読み取り専用 Int32。 |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | コネクタのロックを返します。 読み取り専用 [`IConnectorLock`](../iconnectorlock)。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape のカスタム データを返します。 読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape に適用されたピクセル エフェクトを含む EffectFormat オブジェクトを返します。 注: エフェクト プロパティを持たない特定の shape タイプの場合、null を返すことがあります。 読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | コネクタの末端を接続する shape を取得または設定します。 読み書き [`IShape`](../ishape)。 |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | 終端 shape の接続サイトのインデックスを取得または設定します。 読み書き UInt32。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。 注: 塗りつぶしプロパティを持たない特定の shape タイプの場合、null を返すことがあります。 読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape フレームのプロパティを取得または設定します。 読み書き [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape の高さ（ポイント単位）を取得または設定します。 読み書き Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape が非表示かどうかを決定します。 読み書き Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック時に定義されたハイパーリンクを取得または設定します。 読み書き [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを返します。 読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー時に定義されたハイパーリンクを取得または設定します。 読み書き [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。 読み書き Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape がグループ化されているかどうかを判断します。 読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape が TextHolder_PPT かどうかを判断します。 読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape の線書式プロパティを含む LineFormat オブジェクトを返します。 注: 線プロパティを持たない特定の shape タイプの場合、null を返すことがあります。 読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape の名前を取得または設定します。 null であってはなりません。必要に応じて空文字列を使用してください。 読み書き String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape の存続期間中一定であり、PowerPoint や interop コードがドキュメント内の任意の場所から shape を確実に参照できるスライドスコープの一意の識別子を返します。 読み取り専用 UInt32。 参照: [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ null を返します。 読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape のプレースホルダーを返します。shape にプレースホルダーがない場合は null を返します。 読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。 読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の shape フレームのプロパティを取得または設定します。 読み書き [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された shape が z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。 読み書き Single。 |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | shape のロックを返します。 読み取り専用 [`IConnectorLock`](../iconnectorlock)。 (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape のスタイル オブジェクトを返します。 読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape の種類を取得または設定します。 読み書き [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape の親スライドを返します。 読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | コネクタの開始端を接続する shape を取得または設定します。 読み書き [`IShape`](../ishape)。 |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | 開始 shape の接続サイトのインデックスを取得または設定します。 読み書き UInt32。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。 注: 3D プロパティを持たない特定の shape タイプの場合、null を返すことがあります。 読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを想定した、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。 読み取り専用 UInt32。 参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape の幅（ポイント単位）を取得または設定します。 |
| [X](../../aspose.slides/shape/x) { get; set; } | shape の左上隅の x 座標（ポイント単位）を取得または設定します。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape の左上隅の y 座標（ポイント単位）を取得または設定します。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape の Z オーダー内での位置を返します。Shapes[0] は Z オーダーの最背面の shape を返し、Shapes[Shapes.Count - 1] は最前面の shape を返します。 読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定したものに設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape の要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー shape を返します（現在の shape が継承されているレイアウトまたはマスタースライドからの shape）。現在の shape が継承されていない場合は null を返します。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリ shape のパスのコピーを返します。座標は shape の左上隅を基準とします。 |
| [GetImage](../../aspose.slides/shape/getimage)() | shape のサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape の shape サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape のサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 描画されたコンテンツから計算された shape のビジュアル境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この shape がプレースホルダーではないことを定義します。 |
| [Reroute](../../aspose.slides/connector/reroute)() | コネクタを再ルーティングし、接続する shape 間の最短パスを取るようにします。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトから shape のジオメトリを更新します。座標は shape の左上隅を基準にする必要があります。shape のタイプ（[`ShapeType`](../geometryshape/shapetype)）をカスタムに変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列から shape のジオメトリを更新します。座標は shape の左上隅を基準にする必要があります。shape のタイプ（[`ShapeType`](../geometryshape/shapetype)）をカスタムに変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GeometryShape](../geometryshape)
* インターフェイス [IConnector](../iconnector)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->