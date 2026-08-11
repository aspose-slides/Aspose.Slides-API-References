---
title: ChartTitle
second_title: مرجع API Aspose.Slides برای C++
description: خواص عنوان نمودار را نمایش می‌دهد.
type: docs
weight: 326
url: /fa/aspose.slides.charts/charttitle/
---
## ChartTitle کلاس

خواص عنوان نمودار را نمایش می‌دهد.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | TextFrameForOverriding را با متن پارامتر \"text\" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی اولیه شده باشد، به سادگی متن آن را تغییر می‌دهد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید تا مقادیر واقعی دریافت شوند. قابل خواندن **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید تا مقادیر واقعی دریافت شوند. قابل خواندن **float**. |
| **float** [get_ActualX](./get_actualx/)() override | موقعیت x واقعی (چپ) عنصر نمودار نسبت به گوشه بالایی چپ نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید تا مقادیر واقعی دریافت شوند. قابل خواندن **float**. |
| **float** [get_ActualY](./get_actualy/)() override | بالای واقعی عنصر نمودار نسبت به گوشه بالایی چپ نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را صدا بزنید تا مقادیر واقعی دریافت شوند. قابل خواندن **float**. |
| **float** [get_Bottom](./get_bottom/)() override | پایین. فقط‌خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | نمودار والد را برمی‌گرداند. فقط‌خواندنی [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | قالب‌های پر، خط، اثر یک عنوان را برمی‌گرداند. فقط‌خواندنی [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند. **float** خواندنی. |
| **bool** [get_Overlay](./get_overlay/)() override | مشخص می‌کند آیا عناصر دیگر نمودار اجازه همپوشانی با عنوان را دارند یا نه. **bool** خواندنی. |
| **float** [get_Right](./get_right/)() override | راست. فقط‌خواندنی **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | قالب متن را برمی‌گرداند. فقط‌خواندنی [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | می‌تواند شامل متنی با فرمت غنی باشد. اگر این خصوصیت null نباشد، مقدار متن قالب‌بندی‌شده، متن ایجاد خودکار را بازنویسی می‌کند. متن ایجاد خودکار یک ویژگی ضمنی برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار، برچسب خط روند است. متن ایجاد خودکار با ویژگی [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) قالب‌بندی می‌شود. فقط‌خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | عرض عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند. **float** خواندنی. |
| **float** [get_X](./get_x/)() override | مختصات x عنوان را به عنوان کسری از عرض نمودار برمی‌گرداند. **float** خواندنی. |
| **float** [get_Y](./get_y/)() override | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار برمی‌گرداند. **float** خواندنی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن نسخهٔ کپی برای کلاس‌های فرعی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Height](./set_height/)(**float**) override | ارتفاع عنوان را به عنوان کسری از ارتفاع نمودار تنظیم می‌کند. **float** قابل نوشتن. |
| void [set_Overlay](./set_overlay/)(**bool**) override | مشخص می‌کند آیا عناصر دیگر نمودار اجازه همپوشانی با عنوان را دارند یا نه. **bool** قابل نوشتن. |
| void [set_Width](./set_width/)(**float**) override | عرض عنوان را به عنوان کسری از عرض نمودار تنظیم می‌کند. **float** قابل نوشتن. |
| void [set_X](./set_x/)(**float**) override | مختصات x عنوان را به عنوان کسری از عرض نمودار تنظیم می‌کند. **float** قابل نوشتن. |
| void [set_Y](./set_y/)(**float**) override | مختصات y عنوان را به عنوان کسری از ارتفاع نمودار تنظیم می‌کند. **float** قابل نوشتن. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IChartTitle](../icharttitle/)
* کلاس [IDOMObject](../../aspose.slides/idomobject/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)