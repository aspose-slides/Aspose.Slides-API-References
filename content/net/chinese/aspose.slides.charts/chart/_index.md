---
title: Chart
second_title: Aspose.Slides for .NET API 参考
description: 表示幻灯片上的图形图表
type: docs
weight: 1120
url: /zh/aspose.slides.charts/chart/
---
## Chart class

表示幻灯片上的图形图表。

```csharp
public class Chart : GraphicalObject, IChart
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 返回或设置与形状关联的替代文本。 读/写String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 返回或设置与形状关联的替代文本的标题。 读/写String。 |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | 允许获取基本 IFormattedTextContainer 接口。 只读[`IFormattedTextContainer`](../iformattedtextcontainer)。 |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | 允许获取基本 IThemeable 接口。 只读[`IThemeable`](../../aspose.slides.theme/ithemeable)。 |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | 提供对图表轴的访问。 只读[`IAxesManager`](../iaxesmanager)。 |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | 返回一个允许更改 3D 图表后墙格式的对象。 只读[`IChartWall`](../ichartwall)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 属性指定形状在黑白显示模式下的渲染方式。 读/写[`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | 返回有关与图表关联的链接或嵌入数据的信息。 只读[`IChartData`](../ichartdata)。 |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | 返回图表的数据表。 只读[`IDataTable`](../idatatable)。 |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | 返回或设置图表标题。 只读[`IChartTitle`](../icharttitle)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 返回形状上的连接点数。 只读Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 返回形状的自定义数据。 只读[`ICustomData`](../../aspose.slides/icustomdata)。 |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | 返回或设置在图表上绘制空白单元格的方式。 读/写[`DisplayBlanksAsType`](../displayblanksastype)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | 返回包含应用于形状的像素效果的 EffectFormat 对象。 注意:对于不具有效果属性的某些类型的形状，可以返回 null。 只读[`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 返回包含形状填充格式属性的 FillFormat 对象。 注意:对于某些没有填充属性的形状，可以返回 null。 只读[`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | 返回一个允许更改 3D 图表楼层格式的对象。 只读[`IChartWall`](../ichartwall)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 返回或设置形状框架的属性。 读/写[`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 返回形状的锁。 只读[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | 判断图表是否有数据表。 读/写Boolean。 |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | 确定图表是否有图例。 读/写Boolean。 |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | 指定图表区域应具有圆角。 读/写Boolean。 |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | 确定图表是否有可见标题。 读/写Boolean。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 返回或设置形状的高度。 读/写Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 确定形状是否隐藏。 读/写Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | 返回或设置为鼠标单击定义的超链接。 读/写[`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | 返回超链接管理器。 只读[`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | 返回或设置为鼠标悬停定义的超链接。 读/写[`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 确定形状是否被分组。 只读Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 判断形状是否为TextHolder_PPT。 只读Boolean。 |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | 返回或设置图表的图例。 只读[`ILegend`](../ilegend)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 返回包含形状的行格式属性的 LineFormat 对象。 注意:对于某些没有线条属性的形状类型，可以返回 null。 只读[`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 返回或设置形状的名称。 不能为空。如果需要，使用空字符串值。 读/写String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | 获取幻灯片范围内的唯一形状标识符。 只读UInt32。 另请参见[`UniqueId`](../../aspose.slides/shape/uniqueid)以获取表示范围内的唯一形状标识符。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 如果形状被分组，则返回父 GroupShape 对象。否则返回 null。 只读[`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 返回形状的占位符。如果形状没有占位符，则返回 null。 只读[`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | 表示图表的绘图区域。 只读[`IChartPlotArea`](../ichartplotarea)。 |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | 确定是否仅绘制可见单元格。 False 绘制可见和隐藏单元格。 读/写Boolean。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | 返回幻灯片的父演示文稿。 只读[`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 返回或设置原始形状框架的属性。 读/写[`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 返回或设置指定形状围绕 z 轴 旋转的度数。正值表示顺时针旋转；负值 表示逆时针旋转。 读/写Single。 |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | 返回图表的 3D 旋转。 只读[`IRotation3D`](../irotation3d)。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 返回形状的锁。 只读[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | 指定应显示图表最大值的数据标签。 读/写Boolean。 |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | 返回一个允许更改 3D 图表侧壁格式的对象。 只读[`IChartWall`](../ichartwall)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 返回形状的父幻灯片。 只读[`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | 返回或设置图表样式。 读/写[`StyleType`](../styletype)。 |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | 返回图表文本格式。 该属性不适用于以下类型:Treemap,Sunburst, Waterfall,Histogram,Funnel,BoxAndWhisker。 只读[`IChartTextFormat`](../icharttextformat)。 |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | 返回主题管理器。 只读[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 返回对形状产生 3d 效果的 ThreeDFormat 对象。 注意:对于没有 3d 属性的某些类型的形状，可以返回 null。 只读[`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | 返回或设置图表类型。 读/写[`ChartType`](../charttype)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 获取表示范围内的唯一形状标识符。 只读UInt32。 另请参见[`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)以获取幻灯片范围内的唯一形状标识符。 |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | 指定在图表顶部绘制的形状。 只读[`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 返回或设置形状的宽度。 读/写Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 返回或设置形状左上角的 x 坐标。 读/写Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 返回或设置形状左上角的 y 坐标。 读/写Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 返回形状在 z 顺序中的位置。 Shapes[0] 返回 z 顺序后面的形状， 和 Shapes[Shapes.Count - 1] 返回 z 顺序前面的形状. 只读Int32。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 如果没有，则添加新的占位符并将占位符属性设置为指定的占位符。 |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | 返回此图表的有效主题。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | 返回形状缩略图。 ShapeThumbnailBounds.Shape 形状缩略图边界类型默认使用。 |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | 返回形状缩略图。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | 定义此形状不是占位符。 |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | 计算图表元素的实际值。实际值包括实现 IActualLayout 接口 (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) 和实际轴值 (IAxis.ActualMaxValue) 的元素的位置, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | 将 Shape 的内容保存为 SVG 文件。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | 将 Shape 的内容保存为 SVG 文件。 |

### 也可以看看

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
