---
title: Convert()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует байты в символы.
type: docs
weight: 1
url: /ru/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) метод


Преобразует байты в символы.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Параметры

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

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) метод


Преобразует байты в символы.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| byteIndex | int | Смещение во входном буфере. |
| byteCount | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Буфер символов назначения. |
| charIndex | int | Смещение в массиве назначения. |
| charCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную для хранения количества записанных символов. |
| completed | **bool**\& | Ссылка на переменную, которая будет установлена в true, если входной буфер исчерпан, и в false в противном случае. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [EncodingDecoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)