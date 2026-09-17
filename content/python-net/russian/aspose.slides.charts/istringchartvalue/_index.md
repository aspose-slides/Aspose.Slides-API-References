---
title: IStringChartValue class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue класс

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами:
            1) в ячейке/ячейках рабочей книги, связанной с диаграммой;
            2) как буквальное значение.

Тип IStringChartValue раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`as_literal_string`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/as_literal_string/) | Возвращает или задает буквальную строку, если свойство DataSourceType имеет значение DataSourceType.StringLiterals.<br/>            Чтение/запись **str**. |
| [`as_cells`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/data/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`to_string(self)`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/to_string/#) | Возвращает строковое представление. |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | Устанавливает значение из указанной ячейки. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ru/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | Если свойство DataSourceType имеет значение DataSourceType.Worksheet, то этот метод возвращает адрес<br/>            ячеек в рабочей книге, представляющих строковые данные. В противном случае возвращает<br/>            пустую строку. |


### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)