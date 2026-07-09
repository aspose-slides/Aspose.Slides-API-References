---
title: IChart
second_title: Aspose.Sildes für .NET API Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1740
url: /de/aspose.slides.charts/ichart/
---
## IChart Schnittstelle

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basis-IFormattedTextContainer-Schnittstelle. Nur-Lesen [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Ermöglicht das Abrufen der Basis-IGraphicalObject-Schnittstelle. Nur-Lesen [`IGraphicalObject`](../../aspose.slides/igraphicalobject). |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Gibt die IOverrideThemeable-Schnittstelle zurück. Nur-Lesen [`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable). |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Stellt Zugriff auf Diagrammachsen bereit. Nur-Lesen [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Gibt ein Objekt zurück, das das Format der Rückwand eines 3D-Diagramms ändern kann. Nur-Lesen [`IChartWall`](../ichartwall). |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten eines Diagramms zurück. Nur-Lesen [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Nur-Lesen [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Gibt einen Diagrammtitel zurück oder legt ihn fest. Nur-Lesen [`IChartTitle`](../icharttitle). |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Gibt die Methode zurück oder legt sie fest, wie leere Zellen in einem Diagramm dargestellt werden. Lesen/Schreiben [`DisplayBlanksAsType`](../displayblanksastype). |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Gibt ein Objekt zurück, das das Format des Bodens eines 3D-Diagramms ändern kann. Nur-Lesen [`IChartWall`](../ichartwall). |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/Schreiben Boolean. |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lesen/Schreiben Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/Schreiben Boolean. |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/Schreiben Boolean. |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Nur-Lesen [`ILegend`](../ilegend). |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Stellt den Zeichenbereich eines Diagramms dar. Nur-Lesen [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Bestimmt, ob nur sichtbare Zellen geplottet werden. False, um sowohl sichtbare als auch ausgeblendete Zellen zu plotten. Lesen/Schreiben Boolean. |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Gibt eine 3D-Drehung eines Diagramms zurück. Nur-Lesen [`IRotation3D`](../irotation3d). |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/Schreiben Boolean. |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Gibt ein Objekt zurück, das das Format der Seitenwand eines 3D-Diagramms ändern kann. Nur-Lesen [`IChartWall`](../ichartwall). |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben [`StyleType`](../styletype). |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben [`ChartType`](../charttype). |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Legt die Formen fest, die über dem Diagramm gezeichnet werden. Nur-Lesen [`IGroupShape`](../../aspose.slides/igroupshape). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Berechnet die tatsächlichen Werte von Diagrammelementen. Tatsächliche Werte enthalten die Position von Elementen, die die IActualLayout-Schnittstelle implementieren (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und die tatsächlichen Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |

### Siehe auch

* Schnittstelle [IFormattedTextContainer](../iformattedtextcontainer)
* Schnittstelle [IGraphicalObject](../../aspose.slides/igraphicalobject)
* Schnittstelle [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->