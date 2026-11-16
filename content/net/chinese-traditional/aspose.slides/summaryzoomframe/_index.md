---
title: SummaryZoomFrame
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示投影片中的 Summary Zoom 物件。
type: docs
weight: 10790
url: /zh-hant/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame 類別

表示投影片中的 Summary Zoom 物件。

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與形狀關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與形狀關聯的替代文字標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 此屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀，可能返回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 取得包含形狀填色格式屬性的 FillFormat 物件。注意：對於某些沒有填色屬性的形狀，可能返回 null。唯讀 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得形狀的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度（單位為點）。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定點擊滑鼠時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定 “標記為裝飾” 選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | 取得 Summary Zoom 區段在框架中的版面配置。預設值為 GridLayout。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀，可能返回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定形狀的名稱。不得為 null。如有需要，請使用空字串。讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參照此形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組，回傳父層 GroupShape 物件；否則返回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得形狀的佔位符。若形狀沒有佔位符，返回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父層簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始形狀框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定形狀繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得形狀的鎖定資訊。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得形狀所在的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | 取得 Summary Zoom 框架物件的 [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得形狀的 ThreeDFormat 物件，包含 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀，可能返回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得內部、簡報範圍的識別碼，供外掛或其他程式碼使用。因為此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度（單位為點）。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標（單位為點）。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標（單位為點）。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得形狀在 Z 次序中的位置。Shapes[0] 代表 Z 次序最背面的形狀，Shapes[Shapes.Count - 1] 代表最前面的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 取得基本佔位符形狀（從版面配置或母版投影片繼承而來的形狀）。若目前形狀未繼承，返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 取得形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 取得形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 以 SVG 檔案儲存形狀內容。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 以 SVG 檔案儲存形狀內容。 |

### 另請參閱

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ISummaryZoomFrame](../isummaryzoomframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->