---
title: Semaphore()
second_title: Aspose.Slides برای C++ مرجع API
description: یک semaphore بدون نام ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) سازنده

Creates unnamed semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| initialCount | int | تعداد اولیه ورودی‌های فعال. |
| maximumCount | int | حداکثر تعداد ورودی‌های مجاز. |

## Semaphore::Semaphore(int, int, const String\&) سازنده

Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| initialCount | int | تعداد اولیه ورودی‌های فعال. |
| maximumCount | int | حداکثر تعداد ورودی‌های مجاز. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) نام. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) سازنده

Creates named semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| initialCount | int | تعداد اولیه ورودی‌های فعال. |
| maximumCount | int | حداکثر تعداد ورودی‌های مجاز. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) نام. |
| createdNew | **bool**\& | مرجعی به متغیری که در صورتی که semaphore ساخته شده باشد به true تنظیم می‌شود و در صورت استفاده از semaphore موجود با همان نام به false تنظیم می‌شود |

## مراجع

* کلاس [Semaphore](../)
* کلاس [String](../../../system/string/)
* فضای نام [System::Threading](../../)
* کتابخانه [Aspose.Slides](../../../)