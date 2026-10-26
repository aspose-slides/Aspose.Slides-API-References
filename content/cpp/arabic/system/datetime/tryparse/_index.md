---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى كائن DateTime المكافئ.
type: docs
weight: 885
url: /ar/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) طريقة

يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى كائن [DateTime](../) المكافئ.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة تاريخ ووقت لتتم عملية التحويل. |
| result | [DateTime](../)\& | معامل الإخراج الذي، إذا نجحت عملية التحويل، يحتوي على نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

يقوم بتحويل تمثيل السلسلة المحدد لقيمة تاريخ ووقت إلى كائن [DateTime](../) المكافئ باستخدام معلومات تنسيق خاصة بالثقافة المحددة والنمط.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة تاريخ ووقت لتتم عملية التحويل. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | الكائن [IFormatProvider](../../iformatprovider/) الذي يوفر معلومات تنسيق خاصة بالثقافة. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | مجموعة تجميعية بالبتات من قيم التعداد التي توفر معلومات إضافية حول **s**، حول عناصر النمط التي قد تكون موجودة في **s**، أو حول التحويل من **s** إلى كائن [DateTime](../). |
| result | [DateTime](../)\& | معامل الإخراج الذي، إذا نجحت عملية التحويل، يحتوي على نتيجة التحويل. |

### قيمة الإرجاع

صحيح إذا نجحت عملية التحويل، وإلا - خطأ.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) طريقة

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## انظر أيضاً

* تعداد [DateTimeStyles](../../../system.globalization/datetimestyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* صنف [String](../../string/)
* صنف [DateTime](../)
* صنف [IFormatProvider](../../iformatprovider/)
* صنف [CultureInfo](../../../system.globalization/cultureinfo/)
* صنف [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)