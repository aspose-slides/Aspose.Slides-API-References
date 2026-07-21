---
title: Fallback()
second_title: Справочник API Aspose.Slides для C++
description: Обрабатывает ошибку декодирования.
type: docs
weight: 27
url: /ru/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) метод

Обрабатывает ошибку декодирования.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) неизвестных байтов; игнорируется. |
| index | int | Смещение неизвестных байтов; игнорируется. |

### Возвращаемое значение

True если строка замены предоставлена и не пуста, false в противном случае.

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [DecoderReplacementFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)