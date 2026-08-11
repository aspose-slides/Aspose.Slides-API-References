---
title: IChartDataPoint
second_title: Aspose.Slides برای C++ مرجع API
description: نقطه دادهٔ سری را نمایندگی می‌کند.
type: docs
weight: 677
url: /fa/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint کلاس

نقطه دادهٔ سری را نمایندگی می‌کند.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، شامل NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور دو برابر (double) به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN برابر هیچ مقداری نیست، شامل NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواند **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواند **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | موقعیت x واقعی (چپ) عنصر نمودار نسبت به گوشه چپ بالای نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواند **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | موقعیت عمودی (بالا) واقعی عنصر نمودار نسبت به گوشه چپ بالای نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید. خواند **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | اندازه حباب نقطه دادهٔ نمودار را باز می‌گرداند. فقط-خواندنی [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | مقدار رنگ نقطه دادهٔ نمودار را باز می‌گرداند. در نمودارهای نقشه استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | سطح نقطه داده‌ای در ایندکس مشخص را باز می‌گرداند. برای سری‌های Treeamp و Sunburst به کار می‌رود. ایندکس‌گذاری سطوح نقطه داده به صورت صفر-مبنا است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | مجموعه‌ای از سطوح نقطه داده را باز می‌گرداند. برای سری‌های Treeamp و Sunburst به کار می‌رود. ایندکس‌گذاری سطوح نقطه داده به صورت صفر-مبنا است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | مقدار نوارهای خطای سری را در صورت نوع مقدار سفارشی نمایش می‌دهد. فقط-خواندنی [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | مقداری که نقطه داده باید از مرکز پای چرخیده شود را مشخص می‌کند. خواند **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | ویژگی‌های قالب‌بندی را نمایش می‌دهد. خواند [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | مشخص می‌کند که این نقطه داده به کدام مجموعهٔ فرزندان والد تعلق دارد. خواند **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | در صورتی که مقدار منفی باشد، رنگ‌های نقطه داده معکوس می‌شوند. خواند **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. خواند **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | برچسب نقطه دادهٔ نمودار را نمایش می‌دهد. فقط-خواندنی [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | یک نشانگر داده را مشخص می‌کند. فقط-خواندنی [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | ویژگی‌های ورودی مربوط به راهنمای نمودار برای نوع نموداری از این فهرست: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). فقط-خواندنی [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | نقطه داده را به‌عنوان کل تنظیم می‌کند. فقط برای نوع سری Waterfall به کار می‌رود. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | مقدار اندازهٔ نقطه دادهٔ نمودار را باز می‌گرداند. در نمودارهای Treemap و Sunburst استفاده می‌شود. فقط-خواندنی [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | مقدار نقطه دادهٔ نمودار را باز می‌گرداند. فقط-خواندنی [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | مقدار x نقطه دادهٔ نمودار را باز می‌گرداند. فقط-خواندنی [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | مقدار y نقطه دادهٔ نمودار را باز می‌گرداند. فقط-خواندنی [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | رنگ خودکاری نقطه داده را بر پایهٔ ایندکس سری، ایندکس نقطه داده، خاصیت ParentSeriesGroup.IsColorVaried و سبک نمودار باز می‌گرداند. این رنگ به‌طور پیش‌فرض استفاده می‌شود اگر FillType برابر NotDefined باشد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را می‌دهد. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| virtual void [Remove](./remove/)() | نقطه داده را از سری نمودار حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | مقداری که نقطه داده باید از مرکز پای جابه‌جا شود را مشخص می‌کند. نوشتن **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | ویژگی‌های قالب‌بندی را نمایش می‌دهد. نوشتن [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | اگر مقدار منفی باشد، رنگ‌های نقطه داده معکوس می‌شوند. نوشتن **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | مشخص می‌کند که حباب‌ها اثر سه‌بعدی دارند. نوشتن **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | نقطه داده را به‌عنوان کل تنظیم می‌کند. فقط برای نوع سری Waterfall به کار می‌رود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به‌عنوان اشاره‌گر ضعیف (به‌جای Shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بازکردن قفل بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## See Also

* کلاس [IActualLayout](../iactuallayout/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)