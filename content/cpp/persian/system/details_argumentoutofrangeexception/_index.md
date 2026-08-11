---
title: Details_ArgumentOutOfRangeException
second_title: مرجع API Aspose.Slides برای C++
description: "ArgumentOutOfRangeException زمانی پرتاب می‌شود که متدی که فراخوانی می‌شود، آرگومانی دریافت کند که خارج از بازهٔ مورد انتظار مقادیر برای آن آرگومان باشد. هرگز نمونه‌های این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس ArgumentOutOfRangeException استفاده کنید. هرگز نمونه‌های کلاس ArgumentOutOfRangeException را داخل System::SmartPtr بسته‌بندی نکنید."
type: docs
weight: 352
url: /fa/system/details_argumentoutofrangeexception/
---
## Details_ArgumentOutOfRangeException کلاس

ArgumentOutOfRangeException زمانی پرتاب می‌شود که متدی که فراخوانی می‌شود، آرگیومانی دریافت کند که خارج از بازهٔ مورد انتظار مقادیر برای آن آرگومان باشد. هرگز نمونه‌ای از این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس ArgumentOutOfRangeException استفاده کنید. هرگز نمونه‌های کلاس ArgumentOutOfRangeException را داخل [System::SmartPtr](../smartptr/) بسته‌بندی نکنید.

```cpp
class Details_ArgumentOutOfRangeException : public System::Details_ArgumentException
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | شیءها را با استفاده از معنای [Object.Equals](../object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | یک دیکشنری حاوی داده‌های استثنای سفارشی را برمی‌گرداند. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | یک مقدار عددی ۳۲ بیتی را برمی‌گرداند که کد HRESULT مرتبط با استثنای نمایان‌شده توسط شیء فعلی است. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | مرجعی به شیئی که استثنای داخلی را نشان می‌دهد برمی‌گرداند. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | رشته‌ای حاوی توضیح خطا را برمی‌گرداند. |
| [String](../string/) [get_ParamName](./get_paramname/)() |  |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | رشته‌ای حاوی ردپای پشته (stack trace) را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | کپی شیء Exception که نمایانگر استثنای درونی‌ترین است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../object/gethashcode/) در C# است. امکان هش‌گذاری شیءهای سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../object/gettype/) در C# است. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../object/memberwiseclone/) در C# است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به-صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارندهٔ مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقداری عددی کدگذاری‌شده که به یک استثنای خاص اختصاص داده می‌شود. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | نمایش رشته‌ای شیء فعلی را برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | عبارت lock() در C# را برای آزادسازی پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از نشانگرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../details_exception/what/)() const | متد [what()](../details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) فراخوانی می‌شود. علیرغم اینکه این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق‌شده می‌توانند از اعضای protected/private برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Details_ArgumentException](../details_argumentexception/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)