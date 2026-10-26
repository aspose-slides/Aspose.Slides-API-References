---
title: GetChars()
second_title: Справочник API Aspose.Slides for C++
description: Получить символы, полученные в результате декодирования буфера байтов.
type: docs
weight: 66
url: /ru/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) метод

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) для чтения байтов из. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) для помещения символов в. |
| char_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) метод

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |
| byte_index | int | Смещение входного буфера. |
| byte_count | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) для помещения символов в. |
| char_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) метод

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) раскодированных символов.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) метод

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) раскодированных символов.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) метод

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) для чтения байтов из. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) для помещения символов в. |
| char_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUEncoding](../)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)