---
title: TryParse()
second_title: مرجع API Aspose.Slides للغة C++
description: يحوّل السلسلة المحددة التي تحتوي على التمثيل النصي لعدد إلى عدد صحيح غير موقع 64-بت مكافئ.
type: docs
weight: 14
url: /ar/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) طريقة

يحوّل السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح غير موقع 64-بت مكافئ.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| result | **uint64_t**\& | المرجع إلى متغيّر عدد صحيح غير موقع 64-بت تُوضع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) طريقة

يحوّر السلسلة المحددة التي تحتوي على تمثيل نصي لرقم إلى عدد صحيح غير موقع 64-بت مكافئ باستخدام معلومات التنسيق المحددة ونمط الرقم المقدم.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة بشرية من قيم تعداد NumberStyles التي تحدد النمط المسموح به لتمثيل النص للرقم. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة. |
| result | **uint64_t**\& | المرجع إلى متغيّر عدد صحيح غير موقع 64-بت تُوضع فيه نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) طريقة

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) طريقة

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) طريقة

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* بنية [UInt64](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)