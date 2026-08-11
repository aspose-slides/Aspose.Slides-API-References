---
title: MakeScopeGuard()
second_title: Aspose.Slides برای مرجع API C++
description: یک تابع کارخانه‌ای که نمونه‌های کلاس ScopedGuard را ایجاد می‌کند.
type: docs
weight: 2809
url: /fa/system/makescopeguard/
---
## System::MakeScopeGuard(F) تابع

یک تابع کارخانه‌ای که نمونه‌های کلاس ScopedGuard را ایجاد می‌کند.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### پارامترهای قالب

| پارامتر | توضیح |
| --- | --- |
| The | نوع شیء تابعی که توسط شیء ScopedGuard ساخته‌شده فراخوانی می‌شود |

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| f | F | شیء تابعی که به سازندهٔ کلاس ScopedGuard پاس داده می‌شود. |

### مقدار بازگشت

یک نمونهٔ جدید از کلاس ScopedGuard

## موارد مرتبط

* Struct [ScopeGuard](../scopeguard/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)