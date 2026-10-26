---
title: IsEmpty()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, пустая ли строка.
type: docs
weight: 14
url: /ru/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) метод


Проверяет, является ли строка пустой.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) для проверки на пустоту. |

### Возвращаемое значение

True if string is empty (null-length), false otherwise.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) метод


Проверяет, является ли коллекция пустой.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип коллекции. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Коллекция для проверки. |

### Возвращаемое значение

True if collection has zero element count, false otherwise.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)