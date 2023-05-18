---
title: IChart
second_title: Aspose.Sildes for .NET API Reference
description: Represents an graphic chart on a slide.
type: docs
weight: 1630
url: /net/aspose.slides.charts/ichart/
---
## IChart interface

Represents an graphic chart on a slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Properties

| Name | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Allows to get base IFormattedTextContainer interface. Read-only [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Allows to get base IGraphicalObject interface. Read-only [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Returns IOverrideThemeable interface. Read-only [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Provide access to chart axes. Read-only [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Returns an object which allows to change format of the back wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Returns information about the linked or embedded data associated with a chart. Read-only [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Returns a data table of a chart. Read-only [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Returns or sets a chart title Read-only [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Returns or sets the way to plot blank cells on a chart. Read/write [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Returns an object which allows to change format of the floor of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Determines whether a chart has a data table. Read/write Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Determines whether a chart has a legend. Read/write Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Specifies the chart area shall have rounded corners. Read/write Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Determines whether a chart has a visible title. Read/write Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Returns or sets a legend for a chart. Read-only [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Represents the plot area of a chart. Read-only [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Determines whether the only visible cells are plotted. False to plot both visible and hidden cells. Read/write Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Returns a 3D rotation of a chart. Read-only [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Specifies data labels over the maximum of the chart shall be shown. Read/write Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Returns an object which allows to change format of the side wall of a 3D chart. Read-only [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Returns or sets the chart style. Read/write [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Returns or sets the chart type. Read/write [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specify the shapes drawn on top of the chart. Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methods

| Name | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Calculates actual values of chart elements. Actual values inlude position of elements that implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) and actual axes values (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### See Also

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
