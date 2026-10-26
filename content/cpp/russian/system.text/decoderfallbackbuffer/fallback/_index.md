---
title: Fallback()
second_title: Aspose.Slides для C++ справочник API
description: Реализует фактическую процедуру отката.
type: docs
weight: 14
url: /ru/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) метод

Реализует фактическую процедуру отката.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) байтов, включая тот, который декодер не смог декодировать. |
| index | int | Индекс байта, вызвавшего ошибку. |

### Возвращаемое значение

True если буфер обрабатывает неизвестные байты, false если он их игнорирует.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [DecoderFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)