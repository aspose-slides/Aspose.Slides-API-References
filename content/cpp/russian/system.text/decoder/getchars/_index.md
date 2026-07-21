---
title: GetChars()
second_title: Aspose.Slides для C++ справочник API
description: Получает символы, полученные в результате декодирования буфера.
type: docs
weight: 53
url: /ru/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Получает символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение целевого массива. |

### Возвращаемое значение

Количество записанных символов.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Получает символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение целевого массива. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество записанных символов.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Получает символы, полученные в результате декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| chars | char_t * | Буфер символов назначения. |
| charCount | int | Размер целевого массива. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество записанных символов.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Decoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)