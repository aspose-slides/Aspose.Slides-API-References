---
title: DynamicCast_noexcept()
second_title: Aspose.Slides для C++ справочник API
description: Устаревшие приведения. Будут удалены в будущих версиях.
type: docs
weight: 2484
url: /ru/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) функция

Старые устаревшие приведения. Будут удалены в будущих версиях.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

## Комментарии

Выполняет динамическое приведение типов объектов Exception. Устарело
:   Оставлено для обратной совместимости. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) функция

Выполняет динамическое приведение типов объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Оставлено для обратной совместимости. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) функция

Выполняет динамическое приведение типов объектов к объектам Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Оставлено для обратной совместимости. Use AsCast instead.

## См. также

* Класс [SmartPtr](../smartptr/)
* Класс [Object](../object/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)