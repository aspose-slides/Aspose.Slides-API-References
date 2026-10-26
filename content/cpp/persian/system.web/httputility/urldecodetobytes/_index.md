---
title: UrlDecodeToBytes()
second_title: مرجع API Aspose.Slides برای C++
description: قطعهٔ URI را از آرایه بایت‌ها رمزگشایی می‌کند.
type: docs
weight: 14
url: /fa/system.web/httputility/urldecodetobytes/
---
## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&) متد


قطعهٔ URI را از آرایه بایت‌ها رمزگشایی می‌کند.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | قطعهٔ URI کدگذاری‌شده. |

### مقدار بازگشتی

قطعهٔ URI رمزگشایی‌شده.

## HttpUtility::UrlDecodeToBytes(const String\&) متد


قطعهٔ URI را از رشته بایت‌ها رمزگشایی می‌کند.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | قطعهٔ URI کدگذاری‌شده. |

### مقدار بازگشتی

قطعهٔ URI رمزگشایی‌شده.

## HttpUtility::UrlDecodeToBytes(const String\&, const System::SharedPtr\<Text::Encoding\>\&) متد


قطعهٔ URI را از رشته رمزگشایی می‌کند.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const String &str, const System::SharedPtr<Text::Encoding> &e)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | قطعهٔ URI کدگذاری‌شده. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری مورد استفاده. |

### مقدار بازگشتی

قطعهٔ URI رمزگشایی‌شده.

## HttpUtility::UrlDecodeToBytes(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد


قطعهٔ URI را از آرایه بایت‌ها رمزگشایی می‌کند.

```cpp
static System::ArrayPtr<uint8_t> System::Web::HttpUtility::UrlDecodeToBytes(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | قطعهٔ URI کدگذاری‌شده. |
| offset | **int32_t** | افست در آرایه بایت داده شده. |
| count | **int32_t** | تعداد بایت‌ها برای خواندن. |

### مقدار بازگشتی

قطعهٔ URI رمزگشایی‌شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [HttpUtility](../)
* کلاس [String](../../../system/string/)
* کلاس [Encoding](../../../system.text/encoding/)
* فضای نام [System::Web](../../)
* کتابخانه [Aspose.Slides](../../../)