---
title: Axis
second_title: مرجع API برای C++ Aspose.Slides
description: شیئی را که نمایانگر محور نمودار است، در بر می‌گیرد.
type: docs
weight: 14
url: /fa/aspose.slides.charts/axis/
---
## کلاس Axis

شیئی را که نمایانگر محور نمودار است، در بر می‌گیرد.

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## متدها

| متد | توضحیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# اشیاء را مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | حداکثر مقدار واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | مقیاس واحد فرعی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | حداقل مقدار واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید. |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | نشان می‌دهد آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها قطع می‌کند یا نه. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای ۳-بعدی کاربرد ندارد. قابل‌خواندن **bool**. |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | کوچک‌ترین واحد زمان نمایش داده شده بر محور تاریخ را مشخص می‌کند. قابل‌خواندن [TimeUnitType](../timeunittype/). |
| **double** [get_BinWidth](./get_binwidth/)() override | عرض سطل را زمانی که مقدار ویژگی AggregationType برابر [AxisAggregationType::ByBinWidth](../axisaggregationtype/) تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | نوع محور دسته‌بندی را مشخص می‌کند. قابل‌خواندن [Charts::CategoryAxisType](../categoryaxistype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را برمی‌گرداند. فقط‌خواندنی [IChart](../ichart/). |
| **float** [get_CrossAt](./get_crossat/)() override | نقطه‌ای روی محور که محور عمود بر آن تقاطع می‌کند را نشان می‌دهد. قابل‌خواندن **float**. |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | نوع تقاطع (CrossType) روی محور مشخص‌شده که محور دیگر بر آن تقاطع می‌کند را نشان می‌دهد. قابل‌خواندن [CrossesType](../crossestype/). |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | مقدار اسکالینگ واحدهای نمایش برای محور مقدار را مشخص می‌کند. قابل‌خواندن [DisplayUnitType](../displayunittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | قالب محور را نشان می‌دهد. فقط‌خواندنی [IAxisFormat](../iaxisformat/). |
| **bool** [get_HasTitle](./get_hastitle/)() override | تشخیص می‌دهد آیا محور عنوان قابل‌مشاهده دارد یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | نشان می‌دهد آیا مقدار بیشینه به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | نشان می‌دهد آیا مقدار کمینه به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | مقدار سطل سرریز خودکار را مشخص می‌کند. اگر false: از ویژگی OverflowBin استفاده کنید. |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر false: از ویژگی TickLabelSpacing استفاده کنید. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false: از ویژگی TickMarksSpacing استفاده کنید. قابل‌خواندن **bool**. |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | مقدار سطل زیرریزی خودکار را مشخص می‌کند. اگر false: از ویژگی UnderflowBin استفاده کنید. |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | نشان می‌دهد آیا فرمت به داده منبع پیوند خورده است یا نه. قابل‌خواندن **bool**. |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | مشخص می‌کند آیا سطل سرریز اعمال شده است. برای تنظیم مقدار سطل سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | نشان می‌دهد آیا PowerPoint داده‌ها را از آخر به ابتدا رسم می‌کند. قابل‌خواندن **bool**. |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | مشخص می‌کند آیا سطل زیرریزی اعمال شده است. برای تنظیم مقدار سطل زیرریزی از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| **bool** [get_IsVisible](./get_isvisible/)() override | نشان می‌دهد آیا محور قابل مشاهده است. قابل‌خواندن **bool**. |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته‌بندی یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. قابل‌خواندن **uint16_t**. |
| **double** [get_LogBase](./get_logbase/)() override | پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض ۱۰ است. قابل‌خواندن **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | قالب خطوط راهنمای اصلی بر روی محور نمودار را نشان می‌دهد. فقط‌خواندنی [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. قابل‌خواندن [TickMarkType](../tickmarktype/). |
| **double** [get_MajorUnit](./get_majorunit/)() override | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل‌خواندن **double**. |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل‌خواندن [TimeUnitType](../timeunittype/). |
| **double** [get_MaxValue](./get_maxvalue/)() override | حداکثر مقدار بر روی محور مقدار را نشان می‌دهد. قابل‌خواندن **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | قالب خطوط راهنمای فرعی بر روی محور نمودار را نشان می‌دهد. فقط‌خواندنی [IChartLinesFormat](../ichartlinesformat/). |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. قابل‌خواندن [TickMarkType](../tickmarktype/). |
| **double** [get_MinorUnit](./get_minorunit/)() override | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل‌خواندن **double**. |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل‌خواندن [TimeUnitType](../timeunittype/). |
| **double** [get_MinValue](./get_minvalue/)() override | حداقل مقدار بر روی محور مقدار را نشان می‌دهد. قابل‌خواندن **double**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | رشته قالب برای برچسب‌های [Axis](./) را نشان می‌دهد. قابل‌خواندن [System::String](../../system/string/). |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | تعداد سطل‌ها را هنگامی که مقدار ویژگی AggregationType برابر [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) باشد، مشخص می‌کند. برای محورهای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| **double** [get_OverflowBin](./get_overflowbin/)() override | مقدار سفارشی سطل سرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin برابر false تنظیم شده و IsOverflowBin برابر true باشد، اعمال می‌شود. |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | موقعیت محور را نشان می‌دهد. قابل‌خواندن [AxisPositionType](../axispositiontype/). |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | برای مخفی کردن خط راهنمای اصلی، [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() را روی [FillType::NoFill](../../aspose.slides/filltype/) تنظیم کنید. فقط‌خواندنی **bool**. |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | برای مخفی کردن خط راهنمای فرعی، [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() را روی [FillType::NoFill](../../aspose.slides/filltype/) تنظیم کنید. فقط‌خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن را نشان می‌دهد. فقط‌خواندنی [IChartTextFormat](../icharttextformat/). |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | موقعیت برچسب‌های علامت‌تیک روی محور مشخص‌شده را نشان می‌دهد. قابل‌خواندن [TickLabelPositionType](../ticklabelpositiontype/). |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. قابل‌خواندن **float**. |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | تعداد برچسب‌های تیک که بین دو برچسب رسم‌شده باید رد شوند را مشخص می‌کند. برای محورهای دسته‌بندی یا سری اعمال می‌شود. قابل‌خواندن **uint32_t**. |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | تعداد علامت‌های تیک که قبل از رسم علامت بعدی باید رد شوند را مشخص می‌کند. برای محورهای دسته‌بندی یا سری اعمال می‌شود. قابل‌خواندن **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | عنوان محور را دریافت می‌کند. فقط‌خواندنی [IChartTitle](../icharttitle/). |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | مقدار سفارشی سطل زیرریزی را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin برابر false تنظیم شده و IsUnderflowBin برابر true باشد، اعمال می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تولید کپی (کلون) از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌نماید. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr بر پایه مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | نوع تجمیع محور دسته‌بندی (بینی) را نشان می‌دهد. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | نشان می‌دهد آیا محور مقدار، محور دسته‌بندی را بین دسته‌ها قطع می‌کند یا نه. این ویژگی فقط برای محورهای دسته‌بندی اعمال می‌شود و برای نمودارهای ۳-بعدی نیست. قابل‌نوشتن **bool**. |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | کوچک‌ترین واحد زمان نمایش داده شده بر محور تاریخ را مشخص می‌کند. قابل‌نوشتن [TimeUnitType](../timeunittype/). |
| void [set_BinWidth](./set_binwidth/)(**double**) override | عرض سطل را زمانی که مقدار ویژگی AggregationType برابر [AxisAggregationType::ByBinWidth](../axisaggregationtype/) تنظیم شده باشد، مشخص می‌کند. برای محورهای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | نوع محور دسته‌بندی را مشخص می‌کند. قابل‌نوشتن [Charts::CategoryAxisType](../categoryaxistype/). |
| void [set_CrossAt](./set_crossat/)(**float**) override | نقطه‌ای روی محور که محور عمود بر آن تقاطع می‌کند را نشان می‌دهد. قابل‌نوشتن **float**. |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | نوع CrossType روی محور مشخص‌شده که محور دیگر بر آن تقاطع می‌کند را نشان می‌دهد. قابل‌نوشتن [CrossesType](../crossestype/). |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | مقدار اسکالینگ واحدهای نمایش برای محور مقدار را مشخص می‌کند. قابل‌نوشتن [DisplayUnitType](../displayunittype/). |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | تشخیص می‌دهد آیا محور عنوان قابل‌مشاهده دارد یا نه. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | نشان می‌دهد آیا مقدار بیشینه به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | نشان می‌دهد آیا واحد فرعی محور به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | نشان می‌دهد آیا مقدار کمینه به‌صورت خودکار اختصاص داده می‌شود یا نه. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | مقدار سطل سرریز خودکار را مشخص می‌کند. اگر false: از ویژگی OverflowBin استفاده کنید. |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر false: از ویژگی TickLabelSpacing استفاده کنید. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | مقدار فاصله خودکار علامت‌های تیک را مشخص می‌کند. اگر false: از ویژگی TickMarksSpacing استفاده کنید. قابل‌نوشتن **bool**. |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | مقدار سطل زیرریزی خودکار را مشخص می‌کند. اگر false: از ویژگی UnderflowBin استفاده کنید. |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | نشان می‌دهد آیا نوع مقیاس محور مقدار لگاریتمی است یا نه. قابل‌نوشتن **bool**. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | نشان می‌دهد آیا فرمت به داده منبع پیوند خورده است یا نه. قابل‌نوشتن **bool**. |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | مشخص می‌کند آیا سطل سرریز اعمال شده است. برای تنظیم مقدار سطل سرریز از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | نشان می‌دهد آیا PowerPoint داده‌ها را از آخر به ابتدا رسم می‌کند. قابل‌نوشتن **bool**. |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | مشخص می‌کند آیا سطل زیرریزی اعمال شده است. برای تنظیم مقدار سطل زیرریزی از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | نشان می‌دهد آیا محور قابل مشاهده است. قابل‌نوشتن **bool**. |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محورهای دسته‌بندی یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. قابل‌نوشتن **uint16_t**. |
| void [set_LogBase](./set_logbase/)(**double**) override | پایه لگاریتمی را نشان می‌دهد. مقدار پیش‌فرض ۱۰ است. قابل‌نوشتن **double**. |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | نوع علامت تیک اصلی برای محور مشخص‌شده را نشان می‌دهد. قابل‌نوشتن [TickMarkType](../tickmarktype/). |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | واحدهای اصلی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل‌نوشتن **double**. |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل‌نوشتن [TimeUnitType](../timeunittype/). |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | حداکثر مقدار بر روی محور مقدار را نشان می‌دهد. قابل‌نوشتن **double**. |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | نوع علامت تیک فرعی برای محور مشخص‌شده را نشان می‌دهد. قابل‌نوشتن [TickMarkType](../tickmarktype/). |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | واحدهای فرعی برای محور تاریخ یا مقدار را نشان می‌دهد. قابل‌نوشتن **double**. |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | مقیاس واحد اصلی برای محور تاریخ را نشان می‌دهد. قابل‌نوشتن [TimeUnitType](../timeunittype/). |
| void [set_MinValue](./set_minvalue/)(**double**) override | حداقل مقدار بر روی محور مقدار را نشان می‌دهد. قابل‌نوشتن **double**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | رشته قالب برای برچسب‌های [Axis](./) را نشان می‌دهد. قابل‌نوشتن [System::String](../../system/string/). |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | تعداد سطل‌ها را هنگامی که مقدار ویژگی AggregationType برابر [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) باشد، مشخص می‌کند. برای محورهای دسته‌بندی اعمال می‌شود. فقط با سری‌های هیستوگرام یا هیستوگرام‌پارتو استفاده می‌شود. |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | مقدار سفارشی سطل سرریز را مشخص می‌کند. زمانی که ویژگی IsAutomaticOverflowBin برابر false تنظیم شده و IsOverflowBin برابر true باشد، اعمال می‌شود. |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | موقعیت محور را نشان می‌دهد. قابل‌نوشتن [AxisPositionType](../axispositiontype/). |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | موقعیت برچسب‌های علامت‌تیک روی محور مشخص‌شده را نشان می‌دهد. قابل‌نوشتن [TickLabelPositionType](../ticklabelpositiontype/). |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | زاویه چرخش برچسب‌های تیک را نشان می‌دهد. قابل‌نوشتن **float**. |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | تعداد برچسب‌های تیک که بین دو برچسب رسم‌شده باید رد شوند را مشخص می‌کند. برای محورهای دسته‌بندی یا سری اعمال می‌شود. قابل‌نوشتن **uint32_t**. |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | تعداد علامت‌های تیک که قبل از رسم علامت بعدی باید رد شوند را مشخص می‌کند. برای محورهای دسته‌بندی یا سری اعمال می‌شود. قابل‌نوشتن **uint16_t**. |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | مقدار سفارشی سطل زیرریزی را مشخص می‌کند. زمانی که ویژگی IsAutomaticUnderflowBin برابر false تنظیم شده و IsUnderflowBin برابر true باشد، اعمال می‌شود. |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | ویژگی IAxis::get(set)_CategoryAxisType را با مقداری که به‌صورت خودکار بر پایه داده‌های محور تعیین می‌شود، تنظیم می‌کند. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری باز کردن با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [IAxis](../iaxis/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)