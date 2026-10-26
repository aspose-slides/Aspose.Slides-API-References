---
title: SummaryZoomSection
second_title: Aspose.Sildes for .NET API 參考
description: 表示在 Summary Zoom 框架中的 Summary Zoom Section 物件。
type: docs
weight: 10780
url: /zh-hant/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection 類別

表示一個 Summary Zoom 框架中的 Summary Zoom Section 物件。

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與圖形關聯的替代文字。讀/寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與圖形關聯的替代文字標題。讀/寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。讀/寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得圖形的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得圖形的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | 取得 Summary Zoom Section 物件的文字描述。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於圖形之像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的圖形，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含圖形填充格式屬性的 FillFormat 物件。注意：對於某些沒有填充屬性的圖形，可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定圖形框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得圖形的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度，單位為點。讀/寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否隱藏。讀/寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。讀/寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠移過時的超連結。讀/寫 [`IHyperlink`](../ihyperlink)。 |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | 取得或設定縮放物件的影像類型。讀/寫 [`ZoomImageType`](../zoomimagetype)。預設值：Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀/寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。唯讀 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的圖形，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定圖形的名稱。不得為 null。必要時可使用空字串。讀/寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一且在圖形生命週期內保持不變的識別碼，供 PowerPoint 或 interop 程式碼可靠參照圖形。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若圖形已群組，返回其父 GroupShape 物件；否則返回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得圖形的佔位符。若圖形沒有佔位符則返回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始圖形框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe)。 |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | 取得或設定投影片放映時的導覽行為。讀/寫 Boolean。預設值：false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定圖形繞 Z 軸旋轉的角度（度數）。正值表示順時針，負值表示逆時針。讀/寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得圖形的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（共 2 個屬性） |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | 取得或設定 Zoom 是否使用目標投影片的背景。讀/寫 Boolean。預設值：true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得圖形所屬的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | 取得或設定 Section Zoom 物件連結的節 (section) 物件。讀/寫 [`ISection`](../isection)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得圖形的 ThreeDFormat 物件，包含 3D 效果屬性。注意：對於某些沒有 3D 屬性的圖形，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | 取得 Summary Zoom Section 物件的文字標題。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | 取得或設定 Zoom 與投影片之間過渡的持續時間。讀/寫 Single。預設值：1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得供外掛程式或其他程式碼使用的內部、簡報範圍識別碼。因使用者或程式可重新指派此值，故不應視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度，單位為點。讀/寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 X 座標，單位為點。讀/寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 Y 座標，單位為點。讀/寫 Single。 |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | 取得或設定縮放物件的圖像。讀/寫 [`IPPImage`](../ippimage)。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得圖形在 Z 次序中的位置。Shapes[0] 代表 Z 次序最底層的圖形，Shapes[Shapes.Count - 1] 代表最前面的圖形。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基本佔位符圖形（從版面配置或母片投影片繼承的圖形）。若目前圖形未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 圖形縮圖範圍類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據圖形渲染內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖形內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖形內容儲存為 SVG 檔案。 |

### 參見

* class [SectionZoomFrame](../sectionzoomframe)
* interface [ISummaryZoomSection](../isummaryzoomsection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->