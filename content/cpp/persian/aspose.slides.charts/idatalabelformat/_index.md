---
title: IDataLabelFormat
second_title: مرجع API Aspose.Slides برای C++
description: نمایش گزینه‌های قالب‌بندی برای DataLabel.
type: docs
weight: 963
url: /fa/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat کلاس

نمایش گزینه‌های قالب‌بندی برای [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را بر می‌گرداند. فقط خواندنی [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | قالب برچسب داده را نمایش می‌دهد. فقط خواندنی [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | خواندن **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | رشته قالب برای شیء DataLabels را نمایش می‌دهد. خواندنی [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | موقعیت برچسب داده را نمایش می‌دهد. خواندنی [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را بر می‌گرداند. فقط خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | یک Variant که جداساز استفاده شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد تنظیم یا بر می‌گرداند. خواندنی [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار اندازه حباب را نشان می‌دهد. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص را نمایش می‌دهد. True برای نمایش نام دسته‌بندی برچسب‌های داده در یک نمودار. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | تعیین می‌کند که آیا برچسب دادهٔ یک نمودار مشخص به‌صورت فراخوانی داده یا به‌صورت برچسب داده نمایش داده می‌شود. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار سلول را نشان می‌دهد. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | رفتار نمایش خطوط راهنما برچسب داده یک نمودار مشخص را نمایش می‌دهد. True خطوط راهنما را نشان می‌دهد. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص را نمایش می‌دهد. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. خواندنی **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار درصد را نشان می‌دهد. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | یک Boolean بر می‌گرداند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نشان دادن نام سری. False برای پنهان کردن. خواندنی **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار درصد را نشان می‌دهد. False برای پنهان کردن. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را بر می‌گرداند. فقط خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را بر می‌گرداند. فقط خواندنی [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری دستور lock() در C#. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را با مقدار مشخص کاهش می‌دهد. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | نوشتن **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | رشته قالب برای شیء DataLabels را نمایش می‌دهد. نوشتن [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | موقعیت برچسب داده را نمایش می‌دهد. نوشتن [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | یک Variant که جداساز استفاده شده برای برچسب‌های داده در یک نمودار را نشان می‌دهد تنظیم یا بر می‌گرداند. نوشتن [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار اندازه حباب را نشان می‌دهد. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص را نمایش می‌دهد. True برای نمایش نام دسته‌بندی برچسب‌های داده در یک نمودار. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | تعیین می‌کند که آیا برچسب دادهٔ یک نمودار مشخص به‌صورت فراخوانی داده یا به‌صورت برچسب داده نمایش داده می‌شود. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار سلول را نشان می‌دهد. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | رفتار نمایش خطوط راهنما برچسب داده یک نمودار مشخص را نمایش می‌دهد. True خطوط راهنما را نشان می‌دهد. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص را نمایش می‌دهد. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. نوشتن **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار درصد را نشان می‌دهد. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | یک Boolean بر می‌گرداند تا رفتار نمایش نام سری برای برچسب‌های داده در یک نمودار را نشان دهد. True برای نشان دادن نام سری. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص را نمایش می‌دهد. True مقدار درصد را نشان می‌دهد. False برای پنهان کردن. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | ارزش فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل برای دستور lock() در C#. مستقیماً فراخوانی کنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [IFormattedTextContainer](../iformattedtextcontainer/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)