---
title: GetRangeItemListLength()
second_title: Aspose.Slides برای C++ مرجع API
description: یک رشتهٔ داده شده را از موقعیت مشخص به مجموعه‌ای از نمونه‌های کلاس RangeItemHeaderValue تبدیل می‌کند.
type: docs
weight: 79
url: /fa/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) متد

یک رشتهٔ داده شده را از موقعیت مشخص به مجموعه‌ای از نمونه‌های کلاس RangeItemHeaderValue تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | یک رشته برای تجزیه. |
| startIndex | **int32_t** | موقعیت شروع برای تجزیه. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | نمونه‌ای که مجموعهٔ تجزیه‌شده در آن اختصاص خواهد یافت. |

### مقدار بازگشت

طول زیررشتهٔ تجزیه‌شده، در غیر این صورت 0.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ICollection](../../../system.collections.generic/icollection/)
* کلاس [RangeItemHeaderValue](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* کتابخانه [Aspose.Slides](../../../)