---
title: ThreadPool
second_title: مرجع API Aspose.Slides برای C++
description: API استخر نخ‌ها که امکان افزودن کارها به صف برای خوانده شدن توسط استخر نخ‌های کارگر را فراهم می‌کند. این یک نوع استاتیک است که خدمات نمونه‌ای ندارد. شما هرگز نباید به هیچ وجه نمونه‌ای از آن را ایجاد کنید.
type: docs
weight: 222
url: /fa/system.threading/threadpool/
---
## ThreadPool کلاس

[Thread](../thread/) یک API pool است که امکان افزودن کارها به صف را برای خواندن توسط مجموعه‌ای از نخ‌های کارگر فراهم می‌کند. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید نمونه‌ای از آن را به هیچ وجه ایجاد کنید.

```cpp
class ThreadPool : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی با این که بر مبنای IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی با این که بر مبنای IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | تعداد نخ‌های در دسترس را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | نمونه پیاده‌سازی که فهرست کارها و سایر پارامترها را نگه می‌دارد. |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | حداکثر تعداد نخ‌های همزمان را دریافت می‌کند. |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | حداقل تعداد نخ‌هایی که توسط pool ایجاد می‌شود را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نظیر فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایندهٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. نظیر عملگر 'is' C#. |
| static void [JoinAllThreads](./joinallthreads/)() | به تمام نخ‌های مالک‌دار ملحق می‌شود. به‌صورت نامحدود منتظر می‌ماند. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌بندی دستور lock() C#. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کپی‌برداری از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی کپی نمی‌شود؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را می‌دهد. |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | بدون کپی‌برداری. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌شود؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را می‌دهد. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | یک آیتم کاری را به صف می‌گذارد که با کال‌بک بدون پارامتر موجود است. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | یک آیتم کاری را به صف می‌گذارد که با کال‌بک بدون پارامتر موجود است. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | تعداد نخ‌های مالک‌دار توسط pool را تنظیم می‌کند. |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | حداقل تعداد نخ‌های مالک‌دار توسط pool را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | بدون کپی‌برداری. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظیر متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای قفل‌زدایی دستور lock() C#. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌کند. |

## توضیحات

```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 1
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 3
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 5
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 6
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 9
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 1
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 7
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 2
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 4
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 3
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 12
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 8
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 5
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 6
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 16
پس‌زمینه: True, استخر نخ: True, شناسه نخ: 11
*/
```

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)