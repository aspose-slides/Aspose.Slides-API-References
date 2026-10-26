---
title: ToUpperInvariant()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует символы в верхний регистр, используя инвариантную культуру.
type: docs
weight: 482
url: /ru/system.memoryextensions/toupperinvariant/
---
## System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) функция

Преобразует символы к верхнему регистру, используя инвариантную культуру.

```cpp
int32_t System::MemoryExtensions::ToUpperInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Исходный диапазон символов для преобразования |
| destination | [Span](../../system/span/)\<char16_t\>\& | Диапазон назначения для сохранения преобразованных символов |

### Возвращаемое значение

Количество преобразованных символов или -1, если диапазон назначения слишком мал

## См. также

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имен [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)