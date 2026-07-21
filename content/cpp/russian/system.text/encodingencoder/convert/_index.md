---
title: Convert()
second_title: Aspose.Slides для C++ справочник API
description: Преобразует символы в байты.
type: docs
weight: 1
url: /ru/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) метод

Преобразует символы в байты.

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| charCount | int | Размер входного буфера. |
| bytes | **uint8_t** * | Буфер назначения байтов. |
| byteCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную, в которой сохраняется количество считанных символов. |
| bytesUsed | int\& | Ссылка на переменную, в которой сохраняется количество записанных байтов. |
| completed | **bool**\& | Ссылка на переменную, которая устанавливается в true, если входной буфер исчерпан, и в false в противном случае. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) метод

Преобразует символы в байты.

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| charIndex | int | Смещение во входном буфере. |
| charCount | int | Размер входного буфера. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер назначения байтов. |
| byteIndex | int | Смещение в массиве назначения. |
| byteCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную, в которой сохраняется количество считанных символов. |
| bytesUsed | int\& | Ссылка на переменную, в которой сохраняется количество записанных байтов. |
| completed | **bool**\& | Ссылка на переменную, которая устанавливается в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [EncodingEncoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)