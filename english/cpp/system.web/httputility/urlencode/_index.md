---
title: UrlEncode()
second_title: Aspose.Slides for C++ API Reference
description: Encodes URI fragment.
type: docs
weight: 53
url: /cpp/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) method


Encodes URI fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI fragment to encode. |

### Return Value

Encoded URI fragment.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) method


Encodes URI fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [String](../../../system/string/) | URI fragment to encode. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | Encoding to use. |

### Return Value

Encoded URI fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) method


Encodes URI fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI fragment to encode. |

### Return Value

Encoded URI fragment.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


Encodes URI fragment.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | URI fragment to encode. |
| offset | **int32_t** | Offset in the given byte array. |
| count | **int32_t** | Number of bytes to read from. |

### Return Value

Encoded URI fragment.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)