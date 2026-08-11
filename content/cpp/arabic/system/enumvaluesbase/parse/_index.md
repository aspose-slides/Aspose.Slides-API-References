---
title: Parse()
second_title: Aspose.Slides لـ C++ مرجع API
description: إرجاع كائن يمثل قيمة ثابت التعداد للنّوع المحدد بالاسم المحدد.
type: docs
weight: 27
url: /ar/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) طريقة

إرجاع كائن يمثل قيمة ثابت التعداد من نوع التعداد المحدد بالاسم المحدد.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### المعطيات

| معامل | نوع | وصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | الكائن [TypeInfo](../../typeinfo/) الذي يمثل نوع قيمة التعداد المراد إرجاعها |
| str | const [String](../../string/)\& | اسم ثابت التعداد |
| ignoreCase | **bool** | يحدد ما إذا كان يجب تجاهل الحالة عند تفسير اسم ثابت التعداد |

### قيمة الإرجاع

كائن يمثل قيمة ثابت التعداد الذي تم تحديد اسمه في **str**.

## انظر أيضًا

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)