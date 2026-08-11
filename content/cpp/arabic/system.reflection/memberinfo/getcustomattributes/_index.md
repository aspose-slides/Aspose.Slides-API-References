---
title: GetCustomAttributes()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبقة على النوع الذي يمثله الكائن الحالي.
type: docs
weight: 66
url: /ar/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const طريقة

يعيد مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبقة على النوع الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | نوع السمة للبحث عنها. |
| inherit | **bool** | ما إذا كان يجب التحقق من السمات الموروثة أيضًا. |

## MemberInfo::GetCustomAttributes(bool) const طريقة

يعيد مصفوفة تحتوي على كائنات تمثل جميع السمات المخصصة المطبقة على النوع الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inherit | **bool** | ما إذا كان يجب التحقق من السمات الموروثة أيضًا. |

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Object](../../../system/object/)
* فئة [TypeInfo](../../../system/typeinfo/)
* فئة [MemberInfo](../)
* نطاق الاسم [System::Reflection](../../)
* مكتبة [Aspose.Slides](../../../)