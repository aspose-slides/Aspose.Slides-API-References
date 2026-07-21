---
title: InitObject()
second_title: Справочник API Aspose.Slides для C++
description: Начинает инициализацию объекта с совместным владением.
type: docs
weight: 2237
url: /ru/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) функция

Начинает инициализацию объекта с совместным владением.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта для инициализации |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) для инициализации |

### Возврат значения

ObjectBuilder, настроенный для построения разделяемого указателя

## Примечания

[Object](../object/) инициализация должна быть завершена вызовом [Get()](../get/) 

## Смотрите также

* Typedef [SharedPtr](../sharedptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)