---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحول السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى القيمة المساوية من نوع نقطة عائمة ذات دقة مزدوجة.
type: docs
weight: 14
url: /ar/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى القيمة المساوية من نوع نقطة عائمة ذات دقة مزدوجة.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| result | **double**\& | المرجع إلى متغير من نوع نقطة عائمة ذات دقة مزدوجة حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) طريقة

يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل العدد كسلسلة إلى القيمة المساوية من نوع نقطة عائمة ذات دقة مزدوجة باستخدام معلومات التنسيق المقدمة ونمط الرقم.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | تركيبة بتية من قيم تعداد NumberStyles التي تحدد النمط المسموح به لتمثيل السلسلة للعدد. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **double**\& | المرجع إلى متغير من نوع نقطة عائمة ذات دقة مزدوجة حيث يتم وضع نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) طريقة

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) طريقة

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) طريقة

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)