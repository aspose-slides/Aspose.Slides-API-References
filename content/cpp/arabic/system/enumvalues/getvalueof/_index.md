---
title: GetValueOf()
second_title: Aspose.Slides لـ C++ مرجع API
description: إرجاع قيمة مُعبأة للثابت enum بالاسم المحدد.
type: docs
weight: 53
url: /ar/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const method

Returns boxed value of the enum constant with the specified name.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../string/)\& | اسم ثابت enum |
| ignoreCase | **bool** | يحدد ما إذا كان يجب تجاهل حالة الأحرف عند تفسير اسم ثابت enum |

### قيمة الإرجاع

قيمة معبأة للثابت enum الذي تم تحديد اسمه في **str**.

## EnumValues::GetValueOf(long) const method

Returns boxed value of the enum constant with the specified value.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| val | long | قيمة ثابت enum |

### قيمة الإرجاع

قيمة معبأة للثابت enum الذي تم تحديد القيمة vakye له في **str**.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../sharedptr/)
* الفئة [Object](../../object/)
* الفئة [String](../../string/)
* الفئة [EnumValues](../)
* النطاق [System](../../)
* المكتبة [Aspose.Slides](../../../)