---
title: ChartData class
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/
---
## ChartData klasa

Represents data used for a chart plotting.

Typ ChartData udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pl/aspose.slides.charts/chartdata/chart_data_workbook/) | Pobiera fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach.<br/> Tylko do odczytu [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pl/aspose.slides.charts/chartdata/series/) | Pobiera serie.<br/> Tylko do odczytu [`IChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pl/aspose.slides.charts/chartdata/series_groups/) | Pobiera grupy serii.<br/> Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories/) | Pobiera podstawowe kategorie (lub zarówno podstawowe jak i drugorzędne kategorie <br/> jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is false).<br/> Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories/) | Jeśli false, to [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) property return None and data <br/> in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used both for primary and secondary series.<br/> Jeśli true, to data in [`ChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories) property is used for secondary series and data <br/> in [`ChartData.categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/categories) property is used for primary series.<br/> Odczyt/zapis **bool**. |
| [`secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/secondary_categories/) | Pobiera drugorzędne kategorie, jeśli [`ChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/chartdata/use_secondary_categories) property is true.<br/> Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/data_source_type/) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli zastosowano zewnętrzne źródło danych, w przeciwnym razie None. |
| [`external_workbook_path`](/slides/python-net/pl/aspose.slides.charts/chartdata/external_workbook_path/) | Reprezentuje źródło danych wykresu. |
| [`embedded_workbook_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/embedded_workbook_type/) | Pobiera typ osadzonego skoroszytu.<br/> Zwraca [`WorkbookType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides.charts/workbooktype/NOT_DEFINED) jeśli [`ChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/chartdata/data_source_type) jest <br/> [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/> Tylko do odczytu [`WorkbookType`](/slides/python-net/pl/aspose.slides.charts/workbooktype). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_external_workbook/#str) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [`read_workbook_stream(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/read_workbook_stream/#) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pl/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością określoną przez użytkownika. |
| [`get_range(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/get_range/#) | Pobiera zakres danych wykresu. |
| [`set_range(self, formula)`](/slides/python-net/pl/aspose.slides.charts/chartdata/set_range/#str) | Ustawia zakres danych wykresu. Seria i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych.<br/> Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, zostaną dodane dodatkowe serie o tym samym typie<br/> co ostatnia seria w bieżącej kolekcji, na końcu kolekcji. |
| [`refresh_data(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/refresh_data/#) | Odświeża dane wykresu, ponownie ładując je ze źródłowego skoroszytu. |
| [`switch_row_column(self)`](/slides/python-net/pl/aspose.slides.charts/chartdata/switch_row_column/#) | Zamienia dane pomiędzy osiami.<br/> Dane wykreślane na osi X zostaną przeniesione na oś Y i odwrotnie. |

### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)