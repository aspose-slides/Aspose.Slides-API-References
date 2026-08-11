---
title: ChartSeriesGroup
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر گروهی از سری‌ها.
type: docs
weight: 300
url: /fa/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup کلاس

نمایانگر گروهی از سری‌ها است.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. خواندن [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). خواندن **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | سری‌های نمودار موجود در گروه را در ایندکس مشخص‌شده برمی‌گرداند. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). خواندن **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | زاویهٔ اولین برش نمودار دایره‌ای یا دونات را برحسب درجه (ساعتگرد از بالا، از 0 تا 360 درجه) دریافت می‌کند. خواندن **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | فاصله را به صورت درصدی از عرض علامت، بین سری‌های داده در نمودار 3D برمی‌گرداند. خواندن **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | فاصله بین خوشه‌های نوار یا ستون را به صورت درصدی از عرض نوار یا ستون مشخص می‌کند. خواندن **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | در صورتی که نمودار خطوط سری داشته باشد، true است. برای نمودارهای نوار انبوه و OfPie اعمال می‌شود. خواندن **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | قالب HiLowLines را مشخص می‌کند. HiLowLines همراه با انواع نمودار HiLowClose، OpenHiLowClose، VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | مشخص می‌کند که هر علامت داده در سری رنگ متفاوتی دارد. خواندن **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو-بعدی را به صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | نحوه تعیین اینکه کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند را مشخص می‌کند. خواندن [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. نقطهٔ داده‌ای را که باید بر حسب ایندکس در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie رسم شود، برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie رسم شوند. فقط-خواندنی [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند، استفاده می‌شود. همراه با ویژگی PieSplitBy به کار می‌رود. خواندن **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | نشان می‌دهد که آیا سری‌های این گروه بر محور ثانویه رسم می‌شوند. فقط-خواندنی **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | اندازهٔ دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie را به صورت درصدی از اندازهٔ دایرهٔ اول (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. خواندن **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | مجموعه‌ای از سری‌ها را برمی‌گرداند. فقط-خواندنی [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | نوع این گروه سری را برمی‌گرداند. فقط-خواندنی [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | دسترسی به نوارهای بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. فقط-خواندنی [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | عنصر در ایندکس مشخص‌شده را دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ‌ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌وسیلهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | نحوه نمایش مقادیر اندازه حباب در نمودار حبابی را مشخص می‌کند. بنویسید [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | عامل مقیاس برای نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازه پیش‌فرض باشد). بنویسید **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 0 تا 90 درصد از اندازهٔ ناحیهٔ نمودار باشد). بنویسید **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | زاویهٔ اولین برش نمودار دایره‌ای یا دونات را برحسب درجه (ساعتگرد از بالا، از 0 تا 360 درجه) تنظیم می‌کند. بنویسید **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | فاصله را به عنوان درصدی از عرض علامت، بین سری‌های داده در نمودار 3D تنظیم می‌کند. بنویسید **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | فضای بین خوشه‌های نوار یا ستون را به عنوان درصدی از عرض نوار یا ستون تنظیم می‌کند. بنویسید **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | در صورتی که نمودار خطوط سری داشته باشد، true است. برای نمودارهای نوار انبوه و OfPie اعمال می‌شود. بنویسید **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | مشخص می‌کند که هر علامت داده در سری رنگ متفاوتی دارد. بنویسید **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | مقدار همپوشانی نوارها و ستون‌ها در نمودارهای دو-بعدی را به صورت درصد (از -100٪ تا 100٪) مشخص می‌کند. |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | نحوه تعیین اینکه کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند را مشخص می‌کند. بنویسید [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | مقداری را مشخص می‌کند که برای تعیین اینکه کدام نقاط داده در دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند، استفاده می‌شود. همراه با ویژگی PieSplitBy به کار می‌رود. بنویسید **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | اندازهٔ دایره یا نوار دوم در نمودار pie-of-pie یا bar-of-pie را به صورت درصدی از اندازهٔ دایرهٔ اول (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. بنویسید **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## توضیحات

1) خلاصه و توضیحات برای کلاس ChartSeriesGroupCollection و شمارنده CombinableSeriesTypesGroup را ببینید. 2) گروهی از سری‌ها شامل برخی ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). "Series group properties" در [ChartSeriesGroup](./) کلاس قابلیت خواندن/نوشتن دارد. هر کدام از "series group properties" می‌توانند یک نمایش فقط-خواندنی در [ChartSeries](../chartseries/) کلاس داشته باشند. 

## موارد مرتبط

* کلاس [IChartSeriesGroup](../ichartseriesgroup/)
* کلاس [IDOMObject](../../aspose.slides/idomobject/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)