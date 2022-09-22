---
title: IChart
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt ein grafisches Diagramm auf einer Folie dar.
type: docs
weight: 1620
url: /de/net/aspose.slides.charts/ichart/
---
## IChart interface

Stellt ein grafisches Diagramm auf einer Folie dar.

```csharp
public interface IChart : IFormattedTextContainer, IGraphicalObject, IOverrideThemeable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIFormattedTextContainer](../../aspose.slides.charts/ichart/asiformattedtextcontainer) { get; } | Ermöglicht das Abrufen der Basis-IFormattedTextContainer-Schnittstelle. Schreibgeschützt[`IFormattedTextContainer`](../iformattedtextcontainer) . |
| [AsIGraphicalObject](../../aspose.slides.charts/ichart/asigraphicalobject) { get; } | Ermöglicht das Abrufen der IGraphicalObject-Basisschnittstelle. Schreibgeschützt[`IGraphicalObject`](../../aspose.slides/igraphicalobject) . |
| [AsIOverrideThemeable](../../aspose.slides.charts/ichart/asioverridethemeable) { get; } | Gibt die IOverrideThemeable-Schnittstelle zurück. Schreibgeschützt[`IOverrideThemeable`](../../aspose.slides.theme/ioverridethemeable) . |
| [Axes](../../aspose.slides.charts/ichart/axes) { get; } | Bietet Zugriff auf Diagrammachsen. Schreibgeschützt[`IAxesManager`](../iaxesmanager) . |
| [BackWall](../../aspose.slides.charts/ichart/backwall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Rückwand eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [ChartData](../../aspose.slides.charts/ichart/chartdata) { get; } | Gibt Informationen über die verknüpften oder eingebetteten Daten zurück, die einem Diagramm zugeordnet sind. Schreibgeschützt[`IChartData`](../ichartdata) . |
| [ChartDataTable](../../aspose.slides.charts/ichart/chartdatatable) { get; } | Gibt eine Datentabelle eines Diagramms zurück. Schreibgeschützt[`IDataTable`](../idatatable) . |
| [ChartTitle](../../aspose.slides.charts/ichart/charttitle) { get; } | Gibt einen Diagrammtitel zurück oder legt ihn fest. Schreibgeschützt[`IChartTitle`](../icharttitle) . |
| [DisplayBlanksAs](../../aspose.slides.charts/ichart/displayblanksas) { get; set; } | Gibt zurück oder legt fest, wie leere Zellen in einem Diagramm dargestellt werden. Lesen/Schreiben[`DisplayBlanksAsType`](../displayblanksastype) . |
| [Floor](../../aspose.slides.charts/ichart/floor) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format des Bodens eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [HasDataTable](../../aspose.slides.charts/ichart/hasdatatable) { get; set; } | Bestimmt, ob ein Diagramm eine Datentabelle hat. Lesen/SchreibenBoolean . |
| [HasLegend](../../aspose.slides.charts/ichart/haslegend) { get; set; } | Bestimmt, ob ein Diagramm eine Legende hat. Lesen/SchreibenBoolean . |
| [HasRoundedCorners](../../aspose.slides.charts/ichart/hasroundedcorners) { get; set; } | Gibt an, dass der Diagrammbereich abgerundete Ecken haben soll. Lesen/SchreibenBoolean . |
| [HasTitle](../../aspose.slides.charts/ichart/hastitle) { get; set; } | Bestimmt, ob ein Diagramm einen sichtbaren Titel hat. Lesen/SchreibenBoolean . |
| [Legend](../../aspose.slides.charts/ichart/legend) { get; } | Gibt eine Legende für ein Diagramm zurück oder legt sie fest. Schreibgeschützt[`ILegend`](../ilegend) . |
| [PlotArea](../../aspose.slides.charts/ichart/plotarea) { get; } | Repräsentiert den Plotbereich eines Diagramms. Schreibgeschützt[`IChartPlotArea`](../ichartplotarea) . |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/ichart/plotvisiblecellsonly) { get; set; } | Legt fest, ob nur die sichtbaren Zellen gezeichnet werden. False, um sowohl sichtbare als auch verborgene Zellen zu zeichnen. Lesen/SchreibenBoolean . |
| [Rotation3D](../../aspose.slides.charts/ichart/rotation3d) { get; } | Gibt eine 3D-Rotation eines Diagramms zurück. Schreibgeschützt[`IRotation3D`](../irotation3d) . |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/ichart/showdatalabelsovermaximum) { get; set; } | Gibt an, dass Datenbeschriftungen über dem Maximum des Diagramms angezeigt werden sollen. Lesen/SchreibenBoolean . |
| [SideWall](../../aspose.slides.charts/ichart/sidewall) { get; } | Gibt ein Objekt zurück, das es ermöglicht, das Format der Seitenwand eines 3D-Diagramms zu ändern. Schreibgeschützt[`IChartWall`](../ichartwall) . |
| [Style](../../aspose.slides.charts/ichart/style) { get; set; } | Gibt den Diagrammstil zurück oder legt ihn fest. Lesen/Schreiben[`StyleType`](../styletype) . |
| [Type](../../aspose.slides.charts/ichart/type) { get; set; } | Gibt den Diagrammtyp zurück oder legt ihn fest. Lesen/Schreiben[`ChartType`](../charttype) . |
| [UserShapes](../../aspose.slides.charts/ichart/usershapes) { get; } | Geben Sie die oben auf dem Diagramm gezeichneten Formen an. Schreibgeschützt[`IGroupShape`](../../aspose.slides/igroupshape) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ValidateChartLayout](../../aspose.slides.charts/ichart/validatechartlayout)() | Berechnet tatsächliche Werte von Diagrammelementen. Tatsächliche Werte umfassen die Position von Elementen, die die IActualLayout-Schnittstelle (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) und tatsächliche Achsenwerte (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMajorUnit, IAxis.ActualMajorUnit, IAxis.ActualMaxValue, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |

### Siehe auch

* interface [IFormattedTextContainer](../iformattedtextcontainer)
* interface [IGraphicalObject](../../aspose.slides/igraphicalobject)
* interface [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
