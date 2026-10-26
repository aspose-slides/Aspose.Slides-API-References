---
title: GetRangeItemLength()
second_title: مرجع API Aspose.Slides برای C++
description: یک رشتهٔ داده‌شده را از اندیس مشخص به یک نمونه از کلاس RangeItemHeaderValue تبدیل می‌کند.
type: docs
weight: 92
url: /fa/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) متد


یک رشتهٔ ورودی را از ایندکس مشخص به یک نمونه از کلاس [RangeItemHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input | [String](../../../system/string/) | یک رشته برای تجزیه. |
| startIndex | **int32_t** | یک موقعیت شروع برای تجزیه. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | یک نمونه که شیء تجزیه‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشت

طول زیررشتهٔ تجزیه‌شده را بر می‌گرداند، در غیر اینصورت 0.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [RangeItemHeaderValue](../)
* فضای‌نام [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)