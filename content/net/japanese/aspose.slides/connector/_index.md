---
title: Connector
second_title: Aspose.Sildes の .NET API リファレンス
description: コネクタを表します。
type: docs
weight: 2650
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き可能 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み書き可能 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | コネクタのロックを返します。読み取り専用 [`IConnectorLock`](../iconnectorlock)。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注: 効果プロパティを持たない特定の種類のシェイプについては null を返す可能性があります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | コネクタの終端を接続するシェイプを取得または設定します。読み書き可能 [`IShape`](../ishape)。 |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | 終端シェイプの接続ポイントのインデックスを取得または設定します。読み書き可能 UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定の種類のシェイプについては null を返す可能性があります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み書き可能 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み書き可能 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み書き可能 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定の種類のシェイプについては null を返す可能性があります。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み書き可能 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド単位の一意の識別子を返します。この識別子はシェイプの存続期間中は一定で、PowerPoint またはインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。参照 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | シェイプフレームの生データプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが z 軸を中心に回転する角度（度数）を取得または設定します。正の値は時計回りの回転、負の値は反時計回りの回転を示します。読み書き可能 Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | シェイプのロックを返します。読み取り専用 [`IConnectorLock`](../iconnectorlock)。 (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | AutoShape のタイプを取得または設定します。読み書き可能 [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | コネクタの始点を接続するシェイプを取得または設定します。読み書き可能 [`IShape`](../ishape)。 |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | 開始シェイプの接続ポイントのインデックスを取得または設定します。読み書き可能 UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定の種類のシェイプについては null を返す可能性があります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、内部的なプレゼンテーション単位の識別子を返します。この値はユーザーやプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。参照 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み書き可能 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の x 座標（ポイント単位）を取得または設定します。読み書き可能 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の y 座標（ポイント単位）を取得または設定します。読み書き可能 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダー上の位置を返します。Shapes[0] は Z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプの要素の配列を作成し、返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。継承されていない場合は null が返されます。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [Reroute](../../aspose.slides/connector/reroute)() | コネクタのルートを再設定し、接続するシェイプ間の最短経路を取るようにします。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準としてください。シェイプのタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準としてください。シェイプのタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GeometryShape](../geometryshape)
* インターフェイス [IConnector](../iconnector)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->