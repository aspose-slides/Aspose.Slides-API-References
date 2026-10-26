---
title: GetCharCount()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает количество символов, необходимых для декодирования буфера байтов.
type: docs
weight: 53
url: /ru/system.text/icuencoding/getcharcount/
---
## ICUEncoding::GetCharCount(const uint8_t *, int) метод

Получает количество символов, необходимых для декодирования буфера байтов.

```cpp
int System::Text::ICUEncoding::GetCharCount(const uint8_t *bytes, int count) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Возвращаемое значение

Number of characters.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) метод

Получает количество символов, необходимых для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | Slice beginning. |
| count | int | Slice size. |

### Возвращаемое значение

Number of characters.

## ICUEncoding::GetCharCount(ArrayPtr\<uint8_t\>) метод

Получает количество символов, необходимых для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |

### Возвращаемое значение

Number of characters.

## ICUEncoding::GetCharCount(const uint8_t *, int) метод

Получает количество символов, необходимых для декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Bytes count. |

### Возвращаемое значение

Number of characters.

## Смотрите также

* Типedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUEncoding](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)