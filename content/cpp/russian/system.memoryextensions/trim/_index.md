---
title: Trim()
second_title: Aspose.Slides для C++ Справочник API
description: Обрезает указанный элемент с обоих концов типизированного спана.
type: docs
weight: 365
url: /ru/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) функция

Обрезает указанный элемент с обоих концов типизированного спана.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан для обрезки |
| trimElement | T | Элемент для обрезки |

### Возвращаемое значение

Новый спан, из которого указанный элемент обрезан с обоих концов

## System::MemoryExtensions::Trim(Span\<T\>\&, T) функция

Обрезает указанный элемент с обоих концов изменяемого типизированного спана.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Изменяемый спан для обрезки |
| trimElement | T | Элемент для обрезки |

### Возвращаемое значение

Новый спан, из которого указанный элемент обрезан с обоих концов

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Обрезает указанные элементы с обоих концов типизированного спана.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан для обрезки |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Элементы для обрезки |

### Возвращаемое значение

Новый спан с указанными элементами, обрезанными с обоих концов

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция

Обрезает указанные элементы с обоих концов изменяемого типизированного спана.

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Изменяемый спан для обрезки |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Элементы для обрезки |

### Возвращаемое значение

Новый спан с указанными элементами, обрезанными с обоих концов

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) функция

Обрезает пробельные символы с обоих концов спана символов.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Спан символов для обрезки |

### Возвращаемое значение

Новый спан, из которого пробельные символы обрезаны с обоих концов

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) функция

Обрезает пробельные символы с обоих концов изменяемого спана символов.

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый спан символов для обрезки |

### Возвращаемое значение

Новый спан, из которого пробельные символы обрезаны с обоих концов

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)