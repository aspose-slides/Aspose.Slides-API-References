---
title: GetDateTimeFormats()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُعيد مصفوفة من السلاسل حيث يكون كل عنصر هو تمثيل النص للكيان الحالي مُنسقًا باستخدام أحد محددات صيغة التاريخ والوقت القياسية.
type: docs
weight: 547
url: /ar/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const طريقة

يعيد مصفوفة من السلاسل حيث يكون كل عنصر هو تمثيل النص للكيان الحالي مُنسقًا باستخدام أحد صيغ التاريخ والوقت القياسية.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const طريقة

يعيد مصفوفة من السلاسل حيث يكون كل عنصر هو تمثيل النص للكيان الحالي مُنسقًا باستخدام محدد صيغة التاريخ والوقت القياسية المحدد.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | char_t | محدد صيغة التاريخ والوقت القياسية. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const طريقة

يعيد مصفوفة من السلاسل حيث يكون كل عنصر هو تمثيل النص للكيان الحالي مُنسقًا باستخدام أحد صيغ التاريخ والوقت القياسية ومُوفر الصيغة المحدد.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مُوفر الصيغة. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const طريقة

يعيد مصفوفة من السلاسل حيث يكون كل عنصر هو تمثيل النص للكيان الحالي مُنسقًا باستخدام محدد صيغة التاريخ والوقت القياسية المحدد ومُوفر الصيغة.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | char_t | محدد صيغة التاريخ والوقت القياسية. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | مُوفر الصيغة. |

## أنظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)