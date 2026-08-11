---
title: Details_DivideByZeroException
second_title: Aspose.Slides برای C++ مرجع API
description: "DivideByZeroException زمانی پرتاب می‌شود که در یک عملیات ریاضی سعی در تقسیم بر 0 شود. هرگز به‌صورت دستی نمونه‌ای از این کلاس ایجاد نکنید. به‌جای آن از کلاس DivideByZeroException استفاده کنید. هرگز نمونه‌های کلاس DivideByZeroException را درون System::SmartPtr بسته‌بندی نکنید."
type: docs
weight: 404
url: /fa/system/details_dividebyzeroexception/
---
## Details_DivideByZeroException کلاس

DivideByZeroException زمانی که در یک عملیات ریاضی سعی در تقسیم بر 0 شود، پرتاب می‌شود. هرگز به‌صورت دستی نمونه‌ای از این کلاس را ایجاد نکنید. به‌جای آن از کلاس DivideByZeroException استفاده کنید. هرگز نمونه‌های کلاس DivideByZeroException را درون [System::SmartPtr](../smartptr/) بسته‌بندی نکنید.

```cpp
class Details_DivideByZeroException : public System::Details_ArithmeticException
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ مقداری نیست، شامل NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ‌ مقداری نیست، شامل NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | لغت‌نامه‌ای با داده‌های سفارشی استثنا را برمی‌گرداند. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | یک مقدار عدد صحیح ۳۲ بیتی را برمی‌گرداند که کد HRESULT مرتبط با استثنای نمایان‌شده توسط شیء جاری است. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | یک ارجاع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | رشته‌ای که شامل توصیف خطا است را برمی‌گرداند. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | رشته‌ای که شامل ردپای پشته است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | کپی شیء Exception که نمایانگر داخلی‌ترین استثنا است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | امکان قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء مراقب [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازنده‌ی کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد ارجاع‌های اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، که یک مقدار عددی کدگذاری‌شده است که به یک استثنای خاص اختصاص می‌یابد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارنده‌ی ارجاع اشتراکی را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | تعداد ارجاع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | تعداد ارجاع اشتراکی را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | نمایش متنی شیء جاری را برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | امکان رفع قفل با عبارت C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شیء مراقب [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | تعداد ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | تعداد ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../details_exception/what/)() const | متد [what()](../details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) فراخوانی می‌شود. با وجود این‌که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای protected/private برای اجرای منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را بشکند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

OutOfMemoryException زمانی که برنامه حافظه کافی نداشته باشد، پرتاب می‌شود. هرگز به‌صورت دستی نمونه‌ای از این کلاس را ایجاد نکنید. به‌جای آن از کلاس OutOfMemoryException استفاده کنید. هرگز نمونه‌های کلاس OutOfMemoryException را درون [System::SmartPtr](../smartptr/) بسته‌بندی نکنید. 

## موارد مرتبط

* کلاس [Details_ArithmeticException](../details_arithmeticexception/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)