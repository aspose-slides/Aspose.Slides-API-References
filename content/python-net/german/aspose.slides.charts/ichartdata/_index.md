---
title: IChartData class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/
---
## IChartData Klasse

Stellt Daten dar, die für die Diagrammerstellung verwendet werden.

Der Typ IChartData stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/de/aspose.slides.charts/ichartdata/chart_data_workbook/) | Liefert die Zellenfabrik zum Erstellen von Zellen, die für Diagrammreihen oder -kategorien verwendet werden.<br/>            Schreibgeschützt [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/de/aspose.slides.charts/ichartdata/series/) | Liefert die Serien.<br/>            Schreibgeschützt [`IChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/de/aspose.slides.charts/ichartdata/series_groups/) | Liefert die Gruppen von Serien.<br/>            Schreibgeschützt [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories/) | Liefert die primären Kategorien (oder sowohl primäre als auch sekundäre Kategorien <br/>            wenn die Eigenschaft [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) false ist).<br/>            Schreibgeschützt [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories/) | Wenn false, dann gibt die Eigenschaft [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) None zurück und Daten <br/>            in der Eigenschaft [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) werden sowohl für primäre als auch für sekundäre Serien verwendet.<br/>            Wenn true, dann werden Daten in der Eigenschaft [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) für sekundäre Serien und Daten <br/>            in der Eigenschaft [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) für primäre Serien verwendet.<br/>            Lese/Schreib **bool**. |
| [`secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories/) | Liefert die sekundären Kategorien, wenn die Eigenschaft [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) true ist.<br/>            Schreibgeschützt [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/data_source_type/) | Stellt die Datenquelle des Diagramms dar |
| [`external_workbook_path`](/slides/python-net/de/aspose.slides.charts/ichartdata/external_workbook_path/) | Stellt den Pfad zu einer externen Arbeitsmappe dar, wenn die Datenquelle extern ist, andernfalls None |
| [`embedded_workbook_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Liefert den Typ der eingebetteten Arbeitsmappe.<br/>            Gibt [`WorkbookType.NOT_DEFINED`](/slides/python-net/de/aspose.slides.charts/workbooktype/NOT_DEFINED) zurück, wenn [`IChartData.data_source_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/de/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ist.<br/>            Schreibgeschützt [`WorkbookType`](/slides/python-net/de/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [`read_workbook_stream(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/de/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit einem vom Benutzer angegebenen Wert. |
| [`set_range(self, formula)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_range/#str) | Setzt den Datenbereich des Diagramms. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.<br/>            Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen in den Diagrammdaten, werden zusätzliche Reihen mit dem gleichen Typ<br/>            wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| [`get_range(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/get_range/#) | Liefert den Datenbereich des Diagramms. |
| [`switch_row_column(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/switch_row_column/#) | Vertauscht die Daten über die Achse.<br/>            Daten, die auf der X-Achse dargestellt werden, wechseln zur Y-Achse und umgekehrt. |
| [`refresh_data(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/refresh_data/#) | Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden. |

### Siehe Auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)