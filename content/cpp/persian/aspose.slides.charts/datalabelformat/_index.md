---
title: DataLabelFormat
second_title: Aspose.Slides برای C++ مرجع API
description: گزینه‌های قالب‌بندی برای DataLabel را نمایش می‌دهد.
type: docs
weight: 391
url: /fa/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat کلاس

گزینه‌های قالب‌بندی برای [DataLabel](../datalabel/) را نشان می‌دهد.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه با شیء مشخص‌شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسه اشیا با استفاده از معنای C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسه اشیاء نوع مرجع به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقاط شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار را برمی‌گرداند. فقط‌خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | قالب برچسب داده را نشان می‌دهد. فقط‌خواندنی [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | خواند **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | رشته قالب برای شی DataLabels را نشان می‌دهد. خواند [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | شی Parent_Immediate را برمی‌گرداند. فقط‌خواندنی [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) را برمی‌گرداند. فقط‌خواندنی [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | موقعیت برچسب داده را نشان می‌دهد. خواند [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | یک Variant که جداساز مورد استفاده برای برچسب‌های داده روی نمودار را نشان می‌دهد تنظیم یا برمی‌گرداند. خواند [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص را نشان می‌دهد. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص. True برای نمایش نام دسته‌بندی برچسب‌های داده روی نمودار. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | تعیین می‌کند که برچسب داده یک نمودار مشخص به‌صورت فراخوان داده یا به‌صورت برچسب داده نمایش داده شود. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص. True مقدار سلول را نمایش می‌دهد. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | رفتار نمایش خطوط راهنما برچسب داده یک نمودار مشخص. True خطوط راهنما را نمایش می‌دهد. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. خواند **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | برگرداندن Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده روی یک نمودار. True برای نمایش نام سری. False برای مخفی‌سازی. خواند **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌سازی. خواند **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن نمودار را برمی‌گرداند. فقط‌خواندنی [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دسترسی به ساختار داده شمارنده مرجع مرتبط با شیء را به دست می‌آورد. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را به دست می‌آورد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | ممیز قفل (lock()) در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | نوشتن **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | رشته قالب برای شی DataLabels را نشان می‌دهد. نوشتن [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | موقعیت برچسب داده را نشان می‌دهد. نوشتن [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | یک Variant که جداساز مورد استفاده برای برچسب‌های داده روی نمودار را نشان می‌دهد تنظیم یا برمی‌گرداند. نوشتن [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | رفتار نمایش مقدار اندازه حباب برچسب داده یک نمودار مشخص. True مقدار اندازه حباب را نمایش می‌دهد. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | رفتار نمایش نام دسته‌بندی برچسب داده یک نمودار مشخص. True برای نمایش نام دسته‌بندی برچسب‌های داده روی نمودار. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | تعیین می‌کند که برچسب داده یک نمودار مشخص به‌صورت فراخوان داده یا به‌صورت برچسب داده نمایش داده شود. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | رفتار نمایش مقدار سلول برچسب داده یک نمودار مشخص. True مقدار سلول را نمایش می‌دهد. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | رفتار نمایش خطوط راهنما برچسب داده یک نمودار مشخص. True خطوط راهنما را نمایش می‌دهد. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | رفتار نمایش کلید افسانه برچسب داده یک نمودار مشخص. True اگر کلید افسانه برچسب داده قابل مشاهده باشد. نوشتن **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | تنظیم Boolean برای نشان دادن رفتار نمایش نام سری برای برچسب‌های داده روی یک نمودار. True برای نمایش نام سری. False برای مخفی‌سازی. نوشتن **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | رفتار نمایش مقدار درصد برچسب داده یک نمودار مشخص. True مقدار درصد را نمایش می‌دهد. False برای مخفی‌سازی. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را به دست می‌آورد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل (lock()) در C#. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [PVIObject](../../aspose.slides/pviobject/)
* کلاس [IDataLabelFormat](../idatalabelformat/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)