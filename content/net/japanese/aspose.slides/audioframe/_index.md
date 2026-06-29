---
title: AudioFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のオーディオクリップを表します。
type: docs
weight: 850
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
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | shape の調整値のコレクションを返します。読み取り専用 [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | shape に関連付けられた代替テキストを取得または設定します。読み書き String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | shape に関連付けられた代替テキストのタイトルを取得または設定します。読み書き String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 最後のトラックインデックスを取得または設定します。読み書き Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 最後のトラック時間を取得または設定します。読み書き Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 開始トラックインデックスを取得または設定します。読み書き Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 開始トラック時間を取得または設定します。読み書き Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、shape が白黒表示モードでどのようにレンダリングされるかを指定します。読み書き [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [`ICaptionsCollection`](../icaptionscollection) を返します. |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | shape の接続ポイント数を返します。読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | shape のカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | shape に適用されたピクセルエフェクトを含む EffectFormat オブジェクトを返します。注意: エフェクトプロパティを持たない一部の shape タイプでは null を返す可能性があります。読み取り専用 [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | サウンドがプレゼンテーションに埋め込まれているかどうかを判断します。読み取り専用 Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 埋め込みオーディオオブジェクトを取得または設定します。読み書き [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | メディアの最初のフェードイン時間をミリ秒で指定します。読み書き Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | メディアの終了フェードアウト時間をミリ秒で指定します。読み書き Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | shape の塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注意: 塗りつぶしプロパティを持たない一部の shape タイプでは null を返す可能性があります。読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | shape フレームのプロパティを取得または設定します。読み書き [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | shape の高さ（ポイント単位）を取得または設定します。読み書き Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | shape が非表示かどうかを判断します。読み書き Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | AudioFrame が非表示かどうかを判断します。読み書き Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | PictureFrame が Cameo オブジェクトかどうかを判断します。読み取り専用 Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。読み書き Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | shape がグループ化されているかどうかを判断します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | shape が TextHolder_PPT かどうかを判断します。読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | shape の線書式プロパティを含む LineFormat オブジェクトを返します。注意: 線プロパティを持たない一部の shape タイプでは null を返す可能性があります。読み取り専用 [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | AudioFrame にリンクされたオーディオファイルの名前を取得または設定します。読み書き String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | shape の名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み書き String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意識別子を返します。この識別子は shape のライフタイム中一定で、PowerPoint やインターロップコードがドキュメント内の任意の場所から shape を確実に参照できます。読み取り専用 UInt32。詳細は [`UniqueId`](../shape/uniqueid) を参照してください. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | shape がグループ化されている場合は親 GroupShape オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | picture frame の PictureFillFormat オブジェクトを返します。読み取り専用 [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | shape のロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | shape のプレースホルダーを返します。プレースホルダーが無い場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | スライド間でオーディオが再生されるかどうかを判断します。読み書き Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | オーディオがループ再生されるかどうかを判断します。読み書き Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | オーディオ再生モードを取得または設定します。読み書き [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | shape フレームの生データプロパティを取得または設定します。読み書き [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | picture frame の高さスケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | picture frame の幅スケール（元の画像サイズに対する相対）を取得または設定します。値 1.0 は 100% に相当します。読み書き Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 再生後にオーディオが自動的に開始位置に巻き戻されるかどうかを判断します。読み書き Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された shape が Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | shape のロック情報を返します。読み取り専用 [`IPictureFrameLock`](../ipictureframelock)。 (2 プロパティ) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | shape のスタイルオブジェクトを返します。読み取り専用 [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | PictureFrame の AutoShape タイプを取得または設定します。[`ShapeType`](../shapetype) のセットに含まれるすべての項目が許容されますが、すべての種類の線は除外されます: |
| [Slide](../../aspose.slides/shape/slide) { get; } | shape の親スライドを返します。読み取り専用 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | shape の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを返します。注意: 3D プロパティを持たない一部の shape タイプでは null を返す可能性があります。読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 再生中にメディアの末尾から除去する時間（ミリ秒）を指定します。読み書き Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 再生中にメディアの先頭から除去する時間（ミリ秒）を指定します。読み書き Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを想定した、内部のプレゼンテーションスコープ識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。詳細は [`OfficeInteropShapeId`](../shape/officeinteropshapeid) を参照してください. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | オーディオの音量を取得または設定します。読み書き [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | オーディオ音量をパーセントで取得または設定します。読み書き Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | shape の幅（ポイント単位）を取得または設定します。読み書き Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | shape の左上隅の X 座標（ポイント単位）を取得または設定します。読み書き Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | shape の左上隅の Y 座標（ポイント単位）を取得または設定します。読み書き Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z オーダー内の shape の位置を返します。Shapes[0] は z オーダーの最背面の shape を返し、Shapes[Shapes.Count - 1] は最前面の shape を返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | shape の要素の配列を作成して返します. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー shape を返します（レイアウトまたはマスタースライドから継承された shape）。継承されていない場合は null を返します. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | ジオメトリ shape のパスのコピーを返します。座標は shape の左上隅を基準としています. |
| [GetImage](../../aspose.slides/shape/getimage)() | shape のサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape がサムネイル境界タイプとして使用されます. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | shape のサムネイルを返します. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算された shape の視覚的境界を取得します. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この shape がプレースホルダーでないことを定義します. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | [`IGeometryPath`](../igeometrypath) オブジェクトから shape のジオメトリを更新します。座標は shape の左上隅を基準としてください。shape のタイプ ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | [`IGeometryPath`](../igeometrypath) の配列から shape のジオメトリを更新します。座標は shape の左上隅を基準としてください。shape のタイプ ([`ShapeType`](../geometryshape/shapetype)) を Custom に変更します. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します. |

### 例

以下の例は Audio Play Options の変更方法を示します。

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
    // 再生後にオーディオを開始位置に巻き戻します
    audioFrame.RewindAudio = true;
    // PowerPoint ファイルをディスクに保存します
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 関連項目

* クラス [PictureFrame](../pictureframe)
* インターフェイス [IAudioFrame](../iaudioframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->