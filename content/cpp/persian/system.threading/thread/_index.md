---
title: Thread
second_title: مرجع API Aspose.Slides برای C++
description: "پیاده‌سازی رشته. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 209
url: /fa/system.threading/thread/
---
## Thread کلاس

[Thread](./) پیاده‌سازی. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکال‌های اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Thread : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Abort](./abort/)() | رشته را قطع می‌کند. پیاده‌سازی نشده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | فرهنگ رشته را دریافت می‌کند. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | شیئی که رشتهٔ جاری را توصیف می‌کند دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | فرهنگ رابط کاربری مورد استفاده توسط رشته را دریافت می‌کند. |
| **bool** [get_IsAlive](./get_isalive/)() | بررسی می‌کند که آیا رشته زنده است یا نه. |
| **bool** [get_IsBackground](./get_isbackground/)() | بررسی می‌کند که آیا رشته پس‌زمینه است یا نه. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | بررسی می‌کند که آیا رشته توسط یک استخر رشته مالکیت دارد یا نه. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | شناسهٔ رشته را دریافت می‌کند. می‌تواند از سیستم‌عامل گرفته شود، اما اگر شناسهٔ رشتهٔ سیستم‌عامل از محدودیت‌های int فراتر رود، شناسه‌های رشته‌ها ممکن است تداخل داشته باشند. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | نام رشته را دریافت می‌کند. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | وضعیت رشته را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | شناسهٔ رشتهٔ جاری را دریافت می‌کند. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Interrupt](./interrupt/)() | رشته را قطع می‌کند. پیاده‌سازی نشده. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Join](./join/)() | به رشتهٔ مدیریت‌شده ملحق می‌شود. در صورت نیاز انتظار نامحدود انجام می‌دهد. |
| **bool** [Join](./join/)(int) | به رشتهٔ مدیریت‌شده ملحق می‌شود. انتظار محدودی انجام می‌دهد. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | به رشتهٔ مدیریت‌شده ملحق می‌شود. انتظار محدودی انجام می‌دهد. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
| static void [MemoryBarrier](./memorybarrier/)() | دسترسی به حافظه را همگام‌سازی می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی کننده را فراهم می‌کند. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | داده‌های TLS را از رشتهٔ دیگری کپی می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی کننده را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌گونه شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به میزان مشخص‌شده کاهش می‌دهد. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | فرهنگ رشته را تنظیم می‌کند. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | فرهنگ رابط کاربری مورد استفاده توسط رشته را تنظیم می‌کند. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | رشته را به پس‌زمینه یا پیش‌زمینه تنظیم می‌کند. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | نام رشته را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| static void [Sleep](./sleep/)(int) | رشتهٔ جاری را برای مدت زمان مشخصی متوقف می‌کند. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | رشتهٔ جاری را برای مدت زمان مشخصی متوقف می‌کند. |
| static void [SpinWait](./spinwait/)(int) | به تعداد مشخصی از تکرارهای حلقه منتظر می‌شود. |
| void [Start](./start/)() | رشته را با استفاده از شیء آرگومان null شروع می‌کند. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | رشته را شروع می‌کند. |
|  [Thread](./thread/)() | سازنده. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | سازنده. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | سازنده. |
|  [Thread](./thread/)([Thread](./)\&) | سازندهٔ کپی. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| static **bool** [Yield](./yield/)() | رشته را به دیگر وظایف می‌سپارد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
| virtual  [~Thread](./~thread/)() | تخریب‌کننده. |

## توضیحات

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
شناسه رشته اصلی: ۲
شناسه رشته فرزند: ۱
*/
```

## مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)