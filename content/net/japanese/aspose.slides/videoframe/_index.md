---
title: VideoFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
weight: 11700
url: /ja/aspose.slides/videoframe/
---
## VideoFrame クラス

スライド上のビデオクリップを表します。

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 形状の調整値のコレクションを返します。 読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 形状に関連付けられた代替テキストを取得または設定します。 読み取り/書き込み String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 形状に関連付けられた代替テキストのタイトルを取得または設定します。 読み取り/書き込み String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、形状が白黒表示モードでどのように描画されるかを指定します。 読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](../icaptionscollection) を返します。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 形状上の接続点の数を返します。 読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 形状のカスタムデータを返します。 読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 形状に適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。注: エフェクトプロパティを持たない特定の形状タイプでは null が返される場合があります。 読み取り専用 [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 埋め込み動画オブジェクトを取得または設定します。 読み取り/書き込み [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 形状の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定の形状タイプでは null が返される場合があります。 読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 形状フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | 動画が全画面モードで表示されるかどうかを決定します。 読み取り/書き込み Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | 形状の高さ（ポイント単位）を取得または設定します。 読み取り/書き込み Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 形状が非表示かどうかを決定します。 読み取り/書き込み Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | VideoFrame が非表示かどうかを決定します。 読み取り/書き込み Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。 読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame が Cameo オブジェクトかどうかを決定します。 読み取り専用 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。 読み取り/書き込み Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 形状がグループ化されているかどうかを決定します。 読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 形状が TextHolder_PPT かどうかを決定します。 読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 形状の線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定の形状タイプでは null が返される場合があります。 読み取り専用 [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。 読み取り/書き込み String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | 形状の名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。 読み取り/書き込み String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 形状の存続期間中に一定で、PowerPoint やインタープコードがドキュメント内の任意の場所から形状を信頼して参照できるスライドスコープの一意識別子を返します。 読み取り専用 UInt32。 参照: [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 形状がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ null を返します。 読み取り専用 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 画像フレームの PictureFillFormat オブジェクトを返します。 読み取り専用 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 形状のロックを返します。 読み取り専用 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 形状のプレースホルダーを返します。プレースホルダーがない場合は null を返します。 読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | 動画がループ再生されるかどうかを決定します。 読み取り/書き込み Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | 動画の再生モードを取得または設定します。 読み取り/書き込み [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。 読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の形状フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 画像フレームの高さのスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。 読み取り/書き込み Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 画像フレームの幅のスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。 読み取り/書き込み Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 動画の再生が完了した直後に自動的に先頭へ巻き戻すかどうかを決定します。 読み取り/書き込み Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された形状が z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。 読み取り/書き込み Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 形状のロックを返します。 読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。（2 プロパティ） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 形状のスタイルオブジェクトを返します。 読み取り専用 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame の AutoShape タイプを取得または設定します。[`ShapeType`](../shapetype) のセットに含まれるすべての項目が許容されますが、すべての線種は除外されます: |
| [Slide](../../aspose.slides/shape/slide) { get; } | 形状の親スライドを返します。 読み取り専用 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 形状の 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定の形状タイプでは null が返される場合があります。 読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | トリム終了 [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | トリム開始 [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用されることを意図した内部のプレゼンテーションスコープ識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。 読み取り専用 UInt32。 参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | 音声ボリュームを取得または設定します。 読み取り/書き込み [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 形状の幅（ポイント単位）を取得または設定します。 読み取り/書き込み Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 形状左上隅の x 座標（ポイント単位）を取得または設定します。 読み取り/書き込み Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 形状左上隅の y 座標（ポイント単位）を取得または設定します。 読み取り/書き込み Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z 順序における形状の位置を返します。Shapes[0] は z 順序の最背面の形状を返し、Shapes[Shapes.Count - 1] は最前面の形状を返します。 読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新しいプレースホルダーが存在しない場合に追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 形状の要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから現在のシェイプが継承されたもの）を返します。継承されていない場合は null が返されます。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリ形状のパスのコピーを返します。座標は形状の左上隅を基準とします。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 形状のサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape の形状サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 形状のサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算された形状の視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この形状がプレースホルダーでないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトから形状ジオメトリを更新します。座標は形状の左上隣を基準とする必要があります。形状のタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) 配列から形状ジオメトリを更新します。座標は形状の左上隣を基準とする必要があります。形状のタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 形状のコンテンツを SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 形状のコンテンツを SVG ファイルとして保存します。 |

### 参照

* クラス [PictureFrame](../pictureframe)
* インターフェイス [IVideoFrame](../ivideoframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->