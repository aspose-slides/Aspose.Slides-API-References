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

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀相關聯的替代文字。讀/寫 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀相關聯的替代文字的標題。讀/寫 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。讀/寫 [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | 返回欄位的集合。唯讀 [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數量。唯讀 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。唯讀 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀可能會回傳 null。唯讀 [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | 返回包含表格填充格式的 TableFormat.FillFormat 物件。唯讀 [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | 判斷表格的第一欄是否需要使用特殊格式繪製。讀/寫 Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | 判斷表格的第一列是否需要使用特殊格式繪製。讀/寫 Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 取得或設定形狀的高度，以點為單位。讀/寫 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀/寫 Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 判斷偶數列是否需要使用不同的格式繪製。讀/寫 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。讀/寫 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。唯讀 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。讀/寫 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀/寫 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否已群組。唯讀 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | 返回指定欄與列索引處的儲存格。唯讀 [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | 判斷表格的最後一欄是否需要使用特殊格式繪製。讀/寫 Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | 判斷表格的最後一列是否需要使用特殊格式繪製。讀/寫 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀可能會回傳 null。唯讀 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不得為 null。必要時使用空字串值。讀/寫 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一且在形狀生存期內保持不變的識別碼，讓 PowerPoint 或互操作程式碼能可靠地從文件任何位置參照該形狀。唯讀 UInt32。另請參閱 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，返回父層 GroupShape 物件；否則回傳 null。唯讀 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位元件。如果形狀沒有佔位元件則回傳 null。唯讀 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父層簡報。唯讀 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。讀/寫 [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | 判斷表格是否使用從右至左的閱讀順序。讀寫 Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 Z 軸旋轉的角度（度數）。正值表示順時針旋轉；負值表示逆時針旋轉。讀/寫 Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | 返回列的集合。唯讀 [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定。唯讀 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 個屬性） |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父層投影片。唯讀 [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 取得或設定內建的表格樣式。讀/寫 [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | 返回包含此表格格式屬性的 TableFormat 物件。唯讀 [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形狀的 ThreeDFormat 物件，其中包含 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀可能會回傳 null。唯讀 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回用於外掛或其他程式碼的內部、簡報範圍內的識別碼。由於此值可能被使用者或程式重新指派，不能視為永久唯一鍵。唯讀 UInt32。另請參閱 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 判斷偶數欄是否需要使用不同的格式繪製。讀/寫 Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | 取得或設定形狀的寬度，以點為單位。讀/寫 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 取得或設定形狀左上角的 X 座標，以點為單位。讀/寫 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 取得或設定形狀左上角的 Y 座標，以點為單位。讀/寫 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 軸順序中的位置。Shapes[0] 會回傳 Z 軸順序最最後方的形狀，Shapes[Shapes.Count - 1] 會回傳最前方的形狀。唯讀 Int32. |

## 方法

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在則新增佔位元件，並將佔位元件屬性設定為指定的佔位元件。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的佔位元件形狀（從投影片佈局和/或母片繼承的形狀）。如果當前形狀未繼承，則回傳 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得形狀根據其渲染內容計算出的視覺邊界。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 合併相鄰的儲存格。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是佔位元件。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 將定義的段落格式屬性套用至所有表格儲存格的段落。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 將定義的區塊格式屬性套用至所有表格儲存格的區塊。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 將定義的文字框格式屬性套用至所有表格儲存格的文字框。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容另存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容另存為 SVG 檔案。 |

### 另見

* 類別 [GraphicalObject](../graphicalobject)
* 介面 [ITable](../itable)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->