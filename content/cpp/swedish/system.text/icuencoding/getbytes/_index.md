---
title: GetBytes()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar de byte som resultat av att koda en teckenbuffert.
type: docs
weight: 40
url: /sv/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| char_count | int | Antal tecken att konvertera. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_count | int | Storlek på utdata-buffert. |

### Returvärde

Antal skrivna byte.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_index | int | Offset för utdata-buffert. |

### Returvärde

Antal skrivna byte.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_index | int | Offset för utdata-buffert. |

### Returvärde

Antal skrivna byte.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Tecken att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_index | int | Offset för utdata-buffert. |

### Returvärde

Antal skrivna byte.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) att koda. |
| char_index | int | Start på teckensegmentet. |
| char_count | int | Antal tecken att konvertera. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_index | int | Offset för utdata-buffert. |

### Returvärde

Antal skrivna byte.

## ICUEncoding::GetBytes(const String\&) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) att koda. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av tecken som kodas.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av tecken som kodas.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av tecken som kodas.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Tecken att koda. |
| index | int | Start på teckensegmentet. |
| count | int | Antal tecken att konvertera. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av tecken som kodas.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tecken att koda. |

### Returvärde

[Buffer](../../../system/buffer/) som innehåller representation av tecken som kodas.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metod


Hämta de byte som resultat av att koda en teckenbuffert.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Tecken att koda. |
| char_count | int | Antal tecken att konvertera. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) för att lagra tecken. |
| byte_count | int | Storlek på utdata-buffert. |

### Returvärde

Antal skrivna byte.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [ICUEncoding](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Text](../../)
* Bibliotek [Aspose.Slides](../../../)