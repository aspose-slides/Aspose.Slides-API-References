---
title: SmartArtShape
second_title: .NET 用 Aspose.Sildes API リファレンス
description: SmartArt シェイプを表します
type: docs
weight: 10640
url: /ja/aspose.slides.smartart/smartartshape/
---
## SmartArtShape クラス

SmartArt シェイプを表します

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き可能 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み書き可能 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを返します。読み取り専用 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。注意: 効果プロパティを持たない特定の種類のシェイプでは null を返すことがあります。読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注意: 塗りつぶしプロパティを持たない特定の種類のシェイプでは null を返すことがあります。読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み書き可能 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判断します。読み書き可能 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマークする」オプションを取得または設定します。読み書き可能 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判断します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注意: 線プロパティを持たない特定の種類のシェイプでは null を返すことがあります。読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み書き可能 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint またはインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。参照 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが Z 軸回りに回転する角度（度数）を取得または設定します。正の値は時計回り回転、負の値は反時計回り回転を示します。読み書き可能 Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | シェイプのロック状態を返します。読み取り専用 [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../../aspose.slides/ishapestyle)。 |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | ジオメトリのプリセットタイプを取得または設定します。注意: 値を変更するとすべての調整値がデフォルトにリセットされます。読み書き可能 [`ShapeType`](../../aspose.slides/shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | SmartArt シェイプのテキストを返します。読み取り専用 [`ITextFrame`](../../aspose.slides/itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注意: 3D プロパティを持たない特定の種類のシェイプでは null を返すことがあります。読み取り専用 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、内部のプレゼンテーションスコープの識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。参照 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み書き可能 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。読み書き可能 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。読み書き可能 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダー内での位置を返します。Shapes[0] は Z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプの要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。継承されていない場合は null が返されます。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../../aspose.slides/igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) をカスタムに変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../../aspose.slides/igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) をカスタムに変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GeometryShape](../../aspose.slides/geometryshape)
* インターフェイス [ISmartArtShape](../ismartartshape)
* 名前空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->