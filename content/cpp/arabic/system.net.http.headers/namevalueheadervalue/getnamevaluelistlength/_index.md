---
title: GetNameValueListLength()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بتحويل السلسلة المُمرَّرة من الفهرس المحدد إلى مجموعة من كائنات الفئة NameValueHeaderValue ويعيد طول الجزء الفرعي المُحلَّل.
type: docs
weight: 131
url: /ar/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) طريقة

يقوم بتحويل السلسلة المُمرَّرة من الفهرس المحدد إلى مجموعة من كائنات الفئة NameValueHeaderValue ويعيد طول الجزء الفرعي المُحلَّل.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة لتحليلها. |
| startIndex | **int32_t** | موضع بداية للتحليل. |
| delimiter | char16_t | سلسلة تُستخدم لتحديد فواصل العناصر في السلسلة المحددة. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | معامل المخرجات حيث سيتم تعيين مجموعة مُحلَّلة. |

### قيمة الإرجاع

طول الجزء الفرعي المُحلَّل.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ObjectCollection](../../objectcollection/)
* فئة [NameValueHeaderValue](../)
* مساحة الاسم [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)