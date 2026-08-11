---
title: IResponsiveHtmlController
second_title: مرجع API Aspose.Slides برای C++
description: کنترل‌کنندهٔ HTML واکنش‌گرا
type: docs
weight: 339
url: /fa/aspose.slides.export/iresponsivehtmlcontroller/
---
## IResponsiveHtmlController کلاس

کنترل‌کنندهٔ HTML واکنش‌گرا

```cpp
class IResponsiveHtmlController : public Aspose::Slides::Export::IHtmlFormattingController
```
## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شی‌ها را با استفاده از سمانتیک [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شی‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شی‌های نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌گذاری شی‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شی‌ها را بر‌اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شی‌ها را بر‌اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شی نوع مقداری را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع به اشتراک‌گذاری را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک پوینتر ضعیف (به‌جای اشتراک‌گذاری) تنظیم می‌کند. امکان تعویض پوینترها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع به اشتراک‌گذاری را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع به اشتراک‌گذاری را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع به اشتراک‌گذاری را کاهش داده و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل شی‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری دستور lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از هوشمندها یا ThisProtector استفاده کنید. |
| virtual void [WriteDocumentEnd](../ihtmlformattingcontroller/writedocumentend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | برای نوشتن فوتر سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود. |
| virtual void [WriteDocumentStart](../ihtmlformattingcontroller/writedocumentstart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\>) | برای نوشتن هدر سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود. |
| virtual void [WriteShapeEnd](../ihtmlformattingcontroller/writeshapeend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | قبل از رندرینگ شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید جاری پایان می‌یابد، بخش html افزوده شده وارد می‌شود و تصویر جدید بر بالای قبلی آغاز می‌شود. |
| virtual void [WriteShapeStart](../ihtmlformattingcontroller/writeshapestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\>) | قبل از رندرینگ شکل فراخوانی می‌شود. برای هر شکل یک بار فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید جاری پایان می‌یابد، بخش html افزوده شده وارد می‌شود و تصویر جدید بر بالای قبلی آغاز می‌شود. |
| virtual void [WriteSlideEnd](../ihtmlformattingcontroller/writeslideend/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | برای نوشتن فوتر اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود. |
| virtual void [WriteSlideStart](../ihtmlformattingcontroller/writeslidestart/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlGenerator](../ihtmlgenerator/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../../aspose.slides/islide/)\>) | برای نوشتن هدر اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IHtmlFormattingController](../ihtmlformattingcontroller/)
* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)