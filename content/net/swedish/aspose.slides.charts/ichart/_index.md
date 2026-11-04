---
title: IChart
second_title: Aspose.Sildes för .NET API-referens
description: Representerar ett grafiskt diagram på en bild.
type: docs
weight: 1760
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
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Tillåter att hämta bas IFormattedTextContainer-gränssnittet. Läs-endast [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Tillåter att hämta bas IGraphicalObject-gränssnittet. Läs-endast [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Returnerar IOverrideThemeable-gränssnittet. Läs-endast [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Tillhandahåller åtkomst till diagramaxlar. Läs-endast [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Returnerar ett objekt som tillåter att ändra formatet på bakväggen i ett 3D-diagram. Läs-endast [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Returnerar information om de länkade eller inbäddade data som är associerade med ett diagram. Läs-endast [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Returnerar en datatabell för ett diagram. Läs-endast [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Returnerar eller anger en diagramrubrik. Läs-endast [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Returnerar eller anger hur tomma celler ska plottas i ett diagram. Läs-skriv [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Returnerar ett objekt som tillåter att ändra formatet på golvet i ett 3D-diagram. Läs-endast [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Anger om ett diagram har en datatabell. Läs-skriv Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Anger om ett diagram har en förklaring. Läs-skriv Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Anger att diagramområdet ska ha avrundade hörn. Läs-skriv Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Anger om ett diagram har en synlig rubrik. Läs-skriv Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Returnerar eller anger en förklaring för ett diagram. Läs-endast [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Representerar plotområdet för ett diagram. Läs-endast [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Anger om endast synliga celler ska plottas. Falskt för att plotta både synliga och dolda celler. Läs-skriv Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Returnerar en 3D-rotation av ett diagram. Läs-endast [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Anger att datapetiketter över diagrammets maximum ska visas. Läs-skriv Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Returnerar ett objekt som tillåter att ändra formatet på sidoväggen i ett 3D-diagram. Läs-endast [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Returnerar eller anger diagramstilen. Läs-skriv [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Returnerar eller anger diagramtypen. Läs-skriv [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Anger formerna som ritas ovanpå diagrammet. Läs-endast [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Beräknar faktiska värden för diagrammets element. Faktiska värden inkluderar positionen för element som implementerar IActualLayout-gränssnittet (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) och faktiska axelvärden (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Se även

* gränssnitt [IFormattedTextContainer](../iformattedtextcontainer)
* gränssnitt [IGraphicalObject](../../aspose.slides/igraphicalobject)
* gränssnitt [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namnrymd [Aspose.Slides.Charts](../../aspose.slides.charts)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->