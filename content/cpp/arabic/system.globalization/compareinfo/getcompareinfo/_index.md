---
title: GetCompareInfo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بالحصول على CompareInfo المرتبط بالثقافة المحددة وباستخدام أساليب مقارنة السلاسل في التجميع المحدد.
type: docs
weight: 183
url: /ar/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr\<Reflection::Assembly\>\&) طريقة

يحصل على [CompareInfo](../) المرتبط بالثقافة المحددة وباستخدام أساليب مقارنة السلاسل في التجميع المحدد.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| culture | int | معرف الثقافة (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | التجميع الذي يحتوي على أساليب مقارنة السلاسل. |

### قيمة الإرجاع

[CompareInfo](../) كائن.

## CompareInfo::GetCompareInfo(const String\&, const SharedPtr\<Reflection::Assembly\>\&) طريقة

يحصل على [CompareInfo](../) المرتبط بالثقافة المحددة وباستخدام أساليب مقارنة السلاسل في التجميع المحدد.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم الثقافة. |
| assembly | const [SharedPtr](../../../system/sharedptr/)\<[Reflection::Assembly](../../../system.reflection/assembly/)\>\& | التجميع الذي يحتوي على أساليب مقارنة السلاسل. |

### قيمة الإرجاع

[CompareInfo](../) كائن.

## CompareInfo::GetCompareInfo(int) طريقة

يحصل على [CompareInfo](../) المرتبط بالثقافة المحددة.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| culture | int | معرف الثقافة (LCID). |

### قيمة الإرجاع

[CompareInfo](../) كائن.

## CompareInfo::GetCompareInfo(const String\&) طريقة

يحصل على [CompareInfo](../) المرتبط بالثقافة المحددة.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم الثقافة. |

### قيمة الإرجاع

[CompareInfo](../) كائن.

## انظر أيضاً

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Assembly](../../../system.reflection/assembly/)
* فئة [CompareInfo](../)
* فئة [String](../../../system/string/)
* نطاق [System::Globalization](../../)
* مكتبة [Aspose.Slides](../../../)