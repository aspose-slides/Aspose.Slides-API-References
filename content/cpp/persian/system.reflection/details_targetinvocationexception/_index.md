---
title: Details_TargetInvocationException
second_title: مرجع API Aspose.Slides برای C++
description: "TargetInvocationException توسط روش‌هایی که از طریق reflection فراخوانی می‌شوند، پرتاب می‌شود. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به‌جای آن از کلاس TargetInvocationException استفاده کنید. هرگز نمونه‌های کلاس TargetInvocationException را در System::SmartPtr بسته‌بندی نکنید."
type: docs
weight: 79
url: /fa/system.reflection/details_targetinvocationexception/
---
## Details_TargetInvocationException کلاس

TargetInvocationException توسط متدهایی که از طریق reflection فراخوانی می‌شوند، پرتاب می‌شود. هرگز به صورت دستی نمونه‌ای از این کلاس را ایجاد نکنید. به جای آن از کلاس TargetInvocationException استفاده کنید. هرگز نمونه‌های کلاس TargetInvocationException را در [System::SmartPtr](../../system/smartptr/) بسته‌بندی نکنید.

```cpp
class Details_TargetInvocationException : public System::Details_ApplicationException
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | لغت‌نامه‌ای با داده‌های سفارشی استثنا را باز می‌گرداند. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | یک مقدار عددی ۳۲ بیتی که یک کد HRESULT مرتبط با استثنای نمایش داده شده توسط شیء فعلی است را باز می‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | یک مرجع به شیء نمایانگر استثنای داخلی را باز می‌گرداند. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | رشته‌ای حاوی توصیف خطا را باز می‌گرداند. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | رشته‌ای حاوی ردیابی پشته (stack trace) را باز می‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | کپی شیء Exception که نمایانگر استثنای درونی‌ترین سطح است را باز می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌سازی اشیا سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_applicationexception/gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| **bool** [Is](../../system/details_applicationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن با دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر (کلون) انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء جدید ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در حقیقت چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در حقیقت چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, stdnullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, stdnullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند؛ مقدار عددی رمزگذاری‌شده‌ای که به یک استثنای خاص اختصاص می‌یابد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در контейнерها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندهای اشاره‌گر یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندهای اشاره‌گر یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | نمایش رشته‌ای شیء فعلی را باز می‌گرداند. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_applicationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندهای اشاره‌گر یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمندهای اشاره‌گر یا ThisProtector استفاده کنید. |
| virtual const char * [what](../../system/details_exception/what/)() const | متد [what()](../../system/details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../../system/exceptionwrapper/) فراخوانی می‌شود. علیرغم این‌که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای protected/private برای پیاده‌سازی منطق خود استفاده کنند. منتقل کردن پیاده‌سازی این متد به [ExceptionWrapper](../../system/exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Details_ApplicationException](../../system/details_applicationexception/)
* فضای نام [System::Reflection](../)
* کتابخانه [Aspose.Slides](../../)