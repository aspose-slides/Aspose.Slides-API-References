---
title: Process
second_title: مرجع API Aspose.Slides برای C++
description: "اطلاعات و دستکاری فرآیند را دربر می‌گیرد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اخطارهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال آن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 27
url: /fa/system.diagnostics/process/
---
## Process کلاس

Encapsulates process information and manipulation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Process : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ی نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ی نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، حتی NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| **bool** [get_EnableRaisingEvents](./get_enableraisingevents/)() const | مشخص می‌کند آیا رویداد Exited باید هنگام پایان فرآیند فراخوانی شود. |
| int [get_ExitCode](./get_exitcode/)() const | کد خروج فرآیند را دریافت می‌کند. |
| **int64_t** [get_PrivateMemorySize64](./get_privatememorysize64/)() const | اندازه‌ی مجموعه حافظه خصوصی فرآیند را دریافت می‌کند. |
| [String](../../system/string/) [get_ProcessName](./get_processname/)() const | نام فرآیند را دریافت می‌کند. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardError](./get_standarderror/)() const | خوانده‌گری برای خواندن خروجی خطا فرآیند فراهم می‌کند. پیاده‌سازی نشده. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardOutput](./get_standardoutput/)() const | خوانده‌گری برای خواندن خروجی استاندارد فرآیند فراهم می‌کند. پیاده‌سازی نشده. |
| [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\> [get_StartInfo](./get_startinfo/)() const | اطلاعات شروع فرآیند را دریافت می‌کند. |
| **int64_t** [get_WorkingSet64](./get_workingset64/)() const | اندازه‌ی کار مجموعه حافظه فرآیند را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده‌ی مرجع مرتبط با شیء را دریافت می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [GetCurrentProcess](./getcurrentprocess/)() | اطلاعات فرآیند جاری را دریافت می‌کند. فقط [Windows](../../system.windows/). |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| [String](../../system/string/) [GetOutputText](./getoutputtext/)() const | متن خروجی فرآیند را دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده نمایید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | بازنماد متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به صورت مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| void [set_EnableRaisingEvents](./set_enableraisingevents/)(**bool**) | مشخص می‌کند آیا رویداد Exited باید هنگام پایان فرآیند فراخوانی شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمندPointerها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و مقدار آن را بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمندPointerها یا ThisProtector استفاده کنید. |
| **bool** [Start](./start/)() | فرآیند را با پارامترهای از پیش تعریف‌شده آغاز می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | فرآیند را با مسیر و آرگمان‌های مشخص آغاز می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\>\&) | فرآیند را با مسیر و آرگمان‌های مشخص آغاز می‌کند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | بازنماد متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده نمایید. |
| **bool** [WaitForExit](./waitforexit/)(int) | منتظر پایان فرآیند می‌ماند. پیاده‌سازی نشده. |
| void [WaitForExit](./waitforexit/)() | منتظر پایان فرآیند می‌ماند و تا اتمام آن باز نمی‌گردد. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از هوشمندPointerها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به جای آن از هوشمندPointerها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |
| virtual  [~Process](./~process/)() | تخریب‌کننده. |
## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [System::Diagnostics](../)
* کتابخانه [Aspose.Slides](../../)