---
title: ChartData class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/
---
## ChartData Klasse

Stellt Daten bereit, die für die Diagrammerstellung verwendet werden.

Der ChartData-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/de/aspose.slides.charts/chartdata/chart_data_workbook/) | Gibt die Zellenfabrik zurück, um Zellen zu erstellen, die für Diagrammreihen oder -kategorien verwendet werden.<br/>Nur lesbar [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/de/aspose.slides.charts/chartdata/series/) | Gibt die Reihen zurück.<br/>Nur lesbar [`IChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/de/aspose.slides.charts/chartdata/series_groups/) | Gibt die Gruppen von Reihen zurück.<br/>Nur lesbar [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories/) | Gibt die primären Kategorien zurück (oder sowohl primäre als auch sekundäre Kategorien,<br/>wenn die Eigenschaft [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) false ist).<br/>Nur lesbar [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories/) | Wenn false, gibt die Eigenschaft [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) None zurück und Daten<br/>in der Eigenschaft [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) werden sowohl für primäre als auch für sekundäre Reihen verwendet.<br/>Wenn true, werden Daten in der Eigenschaft [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories) für sekundäre Reihen und Daten<br/>in der Eigenschaft [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories) für primäre Reihen verwendet.<br/>Lese/Schreib **bool**. |
| [`secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories/) | Gibt die sekundären Kategorien zurück, wenn die Eigenschaft [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories) true ist.<br/>Nur lesbar [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/chartdata/data_source_type/) | Stellt den Pfad zur externen Arbeitsmappe dar, falls eine externe Datenquelle verwendet wird, sonst None. |
| [`external_workbook_path`](/slides/python-net/de/aspose.slides.charts/chartdata/external_workbook_path/) | Stellt die Datenquelle des Diagramms dar |
| [`embedded_workbook_type`](/slides/python-net/de/aspose.slides.charts/chartdata/embedded_workbook_type/) | Gibt den Typ der eingebetteten Arbeitsmappe zurück.<br/>Gibt [`WorkbookType.NOT_DEFINED`](/slides/python-net/de/aspose.slides.charts/workbooktype/NOT_DEFINED) zurück, wenn [`ChartData.data_source_type`](/slides/python-net/de/aspose.slides.charts/chartdata/data_source_type)<br/>[`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/de/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ist.<br/>Nur lesbar [`WorkbookType`](/slides/python-net/de/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_external_workbook/#str) | Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [`read_workbook_stream(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/read_workbook_stream/#) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/de/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit einem vom Benutzer angegebenen Wert. |
| [`get_range(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/get_range/#) | Gibt den Diagrammdatenbereich zurück. |
| [`set_range(self, formula)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_range/#str) | Legt den Diagrammdatenbereich fest. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.<br/>Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen in den Diagrammdaten, werden zusätzliche Reihen mit demselben Typ<br/>wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| [`refresh_data(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/refresh_data/#) | Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden. |
| [`switch_row_column(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/switch_row_column/#) | Vertauscht die Daten über die Achsen.<br/>Daten, die auf der X-Achse dargestellt werden, werden auf die Y-Achse verschoben und umgekehrt. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)