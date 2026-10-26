---
title: Convert()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует символы в байты.
type: docs
weight: 79
url: /ru/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Преобразует символы в байты.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| charIndex | int | Смещение входного буфера. |
| charCount | int | Размер входного буфера. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер назначения байтов. |
| byteIndex | int | Смещение массива назначения. |
| byteCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную для хранения количества прочитанных символов. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества записанных байтов. |
| completed | **bool**\& | Ссылка на переменную, которая устанавливается в true, если входной буфер исчерпан, и в false в противном случае. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Преобразует символы в байты.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| charCount | int | Размер входного буфера. |
| bytes | **uint8_t** * | Буфер назначения байтов. |
| byteCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную для хранения количества прочитанных символов. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества записанных байтов. |
| completed | **bool**\& | Ссылка на переменную, которая устанавливается в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Encoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)