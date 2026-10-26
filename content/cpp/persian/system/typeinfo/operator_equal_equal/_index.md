---
title: operator==()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا شیء‌های TypeInfo فعلی و مشخص‌شده برابر هستند.
type: docs
weight: 443
url: /fa/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo&) const متد

تعیین می‌کند که آیا شیء‌های فعلی و [TypeInfo](../) مشخص‌شده برابر هستند یا خیر.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | شیء [TypeInfo](../) برای مقایسه با |

### مقدار بازگشت

درست اگر هش‌های شیء‌ها برابر باشند، در غیر این صورت - نادرست

## TypeInfo::operator==(std::nullptr_t) const متد

تعیین می‌کند که آیا شیء [TypeInfo](../) فعلی یک شیء تهی است، یعنی هیچ نوعی را نشان نمی‌دهد.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### مقدار بازگشت

درست اگر شیء [TypeInfo](../) فعلی یک شیء تهی باشد، در غیر این صورت - نادرست

## مراجع

* کلاس [TypeInfo](../)
* فضای‌نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)