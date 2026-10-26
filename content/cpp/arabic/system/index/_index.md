---
title: Index
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يمثل فهرسًا داخل مجموعة. يمكن أن يكون الفهرس من البداية أو من النهاية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا الفئة System::SmartPtr لإدارة كائنات هذا النوع."
type: docs
weight: 1015
url: /ar/system/index/
---
## Index فئة


يمثل فهرسًا داخل مجموعة. يمكن أن يكون الفهرس من البداية أو من النهاية. يجب تخصيص هذا النوع على المكدس وتمريره إلى الدوال بالقيمة أو بالمرجع. لا تستخدم أبدًا الفئة [System::SmartPtr](../smartptr/) لإدارة كائنات هذا النوع.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | يحدد ما إذا كانت المثيل الحالي والـ [Index](./) المحدد يمثلان نفس الموقع. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | ينشئ [Index](./) يكون نسبيًا إلى نهاية المجموعة. |
| static constexpr [Index](./) [get_End](./get_end/)() | يحصل على كائن [Index](./) يمثل نهاية مجموعة. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | يحصل على قيمة تشير إلى ما إذا كان الفهرس من النهاية. |
| static constexpr [Index](./) [get_Start](./get_start/)() | يحصل على كائن [Index](./) يمثل بداية مجموعة. |
| constexpr **int32_t** [get_Value](./get_value/)() const | يحصل على قيمة الفهرس. |
| **int32_t** [GetHashCode](./gethashcode/)() const | يعيد رمز تجزئة للفهرس الحالي. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | تحول الـ [Index](./) الحالي إلى إزاحة من بداية مجموعة بطول محدد. |
| constexpr [Index](./index/)() | يقوم بإنشاء مثيل يمثل بداية مجموعة. |
| constexpr [Index](./index/)(**int32_t**) | يقوم بإنشاء مثيل يمثل الموضع المحدد من بداية مجموعة. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | يقوم بإنشاء مثيل يمثل الفهرس المحدد. |
## انظر أيضًا

* المجال [System](../)
* المكتبة [Aspose.Slides](../../)