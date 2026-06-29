---
title: GeometryShape
second_title: Aspose.Sildes for .NET API リファレンス
description: すべての幾何学シェイプの基底クラスを表します。
type: docs
weight: 4950
url: /ja/aspose.slides/geometryshape/
---
## GeometryShape クラス

すべての幾何学シェイプの基底クラスを表します。

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定します。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注: 効果プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み取り/書き込み Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを決定します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを決定します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはならず、必要に応じて空文字列を使用してください。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド スコープの一意の識別子を返します。この識別子はシェイプの寿命が続く限り一定で、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できます。読み取り専用 UInt32。[`UniqueId`](../shape/uniqueid) も参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定したシェイプが Z 軸を中心に回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | シェイプのロック情報を返します。読み取り専用 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ジオメトリのプリセットタイプを取得または設定します。注: 値が変更されると、すべての調整値はデフォルトにリセットされます。読み取り/書き込み [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを想定した、プレゼンテーション スコープの内部識別子を返します。この値はユーザーやプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid) も参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプ左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプ左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z 順序でのシェイプの位置を返します。Shapes[0] は Z 順序の最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを表します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプの要素配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。継承されていない場合は null を返します。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプ左上隅を基準としています。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape が使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトからシェイプジオメトリを更新します。座標はシェイプ左上隅を基準としてください。シェイプのタイプ（[`ShapeType`](./shapetype)）を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列からシェイプジオメトリを更新します。座標はシェイプ左上隅を基準としてください。シェイプのタイプ（[`ShapeType`](./shapetype)）を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [Shape](../shape)
* インターフェイス [IGeometryShape](../igeometryshape)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->