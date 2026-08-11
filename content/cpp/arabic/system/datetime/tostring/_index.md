---
title: ToString()
second_title: مرجع API ل Aspose.Slides للغة C++
description: تعيد تمثيل النص للقيمة التاريخية والوقتية التي يمثلها الكائن الحالي باستخدام قواعد التنسيق المحددة من قبل الثقافة الحالية.
type: docs
weight: 482
url: /ar/system/datetime/tostring/
---
## DateTime::ToString() const طريقة

تُرجع تمثيل النص للقيمة التاريخية والوقتية التي يمثلها الكائن الحالي باستخدام قواعد التنسيق المحددة بواسطة الثقافة الحالية.

```cpp
String System::DateTime::ToString() const
```

### قيمة الإرجاع

تمثيل النص للقيمة التي يمثلها الكائن الحالي

## DateTime::ToString(const String\&) const طريقة

تُرجع تمثيل النص للقيمة التاريخية والوقتية التي يمثلها الكائن الحالي باستخدام الصيغة المحددة وقواعد التنسيق المعرفّة بواسطة الثقافة الحالية.

```cpp
String System::DateTime::ToString(const String &format) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../string/)\& | سلسلة تنسيق |

### قيمة الإرجاع

تمثيل النص للقيمة التي يمثلها الكائن الحالي مُنسّق وفقًا للصيغة المحددة بواسطة **format** والثقافة الحالية.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const طريقة

تُرجع تمثيل النص للقيمة التاريخية والوقتية التي يمثلها الكائن الحالي باستخدام معلومات التنسيق المحددة.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن يمثل معلومات التنسيق |

### قيمة الإرجاع

تمثيل النص للقيمة التي يمثلها الكائن الحالي مُنسّق وفقًا لمعلومات التنسيق المقدمة من **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const طريقة

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const طريقة

```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const طريقة

```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const طريقة

تُرجع تمثيل النص للقيمة التاريخية والوقتية التي يمثلها الكائن الحالي باستخدام معلومات التنسيق المحددة.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | const [String](../../string/)\& | سلسلة تنسيق |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | كائن يمثل معلومات التنسيق |

### قيمة الإرجاع

تمثيل النص للقيمة التي يمثلها الكائن الحالي مُنسّق وفقًا لمعلومات التنسيق المقدمة من **provider** وسلسلة التنسيق **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const طريقة

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const طريقة

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const طريقة

```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [DateTime](../)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [CultureInfo](../../../system.globalization/cultureinfo/)
* فئة [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* مساحة الاسم [System](../../)
* مكتبة [Aspose.Slides](../../../)