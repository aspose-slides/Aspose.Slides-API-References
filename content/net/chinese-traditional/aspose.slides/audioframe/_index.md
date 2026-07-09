---
title: AudioFrame
second_title: Aspose.Sildes for .NET API 參考文件
description: 代表投影片上的音訊剪輯。
type: docs
weight: 870
url: /zh-hant/aspose.slides/audioframe/
---
## AudioFrame 類別

代表投影片上的音訊剪輯。

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 傳回形狀調整值的集合。唯讀 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字標題。可讀寫 String。 |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | 傳回或設定最後一個軌道的索引。可讀寫 Int32。 |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | 傳回或設定最後一個軌道的時間。可讀寫 Int32。 |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | 傳回或設定起始軌道的索引。可讀寫 Int32。 |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | 傳回或設定起始軌道的時間。可讀寫 Int32。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/audioframe/captiontracks) { get; } | 取得與音訊框架相關聯的隱藏式字幕集合。此屬性唯讀，並傳回包含所有字幕軌道的 [`ICaptionsCollection`](../icaptionscollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數目。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於沒有效果屬性的某些形狀類型，可能傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | 判斷是否有將聲音嵌入簡報。唯讀 Boolean。 |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | 傳回或設定嵌入式音訊物件。可讀寫 [`IAudio`](../iaudio)。 |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | 指定媒體初始淡入的時間長度（毫秒）。可讀寫 Single。 |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | 指定媒體結束淡出的時間長度（毫秒）。可讀寫 Single。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。注意：對於沒有填充屬性的某些形狀類型，可能傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。可讀寫 Boolean。 |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | 判斷 AudioFrame 是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠懸停時定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 判斷 PictureFrame 是否為 Cameo 物件。唯讀 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於沒有線條屬性的某些形狀類型，可能傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | 傳回或設定連結至 AudioFrame 的音訊檔案名稱。可讀寫 String。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如需可使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，並讓 PowerPoint 或 interop 程式碼能從文件任何位置可靠地參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，傳回其上層 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 傳回圖片框的 PictureFillFormat 物件。唯讀 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位元件。如形狀沒有佔位元件，則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | 判斷音訊是否在投影片之間播放。可讀寫 Boolean。 |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | 判斷音訊是否循環播放。可讀寫 Boolean。 |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | 傳回或設定音訊播放模式。可讀寫 [`AudioPlayModePreset`](../audioplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的上層簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 傳回或設定圖片框高度的縮放比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 傳回或設定圖片框寬度的縮放比例（相對於原始圖片大小）。值 1.0 代表 100%。可讀寫 Single。 |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | 判斷音訊在播放完畢後是否自動倒回起始位置。可讀寫 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。（2 個屬性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 傳回形狀的樣式物件。唯讀 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 傳回或設定 PictureFrame 的 AutoShape 類型。允許的項目皆屬於集合 [`ShapeType`](../shapetype)，但不含各類線條： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的上層投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。注意：對於沒有 3D 屬性的某些形狀類型，可能傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | 指定在播放期間從媒體結尾移除的時間長度（毫秒）。可讀寫 Single。 |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | 指定在播放期間從媒體開頭移除的時間長度（毫秒）。可讀寫 Single。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回內部、簡報範圍的識別碼，供附加元件或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為永久唯一的鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | 傳回或設定音訊音量。可讀寫 [`AudioVolumeMode`](../audiovolumemode)。 |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | 傳回或設定音訊音量（百分比）。可讀寫 Single。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標（以點為單位）。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標（以點為單位）。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 序中的位置。Shapes[0] 會傳回 Z 序最背面的形狀，Shapes[Shapes.Count - 1] 會傳回最前面的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，新增一個佔位元件並將佔位元件屬性設定為指定的佔位元件。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並傳回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位元件形狀（來自版面配置或母片，且為目前形狀所繼承的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 傳回幾何形狀路徑的副本。座標相對於形狀的左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算的形狀可視邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位元件。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 根據 [`IGeometryPath`](../igeometrypath) 物件更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為自訂。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 根據 [`IGeometryPath`](../igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀的左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為自訂。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 範例

以下範例說明如何變更音訊播放選項。

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // 取得 AudioFrame 形狀
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // 將播放模式設定為點擊時播放
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // 將音量設定為低
    audioFrame.Volume = AudioVolumeMode.Low;
    // 將音訊設定為跨投影片播放
    audioFrame.PlayAcrossSlides = true;
    // 停用音訊的循環播放
    audioFrame.PlayLoopMode = false;
    // 在投影片放映時隱藏 AudioFrame
    audioFrame.HideAtShowing = true;
    // 在播放完畢後將音訊倒回開頭
    audioFrame.RewindAudio = true;
    // 將 PowerPoint 檔案儲存至磁碟
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### 參見

* 類別 [PictureFrame](../pictureframe)
* 介面 [IAudioFrame](../iaudioframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->