---
title: IChart
second_title: Aspose.Sildes .NET API referenciához
description: Egy dián megjelenő grafikus diagramot reprezentál.
type: docs
weight: 1720
url: /hu/aspose.slides.charts/ichart/
---
## IChart interfész

Egy dián megjelenő grafikus diagramot reprezentál.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Lehetővé teszi a base IFormattedTextContainer interfész lekérését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Lehetővé teszi a base IGraphicalObject interfész lekérését. Csak olvasható [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Visszaadja az IOverrideThemeable interfészt. Csak olvasható [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Hozzáférést biztosít a diagram tengelyeihez. Csak olvasható [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Visszaad információt a diagramhoz kapcsolódó összekapcsolt vagy beágyazott adatról. Csak olvasható [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Visszaad egy diagram adat táblát. Csak olvasható [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Visszaadja vagy beállítja a diagram címét. Csak olvasható [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Visszaadja vagy beállítja a diagramon az üres cellák ábrázolásának módját. Olvasás/írás [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram talajának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e adat táblával. Olvasás/írás Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e jelmagyarázattal. Olvasás/írás Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Megadja, hogy a diagram területe lekerekített sarkokkal rendelkezzen-e. Olvasás/írás Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Meghatározza, hogy a diagram látható címmel rendelkezik-e. Olvasás/írás Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Visszaadja vagy beállítja a diagram jelmagyarázatát. Csak olvasható [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | A diagram ábrázolási területét reprezentálja. Csak olvasható [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. Hamis esetén mind a látható, mind a rejtett cellák ábrázolódnak. Olvasás/írás Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Visszaad egy 3D forgást a diagramhoz. Csak olvasható [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formázását. Csak olvasható [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Megadja a diagram tetején megrajzolt alakzatokat. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Számolja ki a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák az IActualLayout interfészt megvalósító elemek pozícióját (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tényleges tengelyértékeket (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* interfész [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interfész [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->