---
title: IChartDataCell class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell класс

Представляет ячейку данных диаграммы.

Тип IChartDataCell раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/row/) | Возвращает индекс строки листа, в которой находится ячейка.<br/>            Только для чтения **int**. |
| [`column`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/column/) | Возвращает индекс столбца листа, в котором находится ячейка.<br/>            Только для чтения **int**. |
| [`value`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/value/) | Получает или задает значение ячейки.<br/>            Чтение/запись **any**. |
| [`formula`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/formula/) | Получает или задает формулу в стиле A1. |
| [`r1c1_formula`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/r1c1_formula/) | Получает или задает формулу в стиле R1C1. |
| [`chart_data_worksheet`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | Получает лист.<br/>            Только для чтения [`IChartDataWorksheet`](/slides/python-net/ru/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/is_hidden/) | Определяет, скрыта ли ячейка.<br/>            Только для чтения **bool**. |
| [`custom_number_format`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/custom_number_format/) | Получает или задает пользовательский формат отображения чисел и дат.<br/>            Если значение пусто, будет использовано значение PresetNumberFormat.<br/>            Чтение/запись **str**. |
| [`preset_number_format`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/preset_number_format/) | Получает или задает встроенный формат отображения чисел и дат. Предустановленный номер должен быть в диапазонах [0..22] или [37..49].<br/>            Чтение/запись **int**. |

## Методы

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell/calculate/#bool) | Если ячейка содержит формулу, значение будет обновлено на основе этой формулы. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)