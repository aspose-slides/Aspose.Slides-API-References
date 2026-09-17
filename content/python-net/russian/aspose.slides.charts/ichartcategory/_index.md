---
title: IChartCategory class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartcategory/
---
## IChartCategory класс

Представляет категории диаграммы.

Тип IChartCategory раскрывает следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/use_cell/) | Если true, то свойство AsCell актуально. Другими словами, лист используется для <br/>            хранения категории (в этом случае поддерживается многоуровневая категория).<br/>            Если false, то свойство AsLiteral актуально. Другими словами, лист НЕ используется <br/>            для хранения категории (и в этом случае не поддерживаются многоуровневые категории).<br/>            Только для чтения **bool**. |
| [`as_cell`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/as_cell/) | Возвращает или задает объект IChartDataCell.<br/>            Если категория многоуровневая, то используется объект IChartDataCell для уровня "0".<br/>            Чтение/запись [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/as_literal/) | Возвращает или задает AsLiteral, если UseCell равно false.<br/>            Чтение/запись **any**. |
| [`value`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/value/) | Если UseCell равно true, то это свойство представляет свойство AsCell.Value.<br/>            Если UseCell равно false, то это свойство представляет свойство AsLiteral.<br/>            Чтение/запись **any**. |
| [`grouping_levels`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/grouping_levels/) | Управляемый контейнер значений уровней группировки категории диаграммы.<br/>            Многоуровневая категория содержит более одного уровня группировки.<br/>            Индексация уровней группировки начинается с нуля.<br/>            Только для чтения [`IChartCategoryLevelsManager`](/slides/python-net/ru/aspose.slides.charts/ichartcategorylevelsmanager). |

## Методы

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/remove/#) | Удаляет категорию из диаграммы. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)