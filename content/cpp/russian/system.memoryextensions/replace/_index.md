---
title: Replace()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет все вхождения значения новым значением в Span.
type: docs
weight: 287
url: /ru/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) функция


Заменяет все вхождения значения новым значением в [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в span |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | Span для модификации на месте |
| oldValue | const T\& | Значение для поиска и замены |
| newValue | const T\& | Новое значение, которым заменяется oldValue |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) функция


Копирует элементы из источника в назначение, заменяя указанные значения во время копирования.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| T | Тип элементов в spans |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | Источник [ReadOnlySpan](../../system/readonlyspan/) для копирования |
| destination | [Span](../../system/span/)\<T\>\& | Назначение [Span](../../system/span/) для копирования |
| oldValue | const T\& | Значение для поиска и замены во время копирования |
| newValue | const T\& | Новое значение, которым заменяется oldValue |

## See Also

* Class [Span](../../system/span/)
* Class [ReadOnlySpan](../../system/readonlyspan/)
* Namespace [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)