---
title: Is()
second_title: مرجع API Aspose.Slides للـ C++
description: 
type: docs
weight: 27
url: /ar/system/details_outofmemoryexception/is/
---
## Details_OutOfMemoryException::Is(const System::TypeInfo\&) const method

```cpp
bool System::Details_OutOfMemoryException::Is(const System::TypeInfo &target) const override
```

### المعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | الهيكل [TypeInfo](../../typeinfo/) الذي يصف النوع لاختبار الكائن الحالي ضده. |

### قيمة الإرجاع

صحيح إذا كان الكائن من النوع المعلم أو من الفئة الفرعية له، وإلا خاطئ.

## ملاحظات

تحقق مما إذا كان الكائن يمثل مثالا للنوع الموصوف بواسطة targetType. مماثل لمعامل 'is' في C#.

## انظر أيضًا

- الفئة [TypeInfo](../../typeinfo/)
- الفئة [Details_OutOfMemoryException](../)
- فضاء الاسم [System](../../)
- المكتبة [Aspose.Slides](../../../)