---
title: GetBytes()
second_title: Aspose.Slides for C++ API Reference
description: Get the bytes that result from encoding a character buffer.
type: docs
weight: 40
url: /system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method


Get the bytes that result from encoding a character buffer.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) to put characters to. |
| byte_count | int | Output buffer size. |

### Return Value

Number of written bytes.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### Return Value

Number of written bytes.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### Return Value

Number of written bytes.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


Get the bytes that result from encoding a character buffer.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### Return Value

Number of written bytes.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to put characters to. |
| byte_index | int | Output buffer offset. |

### Return Value

Number of written bytes.

## ICUEncoding::GetBytes(const String\&) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) to encode. |

### Return Value

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Return Value

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Return Value

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


Get the bytes that result from encoding a character buffer.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### Return Value

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |

### Return Value

[Buffer](../../../system/buffer/) that holds representation of characters being encoded.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) method


Get the bytes that result from encoding a character buffer.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) to put characters to. |
| byte_count | int | Output buffer size. |

### Return Value

Number of written bytes.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)