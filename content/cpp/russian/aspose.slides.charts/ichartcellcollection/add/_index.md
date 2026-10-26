---
title: Add()
second_title: Aspose.Slides для справочника API C++
description: Добавляет новую ячейку в коллекцию.
type: docs
weight: 53
url: /ru/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) метод

Добавляет новую ячейку в коллекцию.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | New cell to add. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) метод

Создаёт [IChartDataCell](../../ichartdatacell/) из указанного значения и добавляет его в коллекцию.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | The value. |

## Примечания

Этот метод добавляет лист с именем AUTO_DATA и помещает туда все значения. Если вы используете [IChartDataWorkbook](../../ichartdataworkbook/) для добавления или редактирования значений [Cell](../../../aspose.slides/cell/), убедитесь, что вы не используете этот лист. Максимальное количество значений, добавляемых с помощью этого метода, не должно превышать 16711680.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataCell](../../ichartdatacell/)
* Класс [IChartCellCollection](../)
* Класс [Object](../../../system/object/)
* Пространство имен [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)