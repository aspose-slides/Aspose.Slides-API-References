---
title: ToArray()
second_title: Aspose.Slides для C++ справка API
description: Создает и возвращает массив со всеми слайдами в нем.
type: docs
weight: 92
url: /ru/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() method

Создает и возвращает массив со всеми слайдами в нем.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```

### Возвращаемое значение

Массив [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) method

Создает и возвращает массив со всеми слайдами из указанного диапазона в нем.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | **int32_t** | Индекс первого слайда для добавления. |
| count | **int32_t** | Количество слайдов для добавления. |

### Возвращаемое значение

Массив [ISlide](../../islide/)

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [ISlideCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)