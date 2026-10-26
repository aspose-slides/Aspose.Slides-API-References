---
title: IChart
second_title: Aspose.Sildes .NET API referenciája
description: Egy grafikus diagramot képvisel egy dián.
type: docs
weight: 1740
url: /hu/aspose.slides.charts/ichart/
---
## IChart interfész

Egy grafikus diagramot képvisel a dián.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Lehetővé teszi a base IFormattedTextContainer interfész lekérdezését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Lehetővé teszi a base IGraphicalObject interfész lekérdezését. Csak olvasható [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Visszaadja az IOverrideThemeable interfészt. Csak olvasható [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Elérést biztosít a diagram tengelyeihez. Csak olvasható [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram háttérfalának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Visszaad információt a diagrammal kapcsolatos, hivatkozott vagy beágyazott adatokról. Csak olvasható [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Visszaad a diagram adat tábláját. Csak olvasható [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Visszaadja vagy beállítja a diagram címét. Csak olvasható [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. Olvasás/írás [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram padlójának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e adat táblával. Olvasás/írás Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e jelmagyarázattal. Olvasás/írás Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Megadja, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Meghatározza, hogy a diagram címe látható-e. Olvasás/írás Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Visszaadja vagy beállítja a diagram jelmagyarázatát. Csak olvasható [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | A diagram ábrázolási területét képviseli. Csak olvasható [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. Hamis érték esetén a látható és rejtett cellák egyaránt ábrázolásra kerülnek. Olvasás/írás Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Visszaadja a diagram 3D forgását. Csak olvasható [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Megadja, hogy a diagram maximális értéke fölött adatcímkék jelenjenek meg. Olvasás/írás Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Megadja a diagram tetejére rajzolt alakzatokat. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Kiszámítja a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák az IActualLayout interfészt megvalósító elemek helyzetét (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tengelyek tényleges értékeit (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* interfész [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interfész [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->