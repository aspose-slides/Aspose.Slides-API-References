---
title: Trendline
second_title: Aspose.Slides برای C++ مرجع API
description: کلاس نمایانگر خط روند سری نمودار است
type: docs
weight: 1366
url: /fa/aspose.slides.charts/trendline/
---
## Trendline کلاس

کلاس نمایانگر خط روند سری نمودار است

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | TextFrameForOverriding را با متن موجود در پارامتر \"text\" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی اولیه شده باشد، به سادگی متن آن را تغییر می‌دهد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه عدد دو برابر (double) به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای کاربردهای داخلی. |
| **double** [get_Backward](./get_backward/)() override | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) را که خط روند قبل از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار باید هر مقدار غیرمنفی باشد. فقط-خواندنی **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را برمی‌گرداند. فقط-خواندنی [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | مشخص می‌کند که معادله خط روند روی نمودار نمایش داده شود (در همان برچسب که مقدار Rsquaredvalue قرار دارد). فقط-خواندنی **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | مشخص می‌کند که مقدار R-مربع خط روند روی نمودار نمایش داده شود (در همان برچسب که معادله قرار دارد). فقط-خواندنی **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | قالب خط روند را نشان می‌دهد. فقط-خواندنی [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) را که خط روند پس از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار باید هر مقدار غیرمنفی باشد. فقط-خواندنی **double**. |
| **double** [get_Intercept](./get_intercept/)() override | مقداری را که خط روند محور y را قطع می‌کند، مشخص می‌کند. این ویژگی فقط زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. فقط-خواندنی **double**. |
| **uint8_t** [get_Order](./get_order/)() override | مرتبهٔ خط روند چندجمله‌ای را مشخص می‌کند. برای انواع دیگر خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. فقط-خواندنی **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | دورهٔ خط روند برای خط روند متوسط متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. فقط-خواندنی **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | ورودی افسانه مربوط به این خط روند را نشان می‌دهد. فقط-خواندنی [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | می‌تواند شامل متن غنی قالب‌بندی شده باشد. اگر این ویژگی null نباشد، این مقدار متن قالب‌بندی شده متن تولید خودکار برچسب داده را جایگزین می‌کند. متن تولید خودکار برچسب داده به متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | نام خط روند را دریافت می‌کند. خواندنی [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | نوع خط روند را دریافت می‌کند. خواندنی [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، تنها شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Backward](./set_backward/)(**double**) override | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) را که خط روند قبل از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار باید هر مقدار غیرمنفی باشد. نوشتن **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | مشخص می‌کند که معادله خط روند روی نمودار نمایش داده شود (در همان برچسب مقدار Rsquaredvalue). نوشتن **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | مشخص می‌کند که مقدار R-مربع خط روند روی نمودار نمایش داده شود (در همان برچسب معادله). نوشتن **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | قالب خط روند را نشان می‌دهد. نوشتن [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | تعداد دسته‌ها (یا واحدها در نمودار پراکنده) را که خط روند پس از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکنده و غیرپراکنده، مقدار باید هر مقدار غیرمنفی باشد. نوشتن **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | مقداری را که خط روند محور y را قطع می‌کند، مشخص می‌کند. این ویژگی فقط زمانی پشتیبانی می‌شود که نوع خط روند exp، linear یا poly باشد. نوشتن **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | مرتبهٔ خط روند چندجمله‌ای را مشخص می‌کند. برای انواع دیگر خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۶ باشد. نوشتن **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | دورهٔ خط روند برای خط روند متوسط متحرک را مشخص می‌کند. برای سایر انواع خط روند نادیده گرفته می‌شود. مقدار باید بین ۲ تا ۲۵۵ باشد. نوشتن **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | نام خط روند را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | نوع خط روند را تنظیم می‌کند. نوشتن [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C# است. تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با بیان lock() در C# را باز می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [DomObject](../../aspose.slides/domobject/)
* کلاس [ITrendline](../itrendline/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)