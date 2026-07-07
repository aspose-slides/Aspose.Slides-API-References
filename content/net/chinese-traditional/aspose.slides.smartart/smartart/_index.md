---
title: SmartArt
second_title: Aspose.Sildes 適用於 .NET 的 API 參考
description: 表示一個 SmartArt 圖表
type: docs
weight: 10600
url: /zh-hant/aspose.slides.smartart/smartart/
---
## SmartArt 類別

表示一個 SmartArt 圖表

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | 返回 SmartArt 物件中所有節點的集合。唯讀 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀關聯的替代文字標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | 返回或設定 SmartArt 物件的色彩樣式。讀寫 [`SmartArtColorType`](../smartartcolortype)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀的像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀，可能返回 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填色屬性的 FillFormat 物件。注意：對於某些沒有填色屬性的形狀，可能返回 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否被隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時定義的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理員。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠暈輪時定義的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定 'Mark as decorative' 選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean。 |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | 返回或設定 SmartArt 圖表相對於 (左至右) LTR 或 (右至左) RTL 的狀態，如果圖表支援反轉的話。讀寫 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | 返回或設定 SmartArt 物件的版面配置。讀寫 [`SmartArtLayoutType`](../smartartlayouttype)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀，可能返回 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。必須非 null。如有需要使用空字串值。讀寫 String。 |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | 返回 SmartArt 物件中根節點的集合。唯讀 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回一個投影片範圍內唯一的識別碼，在形狀生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能從文件任何位置可靠地參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，返回其父 GroupShape 物件。否則返回 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符。若形狀沒有佔位符，返回 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父投影片集。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | 返回或設定 SmartArt 物件的快速樣式。讀寫 [`SmartArtQuickStyleType`](../smartartquickstyletype)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 Z 軸旋轉的度數。正值表示順時針旋轉；負值表示逆時針旋轉。讀寫 Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形狀 3D 效果屬性的 ThreeDFormat 物件。注意：對於某些沒有 3D 屬性的形狀，可能返回 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛或其他程式碼使用的內部、投影片範圍識別碼。由於此值可能被使用者或程式重新指派，不能視為持久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 順序中的位置。Shapes[0] 代表 Z 順序最底端的形狀，Shapes[Shapes.Count - 1] 代表最前端的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本佔位符形狀（從版面配置和/或母版投影片繼承而來的形狀）。如果當前形狀未繼承，則返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖範圍類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀已渲染內容計算出的視覺範圍。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位符。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參閱

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [ISmartArt](../ismartart)
* 命名空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->