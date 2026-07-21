---
title: GetBytes()
second_title: Aspose.Slides для C++ справочник API
description: Получить байты, полученные в результате кодирования буфера символов.
type: docs
weight: 66
url: /ru/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| char_count | int | Количество символов для преобразования. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_index | int | Смещение выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## UTF7Encoding::GetBytes(const String\&) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) которая содержит представление кодируемых символов.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) которая содержит представление кодируемых символов.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) которая содержит представление кодируемых символов.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) которая содержит представление кодируемых символов.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) которая содержит представление кодируемых символов.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method

Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| char_count | int | Количество символов для преобразования. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) для помещения символов. |
| byte_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Класс [UTF7Encoding](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)