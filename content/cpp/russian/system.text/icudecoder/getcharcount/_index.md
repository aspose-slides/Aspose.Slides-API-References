---
title: GetCharCount()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает количество символов, необходимых для декодирования буфера.
type: docs
weight: 40
url: /ru/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод


Возвращает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |

### Возвращаемое значение

Количество символов, необходимых для декодирования буфера.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) метод


Возвращает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после расчёта. |

### Возвращаемое значение

Количество символов, необходимых для декодирования буфера.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) метод


Возвращает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| count | int | Количество байтов для декодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после расчёта. |

### Возвращаемое значение

Количество символов, необходимых для декодирования буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUDecoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)