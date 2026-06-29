---
title: AutoShape
second_title: Aspose.Sildes for .NET API リファレンス
description: AutoShape を表します。
type: docs
weight: 880
url: /ja/aspose.slides/autoshape/
---
## AutoShape クラス

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | AutoShape のロックを返します。読み取り専用 [`IAutoShapeLock`](../iautoshapelock)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上のコネクション ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注意: 効果プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注意: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | ポイント単位で測定されたシェイプの高さを取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判定します。読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み取り/書き込み Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。読み取り専用 Boolean。 |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | シェイプがテキストボックスかどうかを指定します。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注意: 線プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはならず、必要に応じて空文字列を使用してください。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を返します。これはシェイプの存続期間中一定で、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。関連記事 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーが無い場合は null が返されます。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが z 軸周りに回転する度数を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | シェイプのロックを返します。読み取り専用 [`IAutoShapeLock`](../iautoshapelock)。 (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | ジオメトリ プリセット タイプを取得または設定します。注意: 値が変更されるとすべての調整値がデフォルト値にリセットされます。読み取り/書き込み [`ShapeType`](../shapetype)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | AutoShape 用の TextFrame オブジェクトを返します。読み取り専用 [`ITextFrame`](../itextframe)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注意: 3D プロパティを持たない特定のシェイプタイプでは null を返す場合があります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、内部的なプレゼンテーションスコープの識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。関連記事 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | この AutoShape がスタイルや塗りつぶし書式ではなく、スライドの背景塗りつぶしで塗りつぶされるべきかどうかを判定します。読み取り/書き込み Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | ポイント単位で測定されたシェイプの幅を取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の x 座標をポイント単位で取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の y 座標をポイント単位で取得または設定します。読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダーにおける位置を返します。Shapes[0] は Z オーダーの最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新しいプレースホルダーが存在しない場合に追加し、プレースホルダー属性を指定されたものに設定します。 |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | シェイプに新しい TextFrame を追加します。シェイプがすでに TextFrame を持っている場合は、単にテキストを変更します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプの要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。現在のシェイプが継承されていない場合は null が返されます。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリ シェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 描画されたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトからシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプの種類 ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列からシェイプのジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプの種類 ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GeometryShape](../geometryshape)
* インターフェイス [IAutoShape](../iautoshape)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->