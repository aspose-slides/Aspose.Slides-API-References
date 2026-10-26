---
title: Is()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: 
type: docs
weight: 27
url: /ar/system.runtime.serialization/details_serializationexception/is/
---
## Details_SerializationException::Is(const System::TypeInfo\&) const طريقة

```cpp
bool System::Runtime::Serialization::Details_SerializationException::Is(const System::TypeInfo &target) const override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) structure describing the type to test current object against. |

### قيمة الإرجاع

صحيح إذا كان الكائن من نوع محدد أو من فئته الفرعية، خطأ خلاف ذلك.

## ملاحظات

تحقق مما إذا كان الكائن يمثل مثالا من النوع الموصوف بواسطة targetType. مشابه لمشغل 'is' في C#.

## انظر أيضا

* الفئة [TypeInfo](../../../system/typeinfo/)
* الفئة [Details_SerializationException](../)
* النطاق [System::Runtime::Serialization](../../)
* المكتبة [Aspose.Slides](../../../)