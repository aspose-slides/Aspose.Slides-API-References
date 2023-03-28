---
title: GetChars()
second_title: Aspose.Slides for C++ API Reference
description: Get the characters that result from decoding a byte buffer.
type: docs
weight: 66
url: /cpp/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const **uint8_t** *, int, char_t *, int) method


Get the characters that result from decoding a byte buffer.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) to put characters to. |
| char_count | int | Output buffer size. |

### Return Value

Number of written characters.

## See Also

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## ICUEncoding::GetChars([ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../../system/arrayptr/)\<char_t\>, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_index | int | Input buffer offset. |
| byte_count | int | Input buffer size. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) to put characters to. |
| char_index | int | Output buffer offset. |

### Return Value

Number of written characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## ICUEncoding::GetChars([ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, int, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Return Value

[Buffer](../../../system/buffer/) of decoded characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## ICUEncoding::GetChars([ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |

### Return Value

[Buffer](../../../system/buffer/) of decoded characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
## ICUEncoding::GetChars(const **uint8_t** *, int, char_t *, int) method


Get the characters that result from decoding a byte buffer.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_count | int | Input buffer size. |
| chars | char_t * | [Buffer](../../../system/buffer/) to put characters to. |
| char_count | int | Output buffer size. |

### Return Value

Number of written characters.

## See Also

* Class [ICUEncoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)
