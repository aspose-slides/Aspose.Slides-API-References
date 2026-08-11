---
title: IChartTitle
second_title: مرجع API Aspose.Slides برای C++
description: نمایانگر خصوصیات عنوان نمودار است.
type: docs
weight: 911
url: /fa/aspose.slides.charts/icharttitle/
---
## IChartTitle کلاس

نمایانگر خصوصیات عنوان نمودار است.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | TextFrameForOverriding را با متن موجود در پارامتر \"text\" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی اولیه شده باشد، صرفاً متن آن را تغییر می‌دهد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. خواندن **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. خواندن **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | موقعیت x واقعی (چپ) عنصر نمودار را نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. خواندن **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | بالای واقعی عنصر نمودار نسبت به گوشهٔ بالا-چپ نمودار مشخص می‌شود. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. خواندن **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | بالای عنصر نمودار را به عنوان کسر ارتفاع نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را برمی‌گرداند. فقط-خواندنی [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | سبک‌های پر، خط، اثر یک عنوان را برمی‌گرداند. فقط-خواندنی [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ارتفاع عنصر نمودار را به عنوان کسر ارتفاع نمودار مشخص می‌کند. خواندن **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | مشخص می‌کند آیا عناصر دیگر نمودار می‌توانند بر عنوان هم‌پوشانی داشته باشند. خواندن **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | پرزنتیشن را برمی‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | سمت راست عنصر نمودار را به عنوان کسر عرض نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | می‌تواند متنی با قالب‌بندی غنی داشته باشد. اگر این ویژگی null نباشد، مقدار متن قالب‌بندی‌شده، متن تولید خودکار را بازنویسی می‌کند. متن تولید خودکار یک ویژگی ضمنی برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار، برچسب خط روند است. متن تولید خودکار با ویژگی [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | عرض عنصر نمودار را به عنوان کسر عرض نمودار مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | موقعیت x (چپ) عنصر نمودار را به عنوان کسر عرض نمودار مشخص می‌کند. خواندن **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | بالای عنصر نمودار را به عنوان کسر ارتفاع نمودار مشخص می‌کند. خواندن **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل کردن با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr به‌وسیلهٔ مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ارتفاع عنصر نمودار را به عنوان کسر ارتفاع نمودار مشخص می‌کند. نوشتن **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | مشخص می‌کند آیا به دیگر عناصر اجازه هم‌پوشانی با عنوان داده شود. نوشتن **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | عرض عنصر نمودار را به عنوان کسر عرض نمودار مشخص می‌کند. نوشتن **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | موقعیت x (چپ) عنصر نمودار را به عنوان کسر عرض نمودار مشخص می‌کند. نوشتن **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | بالای عنصر نمودار را به عنوان کسر ارتفاع نمودار مشخص می‌کند. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عملگر C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [ILayoutable](../ilayoutable/)
* کلاس [IOverridableText](../ioverridabletext/)
* کلاس [IActualLayout](../iactuallayout/)
* فضازمان [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)