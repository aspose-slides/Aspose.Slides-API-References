---
title: StaticCast_noexcept()
second_title: Aspose.Slides для C++ – справочник API
description: Выполняет статическое приведение объектов SmartPtr.
type: docs
weight: 2510
url: /ru/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) функция


Выполняет статическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) функция


Выполняет статическое приведение объектов [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(const TFrom\&) функция


Выполняет статическое приведение объектов Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) функция


Выполняет статическое приведение объектов к объектам Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Возвращаемое значение

Cast result if cast is allowed or nullptr otherwise.

Устарело
:   Left for backwards compatibility. Use AsCast instead.

## См. также

* Класс [SmartPtr](../smartptr/)
* Класс [WeakPtr](../weakptr/)
* Класс [Object](../object/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Структура [CastResult](../castresult/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)