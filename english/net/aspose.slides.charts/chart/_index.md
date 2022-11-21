---
title: Chart
second_title: Aspose.Sildes for .NET API Reference
description: Represents an graphic chart on a slide.
type: docs
weight: 1140
url: /net/aspose.slides.charts/chart/
---
## Chart class

Represents an graphic chart on a slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Returns or sets the alternative text associated with a shape. Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Returns or sets the title of alternative text associated with a shape. Read/write String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Allows to get base IFormattedTextContainer interface. Read-only [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Allows to get base IThemeable interface. Read-only [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Provide access to chart axes. Read-only [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Returns an object which allows to change format of the back wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Property specifies how a shape will render in black-and-white display mode.. Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Returns information about the linked or embedded data associated with a chart. Read-only [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Returns a data table of a chart. Read-only [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Returns or sets a chart title. Read-only [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Returns the number of connection sites on the shape. Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Returns the shape's custom data. Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Returns or sets the way to plot blank cells on a chart. Read/write [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Returns the EffectFormat object which contains pixel effects applied to a shape. Note: can return null for certain types of shapes which don't have effect properties. Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Returns an object which allows to change format of the floor of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Returns or sets the shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Returns shape's locks. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Determines whether a chart has a data table. Read/write Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Determines whether a chart has a legend. Read/write Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Specifies the chart area shall have rounded corners. Read/write Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Determines whether a chart has a visible title. Read/write Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Returns or sets the height of the shape. Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determines whether the shape is hidden. Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Returns or sets the hyperlink defined for mouse click. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Returns the hyperlink manager. Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Returns or sets the hyperlink defined for mouse over. Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determines whether the shape is grouped. Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determines whether the shape is TextHolder_PPT. Read-only Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Returns or sets a legend for a chart. Read-only [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Returns the LineFormat object that contains line formatting properties for a shape. Note: can return null for certain types of shapes which don't have line properties. Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Returns or sets the name of a shape. Must be not null. Use empty string value if needed. Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Gets unique shape identifier in slide scope. Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid) for getting unique shape identifier in presentation scope. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Returns parent GroupShape object if shape is grouped. Otherwise returns null. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Returns the placeholder for a shape. Returns null if the shape has no placeholder. Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Represents the plot area of a chart. Read-only [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Returns the parent presentation of a slide. Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Returns or sets the raw shape frame's properties. Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Returns or sets the number of degrees the specified shape is rotated around the z-axis. A positive value indicates clockwise rotation; a negative value indicates counterclockwise rotation. Read/write Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Returns a 3D rotation of a chart. Read-only [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Returns shape's locks. Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Specifies data labels over the maximum of the chart shall be shown. Read/write Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Returns an object which allows to change format of the side wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Returns the parent slide of a shape. Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Returns or sets the chart style. Read/write [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Returns chart text format. The property is not applicable for the following types: Treemap, Sunburst, Waterfall, Histogram, Funnel,BoxAndWhisker. Read-only [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Returns theme manager. Read-only [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Returns the ThreeDFormat object that 3d effect properties for a shape. Note: can return null for certain types of shapes which don't have 3d properties. Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Returns or sets the chart type. Read/write [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Gets unique shape identifier in presentation scope. Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) for getting unique shape identifier in slide scope. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Specify the shapes drawn on top of the chart. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Returns or sets the width of the shape. Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Returns or sets the x-coordinate of the upper-left corner of the shape. Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Returns or sets the y-coordinate of the upper-left corner of the shape. Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Returns the position of a shape in the z-order. Shapes[0] returns the shape at the back of the z-order, and Shapes[Shapes.Count - 1] returns the shape at the front of the z-order. Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Returns an effective theme for this chart. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). A null is returned if the current shape is not inherited. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Returns shape thumbnail. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Returns shape thumbnail. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Defines that this shape isn't a placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Calculates actual values of chart elements. The actual values include position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Saves content of Shape as SVG file. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Saves content of Shape as SVG file. |

### See Also

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
