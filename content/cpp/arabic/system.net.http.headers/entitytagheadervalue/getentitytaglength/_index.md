---
title: GetEntityTagLength()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحوّل السلسلة المُمرَّرة من الفهرس المحدد إلى مثال من فئة EntityTagHeaderValue.
type: docs
weight: 118
url: /ar/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) طريقة

يحوّل السلسلة المُمرَّرة من الفهرس المحدد إلى مثال من الفئة [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### المعطيات

| معامل | نوع | وصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة لتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | مثال سيتم تعيين الكائن المحلل فيه. |

### قيمة الإرجاع

طول الجزء الفرعي المحلل، وإلا 0.

## أنظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [EntityTagHeaderValue](../)
* نطاق [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)