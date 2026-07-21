---
title: TrimEnd()
second_title: Aspose.Slides для C++ справочник API
description: Обрезает указанный элемент с конца типизированного span.
type: docs
weight: 378
url: /ru/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) функция


Обрезает указанный элемент с конца типизированного span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который нужно обрезать |
| trimElement | const T\& | Элемент, который нужно обрезать |

### Возвращаемое значение

Новый span с указанным элементом, обрезанным с конца

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) функция


Обрезает указанный элемент с конца изменяемого типизированного span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Изменяемый span, который нужно обрезать |
| trimElement | const T\& | Элемент, который нужно обрезать |

### Возвращаемое значение

Новый span с указанным элементом, обрезанным с конца

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция


Обрезает указанные элементы с конца типизированного span.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span, который нужно обрезать |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Элементы, которые нужно обрезать |

### Возвращаемое значение

Новый span с указанными элементами, обрезанными с конца

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция


Обрезает указанные элементы с конца изменяемого типизированного span.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Изменяемый span, который нужно обрезать |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Элементы, которые нужно обрезать |

### Возвращаемое значение

Новый span с указанными элементами, обрезанными с конца

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) функция


Обрезает пробельные символы с конца спана символов.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Спан символов, который нужно обрезать |

### Возвращаемое значение

Новый span с пробелами, обрезанными с конца

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) функция


Обрезает пробельные символы с конца изменяемого спана символов.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый спан символов, который нужно обрезать |

### Возвращаемое значение

Новый span с пробелами, обрезанными с конца

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) функция


Обрезает указанный символ с конца спана символов.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Спан символов, который нужно обрезать |
| trimchar | char16_t | Символ, который нужно обрезать |

### Возвращаемое значение

Новый span с указанным символом, обрезанным с конца

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) функция


Обрезает указанный символ с конца изменяемого спана символов.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый спан символов, который нужно обрезать |
| trimchar | char16_t | Символ, который нужно обрезать |

### Возвращаемое значение

Новый span с указанным символом, обрезанным с конца

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) функция


Обрезает указанные символы с конца спана символов.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Спан символов, который нужно обрезать |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символы, которые нужно обрезать |

### Возвращаемое значение

Новый span с указанными символами, обрезанными с конца

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) функция


Обрезает указанные символы с конца изменяемого спана символов.

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый спан символов, который нужно обрезать |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символы, которые нужно обрезать |

### Возвращаемое значение

Новый span с указанными символами, обрезанными с конца

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)