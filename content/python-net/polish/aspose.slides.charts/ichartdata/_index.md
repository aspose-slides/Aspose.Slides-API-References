---
title: IChartData class
second_title: Aspose.Slides dla Pythona przez .NET API Referencję
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/
---
## IChartData klasa

Represents data used for a chart plotting.

The IChartData type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pl/aspose.slides.charts/ichartdata/chart_data_workbook/) | Pobiera fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach.<br/>            Tylko do odczytu [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pl/aspose.slides.charts/ichartdata/series/) | Pobiera serie.<br/>            Tylko do odczytu [`IChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pl/aspose.slides.charts/ichartdata/series_groups/) | Pobiera grupy serii.<br/>            Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories/) | Pobiera główne kategorie (lub zarówno główne, jak i drugorzędne kategorie <br/>            jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) property jest fałsz).<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories/) | Jeśli fałsz, to [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) property zwraca None, a dane <br/>            w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) property są używane zarówno dla serii głównych, jak i drugorzędnych.<br/>            Jeśli prawda, to dane w [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) property są używane dla serii drugorzędnych, a dane <br/>            w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) property są używane dla serii głównych.<br/>            Do odczytu i zapisu **bool**. |
| [`secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories/) | Pobiera drugorzędne kategorie, jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) property jest prawda.<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/data_source_type/) | Reprezentuje źródło danych wykresu |
| [`external_workbook_path`](/slides/python-net/pl/aspose.slides.charts/ichartdata/external_workbook_path/) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, None w przeciwnym razie |
| [`embedded_workbook_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Pobiera typ osadzonego skoroszytu.<br/>            Zwraca [`WorkbookType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides.charts/workbooktype/NOT_DEFINED) jeśli [`IChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/data_source_type) jest <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Tylko do odczytu [`WorkbookType`](/slides/python-net/pl/aspose.slides.charts/workbooktype). |

## Metody

| Method | Description |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [`read_workbook_stream(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością określoną przez użytkownika. |
| [`set_range(self, formula)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_range/#str) | Ustaw zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych.<br/>            Jeśli liczba serii w zakresie danych jest większa od liczby serii w danych wykresu, wtedy zostaną dodane dodatkowe serie o tym samym typie<br/>            co ostatnia seria w bieżącej kolekcji, dodane na końcu kolekcji. |
| [`get_range(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/get_range/#) | Pobiera zakres danych wykresu. |
| [`switch_row_column(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/switch_row_column/#) | Zamienia dane na osi.<br/>            Dane wykreślone na osi X zostaną przeniesione na oś Y i odwrotnie. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)