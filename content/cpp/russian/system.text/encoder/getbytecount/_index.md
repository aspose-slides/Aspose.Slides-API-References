---
title: GetByteCount()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает количество байтов, необходимое для кодирования буфера.
type: docs
weight: 40
url: /ru/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) метод

Возвращает количество байтов, необходимое для кодирования буфера.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество символов для кодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возвращаемое значение

Количество байтов, необходимое для кодирования буфера.

## Encoder::GetByteCount(const char_t *, int, bool) метод

Возвращает количество байтов, необходимое для кодирования буфера.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| count | int | Количество символов для кодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возвращаемое значение

Количество байтов, необходимое для кодирования буфера.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)