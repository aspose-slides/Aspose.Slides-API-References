---
title: GetCacheControlLength()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ داده‌شده را از اندیس مشخص‌شده به یک نمونه از کلاس CacheControlHeaderValue تبدیل می‌کند.
type: docs
weight: 456
url: /fa/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) متد

رشتهٔ ورودی را از اندیس مشخص‌شده به یک نمونه از کلاس [CacheControlHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | رشته‌ای برای تجزیه. |
| startIndex | **int32_t** | موقعیت شروع برای تجزیه. |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | مقداری که باید به شیء تجزیه‌شده اضافه شود. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | نمونه‌ای که شیء تجزیه‌شده به آن اختصاص خواهد یافت. |

### مقدار بازگشت

طول یک زیررشتهٔ تجزیه‌شده، در غیر این صورت 0.

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [CacheControlHeaderValue](../)
* فضای نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)