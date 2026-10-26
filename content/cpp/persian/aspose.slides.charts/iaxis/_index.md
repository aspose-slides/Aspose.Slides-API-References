---
title: IAxis
second_title: مرجع API Aspose.Slides برای C++
description: شیئی را محصور می‌کند که نمایانگر محور نمودار است.
type: docs
weight: 534
url: /fa/aspose.slides.charts/iaxis/
---
## IAxis کلاس

شیئی که نمایانگر محور نمودار است را محصور می‌کند.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## روش‌ها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | مقیاس واحد اصلی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | حداکثر مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | واحد جزئی واقعی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | مقیاس واحد جزئی واقعی محور را مشخص می‌کند. [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را بخوانید. |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | حداقل مقدار واقعی روی محور را مشخص می‌کند. برای دریافت مقدار واقعی، پیش از این متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | نوع تجمیع محور دسته (بینه‌بندی) را نمایندگی می‌کند. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته را قطع می‌کند یا خیر. این ویژگی فقط برای محورهای دسته اعمال می‌شود و برای نمودارهای 3-بعدی کاربرد ندارد. **bool** را بخوانید. |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | کوچک‌ترین واحد زمان که روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. [TimeUnitType](../timeunittype/) را بخوانید. |
| virtual **double** [get_BinWidth](./get_binwidth/)() | عرض بین‌که هنگام مقدار [AxisAggregationType::ByBinWidth](../axisaggregationtype/) برای ویژگی AggregationType تنظیم شده باشد را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | نوع محور دسته را مشخص می‌کند. [CategoryAxisType](../categoryaxistype/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را برمی‌گرداند. [IChart](../ichart/) فقط خواندنی است. |
| virtual **float** [get_CrossAt](./get_crossat/)() | نقطه‌ای روی محور که محور عمود آن را قطع می‌کند را نمایندگی می‌کند. **float** را بخوانید. |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | نوع CrossType روی محور مشخص شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. [CrossesType](../crossestype/) را بخوانید. |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. [DisplayUnitType](../displayunittype/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | قالب محور را نمایندگی می‌کند. [IAxisFormat](../iaxisformat/) فقط خواندنی است. |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | تعیین می‌کند آیا یک محور عنوان قابل مشاهده دارد یا خیر. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | نشان می‌دهد آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | نشان می‌دهد آیا واحد جزئی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | نشان می‌دهد آیا حداقل مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | مقدار بین‌پوشش خودکار (overflow) را مشخص می‌کند. اگر نادرست باشد: از ویژگی OverflowBin استفاده کنید. |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر نادرست باشد: از ویژگی TickLabelSpacing استفاده کنید. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | مقدار فاصله خودکار خطوط تیک را مشخص می‌کند. اگر نادرست باشد: از ویژگی TickMarksSpacing استفاده کنید. **bool** را بخوانید. |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | مقدار بین‌پوشش زیر (underflow) خودکار را مشخص می‌کند. اگر نادرست باشد: از ویژگی UnderflowBin استفاده کنید. |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | نشان می‌دهد آیا نوع مقیاس محور مقدار لوجاریتمی است یا نه. **bool** را بخوانید. |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | نشان می‌دهد آیا قالب به داده منبع لینک شده است یا نه. **bool** را بخوانید. |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | مشخص می‌کند آیا بین‌پوشش overflow اعمال شده است یا نه. برای تنظیم مقدار بین‌پوشش overflow از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | نشان می‌دهد آیا MS PowerPoint نقاط داده را از آخر به اول رسم می‌کند یا نه. **bool** را بخوانید. |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | مشخص می‌کند آیا بین‌پوشش underflow اعمال شده است یا نه. برای تنظیم مقدار بین‌پوشش underflow از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | نشان می‌دهد آیا محور قابل مشاهده است یا نه. **bool** را بخوانید. |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. **uint16_t** را بخوانید. |
| virtual **double** [get_LogBase](./get_logbase/)() | پایه لگاریتم را نمایندگی می‌کند. مقدار پیش‌فرض 10 است. **double** را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | قالب خطوط شبکه اصلی روی محور نمودار را نمایندگی می‌کند. [IChartLinesFormat](../ichartlinesformat/) فقط خواندنی است. |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | نوع تیک اصلی برای محور مشخص شده را نمایندگی می‌کند. [TickMarkType](../tickmarktype/) را بخوانید. |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | واحدهای اصلی برای محور تاریخ یا مقدار را نمایندگی می‌کند. **double** را بخوانید. |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند. [TimeUnitType](../timeunittype/) را بخوانید. |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | حداکثر مقدار روی محور مقدار را نمایندگی می‌کند. **double** را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | قالب خطوط شبکه جزئی روی محور نمودار را نمایندگی می‌کند. [IChartLinesFormat](../ichartlinesformat/) فقط خواندنی است. |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | نوع تیک جزئی برای محور مشخص شده را نمایندگی می‌کند. [TickMarkType](../tickmarktype/) را بخوانید. |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | واحدهای جزئی برای محور تاریخ یا مقدار را نمایندگی می‌کند. **double** را بخوانید. |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند. [TimeUnitType](../timeunittype/) را بخوانید. |
| virtual **double** [get_MinValue](./get_minvalue/)() | حداقل مقدار روی محور مقدار را نمایندگی می‌کند. **double** را بخوانید. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | رشته قالب برای برچسب‌های [Axis](../axis/) را نمایندگی می‌کند. [System::String](../../system/string/) را بخوانید. |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | تعداد بین‌ها را هنگام مقدار [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) برای ویژگی AggregationType تنظیم شده باشد مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | مقدار سفارشی بین‌پوشش overflow را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin برابر false و IsOverflowBin برابر true باشد اعمال می‌شود. |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | موقعیت محور را نمایندگی می‌کند. [AxisPositionType](../axispositiontype/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. [IPresentation](../../aspose.slides/ipresentation/) فقط خواندنی است. |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | نشان می‌دهد آیا خطوط شبکه اصلی نشان داده می‌شوند یا نه. **bool** فقط خواندنی است. |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | نشان می‌دهد آیا خطوط شبکه جزئی نشان داده می‌شوند یا نه. **bool** فقط خواندنی است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. [IBaseSlide](../../aspose.slides/ibaseslide/) فقط خواندنی است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را برمی‌گرداند. [IChartTextFormat](../icharttextformat/) فقط خواندنی است. |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | موقعیت برچسب‌های تیک-مارک روی محور مشخص شده را نمایندگی می‌کند. [TickLabelPositionType](../ticklabelpositiontype/) را بخوانید. |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | زاویه چرخش برچسب‌های تیک را نمایندگی می‌کند. **float** را بخوانید. |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | تعداد برچسب‌های تیکی که باید بین دو برچسب رسم‌شده رد شود را مشخص می‌کند. **uint32_t** را بخوانید. |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | تعداد تیک‌هایی که باید پیش از تیک بعدی رد شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. **uint16_t** را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | عنوان محور را دریافت می‌کند. [IChartTitle](../icharttitle/) فقط خواندنی است. |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | مقدار سفارشی بین‌پوشش underflow را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin برابر false و IsUnderflowBin برابر true باشد اعمال می‌شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نشانگر یک نمونه از نوعی است که توسط targetType توصیف شده. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل کردن با بیان C# lock(). به‌صورت مستقیم فراخوانی کنید یا از شئ نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr مقایسه مرجع می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | نوع تجمیع محور دسته (بینه‌بندی) را نمایندگی می‌کند. برای دسته‌بندی اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | نشان می‌دهد آیا محور مقدار بین دسته‌ها محور دسته را قطع می‌کند یا خیر. این ویژگی فقط برای محورهای دسته اعمال می‌شود و برای نمودارهای 3-بعدی کاربرد ندارد. **bool** را بنویسید. |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | کوچک‌ترین واحد زمان که روی محور تاریخ نمایش داده می‌شود را مشخص می‌کند. [TimeUnitType](../timeunittype/) را بنویسید. |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | عرض بین‌که هنگام مقدار [AxisAggregationType::ByBinWidth](../axisaggregationtype/) برای ویژگی AggregationType تنظیم شده باشد را مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | نوع محور دسته را مشخص می‌کند. [CategoryAxisType](../categoryaxistype/) را بنویسید. |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | نقطه‌ای روی محور که محور عمود آن را قطع می‌کند را نمایندگی می‌کند. **float** را بنویسید. |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | نوع CrossType روی محور مشخص شده که محور دیگر آن را قطع می‌کند را نشان می‌دهد. [CrossesType](../crossestype/) را بنویسید. |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | مقدار مقیاس واحدهای نمایش برای محور مقدار را مشخص می‌کند. [DisplayUnitType](../displayunittype/) را بنویسید. |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | تعیین می‌کند آیا یک محور عنوان قابل مشاهده دارد یا خیر. **bool** را بنویسید. |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | نشان می‌دهد آیا واحد اصلی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بنویسید. |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | نشان می‌دهد آیا حداکثر مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بنویسید. |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | نشان می‌دهد آیا واحد جزئی محور به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بنویسید. |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | نشان می‌دهد آیا حداقل مقدار به‌صورت خودکار اختصاص داده می‌شود یا خیر. **bool** را بنویسید. |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | مقدار بین‌پوشش خودکار (overflow) را مشخص می‌کند. اگر نادرست باشد: از ویژگی OverflowBin استفاده کنید. |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | مقدار فاصله خودکار برچسب‌های تیک را مشخص می‌کند. اگر نادرست باشد: از ویژگی TickLabelSpacing استفاده کنید. **bool** را بنویسید. |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | مقدار فاصله خودکار خطوط تیک را مشخص می‌کند. اگر نادرست باشد: از ویژگی TickMarksSpacing استفاده کنید. **bool** را بنویسید. |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | مقدار بین‌پوشش زیر (underflow) خودکار را مشخص می‌کند. اگر نادرست باشد: از ویژگی UnderflowBin استفاده کنید. |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | نشان می‌دهد آیا نوع مقیاس محور مقدار لوجاریتمی است یا نه. **bool** را بنویسید. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | نشان می‌دهد آیا قالب به داده منبع لینک شده است یا نه. **bool** را بنویسید. |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | مشخص می‌کند آیا بین‌پوشش overflow اعمال شده است یا نه. برای تنظیم مقدار بین‌پوشش overflow از IsAutomaticOverflowBin و OverflowBin استفاده کنید. |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | نشان می‌دهد آیا MS PowerPoint نقاط داده را از آخر به اول رسم می‌کند یا نه. **bool** را بنویسید. |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | مشخص می‌کند آیا بین‌پوشش underflow اعمال شده است یا نه. برای تنظیم مقدار بین‌پوشش underflow از IsAutomaticUnderflowBin و UnderflowBin استفاده کنید. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | نشان می‌دهد آیا محور قابل مشاهده است یا نه. **bool** را بنویسید. |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | فاصله برچسب‌ها از محور را مشخص می‌کند. برای محور دسته یا تاریخ اعمال می‌شود. مقدار باید بین 0٪ و 1000٪ باشد. **uint16_t** را بنویسید. |
| virtual void [set_LogBase](./set_logbase/)(**double**) | پایه لگاریتم را نمایندگی می‌کند. مقدار پیش‌فرض 10 است. **double** را بنویسید. |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | نوع تیک اصلی برای محور مشخص شده را نمایندگی می‌کند. [TickMarkType](../tickmarktype/) را بنویسید. |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | واحدهای اصلی برای محور تاریخ یا مقدار را نمایندگی می‌کند. **double** را بنویسید. |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند. [TimeUnitType](../timeunittype/) را بنویسید. |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | حداکثر مقدار روی محور مقدار را نمایندگی می‌کند. **double** را بنویسید. |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | نوع تیک جزئی برای محور مشخص شده را نمایندگی می‌کند. [TickMarkType](../tickmarktype/) را بنویسید. |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | واحدهای جزئی برای محور تاریخ یا مقدار را نمایندگی می‌کند. **double** را بنویسید. |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | مقیاس واحد اصلی برای محور تاریخ را نمایندگی می‌کند. [TimeUnitType](../timeunittype/) را بنویسید. |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | حداقل مقدار روی محور مقدار را نمایندگی می‌کند. **double** را بنویسید. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | رشته قالب برای برچسب‌های [Axis](../axis/) را نمایندگی می‌کند. [System::String](../../system/string/) را بنویسید. |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | تعداد بین‌ها را هنگام مقدار [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) برای ویژگی AggregationType تنظیم شده باشد مشخص می‌کند. برای محورهای دسته اعمال می‌شود. فقط با سری‌های Histogram یا HistogramPareto استفاده می‌شود. |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | مقدار سفارشی بین‌پوشش overflow را مشخص می‌کند. وقتی ویژگی IsAutomaticOverflowBin برابر false و IsOverflowBin برابر true باشد اعمال می‌شود. |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | موقعیت محور را نمایندگی می‌کند. [AxisPositionType](../axispositiontype/) را بنویسید. |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | موقعیت برچسب‌های تیک-مارک روی محور مشخص شده را نمایندگی می‌کند. [TickLabelPositionType](../ticklabelpositiontype/) را بنویسید. |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | زاویه چرخش برچسب‌های تیک را نمایندگی می‌کند. **float** را بنویسید. |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | تعداد برچسب‌های تیکی که باید بین دو برچسب رسم‌شده رد شود را مشخص می‌کند. **uint32_t** را بنویسید. |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | تعداد تیک‌هایی که باید پیش از تیک بعدی رد شوند را مشخص می‌کند. برای محور دسته یا سری اعمال می‌شود. **uint16_t** را بنویسید. |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | مقدار سفارشی بین‌پوشش underflow را مشخص می‌کند. وقتی ویژگی IsAutomaticUnderflowBin برابر false و IsUnderflowBin برابر true باشد اعمال می‌شود. |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | ویژگی IAxis::get(set)_CategoryAxisType را با مقداری که به‌صورت خودکار بر اساس داده‌های محور تعیین می‌شود تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل با بیان C# lock(). به‌صورت مستقیم فراخوانی کنید یا از شئ نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مطالب مرتبط

* کلاس [IFormattedTextContainer](../iformattedtextcontainer/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)