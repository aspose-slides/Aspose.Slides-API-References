---
title: ToType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يحوّل قيمة هذا الكائن إلى System::Object من System::Type المحدد والذي له قيمة مكافئة، باستخدام معلومات التنسيق الخاصة بالثقافة المحددة."
type: docs
weight: 209
url: /ar/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) طريقة

تحول قيمة هذا الكائن إلى [System::Object](../../object/) من System::Type المحدد والذي له قيمة مكافئة، باستخدام معلومات التنسيق الخاصة بالثقافة المحددة.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### معاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | System::Type الذي يتم تحويل قيمة هذا الكائن إليه. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | تنفيذ لواجهة [System::IFormatProvider](../../iformatprovider/) توفر معلومات التنسيق الخاصة بالثقافة. |

### قيمة الإرجاع

مثال [System::Object](../../object/) من النوع conversionType الذي قيمته مكافئة لقيمة هذا الكائن.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [Object](../../object/)
* فئة [TypeInfo](../../typeinfo/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [IConvertible](../)
* مساحة اسم [System](../../)
* مكتبة [Aspose.Slides](../../../)