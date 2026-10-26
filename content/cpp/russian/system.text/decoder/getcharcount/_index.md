---
title: GetCharCount()
second_title: Справочник API Aspose.Slides для C++
description: Получает количество символов, необходимых для декодирования буфера.
type: docs
weight: 40
url: /ru/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод

Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |

### Возвращаемое значение

Количество символов, необходимое для декодирования буфера.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) метод

Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Байты для декодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество байтов для декодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество символов, необходимое для декодирования буфера.

## Decoder::GetCharCount(const uint8_t *, int, bool) метод

Получает количество символов, необходимых для декодирования буфера.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Байты для декодирования. |
| count | int | Количество байтов для декодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние декодера после вычисления. |

### Возвращаемое значение

Количество символов, необходимое для декодирования буфера.

## См. также

* Типedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Decoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)