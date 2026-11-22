---
title: ChartCategory class
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides.charts/chartcategory/
---
## ChartCategory класс

Представляет категории диаграммы.

Тип ChartCategory раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`use_cell`](/slides/python-net/ru/aspose.slides.charts/chartcategory/use_cell/) | Если true, то свойство AsCell актуально. Другими словами, лист используется для <br/>            хранения категории (в этом случае поддерживается многоуровневая категория).<br/>            Если false, то свойство AsLiteral актуально. Другими словами, лист НЕ используется <br/>            для хранения категории (и в этом случае многоуровневые категории не поддерживаются).<br/>            Только для чтения **bool**. |
| [`as_cell`](/slides/python-net/ru/aspose.slides.charts/chartcategory/as_cell/) | Возвращает или задает объект IChartDataCell.<br/>            Если категория многоуровневая, то используется объект IChartDataCell для уровня "0".<br/>            Чтение/запись [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ru/aspose.slides.charts/chartcategory/as_literal/) | Возвращает или задает объект AsLiteral.<br/>            Чтение/запись **any**. |
| [`value`](/slides/python-net/ru/aspose.slides.charts/chartcategory/value/) | Если UseCell равно true, то это свойство представляет свойство AsCell.Value.<br/>            Если UseCell равно false, то это свойство представляет свойство AsLiteral.<br/>            Чтение/запись **any**. |
| [`grouping_levels`](/slides/python-net/ru/aspose.slides.charts/chartcategory/grouping_levels/) | Управляемый контейнер значений уровней группировки категорий диаграммы.<br/>            Многоуровневая категория содержит более одного уровня группировки.<br/>            Индексация уровней группировки начинается с нуля.<br/>            Только для чтения [`IChartCategoryLevelsManager`](/slides/python-net/ru/aspose.slides.charts/ichartcategorylevelsmanager). |
| [`cached_value`](/slides/python-net/ru/aspose.slides.charts/chartcategory/cached_value/) | Возвращает кэшированное значение категории диаграммы.<br/>            Только для чтения [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |

## Методы

| Метод | Описание |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.charts/chartcategory/remove/#) | Удаляет категорию из диаграммы. |

### См. также
* module [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)