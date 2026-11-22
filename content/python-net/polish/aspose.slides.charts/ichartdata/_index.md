---
title: IChartData class
second_title: Aspose.Slides dla Pythona poprzez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/
---
## IChartData klasa

Reprezentuje dane używane do wykreślania wykresu.

Typ IChartData udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/pl/aspose.slides.charts/ichartdata/chart_data_workbook/) | Zwraca fabrykę komórek służącą do tworzenia komórek używanych w seriach wykresu lub kategoriach.<br/>            Tylko do odczytu [`IChartDataWorkbook`](/slides/python-net/pl/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/pl/aspose.slides.charts/ichartdata/series/) | Zwraca serie.<br/>            Tylko do odczytu [`IChartSeriesCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/pl/aspose.slides.charts/ichartdata/series_groups/) | Zwraca grupy serii.<br/>            Tylko do odczytu [`IChartSeriesGroupCollection`](/slides/python-net/pl/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories/) | Zwraca podstawowe kategorie (lub zarówno podstawowe, jak i dodatkowe kategorie <br/>            jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest false).<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories/) | Jeśli false, to [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość zwraca None, a dane w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane zarówno dla podstawowych, jak i dodatkowych serii.<br/>            Jeśli true, to dane w [`IChartData.secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories) właściwość są używane dla dodatkowych serii, a dane w [`IChartData.categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/categories) właściwość są używane dla podstawowych serii.<br/>            Odczyt/zapis **bool**. |
| [`secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/secondary_categories/) | Zwraca dodatkowe kategorie, jeśli [`IChartData.use_secondary_categories`](/slides/python-net/pl/aspose.slides.charts/ichartdata/use_secondary_categories) właściwość jest true.<br/>            Tylko do odczytu [`IChartCategoryCollection`](/slides/python-net/pl/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/data_source_type/) | Reprezentuje źródło danych wykresu |
| [`external_workbook_path`](/slides/python-net/pl/aspose.slides.charts/ichartdata/external_workbook_path/) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie None |
| [`embedded_workbook_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Zwraca typ osadzonego skoroszytu.<br/>            Zwraca [`WorkbookType.NOT_DEFINED`](/slides/python-net/pl/aspose.slides.charts/workbooktype/NOT_DEFINED) jeśli [`IChartData.data_source_type`](/slides/python-net/pl/aspose.slides.charts/ichartdata/data_source_type) jest [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/pl/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Tylko do odczytu [`WorkbookType`](/slides/python-net/pl/aspose.slides.charts/workbooktype). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [`read_workbook_stream(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika. |
| [`set_range(self, formula)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/set_range/#str) | Ustawia zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych.<br/>            Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, zostaną dodane dodatkowe serie tego samego typu co ostatnia seria w bieżącej kolekcji, na końcu kolekcji. |
| [`get_range(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/get_range/#) | Zwraca zakres danych wykresu. |
| [`switch_row_column(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/switch_row_column/#) | Zamienia dane pomiędzy osiami.<br/>            Dane wykreślone na osi X zostaną przeniesione na oś Y i odwrotnie. |
| [`refresh_data(self)`](/slides/python-net/pl/aspose.slides.charts/ichartdata/refresh_data/#) | Odświeża dane wykresu, ponownie ładując je ze źródłowego skoroszytu. |


### Zobacz także
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)