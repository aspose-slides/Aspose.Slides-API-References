---
title: 图表
second_title: Aspose.Sildes for .NET API 参考
description: 表示幻灯片上的图形图表。
type: docs
weight: 1180
url: /zh/aspose.slides.charts/chart/
---

## Chart 类

表示幻灯片上的图形图表。

```csharp
public class Chart : GraphicalObject, IChart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。可读写字符串。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。可读写字符串。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | 允许获取基本的 IFormattedTextContainer 接口。只读 [`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | 允许获取基本的 IThemeable 接口。只读 [`IThemeable`](../../aspose.slides.theme/ithemeable)。 |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | 提供对图表轴的访问。只读 [`IAxesManager`](../iaxesmanager)。 |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 返回一个对象，允许更改 3D 图表的后墙格式。只读 [`IChartWall`](../ichartwall)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。可读写 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | 返回与图表关联的链接或嵌入数据的信息。只读 [`IChartData`](../ichartdata)。 |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | 返回图表的数据表。只读 [`IDataTable`](../idatatable)。 |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | 返回或设置图表标题。只读 [`IChartTitle`](../icharttitle)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | 返回或设置在图表上绘制空单元格的方式。可读写 [`DisplayBlanksAsType`](../displayblanksastype)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有效果属性的形状类型可能返回 null。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有填充属性的形状类型可能返回 null。只读 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 返回一个对象，允许更改 3D 图表的地板格式。只读 [`IChartWall`](../ichartwall)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。可读写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | 确定图表是否具有数据表。可读写布尔值。 |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | 确定图表是否具有图例。可读写布尔值。 |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | 指定图表区域应具有圆角。可读写布尔值。 |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | 确定图表是否有可见标题。可读写布尔值。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。可读写单精度浮点数。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否被隐藏。可读写布尔值。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。可读写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。可读写 [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰”的选项。可读写布尔值。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。只读布尔值。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读布尔值。 |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | 返回或设置图表的图例。只读 [`ILegend`](../ilegend)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状类型可能返回 null。只读 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须不为 null。如果需要，请使用空字符串值。可读写字符串。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。只读 UInt32。另见 [`UniqueId`](../../aspose.slides/shape/uniqueid) 获取演示文稿范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | 表示图表的绘图区域。只读 [`IChartPlotArea`](../ichartplotarea)。 |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | 确定是否仅绘制可见单元格。 False 以绘制可见和隐藏的单元格。可读写布尔值。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回形状的父演示文稿。只读 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。可读写 [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴旋转的度数。正值表示顺时针旋转；负值表示逆时针旋转。可读写单精度浮点数。 |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | 返回图表的 3D 旋转。只读 [`IRotation3D`](../irotation3d)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 (2 个属性) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | 指定图表的最大值上方应显示数据标签。可读写布尔值。 |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 返回一个对象，允许更改 3D 图表的侧墙格式。只读 [`IChartWall`](../ichartwall)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | 返回或设置图表样式。可读写 [`StyleType`](../styletype)。 |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | 返回图表文本格式。该属性不适用于以下类型：Treemap、Sunburst、Waterfall、Histogram、Funnel、BoxAndWhisker。只读 [`IChartTextFormat`](../icharttextformat)。 |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | 返回主题管理器。只读 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含 3D 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3D 属性的形状类型可能返回 null。只读 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | 返回或设置图表类型。可读写 [`ChartType`](../charttype)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取演示文稿范围内的唯一形状标识符。只读 UInt32。另见 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) 获取幻灯片范围内的唯一形状标识符。 |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | 指定在图表上绘制的形状。只读 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。可读写单精度浮点数。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。可读写单精度浮点数。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。可读写单精度浮点数。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序背面的形状，Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状。只读 Int32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有新的占位符，则添加一个新的占位符并将占位符属性设置为指定的属性。 |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | 返回此图表的有效主题。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基础占位符形状（当前形状所继承的来自布局和/或母版幻灯片的形状）。如果当前形状没有继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义该形状不是占位符。 |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | 计算图表元素的实际值。实际值包括实现 IActualLayout 接口的元素的位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 和实际轴值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将形状的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将形状的内容保存为 SVG 文件。 |

### 另见

* 类 [GraphicalObject](../../aspose.slides/graphicalobject)
* 接口 [IChart](../ichart)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->