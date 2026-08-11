---
title: GetProductInfoLength()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تحول السلسلة الممرَّرة من الفهرس المحدد إلى نسخة من الفئة ProductInfoHeaderValue.
type: docs
weight: 105
url: /ar/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) طريقة

تحول سلسلة مُمرَّرة من الفهرس المحدد إلى نسخة من الفئة [ProductInfoHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| input | [String](../../../system/string/) | سلسلة للتحليل. |
| startIndex | **int32_t** | موضع بدء للتحليل. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | مثال سيتم تعيين كائن تم تحليله فيه. |

### قيمة الإرجاع

يعيد طول الجزء الفرعي المحلل، وإلا 0.

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ProductInfoHeaderValue](../)
* نطاق [System::Net::Http::Headers](../../)
* مكتبة [Aspose.Slides](../../../)