---
title: Legend
second_title: مرجع API Aspose.Slides برای C++
description: خواص راهنمای نمودار را نمایش می‌دهد.
type: docs
weight: 1262
url: /fa/aspose.slides.charts/legend/
---
## کلاس Legend

خواص راهنمای نمودار را نشان می‌دهد.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به دست آید. **float** را بخوانید. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به دست آید. **float** را بخوانید. |
| **float** [get_ActualX](./get_actualx/)() override | موقعیت افقی واقعی (چپ) عنصر نمودار را نسبت به گوشه بالا-چپ نمودار مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به دست آید. **float** را بخوانید. |
| **float** [get_ActualY](./get_actualy/)() override | بالای واقعی عنصر نمودار نسبت به گوشه بالا-چپ نمودار مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به دست آید. **float** را بخوانید. |
| **float** [get_Bottom](./get_bottom/)() override | پایین. **float** فقط-خواندنی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار را برمی‌گرداند. [IChart](../ichart/) فقط-خواندنی. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | ورودی‌های راهنما را دریافت می‌کند. [ILegendEntryCollection](../ilegendentrycollection/) فقط-خواندنی. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | ویژگی‌های ورودی راهنما که به نقطه داده در نمودار با اندیس مشخص مربوط است را دریافت می‌کند. در انواع نمودار: bar-of-pie، exploded pie، exploded pie 3D، pie، pie 3D، pie-of-pie، نقطه داده از اولین سری گرفته می‌شود. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | قالب یک راهنما را برمی‌گرداند. [IFormat](../iformat/) فقط-خواندنی. |
| **float** [get_Height](./get_height/)() override | ارتفاع یک راهنما را به عنوان کسر ارتفاع نمودار برمی‌گرداند. **float** را بخوانید. |
| **bool** [get_Overlay](./get_overlay/)() override | تعیین می‌کند آیا عناصر دیگر نمودار اجازه دارند راهنما را تحت پوشش قرار دهند یا خیر. **bool** را بخوانید. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | موقعیت راهنما بر روی نمودار را مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X، Y، Width، Heigt اثر این ویژگی را لغو می‌کنند. [LegendPositionType](../legendpositiontype/) را بخوانید. |
| **float** [get_Right](./get_right/)() override | راست. **float** فقط-خواندنی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن. [IChartTextFormat](../icharttextformat/) فقط-خواندنی. |
| **float** [get_Width](./get_width/)() override | عرض یک راهنما را به عنوان کسر عرض نمودار برمی‌گرداند. **float** را بخوانید. |
| **float** [get_X](./get_x/)() override | مختصات x یک راهنما را به عنوان کسر عرض نمودار برمی‌گرداند. **float** را بخوانید. |
| **float** [get_Y](./get_y/)() override | مختصات y یک راهنما را به عنوان کسر ارتفاع نمودار برمی‌گرداند. **float** را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کلاس‌های فرزند با کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کلاس‌های فرزند با کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر پایه مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کم می‌کند. |
| void [set_Height](./set_height/)(**float**) override | ارتفاع یک راهنما را به عنوان کسر ارتفاع نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_Overlay](./set_overlay/)(**bool**) override | تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند راهنما را پوشش دهند یا خیر. **bool** را بنویسید. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | موقعیت راهنما بر روی نمودار را مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X، Y، Width، Heigt اثر این ویژگی را لغو می‌کنند. [LegendPositionType](../legendpositiontype/) را بنویسید. |
| void [set_Width](./set_width/)(**float**) override | عرض یک راهنما را به عنوان کسر عرض نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_X](./set_x/)(**float**) override | مختصات x یک راهنما را به عنوان کسر عرض نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_Y](./set_y/)(**float**) override | مختصات y یک راهنما را به عنوان کسر ارتفاع نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان nام قالب را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را باز می‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [ILegend](../ilegend/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)