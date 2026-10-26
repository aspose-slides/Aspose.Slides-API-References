---
title: Convert()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует байты в символы.
type: docs
weight: 66
url: /ru/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method


Преобразует байты в символы.

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
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
| bytesUsed | int\& | Ссылка на переменную, в которую сохраняется количество прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную, в которую сохраняется количество записанных символов. |
| completed | **bool**\& | Ссылка на переменную, которую устанавливают в true, если входной буфер исчерпан, иначе в false. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method


Преобразует байты в символы.

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| byteCount | int | Размер входного буфера. |
| chars | char_t * | Буфер символов назначения. |
| charCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |
| bytesUsed | int\& | Ссылка на переменную, в которую сохраняется количество прочитанных байтов. |
| charsUsed | int\& | Ссылка на переменную, в которую сохраняется количество записанных символов. |
| completed | **bool**\& | Ссылка на переменную, которую устанавливают в true, если входной буфер исчерпан, иначе в false. |

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUDecoder](../)
* Пространство имен [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)