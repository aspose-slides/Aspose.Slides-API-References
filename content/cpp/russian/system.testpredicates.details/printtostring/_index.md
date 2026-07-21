---
title: PrintToString()
second_title: Aspose.Slides для C++ справочник API
description: Печатает объект в строку, выбирая подходящую функцию сериализации.
type: docs
weight: 1
url: /ru/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) function


Печатает объект в строку, выбирая подходящую функцию сериализации.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) to print. |

### Возвращаемое значение

[String](../../system/string/) представления переданного объекта.

## System::TestPredicates::Details::PrintToString(const T\&) function


Печатает контейнеры в стиле ICollection в строку, выводя их элементы (не более 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) для печати. |

### Возвращаемое значение

Объединённые строковые представления содержащихся элементов.

## System::TestPredicates::Details::PrintToString(std::nullptr_t) function


Печатает nullptr в строку.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```


### Возвращаемое значение

\"nullptr\" строка.

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) function


Печатает коллекции [IEnumerable<bool>](../../system.collections.generic/ienumerable/) в строку, выводя их элементы (не более 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) для печати. |

### Возвращаемое значение

Объединённые строковые представления содержащихся элементов.

## См. также

* Класс [IEnumerable](../../system.collections.generic/ienumerable/)
* Структура [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Пространство имён [System::TestPredicates::Details](../)
* Библиотека [Aspose.Slides](../../)