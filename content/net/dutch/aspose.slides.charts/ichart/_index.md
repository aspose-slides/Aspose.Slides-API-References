---
title: IChart
second_title: Aspose.Sildes voor .NET API-referentie
description: Vertegenwoordigt een grafisch diagram op een dia.
type: docs
weight: 1740
url: /nl/aspose.slides.charts/ichart/
---
## IChart interface

Stelt een grafisch diagram op een dia voor.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Properties

| Naam | Beschrijving |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Staat toe de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Staat toe de basis IGraphicalObject interface op te halen. Alleen-lezen [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Geeft IOverrideThemeable interface terug. Alleen-lezen [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Biedt toegang tot de assen van de diagram. Alleen-lezen [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Geeft een object terug dat het formaat van de achterwand van een 3D-diagram kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Geeft informatie over de gekoppelde of ingesloten gegevens die aan een diagram zijn gekoppeld. Alleen-lezen [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Geeft een gegevens tabel van een diagram terug. Alleen-lezen [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Geeft of stelt de titel van een diagram in. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Geeft of stelt de manier in waarop lege cellen in een diagram worden weergegeven. Lezen/Schrijven [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Geeft een object terug dat het formaat van de vloer van een 3D-diagram kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bepaalt of een diagram een gegevenstabel heeft. Lezen/Schrijven Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bepaalt of een diagram een legenda heeft. Lezen/Schrijven Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Specificeert dat het diagramgebied afgeronde hoeken moet hebben. Lezen/Schrijven Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bepaalt of een diagram een zichtbare titel heeft. Lezen/Schrijven Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Geeft of stelt een legenda voor een diagram in. Alleen-lezen [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stelt het plotgebied van een diagram voor. Alleen-lezen [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bepaalt of alleen zichtbare cellen worden weergegeven. False om zowel zichtbare als verborgen cellen weer te geven. Lezen/Schrijven Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Geeft een 3D-rotatie van een diagram terug. Alleen-lezen [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Specificeert dat gegevenslabels boven het maximum van het diagram worden getoond. Lezen/Schrijven Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Geeft een object terug dat het formaat van de zijwand van een 3D-diagram kan wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Geeft of stelt de diagramstijl in. Lezen/Schrijven [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Geeft of stelt het diagramtype in. Lezen/Schrijven [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specificeer de vormen die bovenop het diagram worden getekend. Alleen-lezen [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methods

| Naam | Beschrijving |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Bereken de werkelijke waarden van diagramonderdelen. Werkelijke waarden omvatten de positie van elementen die de IActualLayout interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en de werkelijke assenwaarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->