---
title: IChart
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
weight: 1740
url: /sv/aspose.slides.charts/ichart/
---
## IChart gränssnitt

Representerar ett grafiskt diagram på en bild.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Tillåter att hämta bas IFormattedTextContainer-gränssnittet. Skrivskyddad [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Tillåter att hämta bas IGraphicalObject-gränssnittet. Skrivskyddad [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Returnerar IOverrideThemeable-gränssnittet. Skrivskyddad [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Tillhandahåller åtkomst till diagramaxlar. Skrivskyddad [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Returnerar ett objekt som tillåter att ändra formatet för bakväggen på ett 3D-diagram. Skrivskyddad [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Returnerar information om den länkade eller inbäddade data som är associerad med ett diagram. Skrivskyddad [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Returnerar en datatabell för ett diagram. Skrivskyddad [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Returnerar eller anger diagramrubrik. Skrivskyddad [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Returnerar eller anger sättet att plotta tomma celler i ett diagram. Läs/skriv [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Returnerar ett objekt som tillåter att ändra formatet för golvet i ett 3D-diagram. Skrivskyddad [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bestämmer om ett diagram har en datatabell. Läs/skriv Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bestämmer om ett diagram har en förklaring. Läs/skriv Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Anger att diagramområdet ska ha rundade hörn. Läs/skriv Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bestämmer om ett diagram har en synlig rubrik. Läs/skriv Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Returnerar eller anger en förklaring för ett diagram. Skrivskyddad [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Representerar plotområdet för ett diagram. Skrivskyddad [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bestämmer om endast synliga celler ska plottas. Falskt för att plotta både synliga och dolda celler. Läs/skriv Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Returnerar en 3D-rotation av ett diagram. Skrivskyddad [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Anger att datalabels över diagrammets maximum ska visas. Läs/skriv Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Returnerar ett objekt som tillåter att ändra formatet för sidoväggen på ett 3D-diagram. Skrivskyddad [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Returnerar eller anger diagramstilen. Läs/skriv [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Returnerar eller anger diagramtypen. Läs/skriv [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Specificerar formerna som ritas ovanpå diagrammet. Skrivskyddad [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Beräknar faktiska värden för diagramelement. Faktiska värden inkluderar position för element som implementerar IActualLayout-gränssnittet (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

### Se även

* gränssnitt [IFormattedTextContainer](../iformattedtextcontainer)
* gränssnitt [IGraphicalObject](../../aspose.slides/igraphicalobject)
* gränssnitt [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->