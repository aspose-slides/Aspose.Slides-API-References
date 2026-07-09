---
title: PictureFrame
second_title: Aspose.Sildes for .NET API 參考
description: 表示內含圖片的框架。
type: docs
weight: 9410
url: /zh-hant/aspose.slides/pictureframe/
---
## PictureFrame 類別

表示一個內含圖片的框架。

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | 傳回形狀的調整值集合。唯讀 [`IAdjustValueCollection`](../iadjustvaluecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字的標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 此屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的形狀，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含填充格式屬性的 FillFormat 物件。註：對於某些沒有填充屬性的形狀，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠移過時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | 判斷 PictureFrame 是否為 Cameo 物件。唯讀 Boolean。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的形狀，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不可為 null。如有需要請使用空字串。讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一的識別碼，於形狀的生命期間保持不變，讓 PowerPoint 或 interop 程式碼能可靠地從文件的任何位置參考此形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，傳回父 GroupShape 物件。否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | 傳回圖片框架的 PictureFillFormat 物件。唯讀 [`IPictureFillFormat`](../ipicturefillformat)。 |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。如果形狀沒有佔位符，則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | 傳回或設定圖片框架的高度比例（相對於原始圖片大小）。值 1.0 表示 100%。讀寫 Single。 |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | 傳回或設定圖片框架的寬度比例（相對於原始圖片大小）。值 1.0 表示 100%。讀寫 Single。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。讀寫 Single。 |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IPictureFrameLock`](../ipictureframelock)。（2 個屬性） |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | 傳回形狀的樣式物件。唯讀 [`IShapeStyle`](../ishapestyle)。 |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | 傳回或設定 PictureFrame 的 AutoShape 類型。允許的集合項目為 [`ShapeType`](../shapetype)，但不包括所有種類的線條： |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀的 ThreeDFormat 物件，用於 3D 效果屬性。註：對於某些沒有 3D 屬性的形狀，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回供外掛或其他程式碼使用的內部投影片範圍識別碼。由於此值可能會被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 序中的位置。Shapes[0] 會傳回 Z 序最底層的形狀，而 Shapes[Shapes.Count - 1] 會傳回 Z 序最前端的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | 建立並傳回形狀元素的陣列。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位符形狀（從版面配置或母片取得，供目前形狀繼承的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | 傳回幾何形狀路徑的副本。座標相對於形狀左上角。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | 根據 [`IGeometryPath`](../igeometrypath) 物件更新形狀幾何。座標必須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | 根據 [`IGeometryPath`](../igeometrypath) 陣列更新形狀幾何。座標必須相對於形狀左上角。將形狀類型（[`ShapeType`](../geometryshape/shapetype)）變更為 Custom。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 範例

以下範例說明如何變更音訊框架縮圖。

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // 在投影片上新增一個具有指定位置和大小的音訊框架。
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // 將影像新增至簡報資源。
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // 設定音訊框架的影像。
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//將修改後的簡報儲存至磁碟
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 類別 [GeometryShape](../geometryshape)
* 介面 [IPictureFrame](../ipictureframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->