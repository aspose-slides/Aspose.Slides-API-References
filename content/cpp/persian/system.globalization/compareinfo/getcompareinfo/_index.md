---
title: GetCompareInfo()
second_title: مرجع API Aspose.Slides برای C++
description: CompareInfo مرتبط با فرهنگ مشخص‌شده را دریافت می‌کند و از روش‌های مقایسه رشته‌ای در اسمبلی مشخص‌شده استفاده می‌کند.
type: docs
weight: 183
url: /fa/system.globalization/compareinfo/getcompareinfo/
---
## CompareInfo::GetCompareInfo(int, const SharedPtr<Reflection::Assembly>&) متد

[CompareInfo](../) مرتبط با فرهنگ مشخص‌شده را دریافت می‌کند و از روش‌های مقایسه رشته‌ای در اسمبلی مشخص‌شده استفاده می‌کند.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture, const SharedPtr<Reflection::Assembly> &assembly)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| culture | int | شناسه فرهنگ (LCID). |
| assembly | const [SharedPtr](../../../system/sharedptr/)<[Reflection::Assembly](../../../system.reflection/assembly/)>& | اسمبلی که شامل روش‌های مقایسه رشته‌ای است. |

### مقدار بازگشت

[CompareInfo](../) شیء.

## CompareInfo::GetCompareInfo(const String&, const SharedPtr<Reflection::Assembly>&) متد

[CompareInfo](../) مرتبط با فرهنگ مشخص‌شده را دریافت می‌کند و از روش‌های مقایسه رشته‌ای در اسمبلی مشخص‌شده استفاده می‌کند.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name, const SharedPtr<Reflection::Assembly> &assembly)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | نام فرهنگ. |
| assembly | const [SharedPtr](../../../system/sharedptr/)<[Reflection::Assembly](../../../system.reflection/assembly/)>& | اسمبلی که شامل روش‌های مقایسه رشته‌ای است. |

### مقدار بازگشت

[CompareInfo](../) شیء.

## CompareInfo::GetCompareInfo(int) متد

[CompareInfo](../) مرتبط با فرهنگ مشخص‌شده را دریافت می‌کند.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(int culture)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| culture | int | شناسه فرهنگ (LCID). |

### مقدار بازگشت

[CompareInfo](../) شیء.

## CompareInfo::GetCompareInfo(const String&) متد

[CompareInfo](../) مرتبط با فرهنگ مشخص‌شده را دریافت می‌کند.

```cpp
static CompareInfoPtr System::Globalization::CompareInfo::GetCompareInfo(const String &name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | نام فرهنگ. |

### مقدار بازگشت

[CompareInfo](../) شیء.

## موارد مرتبط

* Typedef [CompareInfoPtr](../../compareinfoptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Assembly](../../../system.reflection/assembly/)
* کلاس [CompareInfo](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Globalization](../../)
* Library [Aspose.Slides](../../../)