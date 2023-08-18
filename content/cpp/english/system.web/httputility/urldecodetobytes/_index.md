---
title: UrlDecodeToBytes()
second_title: Aspose.Slides for C++ API Reference
description: Decodes URI fragment from bytes array.
type: docs
weight: 14
url: /system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


Decodes URI fragment from bytes array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Encoded URI fragment. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecodeToBytes(const String\&) method


Decodes URI fragment from bytes string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Encoded URI fragment. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from string.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Encoded URI fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding to use. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Decodes URI fragment from bytes array.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Encoded URI fragment. |
| offset | **int32_t** | Offset in the given byte array. |
| count | **int32_t** | Number of bytes to read from. |

### Return Value

Decoded URI fragment.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpUtility](../)
* Class [String](../../../system/string/)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)