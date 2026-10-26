---
title: ToArray()
second_title: Aspose.Slides для C++ справка по API
description: Создаёт и возвращает массив, содержащий все фигуры.
type: docs
weight: 326
url: /ru/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() метод


Создаёт и возвращает массив, содержащий все фигуры.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Возвращаемое значение

Массив объектов [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) метод


Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первой фигуры для возврата. |
| count | **int32_t** | Количество фигур для возврата. |

### Возвращаемое значение

Массив объектов [IShape](../../ishape/).

## Смотрите также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IShape](../../ishape/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)