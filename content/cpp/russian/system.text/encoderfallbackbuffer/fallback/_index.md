---
title: Fallback()
second_title: Справочник API Aspose.Slides for C++
description: Реализует фактическую процедуру отката.
type: docs
weight: 14
url: /ru/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) метод

Реализует фактическую процедуру отката.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknown | char_t | Кодировщик символов не смог закодировать символ. |
| index | int | Индекс символа, вызвавшего ошибку. |

### Возвращаемое значение

True, если буфер обрабатывает неизвестные символы, false, если игнорирует их.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) метод

Реализует фактическую процедуру отката.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknownHigh | char_t | Высокая часть суррогатной пары, вызвавшей ошибку. |
| charUnknownLow | char_t | Низкая часть суррогатной пары, вызвавшей ошибку. |
| index | int | Индекс символа, вызвавшего ошибку. |

### Возвращаемое значение

True, если буфер обрабатывает неизвестные символы, false, если игнорирует их.

## См. также

* Класс [EncoderFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)