---
title: Compare()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن كائنات Uri المحددة باستخدام قواعد المقارنة المحددة.
type: docs
weight: 521
url: /ar/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) طريقة


يقارن الكائنات [Uri](../) المحددة باستخدام قواعد المقارنة المحددة.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | المقارن الأول |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | المقارن الثاني |
| partsToCompare | [UriComponents](../../uricomponents/) | يحدد أجزاء **uri1** و **uri2** للمقارنة |
| compareFormat | [UriFormat](../../uriformat/) | يحدد تهرب الأحرف المستخدم عند مقارنة مكونات عناوين URI |
| comparisonType | [StringComparison](../../stringcomparison/) | أحد قيم StringComparison |

### قيمة الإرجاع

قيمة سلبية إذا كان **uri1** أقل من **uri2**؛ 0 إذا كان uri1 و uri2 متساويين؛ قيمة إيجابية إذا كان **uri1** أكبر من **uri2**

## انظر أيضًا

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* فئة [Uri](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)