---
title: BuildArray()
second_title: Справочник API Aspose.Slides для C++
description: Создать массив.
type: docs
weight: 2250
url: /ru/system/buildarray/
---
## System::BuildArray() функция

Build an array.

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов массива для построения |

### Возвращаемое значение

ObjectBuilder, настроенный для построения массива
## Примечания

Создает ArrayPtr<T> и возвращает построитель для него
[Object](../object/) конструкция должна быть завершена вызовом [Get()](../get/)

## См. также

* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)