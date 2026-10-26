---
title: Box()
second_title: Справочник API Aspose.Slides для C++
description: Упаковывает типы значений для преобразования в Object. Реализация для перечислимых типов.
type: docs
weight: 40
url: /ru/system/objectext/box/
---
## ObjectExt::Box(const T\&) метод


Упаковывает типы значений для преобразования в [Object](../../object/). Реализация для перечислимых типов.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) value to box. |

### Возвращаемое значение

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) метод


Упаковывает типы значений для преобразования в [Object](../../object/). Реализация для не-перечислимых типов.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Возвращаемое значение

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) метод


Упаковывает типы [Nullable](../../nullable/) для преобразования в [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Возвращаемое значение

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const String\&) метод


Упаковывает строковые значения.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Value to box. |

### Возвращаемое значение

Boxed value or null, if source string is null.

## См. также

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)