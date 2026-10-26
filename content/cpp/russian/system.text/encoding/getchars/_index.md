---
title: GetChars()
second_title: Справочник API Aspose.Slides for C++
description: Получить символы, полученные в результате декодирования буфера байтов.
type: docs
weight: 274
url: /ru/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов. |
| byte_index | int | Смещение во входном буфере. |
| byte_count | int | Размер входного буфера. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) для записи символов. |
| char_index | int | Смещение в выходном буфере. |

### Возвращаемое значение

Количество записанных символов.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов. |
| index | int | Смещение во входном буфере. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) декодированных символов.

## Encoding::GetChars(ArrayPtr\<uint8_t\>) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) декодированных символов.

## Encoding::GetChars(const uint8_t *, int, char_t *, int) method


Получить символы, полученные в результате декодирования буфера байтов.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) для чтения байтов. |
| byte_count | int | Размер входного буфера. |
| chars | char_t * | [Buffer](../../../system/buffer/) для записи символов. |
| char_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных символов.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [Encoding](../)
* Пространство имён [System::Text](../../)
* Library [Aspose.Slides](../../../)