---
title: GetRangeItemListLength()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يقوم بتحويل السلسلة المُمرَّرة من الموضع المحدد إلى مجموعة من مثيلات فئة RangeItemHeaderValue.
type: docs
weight: 79
url: /ar/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) طريقة

يحوّل السلسلة المُمرَّرة من الموضع المحدد إلى مجموعة من مثيلات RangeItemHeaderValue-فئة.

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | مثيل سيتم تعيين مجموعة تم تحليلها فيه. |

### قيمة الإرجاع

طول الجزء الفرعي الذي تم تحليله، وإلا 0.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ICollection](../../../system.collections.generic/icollection/)
* فئة [RangeItemHeaderValue](../)
* نطاق [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)