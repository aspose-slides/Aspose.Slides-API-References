---
title: IChartCategoryCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет наборIChartCategory./ichartcategory
type: docs
weight: 1620
url: /ru/net/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection interface

Представляет набор[`IChartCategory`](../ichartcategory)

```csharp
public interface IChartCategoryCollection : IGenericCollection<IChartCategory>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [GroupingLevelCount](../../aspose.slides.charts/ichartcategorycollection/groupinglevelcount) { get; } | Возвращает количество использованных уровней группировки категорий. Больше одного для многоуровневых категорий. Только для чтенияInt32 . |
| [Item](../../aspose.slides.charts/ichartcategorycollection/item) { get; } | Получает элемент по указанному индексу. |
| [UseCells](../../aspose.slides.charts/ichartcategorycollection/usecells) { get; set; } | Если true, то рабочий лист используется для хранения категорий (в этом случае поддерживаются многоуровневые категории). Если false, то рабочий лист НЕ используется для хранения значений (и этот случай не поддерживает многоуровневые категории ). Читать /записыватьBoolean . |

## Методы

| Имя | Описание |
| --- | --- |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add)(IChartDataCell) | Если категория существует в коллекции, вернуть ее. Else создает новую категорию диаграммы из [`IChartDataCell`](../ichartdatacell) и добавляет в коллекцию. |
| [Add](../../aspose.slides.charts/ichartcategorycollection/add#add_1)(object) | Создает новый[`IChartCategory`](../ichartcategory) из значения и добавляет его в коллекцию. |
| [Clear](../../aspose.slides.charts/ichartcategorycollection/clear)() | Удаляет все элементы из коллекции. |
| [IndexOf](../../aspose.slides.charts/ichartcategorycollection/indexof)(IChartCategory) | Ищет указанный[`IChartCategory`](../ichartcategory) и возвращает отсчитываемый от нуля индекс первого вхождения во всей коллекции Collection |
| [Remove](../../aspose.slides.charts/ichartcategorycollection/remove)(IChartCategory) | Удаляет указанное значение. |
| [RemoveAt](../../aspose.slides.charts/ichartcategorycollection/removeat)(int) | Удаляет элемент с заданным индексом. |

### Смотрите также

* interface [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)
* interface [IChartCategory](../ichartcategory)
* пространство имен [Aspose.Slides.Charts](../../aspose.slides.charts)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
