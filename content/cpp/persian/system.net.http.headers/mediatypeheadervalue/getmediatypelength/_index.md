---
title: GetMediaTypeLength()
second_title: Aspose.Slides برای مرجع API C++
description: یک رشتهٔ ورودی را از اندیس مشخص شده به یک نمونه از کلاس MediaTypeHeaderValue تبدیل می‌کند.
type: docs
weight: 144
url: /fa/system.net.http.headers/mediatypeheadervalue/getmediatypelength/
---
## MediaTypeHeaderValue::GetMediaTypeLength(String, int32_t, HeaderFunc\<System::SharedPtr\<MediaTypeHeaderValue\>\>, System::SharedPtr\<MediaTypeHeaderValue\>\&) متد

یک رشتهٔ داده‌شده را از اندیس مشخص‌شده به یک نمونه از کلاس [MediaTypeHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::MediaTypeHeaderValue::GetMediaTypeLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<MediaTypeHeaderValue>> mediaTypeCreator, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | رشته‌ای برای تجزیه. |
| startIndex | **int32_t** | موقعیت شروع برای تجزیه. |
| mediaTypeCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\> | نماینده‌ای که برای ایجاد نمونه‌های کلاس [MediaTypeHeaderValue](../) استفاده می‌شود. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | نمونه‌ای که شیء تجزیه‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

طول زیررشتۀ تجزیه‌شده را برمی‌گرداند، در غیر این صورت 0.

## موارد مرتبط

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [MediaTypeHeaderValue](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)