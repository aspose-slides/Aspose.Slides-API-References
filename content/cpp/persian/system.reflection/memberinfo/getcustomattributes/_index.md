---
title: GetCustomAttributes()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایه حاوی اشیائی را برمی‌گرداند که تمام صفات سفارشی اعمال‌شده به نوع نمایان‌شده توسط شیء فعلی را نشان می‌دهند.
type: docs
weight: 66
url: /fa/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const متد

آرایه‌ای را برمی‌گرداند که شامل اشیائی هستند که تمام ویژگی‌های سفارشی اعمال‌شده به نوع نمایان‌شده توسط شیء فعلی را نشان می‌دهند.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | نوع صفتی که باید جستجو شود. |
| inherit | **bool** | اینکه آیا صفات ارث‌برده نیز بررسی شوند یا نه. |

## MemberInfo::GetCustomAttributes(bool) const متد

آرایه‌ای را برمی‌گرداند که شامل اشیائی هستند که تمام ویژگی‌های سفارشی اعمال‌شده به نوع نمایان‌شده توسط شیء فعلی را نشان می‌دهند.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inherit | **bool** | اینکه آیا صفات ارث‌برده نیز بررسی شوند یا نه. |

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [MemberInfo](../)
* فضای نام [System::Reflection](../../)
* Library [Aspose.Slides](../../../)