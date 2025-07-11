---
title: Add
second_title: Aspose.Sildes для .NET API Справочник
description: Если категория существует в коллекции, верните её. Если нет, создаёт новую категорию графика из IChartDataCellaspose.slides.charts/ichartdatacell и добавляет её в коллекцию.
type: docs
weight: 40
url: /ru/aspose.slides.charts/ichartcategorycollection/add/
---

## Add(IChartDataCell) {#add}

Если категория существует в коллекции, верните её. Если нет, создаёт новую категорию графика из [`IChartDataCell`](../../ichartdatacell) и добавляет её в коллекцию.

```csharp
public IChartCategory Add(IChartDataCell chartDataCell)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | IChartDataCell | Ячейка, используемая для создания категории графика. |

### Возврат Значения

Добавленная или существующая категория.

### Также Смотрите

* интерфейс [IChartCategory](../../ichartcategory)
* интерфейс [IChartDataCell](../../ichartdatacell)
* интерфейс [IChartCategoryCollection](../../ichartcategorycollection)
* пространство имен [Aspose.Slides.Charts](../../ichartcategorycollection)
* сборка [Aspose.Slides](../../../)

---

## Add(object) {#add_1}

Создаёт новую [`IChartCategory`](../../ichartcategory) из значения и добавляет её в коллекцию.

```csharp
public IChartCategory Add(object value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | Object | Значение. |

### Возврат Значения

Добавленная [`IChartCategory`](../../ichartcategory).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | если превышен предел |

### Примечания

Этот метод добавляет рабочий лист с именем AUTO_DATA и добавляет все значения туда. Если вы используете [`IChartDataWorkbook`](../../ichartdataworkbook) для добавления или редактирования значений ячеек, убедитесь, что вы не используете этот рабочий лист. Максимальное количество значений, добавленных с помощью этого метода, не должно превышать 16711680.

### Также Смотрите

* интерфейс [IChartCategory](../../ichartcategory)
* интерфейс [IChartCategoryCollection](../../ichartcategorycollection)
* пространство имен [Aspose.Slides.Charts](../../ichartcategorycollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->