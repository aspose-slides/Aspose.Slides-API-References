---
title: GetString()
second_title: Aspose.Slides for C++ API Reference
description: Decodes a buffer of bytes into a string.
type: docs
weight: 313
url: /system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) method


Decodes a buffer of bytes into a string.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) to read bytes from. |
| byte_count | int | Input buffer size. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(ArrayPtr\<uint8_t\>) method


Decodes a buffer of bytes into a string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) method


Decodes a buffer of bytes into a string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) to read bytes from. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) method


Decodes a buffer of bytes into a string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) to read bytes from. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) method


Decodes a buffer of bytes into a string.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) method


Decodes a buffer of bytes into a string.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Return Value

[String](../../../system/string/) of decoded characters.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) method


Decodes a buffer of bytes into a string.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) to read bytes from. |
| index | int | Input buffer offset. |
| count | int | Input buffer size. |

### Return Value

[String](../../../system/string/) of decoded characters.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Encoding](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)