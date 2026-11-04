---
title: Chart
second_title: Aspose.Sildes .NET API 参考
description: 表示幻灯片上的图形 chart。
type: docs
weight: 1270
url: /zh/aspose.slides.charts/chart/
---
## Chart 类

表示幻灯片上的图形 chart。

```csharp
public class Chart : GraphicalObject, IChart
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。读取/写入 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本标题。读取/写入 String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | 允许获取基础 IFormattedTextContainer 接口。只读 [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | 允许获取基础 IThemeable 接口。只读 [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | 提供对 chart 轴的访问。只读 [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 返回一个对象，可用于更改 3D chart 的背墙格式。只读 [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的呈现方式。读取/写入 [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | 返回与 chart 关联的链接或嵌入数据的信息。只读 [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | 返回 chart 的数据表。只读 [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | 返回或设置 chart 标题。只读 [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数量。只读 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。只读 [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | 返回或设置在 chart 上绘制空单元格的方式。读取/写入 [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。注意：对于某些没有 effect 属性的形状，可能返回 null。只读 [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。注意：对于某些没有 fill 属性的形状，可能返回 null。只读 [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 返回一个对象，可用于更改 3D chart 的底面格式。只读 [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。读取/写入 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | 确定 chart 是否具有数据表。读取/写入 Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | 确定 chart 是否具有图例。读取/写入 Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | 指定 chart 区域应具有圆角。读取/写入 Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | 确定 chart 是否有可见标题。读取/写入 Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | 获取或设置形状的高度（单位为磅）。读取/写入 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。读取/写入 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置鼠标单击时定义的超链接。读取/写入 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。只读 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置鼠标悬停时定义的超链接。读取/写入 [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 获取或设置“标记为装饰性”选项。读取/写入 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否已分组。只读 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 确定形状是否为 TextHolder_PPT。只读 Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | 返回或设置 chart 的图例。只读 [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状线条格式属性的 LineFormat 对象。注意：对于某些没有线条属性的形状，可能返回 null。只读 [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。必须为非空。如果需要，可使用空字符串。读取/写入 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 返回在幻灯片范围内唯一标识形状的标识符，该标识符在形状的整个生命周期内保持不变，并允许运行 PowerPoint 或互操作代码可靠地在文档的任何位置引用该形状。只读 UInt32。另请参阅 [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状已分组，则返回父 GroupShape 对象。否则返回 null。只读 [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。只读 [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | 表示 chart 的绘图区域。只读 [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | 确定是否仅绘制可见单元格。若为 false，则绘制可见和隐藏的单元格。读取/写入 Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。只读 [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。读取/写入 [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状绕 z 轴旋转的角度（度数）。正值表示顺时针旋转；负值表示逆时针旋转。读取/写入 Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | 返回 chart 的 3D 旋转。只读 [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁定状态。只读 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 属性） |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | 指定是否在 chart 的最大值上方显示数据标签。读取/写入 Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 返回一个对象，可用于更改 3D chart 的侧墙格式。只读 [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。只读 [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | 返回或设置 chart 样式。读取/写入 [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | 返回 chart 文本格式。此属性不适用于以下类型：Treemap、Sunburst、Waterfall、Histogram、Funnel、BoxAndWhisker。只读 [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | 返回主题管理器。只读 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回包含形状 3d 效果属性的 ThreeDFormat 对象。注意：对于某些没有 3d 属性的形状，可能返回 null。只读 [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | 返回或设置 chart 类型。读取/写入 [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 返回供插件或其他代码使用的内部、演示文稿范围的标识符。由于该值可能被用户或程序重新分配，不能将其视为持久的唯一键。只读 UInt32。另请参阅 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | 指定绘制在 chart 顶部的形状。只读 [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 获取或设置形状的宽度（单位为磅）。读取/写入 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 获取或设置形状左上角的 x 坐标（单位为磅）。读取/写入 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 获取或设置形状左上角的 y 坐标（单位为磅）。读取/写入 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。Shapes[0] 返回 z 顺序最靠后的形状，Shapes[Shapes.Count - 1] 返回最前面的形状。只读 Int32. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果不存在，则添加新的占位符，并将占位符属性设置为指定的占位符。 |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | 返回此 chart 的有效主题。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 返回基本的占位符形状（来自布局和/或母版幻灯片、当前形状继承自该形状的形状）。如果当前形状未继承，则返回 null。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 返回形状缩略图。默认使用 ShapeThumbnailBounds.Shape 形状缩略图边界类型。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 获取根据渲染内容计算的形状可视边界。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | 计算 chart 元素的实际值。实际值包括实现 IActualLayout 接口的元素的位置 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 和实际轴值 (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将 Shape 内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将 Shape 内容保存为 SVG 文件。 |

### 另见

* 类 [GraphicalObject](../../aspose.slides/graphicalobject)
* 接口 [IChart](../ichart)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->