---
title: GetChars()
second_title: Справочник API Aspose.Slides для C++
description: Получить символы, полученные в результате декодирования буфера.
type: docs
weight: 53
url: /ru/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) метод

Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение массива назначения. |

### Возвращаемое значение

Количество записанных символов.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) метод

Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество записанных символов.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) метод

Получить символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| chars | char_t * | Буфер символов назначения. |
| charCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество записанных символов.

## См. также

* Типedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUDecoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)