---
title: GetRangeItemLength()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوِّل سلسلة مُمرَّرة من الفهرس المحدد إلى نسخة من الفئة RangeItemHeaderValue.
type: docs
weight: 92
url: /ar/system.net.http.headers/rangeitemheadervalue/getrangeitemlength/
---
## RangeItemHeaderValue::GetRangeItemLength(String, int32_t, System::SharedPtr\<RangeItemHeaderValue\>\&) طريقة

يحوِّل السلسلة المدخلة من الفهرس المحدد إلى نسخة من الفئة [RangeItemHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemLength(String input, int32_t startIndex, System::SharedPtr<RangeItemHeaderValue> &parsedValue)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\& | نسخة سيتم تعيين الكائن المُحلَّل إليها. |

### قيمة الإرجاع

تُعيد طول الجزء الفرعي المُحلَّل، وإلا 0.

## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [RangeItemHeaderValue](../)
* مساحة الاسم [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)