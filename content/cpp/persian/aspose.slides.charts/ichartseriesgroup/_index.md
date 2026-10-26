---
title: IChartSeriesGroup
second_title: Aspose.Slides برای C++ مرجع API
description: نمایشگر گروهی از سری‌ها.
type: docs
weight: 846
url: /fa/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup کلاس

نمایشگر گروهی از سری‌ها.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | نحوهٔ نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را مشخص می‌کند. خواندن [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | عامل مقیاس نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). خواندن **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را باز می‌گرداند. فقط‌خواندنی [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | سری‌های نمودار را در گروه در ایندکس مشخص شده باز می‌گرداند. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). خواندن **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | زاویهٔ اولین برش کیک یا دونات نمودار را به درجه دریافت می‌کند (به جهت ساعتگرد از بالا، از 0 تا 360 درجه). خواندن **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | فاصله را به عنوان درصدی از عرض نشانگر بین سری‌های داده در نمودار 3D باز می‌گرداند. خواندن **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون تعیین می‌کند. خواندن **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | درست اگر نمودار خطوط سری داشته باشد. برای میلهٔ انباشته و OfPie اعمال می‌شود. خواندن **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | قالب HiLowLines را مشخص می‌کند. HiLowLines با انواع نمودار HiLowClose, OpenHiLowClose, VolumeHiLowClose و VolumeOpenHiLowClose اعمال می‌شود. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. خواندن **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو‌بعدی تا چه اندازه (به درصد، از -100% تا 100%) همپوشانی داشته باشند. |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | نحوهٔ تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند را مشخص می‌کند. خواندن [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. نقطه داده‌ای را که باید در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie بر اساس ایندکس رسم شود باز می‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | اطلاعات تقسیم سفارشی برای نمودار pie-of-pie یا bar-of-pie با تقسیم سفارشی. شامل نقاط داده‌ای است که باید در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie رسم شوند. فقط‌خواندنی [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | مقداری را که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. خواندن **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | نشان می‌دهد آیا سری‌های این گروه بر محور ثانویه رسم می‌شوند. فقط‌خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را باز می‌گرداند. فقط‌خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | اندازهٔ کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ کیک اول (می‌تواند بین 5 تا 200 درصد باشد) مشخص می‌کند. خواندن **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | یک مجموعهٔ فقط‌خواندنی از سری‌های نمودار را باز می‌گرداند. فقط‌خواندنی [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را باز می‌گرداند. فقط‌خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | نوع این گروه سری‌ها را باز می‌گرداند. فقط‌خواندنی [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | دسترسی به میله‌های بالا/پایین نمودار خطی یا سهام را فراهم می‌کند. فقط‌خواندنی [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | عنصر در ایندکس مشخص شده را دریافت می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوعی که توسط targetType توصیف شده است را نشان می‌دهد. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌بندی با دستور C# lock() را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به صورت مرجعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به صورت مرجعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | نحوهٔ نمایش مقادیر اندازهٔ حباب‌ها در نمودار حبابی را مشخص می‌کند. بنویسید [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | عامل مقیاس نمودار حبابی را مشخص می‌کند (می‌تواند بین 0 تا 300 درصد از اندازهٔ پیش‌فرض باشد). بنویسید **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | اندازهٔ سوراخ در نمودار دونات را مشخص می‌کند (می‌تواند بین 10 تا 90 درصد از اندازهٔ ناحیهٔ رسم باشد). بنویسید **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | زاویهٔ اولین قطعهٔ کیک یا دونات نمودار را به درجه تنظیم می‌کند (به جهت ساعتگرد از بالا، از 0 تا 360 درجه). بنویسید **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | فاصلهٔ بین سری‌های داده در نمودار 3D را به عنوان درصدی از عرض نشانگر تنظیم می‌کند. بنویسید **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | فضای بین خوشه‌های میله یا ستون را به عنوان درصدی از عرض میله یا ستون تنظیم می‌کند. بنویسید **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | درست اگر نمودار خطوط سری داشته باشد. برای میله‌های انباشته و نمودارهای OfPie اعمال می‌شود. بنویسید **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | مشخص می‌کند که هر نشانگر داده در سری رنگ متفاوتی داشته باشد. بنویسید **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | مشخص می‌کند که میله‌ها و ستون‌ها در نمودارهای دو‌بعدی تا چه اندازه (به درصد، از -100% تا 100%) همپوشانی داشته باشند. |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | نحوهٔ تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند را مشخص می‌کند. بنویسید [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | مقداری را که برای تعیین اینکه کدام نقاط داده در کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie قرار دارند استفاده می‌شود، مشخص می‌کند. همراه با ویژگی PieSplitBy استفاده می‌شود. بنویسید **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | اندازهٔ کیک یا میله دوم در نمودار pie-of-pie یا bar-of-pie را به عنوان درصدی از اندازهٔ کیک اول (می‌تواند بین 5 تا 200 درصد باشد) تنظیم می‌کند. بنویسید **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | تعداد مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساخت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی دستور C# lock() را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

1) به خلاصه و توضیحاتی برای کلاس ChartSeriesGroupCollection و enum CombinableSeriesTypesGroup مراجعه کنید. 2) گروهی از سری‌ها شامل برخی از ویژگی‌های سری است که برای هر سری در گروه مشترک است ("series group properties"). "Series group properties" در کلاس [ChartSeriesGroup](../chartseriesgroup/) خواند/نوشتنی است. هر یک از "series group properties" می‌تواند یک نمای فقط‌خواندنی در کلاس [ChartSeries](../chartseries/) داشته باشد.

## موارد مرتبط

* کلاس [IChartComponent](../ichartcomponent/)
* فضانام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)