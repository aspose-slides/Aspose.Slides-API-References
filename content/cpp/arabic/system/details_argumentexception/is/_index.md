---
title: Is()
second_title: Aspose.Slides لمرجع API للـ C++
description:
type: docs
weight: 27
url: /ar/system/details_argumentexception/is/
---
## Details_ArgumentException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Details_ArgumentException::Is(const System::TypeInfo &target) const override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| target | const [System::TypeInfo](../../typeinfo/)\& | [TypeInfo](../../typeinfo/) هيكل يصف النوع لاختبار الكائن الحالي ضده. |

### قيمة الإرجاع

صحيح إذا كان الكائن من النوع المميز أو من فئته الفرعية، وإلا خطأ.

## ملاحظات

تحقق مما إذا كان الكائن يمثل مثلاً للنوع الموصوف بواسطة targetType. مماثل لمشغل 'is' في C#.

## انظر أيضاً

* فئة [TypeInfo](../../typeinfo/)
* فئة [Details_ArgumentException](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)