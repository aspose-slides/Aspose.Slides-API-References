---
title: GetEntityTagLength()
second_title: Aspose.Slides برای مرجع API C++
description: یک رشتهٔ ورودی را از اندیس مشخص شده به یک نمونه از کلاس EntityTagHeaderValue تبدیل می‌کند.
type: docs
weight: 118
url: /fa/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) method

یک رشتهٔ ورودی را از اندیس مشخص شده به یک شیء از کلاس [EntityTagHeaderValue](../) تبدیل می‌کند.

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | رشته‌ای برای تجزیه. |
| startIndex | **int32_t** | موقعیت شروع برای تجزیه. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | نمونه‌ای که شیء تجزیه‌شده در آن اختصاص می‌یابد. |

### مقدار بازگشتی

طول زیررشتهٔ تجزیه‌شده، در غیر این صورت 0.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [EntityTagHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)