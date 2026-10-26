---
title: Fallback()
second_title: Справочник API Aspose.Slides для C++
description: Обрабатывает ошибку декодирования.
type: docs
weight: 27
url: /ru/system.text/decoderexceptionfallbackbuffer/fallback/
---
## DecoderExceptionFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) метод

Обрабатывает ошибку декодирования.

```cpp
virtual bool System::Text::DecoderExceptionFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) неизвестных байтов; игнорируется. |
| index | int | Смещение неизвестных байтов; игнорируется. |

### Возвращаемое значение

На самом деле никогда не возвращает, вместо этого бросает исключение.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [DecoderExceptionFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)