---
title: ToString()
second_title: Справочник API Aspose.Slides для C++
description: Замена метода C# ToString для работы с любым типом C++.
type: docs
weight: 27
url: /ru/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) литерал для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(const Nullable\<T\>\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) объект для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(const T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Enum](../../enum/) тип. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) значение для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(const T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип умного указателя. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) значение для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип умного указателя или [ExceptionWrapper](../../exceptionwrapper/). |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Умный указатель или [ExceptionWrapper](../../exceptionwrapper/) для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип скаляра. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Значение скаляра для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(T\&&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип скаляра. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\&& | Значение скаляра для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип структуры. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\& | Значение структуры для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(const T\&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип структуры. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | Значение структуры для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## ObjectExt::ToString(T\&&) метод

Замена метода C# ToString для работы с любым типом C++.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | тип скаляра. |

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | T\&& | Значение скаляра для преобразования в строку. |

### Возвращаемое значение

[String](../../string/) представление **obj**.

## См. также

* Класс [String](../../string/)
* Класс [ObjectExt](../)
* Класс [Nullable](../../nullable/)
* Структура [IsSmartPtr](../../issmartptr/)
* Структура [IsExceptionWrapper](../../isexceptionwrapper/)
* Структура [IsNullable](../../isnullable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)