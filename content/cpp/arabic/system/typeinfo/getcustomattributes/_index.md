---
title: GetCustomAttributes()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: ترجع مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبقة على النوع.
type: docs
weight: 586
url: /ar/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const طريقة

تُرجِع مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبَّقة على النوع.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const طريقة

تُرجِع مصفوفة تحتوي على كائنات تمثل السمات المحددة المطبَّقة على النوع.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | نوع السمة للبحث عنها. |
| inherit | **bool** | ما إذا كان ينبغي البحث عن السمات الموروثة أيضًا. |

## انظر أيضًا

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)