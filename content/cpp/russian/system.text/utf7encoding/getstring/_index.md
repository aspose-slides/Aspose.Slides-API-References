---
title: GetString()
second_title: Справочник API Aspose.Slides для C++
description: Декодирует буфер байтов в строку.
type: docs
weight: 170
url: /ru/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) метод

Декодирует буфер байтов в строку.

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(uint8_t *, int) метод

Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) для чтения байтов из. |
| byte_count | int | Размер входного буфера. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) метод

Декодирует буфер байтов в строку.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) для чтения байтов из. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) метод

Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) метод

Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) для чтения байтов из. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) метод

Декодирует буфер байтов в строку.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) для чтения байтов из. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) метод

Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для чтения байтов из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) метод

Декодирует буфер байтов в строку.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) для чтения байтов из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) метод

Декодирует буфер байтов в строку.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) для чтения байтов из. |
| index | int | Смещение входного буфера. |
| count | int | Размер входного буфера. |

### Возвращаемое значение

[String](../../../system/string/) декодированных символов.

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [UTF7Encoding](../)
* Класс [ReadOnlySpan](../../../system/readonlyspan/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)