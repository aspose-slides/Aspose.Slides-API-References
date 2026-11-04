---
title: VideoFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
weight: 11740
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | shape の調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape に関連付けられた代替テキストを取得または設定します。読み取り/書き込み String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape に関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは shape が白黒表示モードでどのように描画されるかを指定します。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | ビデオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](../icaptionscollection) を返します. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape の接続ポイント数を返します。読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape のカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape に適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。注: effect プロパティを持たない特定の種類の shape では null を返すことがあります。読み取り専用 [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 埋め込みビデオオブジェクトを取得または設定します。読み取り/書き込み [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定の種類の shape では null を返すことがあります。読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | ビデオが全画面モードで表示されるかどうかを決定します。読み取り/書き込み Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape の高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape が非表示かどうかを決定します。読み取り/書き込み Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | VideoFrame が非表示かどうかを決定します。読み取り/書き込み Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame が Cameo オブジェクトかどうかを判断します。読み取り専用 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' オプションを取得または設定します。読み取り/書き込み Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape がグループ化されているかどうかを判断します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape が TextHolder_PPT かどうかを判断します。読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape の線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定の種類の shape では null を返すことがあります。読み取り専用 [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | VideoFrame にリンクされたビデオファイルの名前を取得または設定します。読み取り/書き込み String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape の名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り/書き込み String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | shape の存続期間中一定で、ドキュメント内の任意の場所から PowerPoint または interop コードが shape を確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 UInt32。詳細は [`UniqueId`](../shape/uniqueid) を参照してください. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでなければ null を返します。読み取り専用 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | ピクチャーフレームの PictureFillFormat オブジェクトを返します。読み取り専用 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | shape のロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape のプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | ビデオがループ再生されるかどうかを決定します。読み取り/書き込み Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | ビデオの再生モードを取得または設定します。読み取り/書き込み [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の shape フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | ピクチャーフレームの高さのスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。読み取り/書き込み Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | ピクチャーフレームの幅のスケール（元の画像サイズに対する相対値）を取得または設定します。値 1.0 は 100% に相当します。読み取り/書き込み Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 動画の再生が完了した直後に自動的に先頭に巻き戻すかどうかを決定します。読み取り/書き込み Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された shape が z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | shape のロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock). (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape のスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame の AutoShape タイプを取得または設定します。[`ShapeType`](../shapetype) のセットに含まれるすべての項目が許可されますが、すべての種類の線は除外されます: |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape の親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定の種類の shape では null を返すことがあります。読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | 終了位置をトリミングします [ms] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | 開始位置をトリミングします [ms] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした内部のプレゼンテーションスコープ識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。詳細は [`OfficeInteropShapeId`](../shape/officeinteropshapeid) を参照してください. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | オーディオボリュームを取得または設定します。読み取り/書き込み [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/videoframe/volumevalue) { get; set; } | 正確なビデオボリュームをパーセンテージで取得または設定します。値は 0 から 100 のパーセンテージで表されます。[`Volume`](./volume) プロパティで利用できる事前定義レベルよりも細かいボリューム値を読み書きするためにこのプロパティを使用してください。読み取り/書き込み Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape の幅（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape の左上隅の x 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape の左上隅の y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | shape の Z オーダー内の位置を返します。Shapes[0] は Z オーダーの最背面の shape を返し、Shapes[Shapes.Count - 1] は最前面の shape を返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape の要素配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを返します（現在の shape が継承しているレイアウトまたはマスタースライドからの shape）。継承されていない場合は null が返されます。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標は shape の左上隅を基準とします。 |
| [GetImage](../../aspose.slides/shape/getimage)() | shape のサムネイルを返します。デフォルトで ShapeThumbnailBounds.Shape の shape サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape のサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算された shape の視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この shape がプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトから shape のジオメトリを更新します。座標は shape の左上隅を基準とする必要があります。shape のタイプ ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列から shape のジオメトリを更新します。座標は shape の左上隅を基準とする必要があります。shape のタイプ ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 参照

* クラス [PictureFrame](../pictureframe)
* インターフェイス [IVideoFrame](../ivideoframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->