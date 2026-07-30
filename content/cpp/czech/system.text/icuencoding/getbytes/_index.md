---
title: GetBytes()
second_title: Aspose.Slides pro C++ API referenci
description: Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.
type: docs
weight: 40
url: /cs/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_count | int | Output buffer size. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_index | int | Output buffer offset. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_index | int | Output buffer offset. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_index | int | Output buffer offset. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_index | int | Output buffer offset. |

### Návratová hodnota

Počet zapsaných bajtů.

## ICUEncoding::GetBytes(const String\&) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) k zakódování. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahující reprezentaci kódovaných znaků.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahující reprezentaci kódovaných znaků.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahující reprezentaci kódovaných znaků.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahující reprezentaci kódovaných znaků.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |

### Návratová hodnota

[Buffer](../../../system/buffer/) obsahující reprezentaci kódovaných znaků.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method

Získá bajty, které vzniknou kódováním znakové vyrovnávací paměti.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) pro umístění znaků. |
| byte_count | int | Output buffer size. |

### Návratová hodnota

Počet zapsaných bajtů.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [ICUEncoding](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Text](../../)
* Library [Aspose.Slides](../../../)