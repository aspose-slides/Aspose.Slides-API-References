---
title: UrlEncodeToBytes()
second_title: مرجع API Aspose.Slides للـ C++
description: يقوم بترميز مقطع URI.
type: docs
weight: 66
url: /ar/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) method


يقوم بترميز مقطع URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | مقطع URI للترميز. |

### Return Value

مقطع URI المُرمّز.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) method


يقوم بترميز مقطع URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | مقطع URI للترميز. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | الترميز المطلوب استخدامه. |

### Return Value

مقطع URI المُرمّز.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) method


يقوم بترميز مقطع URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مقطع URI للترميز. |

### Return Value

مقطع URI المُرمّز.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


يقوم بترميز مقطع URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مقطع URI للترميز. |
| offset | **int32_t** | الإزاحة في مصفوفة البايتات المعطاة. |
| count | **int32_t** | عدد البايتات المطلوب قراءتها. |

### Return Value

مقطع URI المُرمّز.

## See Also

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [HttpUtility](../)
* فئة [Encoding](../../../system.text/encoding/)
* مساحة الاسم [System::Web](../../)
* مكتبة [Aspose.Slides](../../../)