---
title: Table
second_title: Aspose.Sildes for .NET API 參考
description: 表示投影片上的表格。
type: docs
weight: 10860
url: /zh-hant/aspose.slides/table/
---
## Table 類別

表示投影片上的表格。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## 屬性

| 名稱 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 取得或設定與圖形相關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 取得或設定與圖形相關聯的替代文字標題。讀寫 String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定圖形在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../blackwhitemode)。 |
| [Columns](../../aspose.slides/table/columns) { get; } | 取得欄位的集合。唯讀 [`IColumnCollection`](../icolumncollection)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 取得圖形的連接點數量。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 取得圖形的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 取得包含套用於圖形之像素效果的 EffectFormat 物件。註：對於某些沒有效果屬性的圖形，可能會傳回 null。唯讀 [`IEffectFormat`](../ieffectformat)。 |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | 取得包含 Table 填充格式的 TableFormat.FillFormat 物件。唯讀 [`IFillFormat`](../ifillformat)。 |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 判斷是否必須以特殊格式繪製表格的第一欄。讀寫 Boolean。 |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 判斷是否必須以特殊格式繪製表格的第一列。讀寫 Boolean。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 取得或設定圖形框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 取得圖形的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定圖形的高度（以點為單位）。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷圖形是否隱藏。讀寫 Boolean。 |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 判斷偶數列是否必須以不同的格式繪製。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 取得或設定滑鼠點擊時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 取得超連結管理員。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 取得或設定滑鼠懸停時的超連結。讀寫 [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷圖形是否已群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷圖形是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Item](../../aspose.slides/table/item) { get; } | 取得指定欄與列索引的儲存格。唯讀 [`Cell`](../cell)。 |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 判斷是否必須以特殊格式繪製表格的最後一欄。讀寫 Boolean。 |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 判斷是否必須以特殊格式繪製表格的最後一列。讀寫 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 取得包含圖形線條格式屬性的 LineFormat 物件。註：對於某些沒有線條屬性的圖形，可能會傳回 null。唯讀 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 取得或設定圖形的名稱。必須非 null。如有需要可使用空字串。讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 取得在投影片範圍內唯一的識別碼，在圖形生命週期內保持不變，讓 PowerPoint 或 interop 程式碼能可靠地從文件任意位置參照該圖形。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果圖形已群組，則取得父層 GroupShape 物件。否則傳回 null。唯讀 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 取得圖形的佔位符。如果圖形沒有佔位符，傳回 null。唯讀 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 取得投影片的父簡報。唯讀 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 取得或設定原始圖形框架的屬性。讀寫 [`IShapeFrame`](../ishapeframe)。 |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 判斷表格是否採用從右至左的閱讀順序。讀寫 Boolean。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 取得或設定指定圖形繞 z 軸旋轉的角度（度數）。正值表示順時針旋轉，負值表示逆時針旋轉。讀寫 Single。 |
| [Rows](../../aspose.slides/table/rows) { get; } | 取得列的集合。唯讀 [`IRowCollection`](../irowcollection)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 取得圖形的鎖定狀態。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 取得圖形的父投影片。唯讀 [`IBaseSlide`](../ibaseslide)。 |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 取得或設定內建表格樣式。讀寫 [`TableStylePreset`](../tablestylepreset)。 |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 取得包含此表格格式屬性的 TableFormat 物件。唯讀 [`ITableFormat`](../itableformat)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 取得圖形的 ThreeDFormat 物件，其包含 3D 效果屬性。註：對於某些沒有 3D 屬性的圖形，可能會傳回 null。唯讀 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 取得內部、簡報範圍內的識別碼，供外掛程式或其他程式碼使用。由於此值可被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid)。 |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 判斷偶數欄是否必須以不同的格式繪製。讀寫 Boolean。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定圖形的寬度（以點為單位）。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定圖形左上角的 x 坐標（以點為單位）。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定圖形左上角的 y 坐標（以點為單位）。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 取得圖形在 Z 順序中的位置。Shapes[0] 會傳回 Z 順序最底層的圖形，而 Shapes[Shapes.Count - 1] 會傳回最上層的圖形。唯讀 Int32。 |

## 方法

| 名稱 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位符，並將佔位符屬性設定為指定的佔位符。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 傳回基本佔位符形狀（來自投影片佈局或母片且目前形狀繼承的形狀）。如果目前形狀未繼承，則傳回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 傳回圖形縮圖。預設使用 ShapeThumbnailBounds.Shape 作為縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 傳回圖形縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得從渲染內容計算出的圖形視覺邊界。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合併相鄰的儲存格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此圖形不是佔位符。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 將指定的段落格式屬性套用至所有表格儲存格的段落。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 將指定的段落格式屬性套用至所有表格儲存格的文字段。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 將指定的文字框架格式屬性套用至所有表格儲存格的文字框架。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將圖形內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將圖形內容儲存為 SVG 檔案。 |

### 另見

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ITable](../itable)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->