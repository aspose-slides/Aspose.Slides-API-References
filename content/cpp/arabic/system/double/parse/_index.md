---
title: Parse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة العائمة ذات الدقة المزدوجة المكافئة.
type: docs
weight: 1
url: /ar/system/double/parse/
---
## Double::Parse(const String\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة العائمة ذات الدقة المزدوجة المكافئة.

```cpp
static double System::Double::Parse(const String &value)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |

### قيمة الإرجاع

القيمة العائمة ذات الدقة المزدوجة المكافئة للعدد الممثل في السلسلة المحددة.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة العائمة ذات الدقة المزدوجة المكافئة باستخدام معلومات التنسيق المقدمة.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

القيمة العائمة ذات الدقة المزدوجة المكافئة للعدد الممثل في السلسلة المحددة.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) طريقة




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

تحول السلسلة المحددة التي تحتوي على تمثيل عدد إلى القيمة العائمة ذات الدقة المزدوجة باستخدام معلومات التنسيق ونمط الرقم المقدمين.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة المراد تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم تعداد NumberStyles يحدد النمط المسموح لتمثيل العدد كسلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |

### قيمة الإرجاع

القيمة العائمة ذات الدقة المزدوجة المكافئة للعدد الممثل في السلسلة المحددة.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) طريقة




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) طريقة 




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) طريقة 




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## انظر أيضًا

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)