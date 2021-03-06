---
title: IChartCategory
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет категории диаграммы.
type: docs
weight: 1610
url: /ru/net/aspose.slides.charts/ichartcategory/
---
## IChartCategory interface

Представляет категории диаграммы.

```csharp
public interface IChartCategory
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsCell](../../aspose.slides.charts/ichartcategory/ascell) { get; set; } | Возвращает или задает объект IChartDataCell. Если категория многоуровневая, то используется объект IChartDataCell для уровня "0". Чтение/запись[`IChartDataCell`](../ichartdatacell) . |
| [AsLiteral](../../aspose.slides.charts/ichartcategory/asliteral) { get; set; } | Возвращает или устанавливает AsLiteral, если UseCell имеет значение false. Чтение/записьObject . |
| [GroupingLevels](../../aspose.slides.charts/ichartcategory/groupinglevels) { get; } | Управляемый контейнер значений уровней группировки категорий диаграмм. Многоуровневые категории содержат более одного уровня группировки. Индексация уровней группировки отсчитывается от нуля. Только для чтения[`IChartCategoryLevelsManager`](../ichartcategorylevelsmanager) . |
| [UseCell](../../aspose.slides.charts/ichartcategory/usecell) { get; } | Если true, то свойство AsCell актуально. Другими словами, рабочий лист используется для хранения категории (в этом случае поддерживается многоуровневая категория). Если false, то свойство AsLiteral является актуальным. Другими словами, рабочий лист НЕ используется для хранения категории (и этот случай не поддерживает многоуровневые категории). Только для чтенияBoolean . |
| [Value](../../aspose.slides.charts/ichartcategory/value) { get; set; } | Если UseCell равно true, то это свойство представляет свойство AsCell.Value. Если UseCell равно false, то это свойство представляет свойство AsLiteral. Чтение/записьObject . |

## Методы

| Имя | Описание |
| --- | --- |
| [Remove](../../aspose.slides.charts/ichartcategory/remove)() | Удаляет категорию из диаграммы. |

### Смотрите также

* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
