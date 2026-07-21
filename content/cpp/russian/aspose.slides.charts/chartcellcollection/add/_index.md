---
title: Add()
second_title: Aspose.Slides для C++ справочник API
description: Добавить новую ячейку в коллекцию.
type: docs
weight: 53
url: /ru/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) метод

Добавить новую ячейку в коллекцию.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Новая ячейка для добавления. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) метод

Создаёт [ChartDataCell](../../chartdatacell/) из указанного значения и добавляет его в коллекцию.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Значение. |

## Примечания

Этот метод добавляет лист с именем AUTO_DATA и размещает там все значения. Если вы используете [ChartDataWorkbook](../../chartdataworkbook/) для добавления или редактирования значений [Cell](../../../aspose.slides/cell/), убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680.

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [ChartCellCollection](../)
* Класс [Object](../../../system/object/)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)