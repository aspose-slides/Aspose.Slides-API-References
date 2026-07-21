---
title: Fallback()
second_title: Aspose.Slides для справки API на C++
description: Обрабатывает ошибку кодирования.
type: docs
weight: 27
url: /ru/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) метод

Обрабатывает ошибку кодирования.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknown | char_t | Неизвестные символы; игнорируются. |
| index | int | Смещение неизвестных символов; игнорируется. |

### Возвращаемое значение

На самом деле не возвращает, вместо этого бросает исключение.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) метод

Обрабатывает ошибку кодирования.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| charUnknownHigh | char_t | Старшая часть суррогатной пары, вызвавшей ошибку. |
| charUnknownLow | char_t | Нижняя часть суррогатной пары, вызвавшей ошибку. |
| index | int | Смещение неизвестного символа; игнорируется. |

### Возвращаемое значение

На самом деле не возвращает, вместо этого бросает исключение.

## См. также

* Класс [EncoderExceptionFallbackBuffer](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)