---
title: ChartData class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/chartdata/
---

## ChartData klass

Representerar data som används för att rita ett diagram.

The ChartData type exposes the following members:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/sv/aspose.slides.charts/chartdata/chart_data_workbook/) | Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier.<br/>            Skrivskyddad [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/sv/aspose.slides.charts/chartdata/series/) | Hämtar serierna.<br/>            Skrivskyddad [`IChartSeriesCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/sv/aspose.slides.charts/chartdata/series_groups/) | Hämtar grupper av serier.<br/>            Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories/) | Hämtar de primära kategorierna (eller både primära och sekundära kategorier <br/>            om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories)-egenskapen är falsk).<br/>            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories/) | Om falskt returnerar [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories)-egenskap None och data i [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories)-egenskapen används både för primära och sekundära serier.<br/>            Om sant används data i [`ChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories)-egenskapen för sekundära serier och data i [`ChartData.categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/categories)-egenskapen för primära serier.<br/>            Läs/skriv **bool**. |
| [`secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/secondary_categories/) | Hämtar de sekundära kategorierna om [`ChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/chartdata/use_secondary_categories)-egenskapen är sann.<br/>            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/sv/aspose.slides.charts/chartdata/data_source_type/) | Representerar extern arbetsboksökväg om extern datakälla, annars None |
| [`external_workbook_path`](/slides/python-net/sv/aspose.slides.charts/chartdata/external_workbook_path/) | Representerar diagrammets datakälla |
| [`embedded_workbook_type`](/slides/python-net/sv/aspose.slides.charts/chartdata/embedded_workbook_type/) | Hämtar typen av den inbäddade arbetsboken.<br/>            Returnerar [`WorkbookType.NOT_DEFINED`](/slides/python-net/sv/aspose.slides.charts/workbooktype/NOT_DEFINED) om [`ChartData.data_source_type`](/slides/python-net/sv/aspose.slides.charts/chartdata/data_source_type) är <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/sv/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Skrivskyddad [`WorkbookType`](/slides/python-net/sv/aspose.slides.charts/workbooktype). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/sv/aspose.slides.charts/chartdata/set_external_workbook/#str) | Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från målarbetsboken. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/sv/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Ställer in extern arbetsbok som datakälla för diagrammet. |
| [`read_workbook_stream(self)`](/slides/python-net/sv/aspose.slides.charts/chartdata/read_workbook_stream/#) | Skriver den internt innehållna Excel-arbetsboken till en ström. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/sv/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Initierar den internt innehållna Excel-arbetsboken med ett användarspecificerat värde. |
| [`get_range(self)`](/slides/python-net/sv/aspose.slides.charts/chartdata/get_range/#) | Hämtar diagrammets dataintervall. |
| [`set_range(self, formula)`](/slides/python-net/sv/aspose.slides.charts/chartdata/set_range/#str) | Ställ in diagrammets dataintervall. Serier och kategorier kommer att uppdateras baserat på det nya dataintervallet.<br/>            Om antalet serier i dataintervallet är större än antalet serier i diagramdata läggs ytterligare serier med samma typ<br/>            som den sista serien i den aktuella samlingen till i slutet av samlingen. |
| [`switch_row_column(self)`](/slides/python-net/sv/aspose.slides.charts/chartdata/switch_row_column/#) | Byt data över axeln.<br/>            Data som plottas på X-axeln flyttas till Y-axeln och tvärtom. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)