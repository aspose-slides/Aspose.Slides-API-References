---
title: PictureFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: 画像を内部に含むフレームを表します。
type: docs
weight: 9390
url: /ja/aspose.slides/pictureframe/
---
## PictureFrame クラス

シェイプ内に画像を含むフレームを表します。

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き可能 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定します。読み書き可能 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注意: これらの効果プロパティを持たない特定のシェイプの場合、null を返す可能性があります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶしプロパティを含む FillFormat オブジェクトを返します。注意: 塗りつぶしプロパティを持たない特定のシェイプの場合、null を返す可能性があります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | ポイント単位でシェイプの高さを取得または設定します。読み書き可能 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判定します。読み書き可能 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | クリック時に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー時に定義されたハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame が Cameo オブジェクトかどうかを判断します。読み取り専用 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み書き可能 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判断します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線の書式プロパティを含む LineFormat オブジェクトを返します。注意: 線プロパティを持たない特定のシェイプの場合、null を返す可能性があります。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null ではない必要があります。必要に応じて空文字列を使用してください。読み書き可能 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を返します。この識別子はシェイプの存続期間中一定であり、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できます。読み取り専用 UInt32。[`UniqueId`](../shape/uniqueid) も参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ピクチャーフレームの PictureFillFormat オブジェクトを返します。読み取り専用 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | シェイプのロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプ フレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ピクチャーフレームの高さのスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。読み書き可能 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ピクチャーフレームの幅のスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。読み書き可能 Single。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定したシェイプが Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを表します。読み書き可能 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | シェイプのロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。（2 つのプロパティ） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame の AutoShape タイプを取得または設定します。[`ShapeType`](../shapetype) のすべての項目が許容されますが、すべての線種は除外されます。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注意: 3D プロパティを持たない特定のシェイプの場合、null を返す可能性があります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコード向けに使用される、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid) も参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | ポイント単位でシェイプの幅を取得または設定します。読み書き可能 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | ポイント単位でシェイプの左上隅の X 座標を取得または設定します。読み書き可能 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | ポイント単位でシェイプの左上隅の Y 座標を取得または設定します。読み書き可能 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z 順序でのシェイプの位置を返します。Shapes[0] は Z 順序の最背面、Shapes[Shapes.Count - 1] は最前面を表します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプの要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。継承されていない場合は null を返します。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape が使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプの種類（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプの種類（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 例

以下の例は Audio Frame サムネイルの変更方法を示します。

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // 指定された位置とサイズでスライドにオーディオフレームを追加します。
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // プレゼンテーションのリソースに画像を追加します。
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // オーディオフレームの画像を設定します。
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//変更されたプレゼンテーションをディスクに保存します。
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* クラス [GeometryShape](../geometryshape)
* インターフェイス [IPictureFrame](../ipictureframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->