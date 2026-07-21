---
title: ToUpper()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует символы в верхний регистр, используя указанную культуру.
type: docs
weight: 469
url: /ru/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t>&, Span<char16_t>&, const SharedPtr<Globalization::CultureInfo>&) функция

Преобразует символы в верхний регистр, используя указанную культуру.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)<char16_t>& | Исходный диапазон символов для преобразования |
| destination | [Span](../../system/span/)<char16_t>& | Диапазон назначения для хранения преобразованных символов |
| culture | const [SharedPtr](../../system/sharedptr/)<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)>& | Культура, используемая для преобразования (nullptr для текущей культуры) |

### Возвращаемое значение

Количество преобразованных символов или -1, если диапазон назначения слишком мал

## См. также

* typedef [SharedPtr](../../system/sharedptr/)
* class [ReadOnlySpan](../../system/readonlyspan/)
* class [Span](../../system/span/)
* class [CultureInfo](../../system.globalization/cultureinfo/)
* namespace [System::MemoryExtensions](../)
* библиотека [Aspose.Slides](../../)