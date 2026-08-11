---
title: Details_AxesCompositionNotCombinableException
second_title: مرجع API Aspose.Slides برای C++
description: استثنایی که زمانی رخ می‌دهد که ترکیب محورهای سری با ترکیب محورهای موجود در نمودار ترکیب‌پذیر نباشد.
type: docs
weight: 430
url: /fa/aspose.slides.charts/details_axescompositionnotcombinableexception/
---
## Details_AxesCompositionNotCombinableException کلاس

Exception which thrown when axes composition of the series is not combinable with present axes composition in chart.

```cpp
class Details_AxesCompositionNotCombinableException : public System::Details_InvalidOperationException
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از semantics [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | دیکشنری با داده‌های استثنا سفارشی را برمی‌گرداند. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | یک مقدار صحیح ۳۲ بیتی را برمی‌گرداند که کد HRESULT مرتبط با استثنای نمایندگی‌شده توسط شیء جاری است. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | مرجع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | رشته‌ای که حاوی توضیح خطا است را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | رشته‌ای که حاوی ردگیری پشته است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | کپی شیء Exception که نشان‌دهندهٔ استثنای درونی‌ترین است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_invalidoperationexception/gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_invalidoperationexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | عمل بیان قفل C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را از طریق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr مقایسه مرجع می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کم می‌کند. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقدار عددی کدگذاری‌شده‌ای که به یک استثنای خاص اختصاص یافته است. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از‌ اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از‌ اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | نمایش رشته‌ای شیء جاری را برمی‌گرداند. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_invalidoperationexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | عمل بیان قفل C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از‌ اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از‌ اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../../system/details_exception/what/)() const | متد [what()](../../system/details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../../system/exceptionwrapper/) فراخوانی می‌شود. بع‌رغم این‌که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای protected/private برای پیاده‌سازی منطق خود استفاده کنند. انتقال این پیاده‌سازی متد به [ExceptionWrapper](../../system/exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Details_InvalidOperationException](../../system/details_invalidoperationexception/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)