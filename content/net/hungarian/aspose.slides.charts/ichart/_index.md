---
title: IChart
second_title: Aspose.Sildes .NET API referenciája
description: Egy grafikus diagramot képvisel egy dián.
type: docs
weight: 1760
url: /hu/aspose.slides.charts/ichart/
---
## IChart interfész

Egy grafikus diagramot képvisel egy dián.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Lehetővé teszi a bázis IFormattedTextContainer interfész lekérését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Lehetővé teszi a bázis IGraphicalObject interfész lekérését. Csak olvasható [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Visszaadja az IOverrideThemeable interfészt. Csak olvasható [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Biztosítja a diagram tengelyeihez való hozzáférést. Csak olvasható [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram hátfalának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Visszaad információt a diagramhoz kapcsolódó hivatkozott vagy beágyazott adatokról. Csak olvasható [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Visszaad a diagram adat táblázatát. Csak olvasható [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Visszaadja vagy beállítja a diagram címét Csak olvasható [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Visszaadja vagy beállítja a diagramon a üres cellák megjelenítésének módját. Olvasható/írható [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram aljzatának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e adat táblázattal. Olvasható/írható Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Meghatározza, hogy a diagram rendelkezik-e jelmagyarázattal. Olvasható/írható Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Megadja, hogy a diagram területének lekerekített sarkokkal kell rendelkeznie. Olvasható/írható Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Meghatározza, hogy a diagram látható címmel rendelkezik-e. Olvasható/írható Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Visszaadja vagy beállítja a diagram jelmagyarázatát. Csak olvasható [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | A diagram ábrázolási területét képviseli. Csak olvasható [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Meghatározza, hogy csak a látható cellák legyenek ábrázolva. Hamis esetén a látható és rejtett cellák egyaránt ábrázolva lesznek. Olvasható/írható Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Visszaadja a diagram 3D forgását. Csak olvasható [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Megadja, hogy a diagram maximumán felül adatcímkék jelenjenek meg. Olvasható/írható Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Visszaadja vagy beállítja a diagram stílusát. Olvasható/írható [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Visszaadja vagy beállítja a diagram típusát. Olvasható/írható [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Megadja a diagram tetején megrajzolt alakzatokat. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Kiszámítja a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák az IActualLayout interfészt megvalósító elemek pozícióját (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) és a tényleges tengelyértékeket (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

### Lásd még

* interfész [IFormattedTextContainer](../iformattedtextcontainer)
* interfész [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interfész [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeszerelés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->