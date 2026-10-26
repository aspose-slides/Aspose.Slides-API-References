---
title: TestTools
second_title: Aspose.Slides для C++ справочник API
description: Предоставляет набор полезных методов, которые проверяют некоторые базовые свойства различных типов и функций.
type: docs
weight: 1899
url: /ru/system/testtools/
---
## TestTools struct

Предоставляет набор полезных методов, которые проверяют некоторые базовые свойства различных типов и функций.

```cpp
class TestTools
```

## Методы

| Метод | Описание |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Проверяет, выбрасывает ли функция исключение любого типа. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Проверяет, является ли строка пустой. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Проверяет, пуста ли коллекция. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Проверяет, является ли конкретное значение null. [Version](../version/) для арифметических и перечислимых типов. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Проверяет, является ли конкретное значение null. [Version](../version/) для неарифметических и не перечислимых типов значений. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Проверяет, является ли конкретное значение null. [Version](../version/) для неарифметических типов значений. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Проверяет, является ли конкретное значение null. [Version](../version/) для пар ключ-значение. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Проверяет, является ли строка null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Проверяет, является ли коллекция null или пустой. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Проверяет, является ли строка null или пустой. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)