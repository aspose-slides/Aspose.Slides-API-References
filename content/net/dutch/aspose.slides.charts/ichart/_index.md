---
title: IChart
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt een grafische grafiek op een dia voor.
type: docs
weight: 1760
url: /nl/aspose.slides.charts/ichart/
---
## IChart interface

Stelt een grafische grafiek op een dia voor.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Maakt het mogelijk de basis IFormattedTextContainer interface op te halen. Alleen-lezen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Maakt het mogelijk de basis IGraphicalObject interface op te halen. Alleen-lezen [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Retourneert IOverrideThemeable interface. Alleen-lezen [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Biedt toegang tot de assen van de grafiek. Alleen-lezen [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Retourneert een object dat het mogelijk maakt het formaat van de achterwand van een 3D-grafiek te wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Retourneert informatie over de gekoppelde of ingesloten gegevens die aan een grafiek zijn gekoppeld. Alleen-lezen [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Retourneert een gegevens-tabel van een grafiek. Alleen-lezen [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Retourneert of stelt een grafiektitel in. Alleen-lezen [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Retourneert of stelt de manier in waarop lege cellen op een grafiek worden geplot. Lezen/Schrijven [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Retourneert een object dat het mogelijk maakt het formaat van de vloer van een 3D-grafiek te wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bepaalt of een grafiek een gegevens-tabel heeft. Lezen/Schrijven Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bepaalt of een grafiek een legenda heeft. Lezen/Schrijven Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Specificeert dat het grafiekgebied afgeronde hoeken moet hebben. Lezen/Schrijven Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bepaalt of een grafiek een zichtbare titel heeft. Lezen/Schrijven Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Retourneert of stelt een legenda voor een grafiek in. Alleen-lezen [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stelt het plotgebied van een grafiek voor. Alleen-lezen [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bepaalt of alleen zichtbare cellen worden geplot. Onwaar om zowel zichtbare als verborgen cellen te plotten. Lezen/Schrijven Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Retourneert een 3D-rotatie van een grafiek. Alleen-lezen [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Specificeert dat gegevenslabels boven het maximum van de grafiek worden getoond. Lezen/Schrijven Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Retourneert een object dat het mogelijk maakt het formaat van de zijwand van een 3D-grafiek te wijzigen. Alleen-lezen [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Retourneert of stelt de grafiekstijl in. Lezen/Schrijven [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Retourneert of stelt het grafiektype in. Lezen/Schrijven [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specificeer de vormen die bovenop de grafiek worden getekend. Alleen-lezen [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Berekent werkelijke waarden van grafiekelementen. Werkelijke waarden omvatten positie van elementen die IActualLayout interface implementeren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) en werkelijke aswaarden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

### Zie ook

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* naamruimte [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->