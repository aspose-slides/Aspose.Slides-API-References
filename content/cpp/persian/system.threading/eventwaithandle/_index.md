---
title: EventWaitHandle
second_title: مرجع API Aspose.Slides برای C++
description: "رویدادی که می‌تواند به نخ در حال انتظار ارسال شود. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 118
url: /fa/system.threading/eventwaithandle/
---
## EventWaitHandle کلاس

رویدادی که می‌تواند به نخ در حال انتظار ارسال شود. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی خواهد شد. همیشه این کلاس را در نشانگر [System::SmartPtr](../../system/smartptr/) بپیچید و از این نشانگر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class EventWaitHandle : public System::Threading::WaitHandle
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [Close](../waithandle/close/)() | هر منبعی مرتبط با دسته را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ‌مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ‌مقداری نیست، از جمله NaN. |
|  [EventWaitHandle](./eventwaithandle/)(**bool**, [EventResetMode](../eventresetmode/)) | سازنده. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [wait_handle_t](../wait_handle_t/) [get_Handle](../waithandle/get_handle/)() | دسته را می‌گیرد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن به صورت بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های فرزند با کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کلاس‌های فرزند با کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی برای [Object::ReferenceEquals](../../system/object/referenceequals/) در مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual **bool** [Reset](./reset/)() | رویداد را به حالت غیرسیگنال‌دار تنظیم می‌کند. |
| virtual **bool** [Set](./set/)() | رویداد را به حالت سیگنال‌دار تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را بر می‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری به صورت بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | صبر می‌کند تا تمام دسته‌ها فعال شوند. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | صبر می‌کند تا تمام دسته‌ها فعال شوند. |
| static **bool** [WaitAll](../waithandle/waitall/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | صبر می‌کند تا تمام دسته‌ها فعال شوند. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, int) | صبر می‌کند تا هر یک از دسته‌ها فعال شود. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&, [TimeSpan](../../system/timespan/)) | صبر می‌کند تا هر یک از دسته‌ها فعال شود. |
| static int [WaitAny](../waithandle/waitany/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[WaitHandle](../waithandle/)\>\>\&) | صبر می‌کند تا هر یک از دسته‌ها فعال شود. |
| virtual **bool** [WaitOne](../waithandle/waitone/)() | صبر می‌کند تا دسته برای مدت نامحدود فعال شود. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int) | صبر می‌کند تا دسته فعال شود. |
| virtual **bool** [WaitOne](../waithandle/waitone/)([TimeSpan](../../system/timespan/)) | صبر می‌کند تا دسته فعال شود. |
| virtual **bool** [WaitOne](../waithandle/waitone/)(int, **bool**) | صبر می‌کند تا دسته فعال شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [~EventWaitHandle](./~eventwaithandle/)() | سُلخ. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |
| virtual  [~WaitHandle](../waithandle/~waithandle/)() | سُلخ. |
## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [WaitTimeout](../waithandle/waittimeout/) | مقدار ویژه‌ای که توسط تابع برگردانده می‌شود؛ در غیر این صورت اندیس شیء سیگنال‌دار در آرایه را برمی‌گرداند، اگر زمان انتظار تمام شود و هیچ‌یک سیگنال ندهد. |
## مراجع

* کلاس [WaitHandle](../waithandle/)
* فضای نام [System::Threading](../)
* کتابخانه [Aspose.Slides](../../)