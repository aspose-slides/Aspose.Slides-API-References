---
title: SummaryZoomFrame
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片中的 Summary Zoom 物件。
type: docs
weight: 10770
url: /zh-hant/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame 類別

代表投影片中的 Summary Zoom 物件。

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀關聯的替代文字。可讀寫 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀關聯的替代文字標題。可讀寫 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的渲染方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。唯讀 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於沒有效果屬性的某些形狀類型可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 傳回包含形狀填充格式屬性的 FillFormat 物件。注意：對於沒有填充屬性的某些形狀類型可能會傳回 null。唯讀 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，單位為點。可讀寫 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否被隱藏。可讀寫 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定為滑鼠點擊所定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定為滑鼠懸停所定義的超連結。可讀寫 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。可讀寫 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | 取得框架中 Summary Zoom 區段的版面配置。預設值為 GridLayout. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於沒有線條屬性的某些形狀類型可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不得為 null。如有需要可使用空字串。可讀寫 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一且在形狀生命週期內保持不變的識別碼，讓 PowerPoint 或 interop 程式碼能可靠地從文件任何位置參考此形狀。唯讀 UInt32. 另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，返回父 GroupShape 物件；否則返回 null。唯讀 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的 placeholder。若形狀沒有 placeholder，則返回 null。唯讀 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父簡報。唯讀 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。可讀寫 Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock).（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | 取得 Summary Zoom 框架物件的 [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回形狀的 ThreeDFormat 物件，其包含 3D 效果屬性。注意：對於沒有 3D 屬性的某些形狀類型可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛程式或其他程式碼使用的內部、簡報範圍內識別碼。由於此值可能被使用者或程式重新指派，故不可視為永久唯一鍵。唯讀 UInt32. 另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，單位為點。可讀寫 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，單位為點。可讀寫 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，單位為點。可讀寫 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 序的定位。Shapes[0] 取得位於 Z 序最背面的形狀，Shapes[Shapes.Count - 1] 取得位於最前面的形狀。唯讀 Int32. |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的佔位符形狀（來自版面配置或母投影片且被目前形狀繼承的形狀）。如果目前形狀未被繼承，則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀渲染內容計算出的視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另見

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ISummaryZoomFrame](../isummaryzoomframe)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->