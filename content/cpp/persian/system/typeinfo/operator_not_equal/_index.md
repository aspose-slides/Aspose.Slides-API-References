---
title: operator!=()
second_title: Aspose.Slides برای مرجع API C++
description: تعیین می‌کند که آیا اشیاء TypeInfo جاری و مشخص‌شده برابر نیستند.
type: docs
weight: 456
url: /fa/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const متد

تعیین می‌کند که آیا اشیاء [TypeInfo](../) جاری و مشخص‌شده برابر نیستند.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | شیء [TypeInfo](../) برای مقایسه |

### مقدار بازگشتی

در صورتی که هش‌های اشیاء برابر نباشند، true؛ در غیر این صورت false

## TypeInfo::operator!=(std::nullptr_t) const متد

تعیین می‌کند که آیا شیء [TypeInfo](../) جاری یک شیء تهی نیست، یعنی نشان‌دهنده‌ای از یک نوع می‌باشد.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```

### مقدار بازگشتی

در صورتی که شیء [TypeInfo](../) جاری یک شیء تهی نباشد، true؛ در غیر این صورت false

## موارد مرتبط

* کلاس [TypeInfo](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)