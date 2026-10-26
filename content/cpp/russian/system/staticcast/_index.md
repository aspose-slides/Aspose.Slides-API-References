---
title: StaticCast()
second_title: Справочник API Aspose.Slides для C++
description: Выполняет статическое приведение объектов SmartPtr.
type: docs
weight: 2523
url: /ru/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) функция


Выполняет статическое приведение объектов [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Тип целевого указателя. |
| TFrom | Тип исходного указателя. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## System::StaticCast(WeakPtr\<TFrom\> const\&) функция


Выполняет статическое приведение объектов [WeakPtr](../weakptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Тип целевого указателя. |
| TFrom | Тип исходного указателя. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## System::StaticCast(std::nullptr_t) функция


Выполняет статическое приведение нулевых объектов.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Тип целевого указателя. |

### Возвращаемое значение

nullptr.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## System::StaticCast(TFrom) функция


Специализация для арифметических типов.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) функция


Выполняет приведение из [String](../string/) в [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) функция


Специализация для арифметических типов.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) функция


Выполняет статическое приведение объектов, не являющихся указателями.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Целевой тип. |
| TFrom | Исходный тип. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Исходный объект. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## System::StaticCast(const TFrom\&) функция


Выполняет статическое приведение объектов Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Целевой тип Exception. |
| TFrom | Исходный тип Exception. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используете ExplicitCast.

## System::StaticCast(SmartPtr\<TFrom\>) функция


Выполняет статическое приведение объектов к объектам Exception.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TTo | Целевой тип Exception. |
| TFrom | [Object](../object/) тип. |

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Исходный указатель. |

### Возвращаемое значение

Результат приведения, если приведение разрешено.

Deprecated
:   Оставлено для обратной совместимости. Вместо этого используйте ExplicitCast.

## Смотрите также

* Класс [SmartPtr](../smartptr/)
* Класс [WeakPtr](../weakptr/)
* Класс [String](../string/)
* Класс [Object](../object/)
* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Структура [CastResult](../castresult/)
* Структура [IsSmartPtr](../issmartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)