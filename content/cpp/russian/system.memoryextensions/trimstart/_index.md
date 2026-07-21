---
title: TrimStart()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет указанный элемент с начала типизированного спана.
type: docs
weight: 391
url: /ru/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) function

Удаляет указанный элемент с начала типизированного спана.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Спан для обрезки |
| trimElement | const T\& | Элемент для обрезки |

### Возвращаемое значение

Новый спан с удалённым указанным элементом с начала

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) function

Удаляет указанный элемент с начала изменяемого типизированного спана.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в спане |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Изменяемый спан для обрезки |
| trimElement | const T\& | Элемент для обрезки |

### Возвращаемое значение

Новый спан с удалённым указанным элементом с начала

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

Удаляет указанные элементы с начала типизированного спана.

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
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

Новый спан с удалёнными указанными элементами с начала

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

Удаляет указанные элементы с начала изменяемого типизированного спана.

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
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

Новый спан с удалёнными указанными элементами с начала

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) function

Удаляет пробельные символы с начала символьного спана.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символьный спан для обрезки |

### Возвращаемое значение

Новый спан с пробельными символами, удалёнными с начала

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) function

Удаляет пробельные символы с начала изменяемого символьного спана.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый символьный спан для обрезки |

### Возвращаемое значение

Новый спан с пробельными символами, удалёнными с начала

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) function

Удаляет указанный символ с начала символьного спана.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символьный спан для обрезки |
| trimchar | char16_t | Символ для обрезки |

### Возвращаемое значение

Новый спан с удалённым указанным символом с начала

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) function

Удаляет указанный символ с начала изменяемого символьного спана.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый символьный спан для обрезки |
| trimchar | char16_t | Символ для обрезки |

### Возвращаемое значение

Новый спан с удалённым указанным символом с начала

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Удаляет указанные символы с начала символьного спана.

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символьный спан для обрезки |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символы для обрезки |

### Возвращаемое значение

Новый спан с удалёнными указанными символами с начала

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) function

Удаляет указанные символы с начала изменяемого символьного спана.

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | Изменяемый символьный спан для обрезки |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Символы для обрезки |

### Возвращаемое значение

Новый спан с удалёнными указанными символами с начала

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)