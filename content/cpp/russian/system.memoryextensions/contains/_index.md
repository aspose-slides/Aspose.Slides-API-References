---
title: Contains()
second_title: Справочник API Aspose.Slides для C++
description: Проверяет, содержит ли только для чтения span заданное значение.
type: docs
weight: 40
url: /ru/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) функция

Проверяет, содержит ли только для чтения span заданное значение.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Span для поиска |
| value | const T\& | Значение для поиска |

### Возвращаемое значение

true если значение найдено в span, false в противном случае

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) функция

Проверяет, содержит ли изменяемый span заданное значение.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый span для поиска |
| value | const T\& | Значение для поиска |

### Возвращаемое значение

true если значение найдено в span, false в противном случае

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) функция

Проверяет, содержит ли символьный span другой символьный span с заданными правилами сравнения.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span для поиска |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Span для поиска |
| comparisonType | [StringComparison](../../system/stringcomparison/) | Тип сравнения строк |

### Возвращаемое значение

true если значение найдено в span, false в противном случае

## См. также

* Enum [StringComparison](../../system/stringcomparison/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Class [Span](../../system/span/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)