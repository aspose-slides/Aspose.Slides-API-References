---
title: ThreadPoolImpl
second_title: Aspose.Slides برای C++ مرجع API
description: داده‌های داخلی استخر رشته‌ها. این یک نوع تک‌نمونه است که مدیریت حافظه توسط تابع(های) دسترسی انجام می‌شود. شما نباید به‌صورت مستقیم نمونه‌های آن را ایجاد کنید.
type: docs
weight: 235
url: /fa/system.threading/threadpoolimpl/
---
## ThreadPoolImpl کلاس


[Thread](../thread/) داده‌های داخلی pool. این یک نوع تک‌نمونه است که مدیریت حافظه توسط تابع(های) دسترسی انجام می‌شود. شما نباید به‌صورت مستقیم نمونه‌های آن را ایجاد کنید.

```cpp
class ThreadPoolImpl
```

## متدها

| متد | توضیح |
| --- | --- |
| void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | تعداد رشته‌های در دسترس را دریافت می‌کند. |
| static **bool**\& [GetInitialized](./getinitialized/)() | حالت اولیه تک‌نمونه را دریافت می‌کند. |
| void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | حداکثر تعداد رشته‌های همزمان را دریافت می‌کند. |
| void [GetMinThreads](./getminthreads/)(int\&, int\&) | حداقل تعداد رشته‌های ایجاد شده توسط pool را دریافت می‌کند. |
| void [JoinAll](./joinall/)() | همه رشته‌های متعلق را می‌پیوندد. به‌صورت نامحدود منتظر می‌ماند. |
| **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | مورد کاری را به صف اضافه می‌کند. |
| **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | تعداد رشته‌های متعلق به pool را تنظیم می‌کند. |
| **bool** [SetMinThreads](./setminthreads/)(int, int) | حداقل تعداد رشته‌های متعلق به pool را تنظیم می‌کند. |
|  [ThreadPoolImpl](./threadpoolimpl/)() | سازنده. |
|  [~ThreadPoolImpl](./~threadpoolimpl/)() | تخریب‌کننده. اگر هنوز تمام نشده باشند، همه رشته‌ها را می‌پیوندد. |
## موارد مرتبط

* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)