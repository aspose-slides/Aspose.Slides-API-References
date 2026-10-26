---
title: IsDefined()
second_title: Aspose.Slides لـ C++ مرجع API
description: غير مُنفَّذ. يحدد ما إذا كانت سمة واحدة أو أكثر من النوع المحدد أو من أنواعه المشتقة مطبقة على هذا العضو.
type: docs
weight: 157
url: /ar/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const طريقة

NOT IMPLEMENTED. يشير إلى ما إذا كان سمة واحدة أو أكثر من النوع المحدد أو من أنواعه المشتقة مطبقة على هذا العضو.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | نوع السمة المخصصة للبحث عنها. تشمل العملية الأنواع المشتقة. |
| inherit | **bool** | true للبحث في سلسلة الوراثة لهذا العضو للعثور على السمات؛ وإلا، false. يتم تجاهل هذا المعامل للخصائص والأحداث. |

### قيمة الإرجاع

true إذا كان هناك نسخة واحدة أو أكثر من attributeType أو أي من أنواعه المشتقة مطبقة على هذا العضو؛ وإلا، false.

## انظر أيضًا

* الفئة [TypeInfo](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)