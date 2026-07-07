---
title: VideoFrame
second_title: Aspose.Sildes for .NET API 參考
description: 代表投影片上的影片剪輯。
type: docs
weight: 11720
url: /zh-hant/aspose.slides/videoframe/
---
## VideoFrame 類別

代表投影片上的影片剪輯。

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 傳回形狀的調整值集合。唯讀 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。可讀寫字串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字標題。可讀寫字串。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | 取得與影片框架相關聯的隱藏式字幕集合。此屬性唯讀，傳回一個包含所有字幕軌道的 [`ICaptionsCollection`](../icaptionscollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。註：對於沒有效果屬性的某些形狀類型，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | 傳回或設定嵌入式影片物件。可讀寫 [`IVideo`](../ivideo)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。註：對於沒有填充屬性的某些形狀類型，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | 判斷影片是否以全螢幕模式顯示。可讀寫 Boolean。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，單位為點。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。可讀寫 Boolean。 |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | 判斷 VideoFrame 是否隱藏。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 判斷 PictureFrame 是否為 Cameo 物件。唯讀 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。註：對於沒有線條屬性的某些形狀類型，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | 傳回或設定連結至 VideoFrame 的影片檔案名稱。可讀寫字串。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如有需要可使用空字串。可讀寫字串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回對投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能從文件的任何位置可靠地參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，傳回其父層 GroupShape 物件；否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 傳回圖片框架的 PictureFillFormat 物件。唯讀 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的預留區位。如果形狀沒有預留區位，則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | 判斷影片是否循環播放。可讀寫 Boolean。 |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | 傳回或設定影片播放模式。可讀寫 [`VideoPlayModePreset`](../videoplaymodepreset)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父層簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 傳回或設定圖片框架高度的比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 傳回或設定圖片框架寬度的比例（相對於原始圖片尺寸）。值 1.0 對應 100%。可讀寫 Single。 |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | 判斷影片在播放完畢後是否自動倒帶至起始。可讀寫 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。（2 個屬性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 傳回形狀的樣式物件。唯讀 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 傳回或設定 PictureFrame 的 AutoShape 類型。允許的集合 [`ShapeType`](../shapetype) 中的所有項目，除各種線條外： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父層投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀的 ThreeDFormat 物件，含 3D 效果屬性。註：對於沒有 3D 屬性的某些形狀類型，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | 剪裁結束 [毫秒] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | 剪裁開始 [毫秒] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回內部、簡報範圍內的識別碼，供外掛程式或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | 傳回或設定音訊音量。可讀寫 [`AudioVolumeMode`](../audiovolumemode)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，單位為點。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，單位為點。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，單位為點。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 順序中的位置。Shapes[0] 會傳回 Z 順序最背後的形狀，Shapes[Shapes.Count - 1] 會傳回最前面的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，新增一個佔位區，並將佔位屬性設定為指定的項目。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並傳回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位形狀（從版面配置和/或母片取得、目前形狀所繼承的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 傳回幾何形狀路徑的副本。座標相對於形狀左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已呈現內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位區。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 從 [`IGeometryPath`](../igeometrypath) 物件更新形狀幾何。座標必須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 從 [`IGeometryPath`](../igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 內容儲存為 SVG 檔案。 |

### 另見

* 類別 [PictureFrame](../pictureframe)
* 介面 [IVideoFrame](../ivideoframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->