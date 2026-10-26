---
title: StringChartValue class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/stringchartvalue/
---
## StringChartValue класс

Представляет строковое значение, которое может быть сохранено в документе презентации pptx двумя способами:
            1) в ячейке/ячейках книги, связанной с диаграммой;
            2) как буквальное значение.

**Наследование:**[`StringChartValue`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/ru/aspose.slides.charts/basechartvalue)

Тип StringChartValue раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`data_source_type`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/data_source_type/) | Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble <br/>            актуальным в наследниках. Другими словами, задаёт тип <br/>            значения свойства Data.<br/>            Чтение/запись [`DataSourceType`](/slides/python-net/ru/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/data/) | Возвращает или задаёт объект Data.<br/>            Чтение/запись **any**. |
| [`as_cells`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/as_cells/) | Присваивание нулевого значения не допускается.<br/>            Возвращаемое значение всегда не None.<br/>            Чтение/запись [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/as_literal_string/) | Возвращает или задаёт значение как буквальную строку.<br/>            Чтение/запись **str**. |

## Методы

| Метод | Описание |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | Устанавливает значение из указанной ячейки. |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | Если свойство DataSourceType равно DataSourceType.Worksheet, то этот метод возвращает адрес<br/>            ячеек в книге, представляющих строковые данные. В противном случае возвращает<br/>            пустую строку. |

### См. также
* класс [`BaseChartValue`](/slides/python-net/ru/aspose.slides.charts/basechartvalue)
* класс [`StringChartValue`](/slides/python-net/ru/aspose.slides.charts/stringchartvalue)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)