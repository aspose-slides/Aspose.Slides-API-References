---
title: IChartData class
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/ichartdata/
---
## IChartData klass

Representerar data som används för att rita ett diagram.

IChartData-typen exponerar följande medlemmar:

## Egenskaper

| Egenskap | Beskrivning |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/sv/aspose.slides.charts/ichartdata/chart_data_workbook/) | Hämtar cellfabriken för att skapa celler som används för diagramserier eller -kategorier.<br/>            Skrivskyddad [`IChartDataWorkbook`](/slides/python-net/sv/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/sv/aspose.slides.charts/ichartdata/series/) | Hämtar serierna.<br/>            Skrivskyddad [`IChartSeriesCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/sv/aspose.slides.charts/ichartdata/series_groups/) | Hämtar grupperna av serier.<br/>            Skrivskyddad [`IChartSeriesGroupCollection`](/slides/python-net/sv/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories/) | Hämtar primärkategorierna (eller både primära och sekundära kategorier <br/>            om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är falsk).<br/>            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories/) | Om falskt så returnerar [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) egenskap None och data 
            i [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskapen används både för primära och sekundära serier.
            Om sant så används data i [`IChartData.secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories) egenskapen för sekundära serier och data 
            i [`IChartData.categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/categories) egenskapen används för primära serier.
            Läs/skriv **bool**. |
| [`secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/secondary_categories/) | Hämtar de sekundära kategorierna om [`IChartData.use_secondary_categories`](/slides/python-net/sv/aspose.slides.charts/ichartdata/use_secondary_categories) egenskap är sann.<br/>            Skrivskyddad [`IChartCategoryCollection`](/slides/python-net/sv/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/sv/aspose.slides.charts/ichartdata/data_source_type/) | Representerar datakällan för diagrammet |
| [`external_workbook_path`](/slides/python-net/sv/aspose.slides.charts/ichartdata/external_workbook_path/) | Representerar sökväg till extern arbetsbok om datakällan är extern, annars None |
| [`embedded_workbook_type`](/slides/python-net/sv/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Hämtar typen av den inbäddade arbetsboken.<br/>            Returnerar [`WorkbookType.NOT_DEFINED`](/slides/python-net/sv/aspose.slides.charts/workbooktype/NOT_DEFINED) om [`IChartData.data_source_type`](/slides/python-net/sv/aspose.slides.charts/ichartdata/data_source_type) är <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/sv/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Skrivskyddad [`WorkbookType`](/slides/python-net/sv/aspose.slides.charts/workbooktype). |

## Metoder

| Metod | Beskrivning |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från målarbetsboken. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Ställer in extern arbetsbok som datakälla för diagrammet. |
| [`read_workbook_stream(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Skriver den internt innehållna Excel-arbetsboken till ett minnesström. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Initierar den internt innehållna Excel-arbetsboken med användarspecificerat värde. |
| [`set_range(self, formula)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/set_range/#str) | Ställ in diagramdataintervall. Serier och kategorier kommer att uppdateras baserat på det nya intervallet.<br/>            Om antalet serier i dataintervallet är större än antalet serier i diagramdata så läggs ytterligare serier med samma typ<br/>            som den sista serien i den aktuella samlingen till i slutet av samlingen. |
| [`get_range(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/get_range/#) | Hämtar diagramdataintervall. |
| [`switch_row_column(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/switch_row_column/#) | Byt plats på data över axeln.<br/>            Data som plottas på X-axeln kommer att flyttas till Y-axeln och vice versa. |
| [`refresh_data(self)`](/slides/python-net/sv/aspose.slides.charts/ichartdata/refresh_data/#) | Uppdaterar diagramdata genom att läsa in den på nytt från källarbetsboken. |

### Se även
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)