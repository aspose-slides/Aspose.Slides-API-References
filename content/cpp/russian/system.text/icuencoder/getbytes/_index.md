---
title: GetBytes()
second_title: Справочник API Aspose.Slides для C++
description: Получить байты, полученные в результате кодирования буфера.
type: docs
weight: 53
url: /ru/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) метод

Получить байты, полученные в результате кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| charIndex | int | Смещение в исходном массиве. |
| charCount | int | Длина подмассива источника. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Буфер назначения байтов. |
| byteIndex | int | Смещение в буфере назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) метод

Получить байты, полученные в результате кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| charCount | int | Длина исходного массива. |
| bytes | **uint8_t** * | Буфер назначения байтов. |
| byteCount | int | Размер буфера назначения. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возвращаемое значение

Количество записанных байтов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)