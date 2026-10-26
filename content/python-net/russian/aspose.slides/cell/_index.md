---
title: Cell class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/cell/
---
## Cell класс

Представляет ячейку таблицы.

Тип Cell предоставляет следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`offset_x`](/slides/python-net/ru/aspose.slides/cell/offset_x/) | Возвращает расстояние от левой стороны таблицы до левой стороны ячейки.<br/> Только для чтения **float**. |
| [`offset_y`](/slides/python-net/ru/aspose.slides/cell/offset_y/) | Возвращает расстояние от верхней стороны таблицы до верхней стороны ячейки.<br/> Только для чтения **float**. |
| [`first_row_index`](/slides/python-net/ru/aspose.slides/cell/first_row_index/) | Возвращает индекс первой строки, покрытой ячейкой.<br/> Только для чтения **int**. |
| [`first_column_index`](/slides/python-net/ru/aspose.slides/cell/first_column_index/) | Возвращает индекс первого столбца, покрытого ячейкой.<br/> Только для чтения **int**. |
| [`width`](/slides/python-net/ru/aspose.slides/cell/width/) | Возвращает ширину ячейки.<br/> Только для чтения **float**. |
| [`height`](/slides/python-net/ru/aspose.slides/cell/height/) | Возвращает высоту ячейки.<br/> Только для чтения **float**. |
| [`minimal_height`](/slides/python-net/ru/aspose.slides/cell/minimal_height/) | Возвращает минимальную высоту ячейки.<br/> Это сумма минимальных высот всех строк, покрываемых ячейкой.<br/> Только для чтения **float**. |
| [`margin_left`](/slides/python-net/ru/aspose.slides/cell/margin_left/) | Возвращает или задает левый отступ в TextFrame.<br/> Чтение/запись **float**. |
| [`margin_right`](/slides/python-net/ru/aspose.slides/cell/margin_right/) | Возвращает или задает правый отступ в TextFrame.<br/> Чтение/запись **float**. |
| [`margin_top`](/slides/python-net/ru/aspose.slides/cell/margin_top/) | Возвращает или задает верхний отступ в TextFrame.<br/> Чтение/запись **float**. |
| [`margin_bottom`](/slides/python-net/ru/aspose.slides/cell/margin_bottom/) | Возвращает или задает нижний отступ в TextFrame.<br/> Чтение/запись **float**. |
| [`text_vertical_type`](/slides/python-net/ru/aspose.slides/cell/text_vertical_type/) | Возвращает или задает тип вертикального текста.<br/> Чтение/запись [`TextVerticalType`](/slides/python-net/ru/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/ru/aspose.slides/cell/text_anchor_type/) | Возвращает или задает тип привязки текста.<br/> Чтение/запись [`TextAnchorType`](/slides/python-net/ru/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/ru/aspose.slides/cell/anchor_center/) | Определяет, центрирован ли текстовый блок внутри ячейки.<br/> Чтение/запись **bool**. |
| [`first_row`](/slides/python-net/ru/aspose.slides/cell/first_row/) | Получает первую строку ячейки.<br/> Только для чтения [`IRow`](/slides/python-net/ru/aspose.slides/irow). |
| [`first_column`](/slides/python-net/ru/aspose.slides/cell/first_column/) | Получает первый столбец ячейки.<br/> Только для чтения [`IColumn`](/slides/python-net/ru/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/ru/aspose.slides/cell/col_span/) | Возвращает количество колонок сетки в таблице-родителе, которые должны быть охвачены текущей ячейкой.<br/> Это свойство позволяет ячейкам выглядеть как объединённые, так как они охватывают вертикальные границы других ячеек в таблице.<br/> Только для чтения **int**. |
| [`row_span`](/slides/python-net/ru/aspose.slides/cell/row_span/) | Возвращает количество строк, охваченных объединённой ячейкой. Используется в сочетании<br/> с атрибутом vMerge у других ячеек для указания начальной ячейки<br/> горизонтального объединения.<br/> Только для чтения **int**. |
| [`text_frame`](/slides/python-net/ru/aspose.slides/cell/text_frame/) | Возвращает текстовый фрейм ячейки.<br/> Только для чтения [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe). |
| [`table`](/slides/python-net/ru/aspose.slides/cell/table/) | Возвращает объект Table-родитель для ячейки.<br/> Только для чтения [`ITable`](/slides/python-net/ru/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/ru/aspose.slides/cell/is_merged_cell/) | Возвращает true, если ячейка объединена с любой смежной ячейкой, иначе false.<br/> Только для чтения **bool**. |
| [`cell_format`](/slides/python-net/ru/aspose.slides/cell/cell_format/) | Возвращает объект CellFormat, содержащий свойства форматирования этой ячейки.<br/> Только для чтения [`ICellFormat`](/slides/python-net/ru/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/ru/aspose.slides/cell/slide/) | Возвращает слайд-родитель ячейки.<br/> Только для чтения [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/ru/aspose.slides/cell/presentation/) | Возвращает презентацию-родитель ячейки.<br/> Только для чтения [`IPresentation`](/slides/python-net/ru/aspose.slides/ipresentation). |

## Методы

| Метод | Описание |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/ru/aspose.slides/cell/split_by_col_span/#int) | Разделяет ячейку на две ячейки по индексу столбца. |
| [`split_by_row_span(self, index)`](/slides/python-net/ru/aspose.slides/cell/split_by_row_span/#int) | Разделяет ячейку на две ячейки по индексу строки. |
| [`split_by_height(self, height)`](/slides/python-net/ru/aspose.slides/cell/split_by_height/#float) | Разделяет ячейку по высоте. |
| [`split_by_width(self, width)`](/slides/python-net/ru/aspose.slides/cell/split_by_width/#float) | Разделяет ячейку по ширине. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)