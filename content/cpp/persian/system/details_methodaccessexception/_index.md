---
title: Details_MethodAccessException
second_title: مرجع API Aspose.Slides برای C++
description: "MemberAccessException زمانی پرتاب می‌شود که دسترسی به متدی که وجود ندارد انجام شود یا زمانی که دسترسی به متد مجاز نباشد. هرگز به‌صورت دستی نمونه‌های این کلاس را ایجاد نکنید. به‌جای آن از کلاس MethodAccessException استفاده کنید. هرگز نمونه‌های کلاس MethodAccessException را داخل System::SmartPtr نپیچانید."
type: docs
weight: 560
url: /fa/system/details_methodaccessexception/
---
## Details_MethodAccessException کلاس

MemberAccessException زمانی رخ می‌دهد که دسترسی به متدی که وجود ندارد سعی شود یا زمانی که دسترسی به متد مجاز نیست. هرگز به‌صورت دستی نمونه‌های این کلاس را ایجاد نکنید. به‌جای آن از کلاس MethodAccessException استفاده کنید. هرگز نمونه‌های کلاس MethodAccessException را داخل [System::SmartPtr](../smartptr/) بپیچید.

```cpp
class Details_MethodAccessException : public System::Details_MemberAccessException
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | تطبیق مقایسهٔ عدد اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | تطبیق مقایسهٔ عدد اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | یک دیکشنری حاوی داده‌های سفارشی استثنا را برمی‌گرداند. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | یک مقدار عدد صحیح 32 بیتی که کد HRESULT مرتبط با استثنایی است که توسط شیء فعلی نشان داده می‌شود را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | یک مرجع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | رشته‌ای حاوی توضیح خطا را برمی‌گرداند. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | رشته‌ای حاوی ردیابی پشته (stack trace) را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | یک کپی از شیء Exception که نمایانگر داخلی‌ترین استثنا است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌آورد. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان ایجاد نسخهٔ کپی از انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌آورد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از کلاس‌های فرزند را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را با استفاده از مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را با استفاده از مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقداری عددی کدگذاری‌شده که به یک استثنای خاص اختصاص یافته است. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | نمایش رشته‌ای شیء فعلی را برمی‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | اجرای باز کردن قفل بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../details_exception/what/)() const | متد [what()](../details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) صدا زده می‌شود. با وجود این که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای محافظت‌شده/خصوصی برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## مطالب مرتبط

* کلاس [Details_MemberAccessException](../details_memberaccessexception/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)