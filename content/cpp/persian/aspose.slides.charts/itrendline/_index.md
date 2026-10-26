---
title: ITrendline
second_title: مرجع API Aspose.Slides برای C++
description: کلاس نمایانگر خط روند سری نمودار
type: docs
weight: 1223
url: /fa/aspose.slides.charts/itrendline/
---
## ITrendline کلاس

Class represents trend line of chart series

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## متدها

| Method | توضیحات |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | متن‌فریم برای بازنویسی را با متن پارامتر "text" مقداردهی می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی شده باشد، به سادگی متن آن را تغییر می‌دهد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **double** [get_Backward](./get_backward/)() | تعداد دسته‌ها (یا واحدها در یک نمودار پراکندگی) را که خط روند قبل از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را باز می‌گرداند. فقط خواندنی [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | مشخص می‌کند که معادلهٔ خط روند بر روی نمودار (در همان برچسبی که مقدار Rsquaredvalue در آن قرار دارد) نمایش داده شود. خواندنی **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار (در همان برچسبی که معادله در آن قرار دارد) نمایش داده شود. خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | قالب خط روند را نشان می‌دهد. خواندنی [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | تعداد دسته‌ها (یا واحدها در یک نمودار پراکندگی) را که خط روند پس از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. خواندنی **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | مقدار نقطه‌ای که خط روند باید محور y را قطع کند را مشخص می‌کند. این ویژگی فقط زمانی پشتیبان است که نوع خط روند exp، linear یا poly باشد. خواندنی **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | ترتیب خط روند چندجمله‌ای را مشخص می‌کند. برای انواع دیگر خط روند نادیده گرفته می‌شود. مقدار باید بین 2 و 6 باشد. خواندنی **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | دورهٔ خط روند برای خط روند متوسط متحرک را مشخص می‌کند. برای انواع دیگر نادیده گرفته می‌شود. مقدار باید بین 2 و 255 باشد. خواندنی **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را باز می‌گرداند. فقط خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | ورودی افسانهٔ مرتبط با این خط روند را نشان می‌دهد. فقط خواندنی [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را باز می‌گرداند. فقط خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را باز می‌گرداند. فقط خواندنی [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | می‌تواند شامل متنی با قالب‌بندی غنی باشد. اگر این ویژگی مقدار null نداشته باشد، مقدار متن قالب‌بندی‌شده آن، متن خودکار تولید‌شده را بازنویسی می‌کند. متن خودکار تولید‌شده یک ویژگی ضمنی برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار، برچسب خط روند است. متن خودکار تولید‌شده با ویژگی [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) قالب‌بندی می‌شود. فقط خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | نام خط روند را دریافت می‌کند. خواندنی [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | نوع خط روند را دریافت می‌کند. خواندنی [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌دار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Backward](./set_backward/)(**double**) | تعداد دسته‌ها (یا واحدها در یک نمودار پراکندگی) را که خط روند قبل از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. نوشتن **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | مشخص می‌کند که معادلهٔ خط روند بر روی نمودار (در همان برچسبی که مقدار Rsquaredvalue در آن قرار دارد) نمایش داده شود. نوشتن **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | مشخص می‌کند که مقدار R-squared خط روند بر روی نمودار (در همان برچسبی که معادله در آن قرار دارد) نمایش داده شود. نوشتن **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | قالب خط روند را نشان می‌دهد. نوشتن [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | تعداد دسته‌ها (یا واحدها در یک نمودار پراکندگی) را که خط روند پس از داده‌های سری مورد روند گسترش می‌یابد، مشخص می‌کند. در نمودارهای پراکندگی و غیرپراکندگی، مقدار می‌تواند هر مقدار غیرمنفی باشد. نوشتن **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | مقدار نقطه‌ای که خط روند باید محور y را قطع کند را مشخص می‌کند. این ویژگی فقط زمانی پشتیبان است که نوع خط روند exp، linear یا poly باشد. نوشتن **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | ترتیب خط روند چندجمله‌ای را مشخص می‌کند. برای انواع دیگر نادیده گرفته می‌شود. مقدار باید بین 2 و 6 باشد. نوشتن **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | دورهٔ خط روند برای خط روند متوسط متحرک را مشخص می‌کند. برای انواع دیگر نادیده گرفته می‌شود. مقدار باید بین 2 و 255 باشد. نوشتن **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | نام خط روند را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | نوع خط روند را تنظیم می‌کند. نوشتن [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [IOverridableText](../ioverridabletext/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)