---
title: ChartData class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/chartdata/
---
## ChartData Klasse

Stellt Daten bereit, die für die Diagrammerstellung verwendet werden.

Der ChartData-Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/de/aspose.slides.charts/chartdata/chart_data_workbook/) | Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammreihen oder -kategorien verwendet werden.<br/>            Nur-Lesen [`IChartDataWorkbook`](/slides/python-net/de/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/de/aspose.slides.charts/chartdata/series/) | Ruft die Reihen ab.<br/>            Nur-Lesen [`IChartSeriesCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/de/aspose.slides.charts/chartdata/series_groups/) | Ruft die Gruppen von Reihen ab.<br/>            Nur-Lesen [`IChartSeriesGroupCollection`](/slides/python-net/de/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories/) | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien <br/>            wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories)-Eigenschaft false ist).<br/>            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories/) | Wenn false, gibt die [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories)-Eigenschaft None zurück und Daten <br/>            in der [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories)-Eigenschaft werden sowohl für primäre als auch für sekundäre Reihen verwendet.<br/>            Wenn true, werden Daten in der [`ChartData.secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories)-Eigenschaft für sekundäre Reihen und Daten <br/>            in der [`ChartData.categories`](/slides/python-net/de/aspose.slides.charts/chartdata/categories)-Eigenschaft für primäre Reihen verwendet.<br/>            Lesen/Schreiben **bool**. |
| [`secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/secondary_categories/) | Ruft die sekundären Kategorien ab, wenn die [`ChartData.use_secondary_categories`](/slides/python-net/de/aspose.slides.charts/chartdata/use_secondary_categories)-Eigenschaft true ist.<br/>            Nur-Lesen [`IChartCategoryCollection`](/slides/python-net/de/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/de/aspose.slides.charts/chartdata/data_source_type/) | Stellt den Pfad zur externen Arbeitsmappe dar, wenn externe Datenquelle, sonst None |
| [`external_workbook_path`](/slides/python-net/de/aspose.slides.charts/chartdata/external_workbook_path/) | Stellt die Datenquelle des Diagramms dar |
| [`embedded_workbook_type`](/slides/python-net/de/aspose.slides.charts/chartdata/embedded_workbook_type/) | Ruft den Typ der eingebetteten Arbeitsmappe ab.<br/>            Gibt [`WorkbookType.NOT_DEFINED`](/slides/python-net/de/aspose.slides.charts/workbooktype/NOT_DEFINED) zurück, wenn [`ChartData.data_source_type`](/slides/python-net/de/aspose.slides.charts/chartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/de/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) ist.<br/>            Nur-Lesen [`WorkbookType`](/slides/python-net/de/aspose.slides.charts/workbooktype). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_external_workbook/#str) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. |
| [`read_workbook_stream(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/read_workbook_stream/#) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Stream. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/de/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit vom Benutzer angegebenem Wert. |
| [`get_range(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/get_range/#) | Ruft den Diagrammdatenbereich ab. |
| [`set_range(self, formula)`](/slides/python-net/de/aspose.slides.charts/chartdata/set_range/#str) | Setzt den Diagrammdatenbereich. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert.<br/>            Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen in den Diagrammdaten, dann werden zusätzliche Reihen mit demselben Typ<br/>            wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| [`switch_row_column(self)`](/slides/python-net/de/aspose.slides.charts/chartdata/switch_row_column/#) | Vertauscht die Daten über die Achse.<br/>            Daten, die auf der X-Achse diagrammiert werden, werden auf die Y-Achse verschoben und umgekehrt. |

### Siehe auch
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)