---
title: Unbox()
second_title: Справочник API Aspose.Slides для C++
description: Разворачивает типы значений после преобразования к Object. Реализация для перечислимых типов.
type: docs
weight: 53
url: /ru/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Разворачивает типы значений после преобразования к [Object](../../object/). Реализация для перечислимых типов.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Enum](../../enum/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для разворачивания. |

### Возвращаемое значение

[Enum](../../enum/) значение.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Разворачивает типы значений после преобразования к [Object](../../object/). Реализация для не перечислимых и не допускающих null типов.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для разворачивания. |

### Возвращаемое значение

Развёрнутое значение.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Разворачивает типы значений после преобразования к [Object](../../object/). Реализация для не перечислимых и не допускающих null типов.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип значения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для разворачивания. |

### Возвращаемое значение

Развёрнутое значение.

## ObjectExt::Unbox(E) method

Разворачивает типы перечислений в целое число.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип целевого целого числа. |
| E | Тип исходного перечисления. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для разворачивания. |

### Возвращаемое значение

Целочисленное представление перечисления.

## ObjectExt::Unbox(E) method

Преобразует типы перечислений.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип целевого перечисления. |
| E | Тип исходного перечисления. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| e | E | Значение для разворачивания. |

### Возвращаемое значение

Преобразованное значение перечисления.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

Разворачивает строковые значения.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) для разворачивания |

### Возвращаемое значение

[String](../../string/) представление упакованной строки, может быть null, если упакованная строка была null.

## См. также

* Класс [SmartPtr](../../smartptr/)
* Класс [Object](../../object/)
* Класс [ObjectExt](../)
* Класс [String](../../string/)
* Простейство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)