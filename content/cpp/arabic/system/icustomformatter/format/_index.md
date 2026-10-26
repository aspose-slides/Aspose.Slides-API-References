---
title: Format()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تعيد تمثيلًا نصيًا لقيمة يتم تمثيلها بواسطة الكائن الحالي باستخدام التنسيق المحدد.
type: docs
weight: 1
url: /ar/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) طريقة

يرجع تمثيلًا نصيًا لقيمة تم تمثيلها بواسطة الكائن الحالي باستخدام التنسيق المحدد.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | [System::String](../../string/) | تنسيق السلسلة |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | الكائن المراد تنسيقه |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | الكائن الذي يقدم معلومات التنسيق |

### قيمة الإرجاع

تمثيل نصي للـ **arg** تم تنسيقه وفقًا للتنسيق المحدد بواسطة **format** و **formatProvider**

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* فئة [String](../../string/)
* فئة [Object](../../object/)
* فئة [IFormatProvider](../../iformatprovider/)
* فئة [ICustomFormatter](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)