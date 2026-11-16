---
title: SummaryZoomSection
second_title: Aspose.Sildes for .NET API 參考
description: 表示 Summary Zoom 框架中的 Summary Zoom Section 物件。
type: docs
weight: 10800
url: /zh-hant/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection 類別

表示 Summary Zoom 框架中的 Summary Zoom Section 物件。

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀相關聯的替代文字。讀寫 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀相關聯的替代文字的標題。讀寫 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。只讀 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。只讀 [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | 返回 Summary Zoom Section 物件的文字說明。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀，可能返回 null。只讀 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。注意：對於某些沒有填充屬性的形狀，可能返回 null。只讀 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定設定。只讀 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（以點為單位）。讀寫 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 決定形狀是否為隱藏。讀寫 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定點擊滑鼠時的超連結。讀寫 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。只讀 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。讀寫 [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | 取得或設定縮放物件的影像類型。讀寫 [`ZoomImageType`](../zoomimagetype). 預設值：Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀寫 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 決定形狀是否已群組。只讀 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 決定形狀是否為 TextHolder_PPT。只讀 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀，可能返回 null。只讀 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不得為 null。如有需要請使用空字串。讀寫 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一的識別碼，於形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參照此形狀。只讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，返回其父 GroupShape 物件；否則返回 null。只讀 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符。如果形狀沒有佔位符，則返回 null。只讀 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父級簡報。只讀 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 取得或設定投影片放映中的導覽行為。讀寫 Boolean。預設值：false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時鐘旋轉，負值表示逆時鐘旋轉。讀寫 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定設定。只讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | 取得或設定 Zoom 是否使用目標投影片的背景。讀寫 Boolean。預設值：true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。只讀 [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | 取得或設定 Section Zoom 物件所連結的區段物件。讀寫 [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形狀的 ThreeDFormat 物件，包含 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀，可能返回 null。只讀 [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | 返回 Summary Zoom Section 物件的文字標題。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | 取得或設定 Zoom 與投影片之間轉場的持續時間。讀寫 Single。預設值：1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛或其他程式碼使用的內部、簡報範圍內的識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。只讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（以點為單位）。讀寫 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 坐標（以點為單位）。讀寫 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 坐標（以點為單位）。讀寫 Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | 取得或設定縮放物件的影像。讀寫 [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 軸排序中的位置。Shapes[0] 返回 Z 軸排序最深的形狀，Shapes[Shapes.Count - 1] 返回最前面的形狀。只讀 Int32. |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果沒有佔位符則新增一個，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的佔位符形狀（來自版面配置和/或母片且被目前形狀繼承的形狀）。如果目前形狀未被繼承，則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [SectionZoomFrame](../sectionzoomframe)
* 介面 [ISummaryZoomSection](../isummaryzoomsection)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->