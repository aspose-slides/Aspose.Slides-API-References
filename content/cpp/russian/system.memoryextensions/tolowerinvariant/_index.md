---
title: ToLowerInvariant()
second_title: Aspose.Slides для C++: справочник API
description: Преобразует символы в нижний регистр, используя инвариантную культуру.
type: docs
weight: 456
url: /ru/system.memoryextensions/tolowerinvariant/
---
## System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&) функция

Преобразует символы в нижний регистр, используя инвариантную культуру.

```cpp
int32_t System::MemoryExtensions::ToLowerInvariant(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination)
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Исходный диапазон символов для преобразования |
| destination | [Span](../../system/span/)\<char16_t\>\& | Диапазон назначения для хранения преобразованных символов |

### Возвращаемое значение

Количество преобразованных символов, или -1, если назначенный диапазон слишком мал

## See Also

* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)