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

| Свойство | Описание |
| :- | :- |
| [`use_cell`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/use_cell/) | Если true, то свойство AsCell актуально. Иными словами, лист используется для <br/>            хранения категории (в этом случае поддерживается многоуровневая категория).<br/>            Если false, то свойство AsLiteral актуально. Иными словами, лист НЕ используется <br/>            для хранения категории (и в этом случае многоуровневые категории не поддерживаются).<br/>            Только для чтения **bool**. |
| [`as_cell`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/as_cell/) | Возвращает или задает объект IChartDataCell.<br/>            Если категория многоуровневая, используется объект IChartDataCell для уровня "0".<br/>            Чтение/запись [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/as_literal/) | Возвращает или задает AsLiteral, если UseCell false.<br/>            Чтение/запись **any**. |
| [`value`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/value/) | Если UseCell true, то это свойство представляет свойство AsCell.Value.<br/>            Если UseCell false, то это свойство представляет свойство AsLiteral.<br/>            Чтение/запись **any**. |
| [`cached_value`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/cached_value/) | Получает кэшированное значение категории диаграммы.<br/>            Только для чтения [`ICachedChartValue`](/slides/python-net/ru/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/grouping_levels/) | Управляемый контейнер значений уровней группировки категории диаграммы.<br/>            Многоуровневая категория содержит более одного уровня группировки.<br/>            Индексация уровней группировки начинается с нуля.<br/>            Только для чтения [`IChartCategoryLevelsManager`](/slides/python-net/ru/aspose.slides.charts/ichartcategorylevelsmanager). |

## Методы

| Метод | Описание |
| :- | :- |
| [`remove(self)`](/slides/python-net/ru/aspose.slides.charts/ichartcategory/remove/#) | Удаляет категорию из диаграммы. |

### См. также
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)