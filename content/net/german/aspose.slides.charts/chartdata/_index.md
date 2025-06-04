---
title: ChartData
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt Daten dar, die für die Diagrammzeichnung verwendet werden.
type: docs
weight: 1230
url: /de/aspose.slides.charts/chartdata/
---

## ChartData-Klasse

Stellt Daten dar, die für die Diagrammzeichnung verwendet werden.

```csharp
public class ChartData : DomObject<Chart>, IChartData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Categories](../../aspose.slides.charts/chartdata/categories) { get; } | Gibt die primären Kategorien (oder sowohl primäre als auch sekundäre Kategorien zurück, wenn die [`UseSecondaryCategories`](./usesecondarycategories)-Eigenschaft false ist). Nur lesbar [`IChartCategoryCollection`](../ichartcategorycollection). |
| [ChartDataWorkbook](../../aspose.slides.charts/chartdata/chartdataworkbook) { get; } | Gibt die Zellenfabrik zurück, um Zellen zu erstellen, die für Diagrammserien oder -kategorien verwendet werden. Nur lesbar [`IChartDataWorkbook`](../ichartdataworkbook). |
| [DataSourceType](../../aspose.slides.charts/chartdata/datasourcetype) { get; } | Stellt den Pfad zur externen Arbeitsmappe dar, wenn eine externe Datenquelle vorhanden ist, andernfalls null |
| [ExternalWorkbookPath](../../aspose.slides.charts/chartdata/externalworkbookpath) { get; } | Stellt die Datenquelle des Diagramms dar |
| [SecondaryCategories](../../aspose.slides.charts/chartdata/secondarycategories) { get; } | Gibt die sekundären Kategorien zurück, wenn die [`UseSecondaryCategories`](./usesecondarycategories)-Eigenschaft true ist. Nur lesbar [`IChartCategoryCollection`](../ichartcategorycollection). |
| [Series](../../aspose.slides.charts/chartdata/series) { get; } | Gibt die Serien zurück. Nur lesbar [`IChartSeriesCollection`](../ichartseriescollection). |
| [SeriesGroups](../../aspose.slides.charts/chartdata/seriesgroups) { get; } | Gibt die Gruppen von Serien zurück. Nur lesbar [`IChartSeriesGroupCollection`](../ichartseriesgroupcollection). |
| [UseSecondaryCategories](../../aspose.slides.charts/chartdata/usesecondarycategories) { get; set; } | Wenn false, gibt die [`SecondaryCategories`](./secondarycategories)-Eigenschaft null zurück und die Daten in der [`Categories`](./categories)-Eigenschaft werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, werden die Daten in der [`SecondaryCategories`](./secondarycategories)-Eigenschaft für sekundäre Serien verwendet und die Daten in der [`Categories`](./categories)-Eigenschaft werden für primäre Serien verwendet. Lese-/schreibbare boolesche Eigenschaft. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetRange](../../aspose.slides.charts/chartdata/getrange)() | Gibt den Datenbereich des Diagramms zurück. |
| [ReadWorkbookStream](../../aspose.slides.charts/chartdata/readworkbookstream)() | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen speicherinternen Stream. |
| [SetExternalWorkbook](../../aspose.slides.charts/chartdata/setexternalworkbook#setexternalworkbook)(string) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. Die Diagrammdaten werden aus der Ziel-Arbeitsmappe aktualisiert. |
| [SetExternalWorkbook](../../aspose.slides.charts/chartdata/setexternalworkbook#setexternalworkbook_1)(string, bool) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. |
| [SetRange](../../aspose.slides.charts/chartdata/setrange)(string) | Setzt den Datenbereich des Diagramms. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, werden zusätzliche Serien vom selben Typ wie die letzte Serie in der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| [SwitchRowColumn](../../aspose.slides.charts/chartdata/switchrowcolumn)() | Tauscht die Daten über die Achse. Die Daten, die auf der X-Achse geplottet werden, werden zur Y-Achse und umgekehrt. |
| [WriteWorkbookStream](../../aspose.slides.charts/chartdata/writeworkbookstream)(MemoryStream) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit einem benutzerdefinierten Wert. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* class [Chart](../chart)
* interface [IChartData](../ichartdata)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)