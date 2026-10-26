---
title: GetCustomAttribute()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُرجع سمة مخصصة من نوع محدد مطبقة على النوع المحدد.
type: docs
weight: 1
url: /ar/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) طريقة

تُرجع سمة مخصصة من نوع محدد مطبق على النوع المحدد.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | سمة النوع التي تم استرجاعها |
| attributeType | const [TypeInfo](../../typeinfo/)\& | نوع السمة المراد استرجاعها |

### قيمة الإرجاع

سمة مسترجعة أو قيمة null إذا كان النوع المحدد لا يحتوي على سمة من النوع المحدد.

## انظر أيضًا

* تعريف نوع [ptr](../../object/ptr/)
* فئة [TypeInfo](../../typeinfo/)
* فئة [Attribute](../)
* نطاق [System](../../)
* مكتبة [Aspose.Slides](../../../)