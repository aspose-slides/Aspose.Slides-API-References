---
title: GetString()
second_title: Aspose.Slides для C++ API Reference
description: Декодирует буфер байтов в строку.
type: docs
weight: 313
url: /ru/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) метод


Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_count | int | Input buffer size. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) метод


Декодирует буфер байтов в строку.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) to read bytes from. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(ArrayPtr\<uint8_t\>) метод


Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) метод


Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) to read bytes from. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) метод


Декодирует буфер байтов в строку.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) to read bytes from. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) метод


Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) метод


Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) метод


Декодирует буфер байтов в строку.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Возвращаемое значение

[String](../../../system/string/) of decoded characters.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)