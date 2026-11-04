---
title: IChart
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1760
url: /de/aspose.slides.charts/ichart/
---
## IChart Schnittstelle

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basisschnittstelle IFormattedTextContainer. Nur lesend [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Ermöglicht das Abrufen der Basisschnittstelle IGraphicalObject. Nur lesend [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Gibt die Schnittstelle IOverrideThemeable zurück. Nur lesend [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Bietet Zugriff auf Diagrammachsen. Nur lesend [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Gibt ein Objekt zurück, das das Ändern des Formats der Rückwand eines 3D-Diagramms ermöglicht. Nur lesend [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. Nur lesend [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Nur lesend [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Gibt oder setzt den Diagrammtitel. Nur lesend [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Gibt oder setzt die Darstellung leerer Zellen in einem Diagramm. Lesen/Schreiben [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Gibt ein Objekt zurück, das das Ändern des Formats des Bodens eines 3D-Diagramms ermöglicht. Nur lesend [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Legt fest, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Legt fest, ob ein Diagramm eine Legende hat. Lesen/Schreiben Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Legt fest, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Legt fest, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Gibt oder setzt eine Legende für ein Diagramm. Nur lesend [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stellt den Plotbereich eines Diagramms dar. Nur lesend [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Legt fest, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch versteckte Zellen zu plotten. Lesen/Schreiben Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Gibt die 3D-Drehung eines Diagramms zurück. Nur lesend [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Legt fest, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden. Lesen/Schreiben Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Gibt ein Objekt zurück, das das Ändern des Formats der Seitenwand eines 3D-Diagramms ermöglicht. Nur lesend [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Gibt oder setzt den Diagrammstil. Lesen/Schreiben [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Gibt oder setzt den Diagrammtyp. Lesen/Schreiben [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Gibt die über dem Diagramm gezeichneten Formen an. Nur lesend [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methoden

| Name | Description |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Berechnet die tatsächlichen Werte von Diagrammelementen. Tatsächliche Werte umfassen die Position von Elementen, die die Schnittstelle IActualLayout implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Schnittstelle [IGraphicalObject](../../aspose.slides/igraphicalobject)
* Schnittstelle [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->