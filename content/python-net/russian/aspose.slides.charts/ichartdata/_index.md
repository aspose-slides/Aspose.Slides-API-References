---
title: IChartData class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdata/
---
## IChartData класс

Представляет данные, используемые для построения диаграммы.

Тип IChartData раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ru/aspose.slides.charts/ichartdata/chart_data_workbook/) | Получает фабрику ячеек для создания ячеек, используемых в рядах или категориях диаграммы.<br/>            Только для чтения [`IChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ru/aspose.slides.charts/ichartdata/series/) | Получает ряды.<br/>            Только для чтения [`IChartSeriesCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ru/aspose.slides.charts/ichartdata/series_groups/) | Получает группы рядов.<br/>            Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories/) | Получает основные категории (или как основные, так и вторичные категории <br/>            если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) ложно).<br/>            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories/) | Если ложно, то свойство [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) возвращает None и данные <br/>            в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются как для основных, так и для вторичных рядов.<br/>            Если истинно, то данные в свойстве [`IChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories) используются для вторичных рядов, а данные <br/>            в свойстве [`IChartData.categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/categories) используются для основных рядов.<br/>            Чтение/запись **bool**. |
| [`secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/secondary_categories/) | Получает вторичные категории, если свойство [`IChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/ichartdata/use_secondary_categories) истинно.<br/>            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ru/aspose.slides.charts/ichartdata/data_source_type/) | Представляет источник данных диаграммы |
| [`external_workbook_path`](/slides/python-net/ru/aspose.slides.charts/ichartdata/external_workbook_path/) | Представляет путь к внешней книге, если источник данных внешнее, иначе None |
| [`embedded_workbook_type`](/slides/python-net/ru/aspose.slides.charts/ichartdata/embedded_workbook_type/) | Получает тип встроенной книги.<br/>            Возвращает [`WorkbookType.NOT_DEFINED`](/slides/python-net/ru/aspose.slides.charts/workbooktype/NOT_DEFINED), если [`IChartData.data_source_type`](/slides/python-net/ru/aspose.slides.charts/ichartdata/data_source_type) <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ru/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Только для чтения [`WorkbookType`](/slides/python-net/ru/aspose.slides.charts/workbooktype). |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/set_external_workbook/#str) | Устанавливает внешнюю книгу как источник данных для диаграммы. Данные диаграммы будут обновлены из целевой книги. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [`read_workbook_stream(self)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/read_workbook_stream/#) | Записывает внутренне содержащуюся книгу Excel в поток в памяти. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | Инициализирует внутренне содержащуюся книгу Excel значением, указанным пользователем. |
| [`set_range(self, formula)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/set_range/#str) | Устанавливает диапазон данных диаграммы. Ряды и категории будут обновлены в соответствии с новым диапазоном данных.<br/>            Если количество рядов в диапазоне данных превышает количество рядов в данных диаграммы, то дополнительные ряды с тем же типом<br/>            что и последний ряд текущей коллекции, будут добавлены в конец коллекции. |
| [`get_range(self)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/get_range/#) | Получает диапазон данных диаграммы. |
| [`switch_row_column(self)`](/slides/python-net/ru/aspose.slides.charts/ichartdata/switch_row_column/#) | Меняет местами данные по оси.<br/>            Данные, построенные по оси X, переместятся на ось Y и наоборот. |


### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)