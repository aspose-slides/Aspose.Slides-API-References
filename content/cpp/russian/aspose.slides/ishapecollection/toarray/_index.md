---
title: ToArray()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт и возвращает массив, содержащий все фигуры.
type: docs
weight: 287
url: /ru/aspose.slides/ishapecollection/toarray/
---
## IShapeCollection::ToArray() метод

Создаёт и возвращает массив, содержащий все фигуры.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray()=0
```

### Возвращаемое значение

Массив объектов [IShape](../../ishape/).

## IShapeCollection::ToArray(int32_t, int32_t) метод

Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::IShapeCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первой возвращаемой фигуры. |
| count | **int32_t** | Количество возвращаемых фигур. |

### Возвращаемое значение

Массив объектов [IShape](../../ishape/).

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)