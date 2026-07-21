---
title: GetChars()
second_title: Справочник API Aspose.Slides для C++
description: Получить символы, полученные в результате декодирования буфера байтов.
type: docs
weight: 92
url: /ru/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) чтобы читать байты из. |
| byte_index | int | Смещение входного буфера. |
| byte_count | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) чтобы разместить символы в. |
| char_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) чтобы читать байты из. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) чтобы разместить символы в. |
| char_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) чтобы читать байты из. |
| byte_index | int | Смещение входного буфера. |
| byte_count | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) чтобы разместить символы в. |
| char_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) чтобы читать байты из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) декодированных символов.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) чтобы читать байты из. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) декодированных символов.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) method

Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) чтобы читать байты из. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) чтобы разместить символы в. |
| char_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)