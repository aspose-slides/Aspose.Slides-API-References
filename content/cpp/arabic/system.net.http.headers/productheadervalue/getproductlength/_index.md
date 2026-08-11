---
title: GetProductLength()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوِّل السلسلة المُمرَّرة من الفهرس المحدد إلى كائن من الفئة ProductHeaderValue.
type: docs
weight: 105
url: /ar/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) طريقة

يحوِّل السلسلة المُمرَّرة من الفهرس المحدد إلى كائن من الفئة [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | كائن سيتم تعيين الكائن المحلل إليه. |

### قيمة الإرجاع

إرجاع طول الجزء الفرعي المُحلل، وإلا 0.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ProductHeaderValue](../)
* نطاق [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)