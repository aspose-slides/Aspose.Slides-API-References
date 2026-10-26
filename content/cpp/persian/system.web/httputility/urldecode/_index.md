---
title: UrlDecode()
second_title: مرجع API Aspose.Slides برای C++
description: پاره‌قطعه URI را از رشته رمزگشایی می‌کند.
type: docs
weight: 1
url: /fa/system.web/httputility/urldecode/
---
## HttpUtility::UrlDecode(String) متد

پاره‌قطعه URI را از رشته رمزگشایی می‌کند.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) | پاره‌قطعهٔ URI رمزگذاری‌شده. |

### مقدار بازگشت

پاره‌قطعه URI رمزگشایی شده.

## HttpUtility::UrlDecode(String, System::SharedPtr\<Text::Encoding\>) متد

پاره‌قطعه URI را از رشته رمزگشایی می‌کند.

```cpp
static String System::Web::HttpUtility::UrlDecode(String str, System::SharedPtr<Text::Encoding> e)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| str | [String](../../../system/string/) | پاره‌قطعهٔ URI رمزگذاری‌شده. |
| e | [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\> | رمزگذاری برای استفاده. |

### مقدار بازگشت

پاره‌قطعه URI رمزگشایی شده.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, const System::SharedPtr\<Text::Encoding\>\&) متد

پاره‌قطعه URI را از آرایه بایت‌ها رمزگشایی می‌کند.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, const System::SharedPtr<Text::Encoding> &e)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | پاره‌قطعهٔ URI رمزگذاری‌شده. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری برای استفاده. |

### مقدار بازگشت

پاره‌قطعه URI رمزگشایی شده.

## HttpUtility::UrlDecode(const System::ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const System::SharedPtr\<Text::Encoding\>\&) متد

پاره‌قطعه URI را از آرایه بایت‌ها رمزگشایی می‌کند.

```cpp
static String System::Web::HttpUtility::UrlDecode(const System::ArrayPtr<uint8_t> &bytes, int32_t offset, int32_t count, const System::SharedPtr<Text::Encoding> &e)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | const [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | پاره‌قطعهٔ URI رمزگذاری‌شده. |
| offset | **int32_t** | افست در آرایه بایت داده شده. |
| count | **int32_t** | تعداد بایت‌هایی که باید خوانده شوند. |
| e | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::Encoding](../../../system.text/encoding/)\>\& | رمزگذاری برای استفاده. |

### مقدار بازگشت

پاره‌قطعه URI رمزگشایی شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [HttpUtility](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Web](../../)
* Library [Aspose.Slides](../../../)