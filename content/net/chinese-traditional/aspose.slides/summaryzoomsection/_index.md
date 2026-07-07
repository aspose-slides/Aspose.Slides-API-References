---
title: SummaryZoomSection
second_title: Aspose.Sildes for .NET API 參考文件
description: 代表 Summary Zoom 框架中的 Summary Zoom 區段物件。
type: docs
weight: 10780
url: /zh-hant/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection 類別

代表 Summary Zoom 框架中的 Summary Zoom 區段物件。

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀相關聯的替代文字。讀/寫 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀相關聯的替代文字標題。讀/寫 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 此屬性指定形狀在黑白顯示模式下的呈現方式。讀/寫 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | 傳回 Summary Zoom 區段物件的文字描述。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回 EffectFormat 物件，該物件包含套用於形狀的像素效果。注意：對於某些沒有效果屬性的形狀，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回 FillFormat 物件，該物件包含形狀的填充格式屬性。注意：對於某些沒有填充屬性的形狀，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 傳回形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。讀/寫 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀/寫 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定滑鼠點擊時的超連結。讀/寫 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定滑鼠懸停時的超連結。讀/寫 [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | 取得或設定縮放物件的影像類型。讀/寫 [`ZoomImageType`](../zoomimagetype)。預設值：Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定 'Mark as decorative' 選項。讀/寫 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回 LineFormat 物件，該物件包含形狀的線條格式屬性。注意：對於某些沒有線條屬性的形狀，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如有需要請使用空字串。讀/寫 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一的識別碼，此識別碼在形狀的生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，則傳回父層 GroupShape 物件。否則傳回 null。唯讀 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的佔位符。若形狀沒有佔位符則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父層簡報。唯讀 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 取得或設定投影片放映時的導覽行為。讀/寫 Boolean。預設值：false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀/寫 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 傳回形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | 取得或設定指定 Zoom 是否使用目標投影片的背景。讀/寫 Boolean。預設值：true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父層投影片。唯讀 [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | 取得或設定 Section Zoom 物件所連結的區段物件。讀/寫 [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回 ThreeDFormat 物件，該物件提供形狀的 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | 傳回 Summary Zoom 區段物件的文字標題。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | 取得或設定 Zoom 與投影片之間過渡的持續時間。讀/寫 Single。預設值：1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回內部的、簡報範圍的識別碼，供外掛程式或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能被視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。讀/寫 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。讀/寫 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。讀/寫 Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | 取得或設定縮放物件的影像。讀/寫 [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 軸排序中的位置。Shapes[0] 會傳回 Z 軸排序最底層的形狀，而 Shapes[Shapes.Count - 1] 會傳回最前層的形狀。唯讀 Int32. |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若未有佔位符，則新增一個佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的佔位符形狀（從版面配置或母片投影片繼承的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已呈現內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 的內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [SectionZoomFrame](../sectionzoomframe)
* 介面 [ISummaryZoomSection](../isummaryzoomsection)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->