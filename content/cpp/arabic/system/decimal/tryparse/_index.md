---
title: TryParse()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوِّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى القيمة المكافئة من نوع Decimal.
type: docs
weight: 482
url: /ar/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) طريقة

يحوِّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى القيمة المكافئة من نوع [Decimal](../).

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها |
| result | [Decimal](../)\& | المرجع إلى متغيّر [Decimal](../) حيث تُوضع نتيجة التحويل |

### قيمة الإرجاع

True إذا نجح التحويل، وإلا - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) طريقة

يحوِّل السلسلة المحددة التي تحتوي على تمثيل عدد على شكل نص إلى القيمة المكافئة من نوع [Decimal](../) باستخدام معلومات التنسيق ونمط الرقم المحددين.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```

### الوسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| value | const [String](../../string/)\& | السلسلة التي سيتم تحويلها |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مجموعة قيم enum NumberStyles التي تحدد النمط المسموح به لتمثيل العدد كسلسلة |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مؤشر إلى كائن يحتوي على معلومات تنسيق السلسلة |
| result | [Decimal](../)\& | معامل إخراج؛ يحتوي على نتيجة التحويل |

### قيمة الإرجاع

True إذا نجح التحويل، وإلا - false

## انظر أيضًا

* تعداد [NumberStyles](../../../system.globalization/numberstyles/)
* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Decimal](../)
* فئة [IFormatProvider](../../iformatprovider/)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)