---
title: Fallback()
second_title: Aspose.Slides для C++ справочник API
description: Обрабатывает ошибку кодирования.
type: docs
weight: 27
url: /ru/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) метод

Обрабатывает ошибку кодирования.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknown | char_t | Неизвестный символ; игнорируется. |
| index | int | Позиция неизвестного символа; игнорируется. |

### Возвращаемое значение

True если строка замены предоставлена и не пуста, false в противном случае.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) метод

Обрабатывает ошибку кодирования.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknownHigh | char_t | Высокая часть суррогатной пары, вызвавшей ошибку. |
| charUnknownLow | char_t | Низкая часть суррогатной пары, вызвавшей ошибку. |
| index | int | Позиция неизвестного символа; игнорируется. |

### Возвращаемое значение

True если строка замены предоставлена и не пуста, false в противном случае.

## См. также

* Класс [EncoderReplacementFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)