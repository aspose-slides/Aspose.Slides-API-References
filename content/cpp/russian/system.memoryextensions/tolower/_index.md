---
title: ToLower()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует символы в нижний регистр, используя указанную культуру.
type: docs
weight: 443
url: /ru/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) функция

Преобразует символы в нижний регистр, используя указанную культуру.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Исходный диапазон символов для преобразования |
| destination | [Span](../../system/span/)\<char16_t\>\& | Диапазон назначения для сохранения преобразованных символов |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Культура, используемая для преобразования (nullptr для текущей культуры) |

### Возвращаемое значение

Количество преобразованных символов или -1, если диапазон назначения слишком мал

## См. также

* Тип [SharedPtr](../../system/sharedptr/)
* Класс [ReadOnlySpan](../../system/readonlyspan/)
* Класс [Span](../../system/span/)
* Класс [CultureInfo](../../system.globalization/cultureinfo/)
* Пространство имён [System::MemoryExtensions](../)
* Библиотека [Aspose.Slides](../../)