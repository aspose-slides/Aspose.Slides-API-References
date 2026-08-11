---
title: Details_FormatException
second_title: Aspose.Slides برای C++ مرجع API
description: "زمانی که قالب آرگومان متد معتبر نباشد، FormatException پرتاب می‌شود. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به جای آن از کلاس FormatException استفاده کنید. هرگز نمونه‌های کلاس FormatException را در System::SmartPtr پیچیده نکنید."
type: docs
weight: 469
url: /fa/system/details_formatexception/
---
## Details_FormatException کلاس

FormatException زمانی پرتاب می‌شود که قالب آرگومان روش معتبر نباشد. هرگز نمونه‌های این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس FormatException استفاده کنید. هرگز نمونه‌های کلاس FormatException را در [System::SmartPtr](../smartptr/) بپیچید.

```cpp
class Details_FormatException : public System::Details_SystemException
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | آبجکت‌ها را با استفاده از معنای [Object.Equals](../object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه عدد شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه عدد شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](../details_exception/get_data/)() | یک دیکشنری با داده‌های استثنا سفارشی باز می‌گرداند. |
| **int32_t** [get_HResult](../details_exception/get_hresult/)() const | یک مقدار عدد صحیح 32 بیتی باز می‌گرداند که کد HRESULT مرتبط با استثنایی است که توسط شیء فعلی نمایان شده است. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [get_InnerException](../details_exception/get_innerexception/)() const | یک ارجاع به شیء نمایانگر استثنای داخلی باز می‌گرداند. |
| virtual [String](../string/) [get_Message](../details_exception/get_message/)() const | رشته‌ای حاوی توضیح خطا را باز می‌گرداند. |
| virtual [String](../string/) [get_StackTrace](../details_exception/get_stacktrace/)() const | رشته‌ای حاوی ردیابی پشته را باز می‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](../details_exception/)\> [GetBaseException](../details_exception/getbaseexception/)() const | یک کپی از شیء Exception که نمایانگر استثنای داخلی‌ترین است را باز می‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../object/gettype/) در C# است. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const override |  |
| void [Lock](../object/lock/)() | قفل‌کردن عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../object/object/)() | یک شیء ایجاد می‌کند. تمامی ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../object/object/)([Object](../object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه‌ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصیص ویژه برای [Object::ReferenceEquals](../object/referenceequals/) در حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصیص ویژه برای [Object::ReferenceEquals](../object/referenceequals/) در حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](../details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقداری عددی کدگذاری شده که به یک استثنای خاص اختصاص داده می‌شود. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](../details_exception/tostring/)() const override | نمایش رشته‌ای شیء فعلی را باز می‌گرداند. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() |  |
| void [Unlock](../object/unlock/)() | قفل‌برداری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../details_exception/what/)() const | متد [what()](../details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) فراخوانی می‌شود. به‌نظر می‌رسد این کلاس از std::exception ارث نمی‌برد اما کلاس‌های مشتق می‌توانند از اعضای محافظت‌شده/خصوصی برای پیاده‌سازی منطق خود استفاده کنند. جابه‌جایی پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Details_SystemException](../details_systemexception/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)