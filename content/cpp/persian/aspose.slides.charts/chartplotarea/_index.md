---
title: ChartPlotArea
second_title: مرجع API Aspose.Slides برای C++
description: مستطیلی که نمودار باید در آن رسم شود را نشان می‌دهد.
type: docs
weight: 248
url: /fa/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea کلاس

مستطیلی که نمودار باید در آن رسم شود.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور دوبل به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مصارف داخلی. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندنی **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندنی **float**. |
| **float** [get_ActualX](./get_actualx/)() override | موقعیت x واقعی (چپ) عنصر نمودار نسبت به گوشه بالای سمت چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندنی **float**. |
| **float** [get_ActualY](./get_actualy/)() override | موقعیت بالایی واقعی عنصر نمودار نسبت به گوشه بالای سمت چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواندنی **float**. |
| **float** [get_Bottom](./get_bottom/)() override | پایین. فقط-خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). فقط-خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | فرمت یک ناحیه‌نقشه را برمی‌گرداند. فقط-خواندنی [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | ارتفاع جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند. خواندنی **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | نحوه محاسبه مکان را تعریف می‌کند: true – به‌صورت خودکار محاسبه می‌شود؛ توسط ویژگی‌های X, Y, Width, Height تعریف می‌شود. فقط-خواندنی **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | اگر چیدمان ناحیه‌نقشه به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه‌نقشه از داخل (بدون محور و برچسب‌های محور) یا خارج (با محور و برچسب‌های محور) چیدمان شود. خواندنی [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | راست. فقط-خواندنی **float**. |
| **float** [get_Width](./get_width/)() override | عرض جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند. خواندنی **float**. |
| **float** [get_X](./get_x/)() override | مختصات x گوشه بالای سمت چپ جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از عرض نمودار (از 0 تا 1) برمی‌گرداند. خواندنی **float**. |
| **float** [get_Y](./get_y/)() override | مختصات y گوشه بالای سمت چپ جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از ارتفاع نمودار (از 0 تا 1) برمی‌گرداند. خواندنی **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Height](./set_height/)(**float**) override | ارتفاع جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از ارتفاع نمودار (از 0 تا 1) تنظیم می‌کند. نوشتنی **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | اگر چیدمان ناحیه‌نقشه به‌صورت دستی تعریف شده باشد، این ویژگی مشخص می‌کند که ناحیه‌نقشه از داخل (بدون محور و برچسب‌های محور) یا خارج (با محور و برچسب‌های محور) چیدمان شود. نوشتنی [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | عرض جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از عرض نمودار (از 0 تا 1) تنظیم می‌کند. نوشتنی **float**. |
| void [set_X](./set_x/)(**float**) override | مختصات x جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از عرض نمودار (از 0 تا 1) تنظیم می‌کند. نوشتنی **float**. |
| void [set_Y](./set_y/)(**float**) override | مختصات y جعبه محدوده ناحیه‌نقشه را به عنوان یک کسری از ارتفاع نمودار (از 0 تا 1) تنظیم می‌کند. نوشتنی **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان الگو nام را به‌عنوان یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر نشانگرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [IChartPlotArea](../ichartplotarea/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)