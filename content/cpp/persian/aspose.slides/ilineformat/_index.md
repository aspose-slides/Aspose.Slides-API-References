---
title: ILineFormat
second_title: Aspose.Slides برای C++ مرجع API
description: نمایش قالب یک خط.
type: docs
weight: 2757
url: /fa/aspose.slides/ilineformat/
---
## ILineFormat کلاس

نمایش قالب یک خط.

```cpp
class ILineFormat : public Aspose::Slides::ILineParamSource
```

## Methods

| Method | توضیح |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](./)\>) | تعیین می‌کند که آیا دو نمونه [LineFormat](../lineformat/) برابر هستند یا نه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌ی شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدارى نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌ی شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو مقدار NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدارى نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | تراز خط را برمی‌گرداند. خواندنی [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | طول سرپیکان در ابتدای خط را برمی‌گرداند. خواندنی [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | سبک سرپیکان در ابتدای خط را برمی‌گرداند. خواندنی [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | عرض سرپیکان در ابتدای خط را برمی‌گرداند. خواندنی [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | سبک انتهای خط را برمی‌گرداند. خواندنی [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | الگوهای خط‌خطی سفارشی را برمی‌گرداند. خواندنی **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | سبک خط‌خطی خط را برمی‌گرداند. خواندنی [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | طول سرپیکان در انتهای خط را برمی‌گرداند. خواندنی [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | سبک سرپیکان در انتهای خط را برمی‌گرداند. خواندنی [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | عرض سرپیکان در انتهای خط را برمی‌گرداند. خواندنی [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() | قالب پر کردن خط را برمی‌گرداند. فقط-خواندنی [ILineFillFormat](../ilinefillformat/). |
| virtual **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() | در صورت عدم تعریف قالب خط (همان‌طور که تازه ساخته شده است، پیش‌فرض) مقدار true را برمی‌گرداند. فقط-خواندنی **bool**. |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | سبک اتصال خطوط را برمی‌گرداند. خواندنی [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | حد میتر خط را برمی‌گرداند. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() | قالب طرح خط را برمی‌گرداند. فقط-خواندنی [ISketchFormat](../isketchformat/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | سبک خط را برمی‌گرداند. خواندنی [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | عرض خط را برمی‌گرداند. خواندنی **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مربوط به شیء را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() | داده‌های قالب‌بندی مؤثر خط را با توجه به ارث‌بری دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع‌های مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) | تراز خط را تنظیم می‌کند. نوشتاری [LineAlignment](../linealignment/). |
| virtual void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | طول سرپیکان در ابتدای خط را تنظیم می‌کند. نوشتاری [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | سبک سرپیکان در ابتدای خط را تنظیم می‌کند. نوشتاری [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | عرض سرپیکان در ابتدای خط را تنظیم می‌کند. نوشتاری [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) | سبک انتهای خط را تنظیم می‌کند. نوشتاری [LineCapStyle](../linecapstyle/). |
| virtual void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) | الگوهای خط‌خطی سفارشی را تنظیم می‌کند. نوشتاری **float**[]. |
| virtual void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) | سبک خط‌خطی خط را تنظیم می‌کند. نوشتاری [LineDashStyle](../linedashstyle/). |
| virtual void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) | طول سرپیکان در انتهای خط را تنظیم می‌کند. نوشتاری [LineArrowheadLength](../linearrowheadlength/). |
| virtual void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) | سبک سرپیکان در انتهای خط را تنظیم می‌کند. نوشتاری [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) | عرض سرپیکان در انتهای خط را تنظیم می‌کند. نوشتاری [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) | سبک اتصال خطوط را تنظیم می‌کند. نوشتاری [LineJoinStyle](../linejoinstyle/). |
| virtual void [set_MiterLimit](./set_miterlimit/)(**float**) | حد میتر خط را تنظیم می‌کند. نوشتاری **float**. |
| virtual void [set_Style](./set_style/)([LineStyle](../linestyle/)) | سبک خط را تنظیم می‌کند. نوشتاری [LineStyle](../linestyle/). |
| virtual void [set_Width](./set_width/)(**double**) | عرض خط را تنظیم می‌کند. نوشتاری **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس بیان lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به جای آن از اشارات هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ILineParamSource](../ilineparamsource/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)