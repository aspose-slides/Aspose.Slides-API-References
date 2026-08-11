---
title: UrlEncode()
second_title: مرجع API Aspose.Slides برای C++
description: بخش URI را رمزگذاری می‌کند.
type: docs
weight: 53
url: /fa/system.web/httputility/urlencode/
---
## HttpUtility::UrlEncode(String) متد

بخش URI را کدگذاری می‌کند.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) | بخش URI برای کدگذاری. |

### مقدار بازگشت

بخش URI رمزگذاری شده.

## HttpUtility::UrlEncode(String, const System::SharedPtr\<Text::Encoding\>\&) متد

بخش URI را کدگذاری می‌کند.

```cpp
static String System::Web::HttpUtility::UrlEncode(String str, const System::SharedPtr<Text::Encoding> &e)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) | بخش URI برای کدگذاری. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری مورد استفاده. |

### مقدار بازگشت

بخش URI رمزگذاری شده.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&) متد

بخش URI را کدگذاری می‌کند.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بخش URI برای کدگذاری. |

### مقدار بازگشت

بخش URI رمزگذاری شده.

## HttpUtility::UrlEncode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t) متد

بخش URI را کدگذاری می‌کند.

```cpp
static String System::Web::HttpUtility::UrlEncode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بخش URI برای کدگذاری. |
| offset | **int32_t** | جابجایی در آرایه بایت داده شده. |
| count | **int32_t** | تعداد بایت‌های خوانده شده. |

### مقدار بازگشت

بخش URI رمزگذاری شده.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [HttpUtility](../)
* کلاس [Encoding](../../../system.text/encoding/)
* فضای نام [System::Web](../../)
* کتابخانه [Aspose.Slides](../../../)