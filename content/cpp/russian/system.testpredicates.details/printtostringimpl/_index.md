---
title: PrintToStringImpl()
second_title: Справочник API Aspose.Slides для C++
description: "Печатает подкласс System::Object в строку, используя метод ToString()."
type: docs
weight: 14
url: /ru/system.testpredicates.details/printtostringimpl/
---
## System::TestPredicates::Details::PrintToStringImpl(const SharedPtr\<T\>\&, long long) функция

Печатает [System::Object](../../system/object/) подкласс в строку, используя метод ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const SharedPtr<T> &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип конечного класса. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Указатель на объект для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представление переданного объекта или "nullptr", если **value** равно null.

## System::TestPredicates::Details::PrintToStringImpl(const WeakPtr\<T\>\&, long long) функция

Печатает [System::Object](../../system/object/) подкласс в строку, используя метод ToString().

```cpp
template<typename T> std::enable_if<System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const WeakPtr<T> &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип конечного класса. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [WeakPtr](../../system/weakptr/)\<T\>\& | Указатель на объект для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представление переданного объекта или "nullptr", если **value** равно null.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) функция

Печатает объект в строку, используя метод ToString().

```cpp
template<typename T> std::enable_if<!TypeTraits::has_print_to_method<T>::value &&System::Details::HasToString<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представление переданного объекта.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) функция

Печатает объект в строку, используя метод PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&!TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представление переданного объекта.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) функция

Печатает объект в строку, используя метод PrintTo.

```cpp
template<typename T> std::enable_if<TypeTraits::has_print_to_method<T>::value &&TypeTraits::IsEnumerable<T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представление переданного объекта.

## System::TestPredicates::Details::PrintToStringImpl(const std::pair\<T1, T2\>\&, long long) функция

Печатает пару в строку.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const std::pair<T1, T2> &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Первый тип аргумента пары. |
| T2 | Второй тип аргумента пары. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const std::pair\<T1, T2\>\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

Объединённые строковые представления обеих компонентов первой и второй пары.

## System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair\<T1, T2\>\&, long long) функция

Печатает пару в строку.

```cpp
template<typename T1,typename T2> std::string System::TestPredicates::Details::PrintToStringImpl(const Collections::Generic::KeyValuePair<T1, T2> &value, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T1 | Первый тип аргумента пары. |
| T2 | Второй тип аргумента пары. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<T1, T2\>\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

Объединённые строковые представления обеих компонентов первой и второй пары.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, long long) функция

Печатает контейнеры в стиле STL в строку, выводя их элементы (не более 32).

```cpp
template<typename T> std::enable_if<TypeTraits::IsCppContainer<T>::value &&!std::is_base_of<Object, T>::value, std::string>::type System::TestPredicates::Details::PrintToStringImpl(const T &container, long long s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| container | const T\& | [Object](../../system/object/) для печати. |
| s | long long | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

Объединённые строковые представления содержащихся элементов.

## System::TestPredicates::Details::PrintToStringImpl(const T\&, int) функция

Печатает другие типы в строку, используя функции, предоставленные gtest.

```cpp
template<typename T> std::string System::TestPredicates::Details::PrintToStringImpl(const T &value, int s)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Object](../../system/object/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) для печати. |
| s | int | Служебный параметр, который служит селектором перегрузки функции на основе типа этого параметра; значение параметра игнорируется. |

### Возвращаемое значение

[String](../../system/string/) представления переданного объекта.

## Смотрите также

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [WeakPtr](../../system/weakptr/)
* Class [KeyValuePair](../../system.collections.generic/keyvaluepair/)
* Class [Object](../../system/object/)
* Struct [has_print_to_method](../../system.testpredicates.typetraits/has_print_to_method/)
* Struct [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* Struct [IsCppContainer](../../system.testpredicates.typetraits/iscppcontainer/)
* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)