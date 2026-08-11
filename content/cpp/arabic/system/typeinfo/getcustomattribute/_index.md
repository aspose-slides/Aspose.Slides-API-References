---
title: GetCustomAttribute()
second_title: Aspose.Slides مرجع API لـ C++
description: يبحث عن السمة المخصصة المطبقة التي لها النوع المحدد والمطبقة على النوع الممثل بواسطة الكائن الحالي.
type: docs
weight: 573
url: /ar/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const method

البحث عن السمة المخصصة المطبقة التي لها النوع المحدد والمطبقة على النوع المُمَثَّل بواسطة الكائن الحالي.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | الإشارة الثابتة إلى كائن [TypeInfo](../) الذي يمثل نوع السمة للبحث عنها |

### قيمة الإرجاع

مؤشر إلى كائن يمثل السمة الموجودة، أو null-pointer إذا لم يتم العثور على سمة تطابق معايير البحث

## راجع أيضًا

* الفئة [SmartPtr](../../smartptr/)
* الفئة [TypeInfo](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)