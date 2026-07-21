---
title: CanCast()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет возможность приведения.
type: docs
weight: 40
url: /ru/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

True, если после приведения возвращается непустое значение, иначе false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

True, если после приведения возвращается непустое значение, иначе false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

True, если после приведения возвращается непустое значение, иначе false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

Всегда возвращает true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

True, если после приведения возвращается непустое значение, иначе false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

Всегда возвращает true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

True, если операция приведения выполнена успешно, иначе false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) функция


Проверяет возможность приведения.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| Source | Тип источника. |
| Result | Тип результата. |

### Возвращаемое значение

Всегда возвращает false.

## См. также

* Структура [CastType](../casttype/)
* Пространство имён [System::Collections::Generic::Details::CastRules](../)
* Библиотека [Aspose.Slides](../../)