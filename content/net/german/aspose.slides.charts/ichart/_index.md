---
title: IChart
second_title: Aspose.Slides für .NET API Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1660
url: /de/aspose.slides.charts/ichart/
---

## IChart-Schnittstelle

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IFormattedTextContainer. Nur lesbar [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Ermöglicht den Zugriff auf die Basis-Schnittstelle IGraphicalObject. Nur lesbar [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Gibt die IOverrideThemeable-Schnittstelle zurück. Nur lesbar [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Bietet Zugriff auf die Diagrammachsen. Nur lesbar [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Rückwand eines 3D-Diagramms zu ändern. Nur lesbar [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die mit einemDiagramm verbunden sind. Nur lesbar [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Nur lesbar [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Gibt einen Diagrammtitel zurück oder setzt ihn. Nur lesbar [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Gibt zurück oder setzt die Art und Weise, wie leere Zellen in einem Diagramm dargestellt werden. Lese-/Schreibzugriff [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format des Bodens eines 3D-Diagramms zu ändern. Nur lesbar [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lese-/Schreibzugriff Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lese-/Schreibzugriff Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Gibt an, ob der Diagrammbereich abgerundete Ecken haben soll. Lese-/Schreibzugriff Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lese-/Schreibzugriff Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder setzt sie. Nur lesbar [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stellt den Plotbereich eines Diagramms dar. Nur lesbar [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bestimmt, ob nur sichtbare Zellen geplottet werden. Falsch, um sowohl sichtbare als auch ausgeblendete Zellen zu plottieren. Lese-/Schreibzugriff Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Gibt eine 3D-Rotation eines Diagramms zurück. Nur lesbar [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lese-/Schreibzugriff Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Seitenwand eines 3D-Diagramms zu ändern. Nur lesbar [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Gibt den Diagrammstil zurück oder setzt ihn. Lese-/Schreibzugriff [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Gibt den Diagrammtyp zurück oder setzt ihn. Lese-/Schreibzugriff [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Gibt die Formen an, die über dem Diagramm gezeichnet werden. Nur lesbar [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Berechnet die aktuellen Werte der Diagrammelemente. Aktuelle Werte umfassen die Position von Elementen, die die IActualLayout-Schnittstelle implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die aktuellen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Siehe Auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Schnittstelle [IGraphicalObject](../../aspose.slides/igraphicalobject)
* Schnittstelle [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->