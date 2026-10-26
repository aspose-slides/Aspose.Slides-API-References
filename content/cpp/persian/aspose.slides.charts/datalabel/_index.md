---
title: DataLabel
second_title: مرجع API Aspose.Slides برای C++
description: برچسب‌های یک سری را نشان می‌دهد.
type: docs
weight: 365
url: /fa/aspose.slides.charts/datalabel/
---
## DataLabel کلاس

Represents a series labels.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | متن TextFrameForOverriding را با متن پارامتر \"text\" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی اولیه شده باشد، به سادگی متن آن را تغییر می‌دهد. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | یک نمونه جدید از کلاس [DataLabel](./) ایجاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقادیر را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از آن باید متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی دریافت شوند. خوانده **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از آن باید متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی دریافت شوند. خوانده **float**. |
| **float** [get_ActualX](./get_actualx/)() override | موقعیت x واقعی (چپ) عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. قبل از آن باید متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی دریافت شوند. خوانده **float**. |
| **float** [get_ActualY](./get_actualy/)() override | موقعیت بالا (top) واقعی عنصر نمودار نسبت به گوشهٔ چپ-بالای نمودار را مشخص می‌کند. قبل از آن باید متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی دریافت شوند. خوانده **float**. |
| **float** [get_Bottom](./get_bottom/)() override | پایین. فقط‌خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را برمی‌گرداند. فقط‌خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | قالب برچسب داده را برمی‌گرداند. فقط‌خواندنی [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند. خوانده **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | مقدار False به این معنی است که برچسب داده قابل مشاهده نیست (و در نتیجه همه پرچم‌های Show* (ShowValue, ...) نیز False هستند). فقط‌خواندنی **bool**. |
| **float** [get_Right](./get_right/)() override | راست. فقط‌خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن را برمی‌گرداند. فقط‌خواندنی [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | می‌تواند شامل متن قالب‌بندی‌شده غنی باشد. اگر این ویژگی null نباشد، مقدار متن قالب‌بندی‌شده آن، متن تولید خودکار برچسب داده را بازنویسی می‌کند. متن تولید خودکار برچسب داده به آن متنی گفته می‌شود که توسط ویژگی‌های ShowSeriesName، ShowValue، ... مدیریت می‌شود و با ویژگی TextFormatManager.TextFormat قالب‌بندی می‌شود. فقط‌خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | سلول داده کتاب کار را دریافت می‌کند. در صورتی اعمال می‌شود که ویژگی IDataLabelFormat::get(set)_ShowLabelValueFromCell برابر true باشد. |
| **float** [get_Width](./get_width/)() override | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند. خوانده **float**. |
| **float** [get_X](./get_x/)() override | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند. خوانده **float**. |
| **float** [get_Y](./get_y/)() override | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند. خوانده **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | متن واقعی برچسب را بر اساس تنظیمات [DataLabelFormat](../datalabelformat/) یا مقدار [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | برچسب داده را با تنظیم تمام پرچم‌های Show* (ShowValue, ...) به وضعیت false مخفی می‌کند. پس از این IsVisible برابر false خواهد بود. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی برای کلاس‌های مشتق‌شده را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Height](./set_height/)(**float**) override | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | سلول داده کتاب کار را تنظیم می‌کند. در صورتی اعمال می‌شود که ویژگی IDataLabelFormat::get(set)_ShowLabelValueFromCell برابر true باشد. |
| void [set_Width](./set_width/)(**float**) override | عرض عنوان را به عنوان کسری از عرض نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_X](./set_x/)(**float**) override | مختصات x عنوان را به عنوان کسری از عرض نمودار تنظیم می‌کند. **float** را بنویسید. |
| void [set_Y](./set_y/)(**float**) override | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار تنظیم می‌کند. **float** را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساخت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان C# lock() را برای باز کردن پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IDataLabel](../idatalabel/)
* کلاس [IDOMObject](../../aspose.slides/idomobject/)
* فضای نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)