---
title: GetType()
second_title: Справочник API Aspose.Slides для C++
description: Реализует перевод typeof(). Перегрузка для умных указателей.
type: docs
weight: 1
url: /ru/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) метод


Реализует перевод typeof(). Перегрузка для умных указателей.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип объекта указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## ObjectType::GetType(const T\&) метод


Реализует перевод typeof(). Перегрузка для структур.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип структуры. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## ObjectType::GetType(const T\&) метод


Реализует перевод typeof(). Перегрузка для исключений.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип исключения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) для получения [TypeInfo](../../typeinfo/). |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую конечный класс переданного объекта.

## ObjectType::GetType(const T) метод


Реализует перевод typeof(). Перегрузка для примитивных типов.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T | IGNORED |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип переданного объекта.

## ObjectType::GetType(const T) метод


Реализует перевод typeof(). Перегрузка для типов [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const T | IGNORED |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип переданного объекта.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для примитивных типов.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанный тип.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для типов enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанный тип.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для структур и указателей.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [Nullable](../../nullable/) тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | MutlicastDelegate тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру.

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для структур и указателей.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую указанную структуру или тип указываемого объекта, если вызвано для [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) метод


Реализует перевод typeof(). Перегрузка для строкового типа.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Примитивный тип. |

### Возвращаемое значение

Константная ссылка на структуру [TypeInfo](../../typeinfo/), описывающую тип [String](../../string/).

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() метод


Реализует перевод typeof(). Перегрузка для [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## См. также

* Класс [ObjectType](../)
* Класс [TypeInfo](../../typeinfo/)
* Класс [String](../../string/)
* Структура [IsSmartPtr](../../issmartptr/)
* Структура [IsExceptionWrapper](../../isexceptionwrapper/)
* Структура [IsNullable](../../isnullable/)
* Структура [IsBoxable](../../isboxable/)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)