---
title: Cast()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует исходный тип в результирующий тип. Используется, когда исходный и результирующий типы совпадают.
type: docs
weight: 14
url: /ru/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный и результирующий типы совпадают.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный тип может быть статически преобразован в результирующий тип.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда типы не совпадают и исходный тип нельзя статически преобразовать в результирующий тип.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный тип упаковывается в экземпляр класса [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный тип распаковывается из экземпляра класса [Nullable](../../system/nullable/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный тип упаковывается в экземпляр класса [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда исходный тип распаковывается из экземпляра класса [Object](../../system/object/).

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## System::Collections::Generic::Details::CastRules::Cast(Source) функция

Преобразует исходный тип в результирующий тип. Используется, когда приведение недействительно или преобразование явное.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Исходный тип. |
| Result | Результирующий тип. |

### Возвращаемое значение

Результат приведения.

## См. также

* Структура [CastType](../casttype/)
* Пространство имён [System::Collections::Generic::Details::CastRules](../)
* Библиотека [Aspose.Slides](../../)