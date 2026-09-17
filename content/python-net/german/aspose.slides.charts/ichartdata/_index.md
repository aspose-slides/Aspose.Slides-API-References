---
title: IChartData class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdata/
---
## IChartData Klasse

Stellt die für die Diagrammerstellung verwendeten Daten dar.

Der Typ IChartData stellt die folgenden Member bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/de/aspose.slides.charts/ichartdata/chart_data_workbook/) | Gibt die Zellenfabrik zurück, um Zellen zu erstellen, die für Diagrammserien oder Kategorien verwendet werden.<br/>            Nur-Lesen [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/de/aspose.slides.charts/ichartdata/series/) | Gibt die Serien zurück.<br/>            Nur-Lesen [`IChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/de/aspose.slides.charts/ichartdata/series_groups/) | Gibt die Gruppen von Serien zurück.<br/>            Nur-Lesen [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories/) | Gibt die primären Kategorien zurück (oder sowohl primäre als auch sekundäre Kategorien <br/>            wenn die Eigenschaft [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) false ist).<br/>            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories/) | Wenn false, gibt die Eigenschaft [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) None zurück und Daten <br/>            in der Eigenschaft [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) werden sowohl für primäre als auch für sekundäre Serien verwendet.<br/>            Wenn true, werden Daten in der Eigenschaft [`IChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories) für sekundäre Serien verwendet und Daten <br/>            in der Eigenschaft [`IChartData.categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/categories) für primäre Serien verwendet.<br/>            Lesen/Schreiben **bool**. |
| [`secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/secondary_categories/) | Gibt die sekundären Kategorien zurück, wenn die Eigenschaft [`IChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/ichartdata/use_secondary_categories) true ist.<br/>            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/data_source_type/) | Stellt die Datenquelle des Diagramms dar. |
| [`external_workbook_path`](/slides/python-net/de/aspose.slides.charts/ichartdata/external_workbook_path/) | Stellt den Pfad zu einer externen Arbeitsmappe dar, wenn die Datenquelle extern ist, sonst None. |
| [`embedded_workbook_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Gibt den Typ der eingebetteten Arbeitsmappe zurück.<br/>            Gibt [`WorkbookType.NOT_DEFINED`](/slides/python-net/de/aspose.slides.charts/workbooktype/NOT_DEFINED) zurück, wenn [`IChartData.data_source_type`](/slides/python-net/de/aspose.slides.charts/ichartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/de/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ist.<br/>            Nur-Lesen [`WorkbookType`](/slides/python-net/de/aspose.slides.charts/workbooktype). |

## Methoden

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Legt die externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [`read_workbook_stream(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Speicherstrom. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/de/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit einem vom Benutzer angegebenen Wert. |
| [`set_range(self, formula)`](/slides/python-net/de/aspose.slides.charts/ichartdata/set_range/#str) | Setzt den Diagrammdatenbereich. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.<br/>            Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, werden zusätzliche Serien mit demselben Typ<br/>            wie die letzte Serie in der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| [`get_range(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/get_range/#) | Gibt den Diagrammdatenbereich zurück. |
| [`switch_row_column(self)`](/slides/python-net/de/aspose.slides.charts/ichartdata/switch_row_column/#) | Vertauscht die Daten über die Achse.<br/>            Daten, die auf der X-Achse dargestellt werden, werden auf die Y-Achse verschoben und umgekehrt. |


### Siehe Auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)