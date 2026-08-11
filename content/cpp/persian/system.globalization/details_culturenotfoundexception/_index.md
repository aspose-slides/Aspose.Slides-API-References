---
title: Details_CultureNotFoundException
second_title: مرجع API Aspose.Slides برای C++
description: "CultureNotFoundException زمانی پرتاب می‌شود که سعی شود فرهنگی ساخته شود که در دسترس نیست. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به جای آن از کلاس CultureNotFoundException استفاده کنید. هرگز نمونه‌های کلاس CultureNotFoundException را داخل System::SmartPtr پیچانید."
type: docs
weight: 92
url: /fa/system.globalization/details_culturenotfoundexception/
---
## Details_CultureNotFoundException کلاس

CultureNotFoundException زمانی پرتاب می‌شود که سعی شود فرهنگی ساخته شود که در دسترس نیست. هرگز نمونه‌های این کلاس را به صورت دستی ایجاد نکنید. به جای آن از کلاس CultureNotFoundException استفاده کنید. هرگز نمونه‌های کلاس CultureNotFoundException را داخل [System::SmartPtr](../../system/smartptr/) نیندازید.

```cpp
class Details_CultureNotFoundException : public System::Details_ArgumentException
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | تنها برای مقاصد داخلی. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | یک فرهنگ‌نامه با داده‌های سفارشی استثنا برمی‌گرداند. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | یک مقدار عدد صحیح 32-بیتی که یک کد HRESULT مرتبط با استثنای نماینده توسط شیء فعلی است، برمی‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | مرجع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [Nullable](../../system/nullable/)\<int\> [get_InvalidCultureId](./get_invalidcultureid/)() const |  |
| virtual [String](../../system/string/) [get_InvalidCultureName](./get_invalidculturename/)() const |  |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | رشته‌ای حاوی توضیح خطا را برمی‌گرداند. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | رشته‌ای حاوی ردیابی پشته (stack trace) را برمی‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | یک کپی از شیء Exception که نمایانگر استثنای درونی‌ترین است، برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارش‌گر مرجع مرتبط با شیء را می‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | نوع واقعی شیء را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | قفل کردن با استفاده از بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فعال می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فعال می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارش مرجع اشتراکی را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقدار عددی کدگذاری شده‌ای که به استثنای خاصی اختصاص داده می‌شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n‌ام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تعویض اشاره‌گرها در مخازن به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارشگر مرجع اشتراکی را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع اشتراکی را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | نمایش رشته‌ای شیء فعلی را برمی‌گرداند. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس با استفاده از بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../../system/details_exception/what/)() const | متد [what()](../../system/details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../../system/exceptionwrapper/) فراخوانی می‌شود. با وجود این که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای protected/ private برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../../system/exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |
## موارد مرتبط

* کلاس [Details_ArgumentException](../../system/details_argumentexception/)
* فضای نام [System::Globalization](../)
* کتابخانه [Aspose.Slides](../../)