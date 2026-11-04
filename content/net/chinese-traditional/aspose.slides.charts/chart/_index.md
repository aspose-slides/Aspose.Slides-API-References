---
title: Chart
second_title: Aspose.Sildes for .NET API 參考文件
description: 表示投影片上的圖形圖表。
type: docs
weight: 1270
url: /zh-hant/aspose.slides.charts/chart/
---
## Chart 類別

表示投影片上的圖形圖表。

```csharp
public class Chart : GraphicalObject, IChart
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或設定與形狀關聯的替代文字。讀寫 String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或設定與形狀關聯的替代文字的標題。讀寫 String。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | 允許取得基礎 IFormattedTextContainer 介面。唯讀 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | 允許取得基礎 IThemeable 介面。唯讀 [`IThemeable`](../../aspose.slides.theme/ithemeable)。 |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | 提供存取圖表坐標軸。唯讀 [`IAxesManager`](../iaxesmanager)。 |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 返回一個可變更 3D 圖表背牆格式的物件。唯讀 [`IChartWall`](../ichartwall)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 屬性指定形狀在黑白顯示模式下的呈現方式。讀寫 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | 返回與圖表相關聯的連結或嵌入資料資訊。唯讀 [`IChartData`](../ichartdata)。 |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | 返回圖表的資料表。唯讀 [`IDataTable`](../idatatable)。 |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | 返回或設定圖表標題。唯讀 [`IChartTitle`](../icharttitle)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形狀的連接點數目。唯讀 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形狀的自訂資料。唯讀 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | 返回或設定圖表繪製空白儲存格的方式。讀寫 [`DisplayBlanksAsType`](../displayblanksastype)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含套用於形狀之像素效果的 EffectFormat 物件。注意：對於某些沒有效果屬性的形狀類型，可能回傳 null。唯讀 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形狀填充格式屬性的 FillFormat 物件。注意：對於某些沒有填充屬性的形狀類型，可能回傳 null。唯讀 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 返回一個可變更 3D 圖表底部格式的物件。唯讀 [`IChartWall`](../ichartwall)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或設定形狀框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | 判斷圖表是否具有資料表。讀寫 Boolean。 |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | 判斷圖表是否具有圖例。讀寫 Boolean。 |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | 指定圖表區域是否具有圓角。讀寫 Boolean。 |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | 判斷圖表是否顯示標題。讀寫 Boolean。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或設定形狀的高度，以點為單位。讀寫 Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 判斷形狀是否隱藏。讀寫 Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或設定滑鼠點擊時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超連結管理器。唯讀 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或設定滑鼠懸停時的超連結。讀寫 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 取得或設定「標記為裝飾」選項。讀寫 Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 判斷形狀是否為群組。唯讀 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判斷形狀是否為 TextHolder_PPT。唯讀 Boolean。 |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | 返回或設定圖表的圖例。唯讀 [`ILegend`](../ilegend)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形狀線條格式屬性的 LineFormat 物件。注意：對於某些沒有線條屬性的形狀類型，可能回傳 null。唯讀 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或設定形狀的名稱。不得為 null。必要時使用空字串。讀寫 String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在投影片範圍內唯一且在形狀生命週期內保持不變的辨識號，讓 PowerPoint 或互通程式碼能從文件任意位置可靠地參照該形狀。唯讀 UInt32。另請參見 [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形狀已群組，返回其父層 GroupShape 物件；否則回傳 null。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形狀的佔位符。若形狀沒有佔位符，則回傳 null。唯讀 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | 代表圖表的繪圖區域。唯讀 [`IChartPlotArea`](../ichartplotarea)。 |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | 判斷是否僅繪製可見儲存格。若為 false，則同時繪製可見與隱藏儲存格。讀寫 Boolean。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回投影片的父級簡報。唯讀 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或設定原始形狀框架的屬性。讀寫 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或設定指定形狀繞 Z 軸旋轉的角度（度）。正值表示順時針旋轉；負值表示逆時針旋轉。讀寫 Single。 |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | 返回圖表的 3D 旋轉。唯讀 [`IRotation3D`](../irotation3d)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形狀的鎖定設定。唯讀 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 個屬性） |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | 指定是否顯示超過圖表最大值的資料標籤。讀寫 Boolean。 |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 返回一個可變更 3D 圖表側牆格式的物件。唯讀 [`IChartWall`](../ichartwall)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形狀的父投影片。唯讀 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | 返回或設定圖表樣式。讀寫 [`StyleType`](../styletype)。 |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | 返回圖表文字格式。此屬性不適用於以下類型：Treemap、Sunburst、Waterfall、Histogram、Funnel、BoxAndWhisker。唯讀 [`IChartTextFormat`](../icharttextformat)。 |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | 返回佈景主題管理器。唯讀 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回形狀的 ThreeDFormat 物件，包含 3D 效果屬性。注意：對於某些沒有 3D 屬性的形狀類型，可能回傳 null。唯讀 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | 返回或設定圖表類型。讀寫 [`ChartType`](../charttype)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供外掛程式或其他程式碼使用的內部簡報範圍辨識號。由於此值可能被使用者或程式碼重新指派，不能視為持久唯一鍵。唯讀 UInt32。另請參見 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | 指定繪製於圖表之上的形狀。唯讀 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或設定形狀的寬度，以點為單位。讀寫 Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或設定形狀左上角的 X 座標，以點為單位。讀寫 Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或設定形狀左上角的 Y 座標，以點為單位。讀寫 Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形狀在 Z 軸排序中的位置。Shapes[0] 取得 Z 軸排序最背的形狀，Shapes[Shapes.Count - 1] 取得最前面的形狀。唯讀 Int32。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，新增一個占位符並將占位符屬性設定為指定的占位符。 |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | 返回此圖表的有效佈景主題。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的占位符形狀（從版面配置或母片投影片繼承的形狀）。若當前形狀未繼承，則回傳 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形狀縮圖。預設使用 ShapeThumbnailBounds.Shape 形狀縮圖邊界類型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形狀縮圖。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 取得根據已渲染內容計算出的形狀視覺邊界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定義此形狀不是占位符。 |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | 計算圖表元素的實際值。實際值包括實作 IActualLayout 介面的元素位置 (IActualLayout.ActualX、IActualLayout.ActualY、IActualLayout.ActualWidth、IActualLayout.ActualHeight) 以及實際坐標軸值 (IAxis.ActualMaxValue、IAxis.ActualMinValue、IAxis.ActualMajorUnit、IAxis.ActualMinorUnit、IAxis.ActualMajorUnitScale、IAxis.ActualMinorUnitScale)。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 將形狀內容儲存為 SVG 檔案。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 將形狀內容儲存為 SVG 檔案。 |

### 另請參見

* 類別 [GraphicalObject](../../aspose.slides/graphicalobject)
* 介面 [IChart](../ichart)
* 命名空間 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->