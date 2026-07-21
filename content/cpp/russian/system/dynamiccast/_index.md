---
title: DynamicCast()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет динамическое приведение к типу объектов Exception.
type: docs
weight: 2497
url: /ru/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) функция

Выполняет динамическое приведение к типу объектов Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип Exception. |
| TFrom | Исходный тип Exception. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const TFrom\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) функция

Выполняет динамическое приведение к типу объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип указателя. |
| TFrom | Исходный тип указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(SmartPtr\<TFrom\>) функция

Разупаковывает упакованный enum посредством приведения.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип enum. |
| TFrom | Исходный тип указателя. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Указатель на объект, из которого нужно разупаковать данные. |

### Возвращаемое значение

Разупакованное значение enum.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(std::nullptr_t) функция

Выполняет динамическое приведение нулевых объектов.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип указателя. |

### Возвращаемое значение

nullptr.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(TFrom\&) функция

Выполняет динамическое приведение к типу объектов без указателей.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Исходный тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | TFrom\& | Исходный объект. |

### Возвращаемое значение

Результат приведения.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(SmartPtr\<TFrom\>) функция

Выполняет динамическое приведение объектов к объектам Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип Exception. |
| TFrom | тип [Object](../object/). |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## System::DynamicCast(TFrom) функция

Выполняет динамическое приведение из IntPtr к указателю.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Исходный тип. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | TFrom | Исходное значение IntPtr. |

### Возвращаемое значение

Результат приведения.

Устарело
:   Оставлено для обратной совместимости. Используйте ExplicitCast вместо него.

## См. также

* Класс [SmartPtr](../smartptr/)
* Класс [Object](../object/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Структура [CastResult](../castresult/)
* Структура [IsSmartPtr](../issmartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)