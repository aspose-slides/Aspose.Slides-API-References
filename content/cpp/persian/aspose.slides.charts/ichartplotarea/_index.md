---
title: IChartPlotArea
second_title: مرجع API Aspose.Slides برای C++
description: خواص عنوان نمودار را نمایش می‌دهد.
type: docs
weight: 794
url: /fa/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea کلاس

نمایش‌دهندهٔ ویژگی‌های عنوان نمودار.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو مقدار NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. قابل خواندن **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. قابل خواندن **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | موقعیت x واقعی (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. قابل خواندن **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | بالای واقعی عنصر نمودار نسبت به گوشهٔ بالا-چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. قابل خواندن **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار به‌دست می‌آورد. فقط-قابل-خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را برمی‌گرداند. فقط-قابل-خواندن [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | قالب ناحیهٔ نمودار را برمی‌گرداند. فقط-قابل-خواندن [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ارتفاع عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. قابل خواندن **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | اگر چیدمان ناحیهٔ نمودار به‌صورت دستی تعریف شده باشد، این ویژگی تعیین می‌کند که ناحیهٔ نمودار را بر اساس داخل (بدون محورها و برچسب‌های محورها) یا خارج (شامل محورها و برچسب‌های محورها) چینش کنیم. قابل خواندن [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-قابل-خواندن [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | راست عنصر نمودار را به عنوان کسری از عرض نمودار به‌دست می‌آورد. فقط-قابل-خواندن **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-قابل-خواندن [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | عرض عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. قابل خواندن **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | موقعیت x (چپ) عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. قابل خواندن **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. قابل خواندن **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را به‌دست می‌آورد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده‌ای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازنده‌ی کپی برای کلاس‌های فرزند را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر تخصیص. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازنده‌ی کپی برای کلاس‌های فرزند را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع‌اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ارتفاع عنصر نمودار را به‌عنوان کسری از ارتفاع نمودار تعیین می‌کند. مقدار **float** را بنویسید. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | اگر طرح ناحیه نمودار به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که آیا ناحیه نمودار را بر اساس داخل آن (بدون محور و برچسب‌های محورها) یا بر اساس خارج آن (شامل محور و برچسب‌های محورها) چیدمان شود. مقدار [LayoutTargetType](../layouttargettype/) را بنویسید. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | عرض عنصر نمودار را به‌عنوان کسری از عرض نمودار تعیین می‌کند. مقدار **float** را بنویسید. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | موقعیت x (چپ) عنصر نمودار را به‌عنوان کسری از عرض نمودار تعیین می‌کند. مقدار **float** را بنویسید. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | بالای عنصر نمودار را به‌عنوان کسری از ارتفاع نمودار تعیین می‌کند. مقدار **float** را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به‌عنوان اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر حالت اشاره‌گرها در کانتینرها به وضعیت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع‌اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع‌اشتراکی را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده‌ای داخلی را آزاد می‌کند. |
## همچنین ببینید

* کلاس [ILayoutable](../ilayoutable/)
* کلاس [IActualLayout](../iactuallayout/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)