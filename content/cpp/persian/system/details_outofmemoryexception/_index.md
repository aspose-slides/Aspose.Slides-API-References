---
title: Details_OutOfMemoryException
second_title: مرجع API Aspose.Slides برای C++
description: 
type: docs
weight: 638
url: /fa/system/details_outofmemoryexception/
---
## Details_OutOfMemoryException کلاس




```cpp
class Details_OutOfMemoryException : public System::Details_SystemException
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ شناور شبیه‌سازی شده به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، گرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ شناور شبیه‌سازی شده به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، گرچه بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | دیکشنری حاوی داده‌های سفارشی استثناء را برمی‌گرداند. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | یک مقدار عدد صحیح ۳۲ بیتی که کد HRESULT مرتبط با استثنای نمایان‌شده توسط شیء جاری است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | مرجع به شیئی که استثنای داخلی را نشان می‌دهد را برمی‌گرداند. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | رشته‌ای که حاوی توصیف خطا است را برمی‌گرداند. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | رشته‌ای که شامل ردیابی پشته است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | کپی شیء Exception که نشان‌دهندهٔ استثنای درونی‌ترین است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | قفل‌گذاری بیانیه lock() C# را پیاده‌سازی می‌کند. به صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقدار عددی کدگذاری‌شده‌ای که به یک استثنای خاص اختصاص دارد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nth را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | نمایش رشته‌ای شیء جاری را برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | قفل‌برداری بیانیه lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../details_exception/what/)() const | متد [what()](../details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) فراخوانی می‌شود. علیرغم این‌که این کلاس از std::exception ارث‌بری نشده، کلاس‌های مشتق می‌توانند از اعضای protected/private برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را مختل کند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [Details_SystemException](../details_systemexception/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)