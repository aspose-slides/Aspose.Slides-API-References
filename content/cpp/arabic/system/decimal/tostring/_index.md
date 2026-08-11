---
title: ToString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد تمثيل السلسلة للقيمة التي يمثلها الكائن.
type: docs
weight: 352
url: /ar/system/decimal/tostring/
---
## Decimal::ToString() const طريقة

يرجع تمثيل السلسلة للقيمة التي يمثلها الكائن.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const طريقة

يحوّل الكائن الحالي إلى سلسلة باستخدام معلومات التنسيق الخاصة بالثقافة.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن [IFormatProvider](../../iformatprovider/) الذي يقدم معلومات التنسيق الخاصة بالثقافة. |

### قيمة الإرجاع

تمثيل السلسلة للكائن الحالي.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const طريقة




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const طريقة




```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const طريقة




```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const طريقة

يحوّل الكائن الحالي إلى تمثيله السلسلي باستخدام تنسيق السلسلة المحدد ومعلومات التنسيق الخاصة بالثقافة التي يقدمها كائن [IFormatProvider](../../iformatprovider/) المحدد.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| format | const [String](../../string/)\& | تنسيق السلسلة. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن [IFormatProvider](../../iformatprovider/) الذي يقدم معلومات التنسيق الخاصة بالثقافة. |

### قيمة الإرجاع

تمثيل السلسلة للكائن الحالي.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const طريقة




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const طريقة




```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const طريقة




```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)