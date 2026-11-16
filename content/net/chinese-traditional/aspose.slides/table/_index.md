---
title: Table
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上的表格。
type: docs
weight: 10880
url: /zh-hant/aspose.slides/table/
---
## Table 類別

代表投影片上的表格。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 屬性

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 傳回或設定與形狀關聯的替代文字。可讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 傳回或設定與形狀關聯的替代文字標題。可讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。可讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [Columns](../../aspose.slides/table/columns) { get; } | 傳回欄位的集合。唯讀 [`IColumnCollection`](../icolumncollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 傳回形狀的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 傳回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 傳回包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀類型可能傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | 傳回包含表格填充格式的 TableFormat.FillFormat 物件。唯讀 [`IFillFormat`](../ifillformat)。 |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 決定表格的第一欄是否以特殊格式繪製。可讀寫 Boolean。 |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 決定表格的第一列是否以特殊格式繪製。可讀寫 Boolean。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 傳回或設定形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。可讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 決定形狀是否隱藏。可讀寫 Boolean。 |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 決定偶數列是否以不同的格式繪製。可讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 傳回或設定於滑鼠點擊時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 傳回超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 傳回或設定於滑鼠懸停時的超連結。可讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項 Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 決定形狀是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 決定形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Item](../../aspose.slides/table/item) { get; } | 傳回指定欄與列索引處的儲存格。唯讀 [`Cell`](../cell)。 |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 決定表格的最後一欄是否以特殊格式繪製。可讀寫 Boolean。 |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 決定表格的最後一列是否以特殊格式繪製。可讀寫 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 傳回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀類型可能傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 傳回或設定形狀的名稱。不得為 null。如有需要請使用空字串。可讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 傳回在投影片範圍內唯一的識別碼，於形狀的生命週期中保持不變，讓 PowerPoint 或 interop 程式碼能從文件任意位置可靠地參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 若形狀已群組，傳回其父層 GroupShape 物件。否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 傳回形狀的占位符。若形狀沒有占位符則傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 傳回投影片的父投影片檔案。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 傳回或設定原始形狀框架的屬性。可讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 決定表格是否使用由右至左的閱讀順序。可讀寫 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 傳回或設定指定形狀繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。可讀寫 Single。 |
| [Rows](../../aspose.slides/table/rows) { get; } | 傳回列的集合。唯讀 [`IRowCollection`](../irowcollection)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 傳回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 傳回形狀的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 取得或設定內建的表格樣式。可讀寫 [`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 傳回包含此表格格式屬性的 TableFormat 物件。唯讀 [`ITableFormat`](../itableformat)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 傳回包含形狀 3D 效果屬性的 ThreeDFormat 物件。注意：對於某些沒有 3D 屬性的形狀類型可能傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 傳回僅限於投影片範圍內的內部識別碼，供外掛程式或其他程式碼使用。由於此值可能被使用者或程式重新指派，不能視為持久的唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 決定偶數欄是否以不同的格式繪製。可讀寫 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。可讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。可讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。可讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 傳回形狀在 Z 序中的位置。Shapes[0] 會傳回 Z 序最背後的形狀，而 Shapes[Shapes.Count - 1] 會傳回最前面的形狀。唯讀 Int32。 |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 若不存在，新增一個占位符並將占位符屬性設定為指定的占位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本的占位符形狀（來自行版或母片投影片，且為目前形狀所繼承的形狀）。如果目前形狀未被繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 作為縮圖範圍類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據形狀渲染內容計算出的視覺邊界。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合併相鄰的儲存格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是占位符。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 將定義的段落格式屬性套用至所有表格儲存格的段落。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 將定義的文字區塊格式屬性套用至所有表格儲存格的文字區塊。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 將定義的文字框格式屬性套用至所有表格儲存格的文字框。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將 Shape 的內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將 Shape 的內容儲存為 SVG 檔案。 |

### 另見

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ITable](../itable)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->