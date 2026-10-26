---
title: UrlEncodeToBytes()
second_title: مرجع API Aspose.Slides برای C++
description: بخش URI را کدگذاری می‌کند.
type: docs
weight: 66
url: /fa/system.web/httputility/urlencodetobytes/
---
## HttpUtility::UrlEncodeToBytes(const String\&) متد

کدگذاری بخش URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | بخشی از URI برای کدگذاری. |

### مقدار بازگشت

بخش کدگذاری‌شده URI.

## HttpUtility::UrlEncodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) متد

کدگذاری بخش URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | بخشی از URI برای کدگذاری. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری مورد استفاده. |

### مقدار بازگشت

بخش کدگذاری‌شده URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&) متد

کدگذاری بخش URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بخشی از URI برای کدگذاری. |

### مقدار بازگشت

بخش کدگذاری‌شده URI.

## HttpUtility::UrlEncodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

کدگذاری بخش URI.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlEncodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بخشی از URI برای کدگذاری. |
| offset | **int32_t** | افست در آرایه بایت داده‌شده. |
| count | **int32_t** | تعداد بایت‌های خوانده‌شده. |

### مقدار بازگشت

بخش کدگذاری‌شده URI.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [HttpUtility](../)
* کلاس [Encoding](../../../system.text/encoding/)
* فضای نام [System::Web](../../)
* Library [Aspose.Slides](../../../)