---
title: ScopeGuard
second_title: Aspose.Slides برای C++ مرجع API
description: کلاس سرویسی که خدماتی را برای اجرای یک شیء تابع خاص زمانی که یک نمونه از کلاس خارج از محدوده می‌شود، فراهم می‌کند.
type: docs
weight: 1886
url: /fa/system/scopeguard/
---
## ScopeGuard struct

کلاس سرویسی که خدماتی را برای اجرای یک شیء تابع خاص زمانی که یک نمونه از کلاس خارج از محدوده می‌شود، فراهم می‌کند.

```cpp
template<typename F>class ScopeGuard
```

### Template parameters

| پارامتر | توضیح |
| --- | --- |
| F | نوع شیء تابعی که توسط نمونه‌های کلاس ScopedGuard فراخوانی می‌شود |

## Methods

| متد | توضیح |
| --- | --- |
| void [Disable](./disable/)() | فراخوانی گارد را غیرفعال می‌کند. |
|  [ScopeGuard](./scopeguard/)(F) | یک نمونه می‌سازد که برای فراخوانی شیء تابع مشخص شده تنظیم شده است. |
|  [~ScopeGuard](./~scopeguard/)() | شیء تابعی که به سازنده پاس داده شده است را فراخوانی می‌کند. |

## موارد مرتبط

* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)