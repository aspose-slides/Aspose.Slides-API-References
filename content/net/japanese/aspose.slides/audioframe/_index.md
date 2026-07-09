---
title: AudioFrame
second_title: Aspose.Sildes の .NET API リファレンス
description: スライド上のオーディオクリップを表します。
type: docs
weight: 870
url: /ja/aspose.slides/audioframe/
---
## AudioFrame クラス

スライド上のオーディオクリップを表します。

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | シェイプの調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き String。 |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 最後のトラックインデックスを取得または設定します。読み書き Int32。 |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 最後のトラック時間を取得または設定します。読み書き Int32。 |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 開始トラックインデックスを取得または設定します。読み書き Int32。 |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 開始トラック時間を取得または設定します。読み書き Int32。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み書き [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](../icaptionscollection) を返します。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注: 効果プロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。読み取り専用 Boolean。 |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 埋め込みオーディオオブジェクトを取得または設定します。読み書き [`IAudio`](../iaudio)。 |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | メディアの初期フェードインの時間長さをミリ秒で指定します。読み書き Single。 |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | メディアの終了フェードアウトの時間長さをミリ秒で指定します。読み書き Single。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み書き [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さをポイント単位で取得または設定します。読み書き Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判定します。読み書き Boolean。 |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | AudioFrame が非表示かどうかを判定します。読み書き Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame が Cameo オブジェクトかどうかを判定します。読み取り専用 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | '装飾としてマーク' オプションを取得または設定します。読み書き Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注: 線プロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。読み書き String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用します。読み書き String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を返します。この識別子はシェイプの存続期間中は一定で、PowerPoint または interop コードがドキュメント内の任意の位置からシェイプを確実に参照できるようにします。読み取り専用 UInt32。詳細は [`UniqueId`](../shape/uniqueid) を参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 画像フレームの PictureFillFormat オブジェクトを返します。読み取り専用 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | シェイプのロックを返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | オーディオがスライド全体で再生されるかどうかを判定します。読み書き Boolean。 |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | オーディオがループ再生されるかどうかを判定します。読み書き Boolean。 |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | オーディオの再生モードを取得または設定します。読み書き [`AudioPlayModePreset`](../audioplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 未処理のシェイプフレームのプロパティを取得または設定します。読み書き [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 画像フレームの高さ（元の画像サイズに対する相対スケール）を取得または設定します。値 1.0 は 100% に相当します。読み書き Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 画像フレームの幅（元の画像サイズに対する相対スケール）を取得または設定します。値 1.0 は 100% に相当します。読み書き Single。 |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 再生後にオーディオが自動的に先頭に巻き戻されるかどうかを判定します。読み書き Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定したシェイプが z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | シェイプのロックを返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。（2 プロパティ） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | シェイプのスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame の AutoShape タイプを取得または設定します。[`ShapeType`](../shapetype) のセットに含まれるすべての項目が許容されますが、すべての種類の線は除外されます。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 再生中にメディアの末尾から削除する時間長さ（ミリ秒）を指定します。読み書き Single。 |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 再生中にメディアの先頭から削除する時間長さ（ミリ秒）を指定します。読み書き Single。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。詳細は [`OfficeInteropShapeId`](../shape/officeinteropshapeid) を参照してください。 |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | オーディオの音量を取得または設定します。読み書き [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 音量をパーセンテージで取得または設定します。読み書き Single。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅をポイント単位で取得または設定します。読み書き Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標をポイント単位で取得または設定します。読み書き Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標をポイント単位で取得または設定します。読み書き Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダー内での位置を返します。Shapes[0] は Z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | シェイプ要素の配列を作成して返します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプ（現在のシェイプが継承元であるレイアウトまたはマスタースライドからのシェイプ）を返します。継承されていない場合は null を返します。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds,float,float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 描画されたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ（[`ShapeType`](../geometryshape/shapetype)）を Custom に変更します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream,ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 例

以下の例は、Audio Play Options の変更方法を示しています。

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // AudioFrame シェイプを取得します
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 再生モードをクリック時再生に設定します
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 音量を Low に設定します
    audioFrame.Volume = AudioVolumeMode.Low;
    // オーディオをスライド全体で再生するように設定します
    audioFrame.PlayAcrossSlides = true;
    // オーディオのループを無効にします
    audioFrame.PlayLoopMode = false;
    // スライドショー中に AudioFrame を非表示にします
    audioFrame.HideAtShowing = true;
    // 再生後にオーディオを先頭に巻き戻します
    audioFrame.RewindAudio = true;
    // PowerPoint ファイルをディスクに保存します
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 参照

* クラス [PictureFrame](../pictureframe)
* インターフェイス [IAudioFrame](../iaudioframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->