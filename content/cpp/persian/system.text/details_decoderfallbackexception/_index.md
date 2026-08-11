---
title: Details_DecoderFallbackException
second_title: مرجع API Aspose.Slides برای C++
description: "استثنایی که توسط DecoderExceptionFallback هنگام شکست در رمزگشایی پرتاب می‌شود. هرگز نمونه‌های این کلاس را به‌صورت دستی ایجاد نکنید. به‌جای آن از کلاس DecoderFallbackException استفاده کنید. هرگز نمونه‌های کلاس DecoderFallbackException را داخل System::SmartPtr بسته‌بندی نکنید."
type: docs
weight: 105
url: /fa/system.text/details_decoderfallbackexception/
---
## کلاس Details_DecoderFallbackException

استثنایی که توسط [DecoderExceptionFallback](../decoderexceptionfallback/) هنگام شکست در رمزگشایی پرتاب می‌شود. هرگز به‌صورت دستی نمونه‌های این کلاس را ایجاد نکنید. به‌جای آن از کلاس DecoderFallbackException استفاده کنید. هرگز نمونه‌های کلاس DecoderFallbackException را داخل [System::SmartPtr](../../system/smartptr/) بسته‌بندی نکنید.

```cpp
class Details_DecoderFallbackException : public System::Details_ArgumentException
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از semantics [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای موارد داخلی. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_BytesUnknown](./get_bytesunknown/)() | آرایه بایتی که خطا را ایجاد کرده است را دریافت می‌کند. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | یک دیکشنری حاوی داده‌های سفارشی استثنا را برمی‌گرداند. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | یک مقدار عدد صحیح ۳۲ بیتی که کد HRESULT مرتبط با استثنای نمایان شده توسط شیء جاری است را برمی‌گرداند. |
| int [get_Index](./get_index/)() | موقعیت بایتی که خطا را در آرایه ورودی ایجاد کرده است را دریافت می‌کند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | یک ارجاع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | رشته‌ای که شامل توصیف خطا است را برمی‌گرداند. |
| [String](../../system/string/) [get_ParamName](../../system/details_argumentexception/get_paramname/)() |  |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | رشته‌ای که شامل ردپاهای پشته است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | کپی شیء Exception که نمایانگر داخلی‌ترین استثنا است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_argumentexception/gettype/)() const override | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| **bool** [Is](../../system/details_argumentexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌بندی عبارت lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | متعداد شمارندهٔ ارجاع مشترک را با مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، مقدار عددی کدگذاری شده‌ای که به یک استثنای خاص اختصاص یافته است. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | نمایش رشته‌ای شیء جاری را برمی‌گرداند. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_argumentexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل عبارت lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](../../system/details_exception/what/)() const | متد [what()](../../system/details_exception/what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../../system/exceptionwrapper/) فراخوانی می‌شود. علیرغم این که این کلاس از std::exception ارث‌بری نمی‌کند، کلاس‌های مشتق می‌توانند از اعضای protected/ private برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../../system/exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [Details_ArgumentException](../../system/details_argumentexception/)
* فضای نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)