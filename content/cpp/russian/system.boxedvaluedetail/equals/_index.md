---
title: Equals()
second_title: Справочник API Aspose.Slides для C++
description: Определяет равенство указанного значения с использованием оператора ==().
type: docs
weight: 66
url: /ru/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) функция

Определяет равенство указанного значения с использованием [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | тип сравниваемых значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value1 | T | Первый сравниваемый объект |
| value2 | T | Второй сравниваемый объект |

### Возвращаемое значение

True, если указанные значения равны, как определено [operator==()](../../system/operator_equal_equal/), иначе — false

## System::BoxedValueDetail::Equals(T, T) функция

Определяет равенство указанного значения с использованием метода [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| The | тип сравниваемых значений |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value1 | T | Первый сравниваемый объект |
| value2 | T | Второй сравниваемый объект |

### Возвращаемое значение

True, если указанные значения равны, как определено методом [Equals()](./), иначе — false

## См. также

* Пространство имен [System::BoxedValueDetail](../)
* Библиотека [Aspose.Slides](../../)