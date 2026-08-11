---
title: Details_Exception
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک استثنا است. هرگز به صورت دستی نمونه‌های این کلاس را ایجاد نکنید. به جای آن از کلاس Exception استفاده کنید. هرگز نمونه‌های کلاس Exception را در System::SmartPtr بسته‌بندی نکنید."
type: docs
weight: 417
url: /fa/system/details_exception/
---
## Details_Exception کلاس

نمایانگر یک استثنا است. هرگز به صورت دستی نمونه‌های این کلاس را ایجاد نکنید. به جای آن از کلاس Exception استفاده کنید. هرگز نمونه‌های کلاس Exception را در [System::SmartPtr](../smartptr/) بسته‌بندی نکنید.

```cpp
class Details_Exception : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [DoThrow](./dothrow/)(const [ExceptionPtr](../exceptionptr/)\&) const | نمونه استثنا را که توسط wrapper استثنا بسته‌بندی شده است پرتاب می‌کند. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از C# [Object.Equals](../object/equals/) سیمانتیک مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی با این که طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی با این که طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [SharedPtr](../sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>, [SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\> [get_Data](./get_data/)() | دیکشنری شامل داده‌های سفارشی استثنا را باز می‌گرداند. |
| **int32_t** [get_HResult](./get_hresult/)() const | یک مقدار عدد صحیح 32 بیتی که کد HRESULT مرتبط با استثنای نمایان‌شده توسط شیء فعلی است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [get_InnerException](./get_innerexception/)() const | یک ارجاع به شیء نمایانگر استثنای داخلی را برمی‌گرداند. |
| virtual [String](../string/) [get_Message](./get_message/)() const | رشته‌ای که شامل توصیف خطا است را برمی‌گرداند. |
| virtual [String](../string/) [get_StackTrace](./get_stacktrace/)() const | رشته‌ای که شامل ردپای پشته است را برمی‌گرداند. |
| virtual [ExceptionWrapper](../exceptionwrapper/)\<[Details_Exception](./)\> [GetBaseException](./getbaseexception/)() const | کپی شیء Exception که نمایانگر استثنای درونی‌ترین است را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارشگر مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). هش‌سازی اشیاء سفارشی را امکان‌پذیر می‌سازد. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../object/lock/)() | عملگر lock() در C# را پیاده‌سازی می‌کند. به صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در کلاس‌های مشتق را فراهم می‌آورد. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | اپراتور تخصیص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی در کلاس‌های مشتق را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء از نوع مقدار را با nullptr به‌صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص برای [Object::ReferenceEquals](../object/referenceequals/) در مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص برای [Object::ReferenceEquals](../object/referenceequals/) در مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | تعداد شمارش مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| void [set_HResult](./set_hresult/)(**int32_t**) | HRESULT را تنظیم می‌کند، یک مقدار عددی کدگذاری شده که به استثنای خاصی اختصاص داده می‌شود. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارشگر مرجع اشتراکی را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارشگر مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارشگر مرجع اشتراکی را کاهش می‌دهد و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](./tostring/)() const override | نمایش رشته‌ای شیء فعلی را برمی‌گرداند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | عملگر lock() در C# را برای باز کردن پیاده‌سازی می‌کند. به صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارشگر مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارشگر مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual const char * [what](./what/)() const | متدی [what()](./what/) را پیاده‌سازی می‌کند که توسط کلاس [ExceptionWrapper](../exceptionwrapper/) فراخوانی می‌شود. علیرغم این که این کلاس از std::exception وارث نیست، کلاس‌های مشتق می‌توانند از اعضای protected/ private برای پیاده‌سازی منطق خود استفاده کنند. انتقال پیاده‌سازی این متد به [ExceptionWrapper](../exceptionwrapper/) ممکن است آن منطق را خراب کند. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Object](../object/)
* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)