---
title: ContainsAny()
second_title: Aspose.Slides для C++ справочник API
description: Проверяет, содержит ли только-для-чтения диапазон (span) хотя бы одно из двух значений.
type: docs
weight: 53
url: /ru/system.memoryextensions/containsany/
---
## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&) функция


Проверяет, содержит ли только-для-чтения диапазон (span) хотя бы одно из двух значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) функция


Проверяет, содержит ли только-для-чтения диапазон (span) хотя бы одно из трёх значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |
| value2 | const T\& | Третье значение для поиска |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&) функция


Проверяет, содержит ли изменяемый диапазон (span) хотя бы одно из двух значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый диапазон, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const T\&, const T\&, const T\&) функция


Проверяет, содержит ли изменяемый диапазон (span) хотя бы одно из трёх значений.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазоне |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый диапазон, в котором выполняется поиск |
| value0 | const T\& | Первое значение для поиска |
| value1 | const T\& | Второе значение для поиска |
| value2 | const T\& | Третье значение для поиска |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## System::MemoryExtensions::ContainsAny(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) функция


Проверяет, содержит ли только-для-чтения диапазон (span) любое значение из другого диапазона.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон, в котором выполняется поиск |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Диапазон значений, которые следует искать |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## System::MemoryExtensions::ContainsAny(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) функция


Проверяет, содержит ли изменяемый диапазон (span) любое значение из только-для-чтения диапазона.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAny(const Span<T> &span, const ReadOnlySpan<T> &values)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип элементов в диапазонах |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | Изменяемый диапазон, в котором выполняется поиск |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Только-для-чтения диапазон значений, которые следует искать |

### Возвращаемое значение

true если хотя бы одно из значений найдено в span, false в противном случае

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)