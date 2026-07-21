---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Если категория существует в коллекции, вернуть её. Иначе создаёт новую категорию диаграммы из IChartDataCell и добавляет её в коллекцию.
type: docs
weight: 53
url: /ru/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) метод

Если категория существует в коллекции, возвращает её. В противном случае создаёт новую категорию диаграммы из [IChartDataCell](../../ichartdatacell/) и добавляет её в коллекцию.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) используется для создания категории диаграммы. |

### Возвращаемое значение

Добавленная или существующая категория.

## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) метод

Создаёт новый [IChartCategory](../../ichartcategory/) из значения и добавляет его в коллекцию.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

### Возвращаемое значение

Добавлен [IChartCategory](../../ichartcategory/).

## Примечания

Этот метод добавляет лист с именем AUTO_DATA и добавляет туда все значения. Если вы используете [IChartDataWorkbook](../../ichartdataworkbook/) для добавления или изменения значений ячеек, убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IChartCategory](../../ichartcategory/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [IChartCategoryCollection](../)
* Класс [Object](../../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)