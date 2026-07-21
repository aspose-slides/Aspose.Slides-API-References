---
title: GetByteCount()
second_title: Aspose.Slides для C++ API справка
description: Возвращает количество байтов, необходимых для кодирования буфера.
type: docs
weight: 40
url: /ru/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) метод

Возвращает количество байтов, необходимых для кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| index | int | [Buffer](../../../system/buffer/) смещение. |
| count | int | Количество символов для кодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возврат значения

Количество байтов, необходимых для кодирования буфера.

## ICUEncoder::GetByteCount(const char_t *, int, bool) метод

Возвращает количество байтов, необходимых для кодирования буфера.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| count | int | Количество символов для кодирования. |
| flush | **bool** | Если true, очищает внутреннее состояние кодировщика после вычисления. |

### Возврат значения

Количество байтов, необходимых для кодирования буфера.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUEncoder](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)