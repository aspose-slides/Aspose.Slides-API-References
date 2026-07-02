---
title: IChart
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een grafische grafiek op een dia voor.
type: docs
weight: 1740
url: /nl/aspose.slides.charts/ichart/
---
## IChart interface

Represents an graphic chart on a slide.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Stelt toe de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Staat toe de basis IGraphicalObject interface op te halen. Alleen-lezen [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Retourneert IOverrideThemeable interface. Alleen-lezen [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Biedt toegang tot de assen van de grafiek. Alleen-lezen [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Retourneert een object dat het formaat van de achterwand van een 3D-grafiek kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Retourneert informatie over de gekoppelde of ingesloten gegevens die aan een grafiek zijn gekoppeld. Alleen-lezen [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Retourneert een gegevenstabel van een grafiek. Alleen-lezen [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Retourneert of stelt de titel van de grafiek in. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Retourneert of stelt de wijze in waarop lege cellen in een grafiek worden weergegeven. Lezen/schrijven [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Retourneert een object dat het formaat van de vloer van een 3D-grafiek kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bepaalt of een grafiek een gegevenstabel heeft. Lezen/schrijven Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bepaalt of een grafiek een legenda heeft. Lezen/schrijven Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Specificeert dat het grafiekgebied afgeronde hoeken moet hebben. Lezen/schrijven Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bepaalt of een grafiek een zichtbare titel heeft. Lezen/schrijven Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Retourneert of stelt een legenda voor een grafiek in. Alleen-lezen [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stelt het plotgebied van een grafiek voor. Alleen-lezen [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bepaalt of alleen de zichtbare cellen worden geplot. False om zowel zichtbare als verborgen cellen te plotten. Lezen/schrijven Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Retourneert een 3D-rotatie van een grafiek. Alleen-lezen [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Specificeert dat gegevenslabels boven het maximum van de grafiek worden weergegeven. Lezen/schrijven Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Retourneert een object dat het formaat van de zijwand van een 3D-grafiek kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Retourneert of stelt de stijl van de grafiek in. Lezen/schrijven [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Retourneert of stelt het type van de grafiek in. Lezen/schrijven [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specificeer de vormen die bovenop de grafiek worden getekend. Alleen-lezen [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methoden

| Name | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Bereken daadwerkelijke waarden van grafiekelementen. Werkelijke waarden omvatten de positie van elementen die de IActualLayout interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en de werkelijke aswaarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->