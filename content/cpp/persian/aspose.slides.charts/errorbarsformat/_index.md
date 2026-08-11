---
title: ErrorBarsFormat
second_title: Aspose.Slides برای C++ مرجع API
description: "نوارهای خطا را برای سری‌های نمودار نمایندگی می‌کند. مقادیر سفارشی ErrorBars در IChartDataPointCollection (در ویژگی IChartDataPoint::get_ErrorBarsCustomValues() ) قرار دارند."
type: docs
weight: 482
url: /fa/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat کلاس

نمودار خطاهای سری نمودار را نمایندگی می‌کند. مقادیر سفارشی ErrorBars در [IChartDataPointCollection](../ichartdatapointcollection/) (در ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)) قرار دارند.

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را بازمی‌گرداند. فقط خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | قالب نوارهای خطا را نمایندگی می‌کند. فقط خواندنی [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | مشخص می‌کند که انتهای سر روی نوارهای خطا ترسیم نشود. فقط خواندنی **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | قابلیت نمایش نوارهای خطا را دریافت می‌کند. فقط خواندنی **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | نوع نوارهای خطا را دریافت می‌کند. فقط خواندنی [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | مقداری را دریافت می‌کند که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برمی‌گرداند. فقط خواندنی **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | روش‌های ممکن برای تعیین طول نوارهای خطا را نمایندگی می‌کند. در صورتی که نوع مقدار سفارشی باشد برای تعیین مقدار از ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) نقطه داده خاص در مجموعه DataPoints از سری استفاده کنید. در صورتی که نوع مقدار Fixed، Percentage یا StandardDeviation باشد از ویژگی Value برای تعیین مقدار استفاده کنید.\n\n فقط خواندنی [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. نظیر فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. نظیر عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی زیربرده‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی می‌کند و امکان ساخت کپی زیربرده‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr مقایسه مرجع می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | قالب نوارهای خطا را نمایندگی می‌کند. قابل نوشتن [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | مشخص می‌کند که انتهای سر روی نوارهای خطا ترسیم نشود. قابل نوشتن **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | قابلیت نمایش نوارهای خطا را تنظیم می‌کند. قابل نوشتن **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | نوع نوارهای خطا را تنظیم می‌کند. قابل نوشتن [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | مقداری را تنظیم می‌کند که با انواع مقدار Fixed، Percentage و StandardDeviation برای تعیین طول نوارهای خطا استفاده می‌شود. در سایر موارد NaN برمی‌گرداند. قابل نوشتن **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | روش‌های ممکن برای تعیین طول نوارهای خطا را نمایندگی می‌کند. در صورتی که نوع مقدار سفارشی باشد برای تعیین مقدار از ویژگی [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) نقطه داده خاص در مجموعه DataPoints از سری استفاده کنید. در صورتی که نوع مقدار Fixed، Percentage یا StandardDeviation باشد از ویژگی Value برای تعیین مقدار استفاده کنید.\n\n قابل نوشتن [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظیر متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با بیان lock() در C# را آزاد می‌کند. مستقیماً صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## همچنین ببینید

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [IErrorBarsFormat](../ierrorbarsformat/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)