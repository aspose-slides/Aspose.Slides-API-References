---
title: UrlDecode()
second_title: Aspose.Slides for C++ API Reference
description: Decodes URI fragment from string.
type: docs
weight: 1
url: /cpp/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) method


Decodes URI fragment from string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Encoded URI fragment. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) method


Decodes URI fragment from string.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | Encoded URI fragment. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | Encoding to use. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from bytes array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Encoded URI fragment. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding to use. |

### Return Value

Decoded URI fragment.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) method


Decodes URI fragment from bytes array.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Encoded URI fragment. |
| offset | **int32_t** | Offset in the given byte array. |
| count | **int32_t** | Number of bytes to read from. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding to use. |

### Return Value

Decoded URI fragment.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)