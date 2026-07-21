---
title: GetBytes()
second_title: Справочник API Aspose.Slides для C++
description: Получить байты, полученные в результате кодирования буфера символов.
type: docs
weight: 40
url: /ru/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| char_count | int | Количество символов для преобразования. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в буфере вывода. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в буфере вывода. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Символы для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в буфере вывода. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |
| char_index | int | Начало фрагмента символов. |
| char_count | int | Количество символов для преобразования. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_index | int | Смещение в буфере вывода. |

### Возвращаемое значение

Количество записанных байтов.

## ICUEncoding::GetBytes(const String\&) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) для кодирования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) который содержит представление кодируемых символов.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) который содержит представление кодируемых символов.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) который содержит представление кодируемых символов.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Символы для кодирования. |
| index | int | Начало фрагмента символов. |
| count | int | Количество символов для преобразования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) который содержит представление кодируемых символов.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Символы для кодирования. |

### Возвращаемое значение

[Buffer](../../../system/buffer/) который содержит представление кодируемых символов.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) метод


Получить байты, полученные в результате кодирования буфера символов.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| chars | const char_t * | Символы для кодирования. |
| char_count | int | Количество символов для преобразования. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) для размещения символов. |
| byte_count | int | Размер выходного буфера. |

### Возвращаемое значение

Количество записанных байтов.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ICUEncoding](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Text](../../)
* Библиотека [Aspose.Slides](../../../)