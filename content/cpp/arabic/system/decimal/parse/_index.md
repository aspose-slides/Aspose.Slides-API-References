---
title: Parse()
second_title: مرجع API Aspose.Slides للـ C++
description: يحول تمثيل السلسلة لعدد عشري إلى نسخة مكافئة من الفئة Decimal.
type: docs
weight: 469
url: /ar/system/decimal/parse/
---
## Decimal::Parse(const String\&) طريقة

يقوم بتحويل تمثيل السلسلة لعدد عشري إلى نسخة مكافئة من الفئة [Decimal](../).

```cpp
static Decimal System::Decimal::Parse(const String &s)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لعدد |

### قيمة الإرجاع

نسخة جديدة من الفئة [Decimal](../) تمثل قيمة مكافئة لتلك الممثلة بالسلسلة المحددة.

## Decimal::Parse(const String\&, Globalization::NumberStyles) طريقة

يقوم بتحويل تمثيل السلسلة لعدد عشري إلى نسخة مكافئة من الفئة [Decimal](../) باستخدام النمط المحدد.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة عشرية للتحويل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم التعداد الذي يوفر معلومات إضافية حول **s**, حول عناصر النمط التي قد تكون موجودة في **s**, أو حول التحويل من **s** إلى كائن [Decimal](../) |

### قيمة الإرجاع

نسخة جديدة من الفئة [Decimal](../) تمثل قيمة مكافئة لتلك الممثلة بالسلسلة المحددة.

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل تمثيل السلسلة لعدد عشري إلى نسخة مكافئة من الفئة [Decimal](../) باستخدام موفر الصيغة المحدد.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة عشرية للتحويل |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة |

### قيمة الإرجاع

نسخة جديدة من الفئة [Decimal](../) تمثل قيمة مكافئة لتلك الممثلة بالسلسلة المحددة.

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) طريقة

يقوم بتحويل تمثيل السلسلة لعدد عشري إلى نسخة مكافئة من الفئة [Decimal](../) باستخدام النمط وموفر الصيغة المحددين.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| s | const [String](../../string/)\& | تمثيل السلسلة لقيمة عشرية للتحويل |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | مزيج بتّي من قيم التعداد الذي يوفر معلومات إضافية حول **s**, حول عناصر النمط التي قد تكون موجودة في **s**, أو حول التحويل من **s** إلى كائن [Decimal](../) |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | موفر الصيغة |

### قيمة الإرجاع

نسخة جديدة من الفئة [Decimal](../) تمثل قيمة مكافئة لتلك الممثلة بالسلسلة المحددة.

## انظر أيضا

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* فئة [Decimal](../)
* فئة [String](../../string/)
* فئة [IFormatProvider](../../iformatprovider/)
* مساحة الاسم [System](../../)
* Library [Aspose.Slides](../../../)