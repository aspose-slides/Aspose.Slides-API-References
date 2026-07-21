---
title: Convert()
second_title: Aspose.Slides для C++ Справочник API
description: Преобразует символы в байты.
type: docs
weight: 66
url: /ru/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) метод

Преобразует символы в байты.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Параметры

| Параметр | Тип | Описание |
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
| completed | **bool**\& | Ссылка на переменную, которая будет установлена в true, если входной буфер был исчерпан, и в false в противном случае. |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) метод

Преобразует символы в байты.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| charCount | int | Размер входного буфера. |
| bytes | **uint8_t** * | Буфер назначения байтов. |
| byteCount | int | Размер массива назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |
| charsUsed | int\& | Ссылка на переменную для хранения количества прочитанных символов. |
| bytesUsed | int\& | Ссылка на переменную для хранения количества записанных байтов. |
| completed | **bool**\& | Ссылка на переменную, которая будет установлена в true, если входной буфер был исчерпан, и в false в противном случае. |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)