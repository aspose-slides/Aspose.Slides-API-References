---
title: IChartData
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt Daten dar die zum Zeichnen von Diagrammen verwendet werden.
type: docs
weight: 1680
url: /de/net/aspose.slides.charts/ichartdata/
---
## IChartData interface

Stellt Daten dar, die zum Zeichnen von Diagrammen verwendet werden.

```csharp
public interface IChartData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Categories](../../aspose.slides.charts/ichartdata/categories) { get; } | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien , wenn[`UseSecondaryCategories`](./usesecondarycategories) Eigenschaft ist falsch). Schreibgeschützt[`IChartCategoryCollection`](../ichartcategorycollection) . |
| [ChartDataWorkbook](../../aspose.slides.charts/ichartdata/chartdataworkbook) { get; } | Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammserien oder Kategorien verwendet werden. Schreibgeschützt[`IChartDataWorkbook`](../ichartdataworkbook) . |
| [DataSourceType](../../aspose.slides.charts/ichartdata/datasourcetype) { get; } | Stellt die Datenquelle des Diagramms dar |
| [ExternalWorkbookPath](../../aspose.slides.charts/ichartdata/externalworkbookpath) { get; } | Stellt den externen Arbeitsmappenpfad dar, wenn die Datenquelle extern ist, andernfalls null |
| [SecondaryCategories](../../aspose.slides.charts/ichartdata/secondarycategories) { get; } | Ruft die sekundären Kategorien ab, wenn[`UseSecondaryCategories`](./usesecondarycategories) Eigenschaft ist wahr. Schreibgeschützt[`IChartCategoryCollection`](../ichartcategorycollection) . |
| [Series](../../aspose.slides.charts/ichartdata/series) { get; } | Ruft die Serie ab. Schreibgeschützt[`IChartSeriesCollection`](../ichartseriescollection) . |
| [SeriesGroups](../../aspose.slides.charts/ichartdata/seriesgroups) { get; } | Ruft die Gruppen von Serien ab. Schreibgeschützt[`IChartSeriesGroupCollection`](../ichartseriesgroupcollection) . |
| [UseSecondaryCategories](../../aspose.slides.charts/ichartdata/usesecondarycategories) { get; set; } | Wenn dann falsch[`SecondaryCategories`](./secondarycategories) Eigenschaft gibt null zurück und Daten in[`Categories`](./categories) Die Eigenschaft wird sowohl für primäre als auch für sekundäre Serien verwendet. Wenn wahr, dann Dateneingang[`SecondaryCategories`](./secondarycategories) Die Eigenschaft wird für sekundäre Serien und Daten in verwendet[`Categories`](./categories)Eigenschaft wird für primäre Serien verwendet. Lesen/SchreibenBoolean . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetRange](../../aspose.slides.charts/ichartdata/getrange)() | Ruft den Diagrammdatenbereich ab. |
| [ReadWorkbookStream](../../aspose.slides.charts/ichartdata/readworkbookstream)() | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream. |
| [SetExternalWorkbook](../../aspose.slides.charts/ichartdata/setexternalworkbook#setexternalworkbook)(string) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert. |
| [SetExternalWorkbook](../../aspose.slides.charts/ichartdata/setexternalworkbook#setexternalworkbook_1)(string, bool) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [SetRange](../../aspose.slides.charts/ichartdata/setrange)(string) | Stellen Sie den Diagrammdatenbereich ein. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, werden zusätzliche Serien mit demselben Typ als letzte Serie in der aktuellen Sammlung am Ende hinzugefügt der Sammlung. |
| [SwitchRowColumn](../../aspose.slides.charts/ichartdata/switchrowcolumn)() | Tauschen Sie die Daten über der Achse aus. Daten, die auf der X-Achse dargestellt werden, werden auf die Y-Achse verschoben und umgekehrt. |
| [WriteWorkbookStream](../../aspose.slides.charts/ichartdata/writeworkbookstream)(MemoryStream) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit einem benutzerdefinierten Wert. |

### Siehe auch

* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->