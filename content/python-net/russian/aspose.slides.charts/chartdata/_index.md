---
title: ChartData class
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdata/
---
## ChartData класс

Представляет данные, используемые для построения диаграммы.

Тип ChartData предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ru/aspose.slides.charts/chartdata/chart_data_workbook/) | Получает фабрику ячеек для создания ячеек, используемых в рядах или категориях диаграммы.<br/>            Только для чтения [`IChartDataWorkbook`](/slides/python-net/ru/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ru/aspose.slides.charts/chartdata/series/) | Получает серии.<br/>            Только для чтения [`IChartSeriesCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ru/aspose.slides.charts/chartdata/series_groups/) | Получает группы рядов.<br/>            Только для чтения [`IChartSeriesGroupCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories/) | Получает основные категории (или как основные, так и вторичные категории <br/>            если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) ложно).<br/>            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories/) | Если ложно, то свойство [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) возвращает None, а данные <br/>            в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются как для основных, так и для вторичных рядов.<br/>            Если истинно, то данные в свойстве [`ChartData.secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories) используются для вторичных рядов, а данные <br/>            в свойстве [`ChartData.categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/categories) используются для основных рядов.<br/>            Чтение/запись **bool**. |
| [`secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/secondary_categories/) | Получает вторичные категории, если свойство [`ChartData.use_secondary_categories`](/slides/python-net/ru/aspose.slides.charts/chartdata/use_secondary_categories) истинно.<br/>            Только для чтения [`IChartCategoryCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ru/aspose.slides.charts/chartdata/data_source_type/) | Представляет путь к внешней рабочей книге, если внешний источник данных, иначе None |
| [`external_workbook_path`](/slides/python-net/ru/aspose.slides.charts/chartdata/external_workbook_path/) | Представляет источник данных диаграммы |
| [`embedded_workbook_type`](/slides/python-net/ru/aspose.slides.charts/chartdata/embedded_workbook_type/) | Получает тип встроенной рабочей книги.<br/>            Возвращает [`WorkbookType.NOT_DEFINED`](/slides/python-net/ru/aspose.slides.charts/workbooktype/NOT_DEFINED), если [`ChartData.data_source_type`](/slides/python-net/ru/aspose.slides.charts/chartdata/data_source_type) равно <br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ru/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK).<br/>            Только для чтения [`WorkbookType`](/slides/python-net/ru/aspose.slides.charts/workbooktype). |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ru/aspose.slides.charts/chartdata/set_external_workbook/#str) | Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы. Данные диаграммы будут обновлены из целевой рабочей книги. |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ru/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | Устанавливает внешнюю рабочую книгу в качестве источника данных для диаграммы. |
| [`read_workbook_stream(self)`](/slides/python-net/ru/aspose.slides.charts/chartdata/read_workbook_stream/#) | Записывает внутреннюю Excel-рабочую книгу в поток. |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ru/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | Инициализирует внутреннюю Excel-рабочую книгу значением, заданным пользователем. |
| [`get_range(self)`](/slides/python-net/ru/aspose.slides.charts/chartdata/get_range/#) | Получает диапазон данных диаграммы. |
| [`set_range(self, formula)`](/slides/python-net/ru/aspose.slides.charts/chartdata/set_range/#str) | Устанавливает диапазон данных диаграммы. Ряды и категории будут обновлены на основе нового диапазона данных.<br/>            Если количество рядов в диапазоне данных превышает количество рядов в данных диаграммы, то дополнительные ряды того же типа,<br/>            что и последний ряд в текущей коллекции, будут добавлены в конец коллекции. |
| [`switch_row_column(self)`](/slides/python-net/ru/aspose.slides.charts/chartdata/switch_row_column/#) | Меняет данные местами по осям.<br/>            Данные, построенные по оси X, будут перемещены на ось Y и наоборот. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)