---
title: Remove()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет элемент из коллекции.
type: docs
weight: 79
url: /ru/aspose.slides.charts/piesplitcustompointcollection/remove/
---
## PieSplitCustomPointCollection::Remove(const System::SharedPtr\<IChartDataPoint\>\&) метод

Удаляет элемент из коллекции.

```cpp
bool Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(const System::SharedPtr<IChartDataPoint> &dataPoint) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPoint | const [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataPoint](../../ichartdatapoint/)\>\& | Точка данных для удаления. |

### Возвращаемое значение

true, если элемент успешно удалён; иначе — false. Этот метод также возвращает false, если элемент не найден в [System::Collections::Generic::List](../../../system.collections.generic/list/){T}.

## PieSplitCustomPointCollection::Remove(int32_t) метод

Удаляет элемент из коллекции по его индексу в коллекции точек родительского ряда.

```cpp
void Aspose::Slides::Charts::PieSplitCustomPointCollection::Remove(int32_t dataPointIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| dataPointIndex | **int32_t** | Индекс точки данных в коллекции точек родительского ряда. |

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChartDataPoint](../../ichartdatapoint/)
* Класс [PieSplitCustomPointCollection](../)
* Пространство имён [Aspose::Slides::Charts](../../)
* Библиотека [Aspose.Slides](../../../)