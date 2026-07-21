---
title: Convert()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует байты в символы.
type: docs
weight: 79
url: /ru/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) метод

Преобразует байты в символы.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение входного буфера. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение массива назначения. |
| charCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную для хранения количества записанных символов. |
| completed | **bool**\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) метод

Преобразует байты в символы.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| chars | char_t * | Буфер символов назначения. |
| charCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную для хранения количества записанных символов. |
| completed | **bool**\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Decoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)