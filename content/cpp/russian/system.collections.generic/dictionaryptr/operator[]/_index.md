---
title: operator[]()
second_title: Aspose.Slides для C++ справочник API
description: Оператор доступа для работы с преобразованием типа ключа.
type: docs
weight: 14
url: /ru/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) константный метод

Оператор доступа для работы с преобразованием типа ключа.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| X | Исходный тип ключа. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) ключ. |

### Возвращаемое значение

Ссылка на значение, соответствующее переданному ключу, существующее или только что созданное.

## DictionaryPtr::operator[](const T\&) константный метод

Оператор доступа.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) ключ. |

### Возвращаемое значение

Ссылка на значение, соответствующее переданному ключу, существующее или только что созданное.

## См. также

* Класс [DictionaryPtr](../)
* Пространство имён [System::Collections::Generic](../../)
* Библиотека [Aspose.Slides](../../../)