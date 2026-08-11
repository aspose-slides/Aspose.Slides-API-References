---
title: ILegend
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های افسانهٔ نمودار را نمایش می‌دهد.
type: docs
weight: 1080
url: /fa/aspose.slides.charts/ilegend/
---
## ILegend کلاس

Represents chart's legend properties.

```cpp
class ILegend : public Aspose::Slides::Charts::ILayoutable,
                public Aspose::Slides::Charts::IFormattedTextContainer,
                public Aspose::Slides::Charts::IActualLayout
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه شناور به سبک C# که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندن **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | عرض واقعی عنصر نمودار را مشخص می‌کند. پیش از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندن **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. پیش از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندن **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | بالای واقعی عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. پیش از دریافت مقادیر واقعی، روش [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندن **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را برمی‌گرداند. فقط-خواندنی [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() | ورودی‌های افسانه را دریافت می‌کند. فقط-خواندنی [ILegendEntryCollection](../ilegendentrycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) | خواص ورودی افسانه‌ای که به نقطه داده در نمودار در اندیس مشخص مربوط است دریافت می‌کند. در مورد انواع نمودار: bar-of-pie، exploded pie، exploded pie 3D، pie، pie 3D، pie-of-pie، نقطه داده از اولین سری گرفته می‌شود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | قالب یک افسانه را برمی‌گرداند. فقط-خواندنی [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ارتفاع عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. خواندن **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | تعیین می‌کند آیا عناصر دیگر نمودار بتوانند بر افسانه غلبه کنند یا نه. خواندن **bool**. |
| virtual [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() | موقعیت افسانه را روی نمودار مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X, Y, Width, Heigt اثر این ویژگی را بازنویسی می‌کنند. خواندن [LegendPositionType](../legendpositiontype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | سمت راست عنصر نمودار را به عنوان کسری از عرض نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | عرض عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | موقعیت x (چپ) عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. خواندن **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نمونهٔ روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نمونهٔ فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. نمونهٔ عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری عبارت lock() در C#. به طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نمونهٔ روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ارتفاع عنصر نمودار را به عنوان کسری از ارتفاع نمودار تعیین می‌کند. نوشتن **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند بر افسانه غلبه کنند. نوشتن **bool**. |
| virtual void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) | موقعیت افسانه را روی نمودار مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X, Y, Width, Heigt اثر این ویژگی را بازنویسی می‌کنند. نوشتن [LegendPositionType](../legendpositiontype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | عرض عنصر نمودار را به عنوان کسری از عرض نمودار تعیین می‌کند. نوشتن **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | موقعیت x (چپ) عنصر نمودار را به عنوان کسری از عرض نمودار تعیین می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار تعیین می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به‌عنوان اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نمونهٔ روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازندهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل عبارت lock() در C#. به‌طور مستقیم فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## موارد مرتبط

* کلاس [ILayoutable](../ilayoutable/)
* کلاس [IFormattedTextContainer](../iformattedtextcontainer/)
* کلاس [IActualLayout](../iactuallayout/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)