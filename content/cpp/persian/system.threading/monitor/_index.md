---
title: Monitor
second_title: مرجع API Aspose.Slides برای C++
description: کلاس Monitor مکانیزمی را فراهم می‌کند که دسترسی به اشیاء را همگام‌سازی می‌کند.
type: docs
weight: 157
url: /fa/system.threading/monitor/
---
## Monitor کلاس

کلاس [Monitor](./) مکانیزمی را فراهم می‌کند که دسترسی به اشیاء را همگام‌سازی می‌کند.

```cpp
class Monitor : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | قفل انحصاری بر روی یک شیء مشخص به دست می‌آورد. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | قفل انحصاری بر روی شیء مشخص به دست می‌آورد و به صورت اتمی مقداری را تنظیم می‌کند که نشان‌دهنده این است که آیا قفل گرفته شده است یا نه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌سازی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | قفل انحصاری بر روی شیء مشخص را رها می‌کند. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | تعیین می‌کند که آیا نخ جاری قفل شیء مشخص را در اختیار دارد یا خیر. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری دستور lock() در C#. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر (کپی) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | یک نخ در صف انتظار را از تغییر وضعیت شیء قفل‌شده آگاه می‌کند. پیاده‌سازی نشده است. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | تمام نخ‌های منتظر را از تغییر وضعیت شیء آگاه می‌کند. پیاده‌سازی نشده است. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nامٍ قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص. پیاده‌سازی نشده است. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص و به‌صورت اتمی مقداری را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص به مدت میلی‌ثانیه‌های تعیین‌شده. پیاده‌سازی نشده است. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص به مدت زمان تعیین‌شده. پیاده‌سازی نشده است. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص به مدت زمان تعیین‌شده و به‌صورت اتمی مقداری را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | تلاش برای به‌دست آوردن قفل انحصاری بر روی شیء مشخص به مدت زمان تعیین‌شده و به‌صورت اتمی مقداری را تنظیم می‌کند که نشان می‌دهد آیا قفل گرفته شده است یا نه. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای آزادسازی در دستور lock() در C#. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | قفل را بر روی یک شیء رها می‌کند و نخ جاری را مسدود می‌سازد تا دوباره قفل را به‌دست آورد. اگر بازه زمان‌موحد مشخص شده، به پایان برسد، نخ به صف آماده می‌رود. به‌صورت اختیاری قبل از انتظار از دامنه همگام‌سازی برای زمینه همگام‌سازی خارج می‌شود و پس از آن دوباره دامنه را به‌دست می‌آورد. پیاده‌سازی نشده است. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | قفل را بر روی یک شیء رها می‌کند و نخ جاری را مسدود می‌سازد تا دوباره قفل را به‌دست آورد. اگر بازه زمان‌موحد مشخص شده، به پایان برسد، نخ به صف آماده می‌رود. به‌صورت اختیاری قبل از انتظار از دامنه همگام‌سازی برای زمینه همگام‌سازی خارج می‌شود و پس از آن دوباره دامنه را به‌دست می‌آورد. پیاده‌سازی نشده است. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | قفل را بر روی یک شیء رها می‌کند و نخ جاری را مسدود می‌سازد تا دوباره قفل را به‌دست آورد. اگر بازه زمان‌موحد مشخص شده، به پایان برسد، نخ به صف آماده می‌رود. پیاده‌سازی نشده است. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | قفل را بر روی یک شیء رها می‌کند و نخ جاری را مسدود می‌سازد تا دوباره قفل را به‌دست آورد. اگر بازه زمان‌موحد مشخص شده، به پایان برسد، نخ به صف آماده می‌رود. پیاده‌سازی نشده است. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | قفل را بر روی یک شیء رها می‌کند و نخ جاری را مسدود می‌سازد تا دوباره قفل را به‌دست آورد. پیاده‌سازی نشده است. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیلاً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
تعداد رشته‌ها: 3
رشته 0: 1
رشته 0: 2
رشته 0: 3
رشته 0: 4
رشته 0: 5
رشته 1: 1
رشته 1: 2
رشته 1: 3
رشته 1: 4
رشته 1: 5
رشته 2: 1
رشته 2: 2
رشته 2: 3
رشته 2: 4
رشته 2: 5
*/
```

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)