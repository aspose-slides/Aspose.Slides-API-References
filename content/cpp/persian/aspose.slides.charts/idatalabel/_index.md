---
title: IDataLabel
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر برچسب‌های یک سری است.
type: docs
weight: 937
url: /fa/aspose.slides.charts/idatalabel/
---
## کلاس IDataLabel

نمایانگر برچسب‌های یک سری است.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | TextFrameForOverriding را با متن موجود در پارامتر \"text\" مقداردهی اولیه می‌کند. اگر TextFrameForOverriding قبلاً مقداردهی شده باشد، به سادگی متن آن را تغییر می‌دهد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداریتی، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداریتی، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای منظورهای داخلی. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به‌دست آید. خواندنی **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به‌دست آید. خواندنی **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | موقعیت واقعی x (چپ) عنصر نمودار نسبت به گوشهٔ بالای چپ نمودار را مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به‌دست آید. خواندنی **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | بالای عنصر نمودار را نسبت به گوشهٔ بالای چپ نمودار مشخص می‌کند. قبل از آن متد [IChart::ValidateChartLayout](../ichart/validatechartlayout/) را فراخوانی کنید تا مقادیر واقعی به‌دست آید. خواندنی **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | نمودار را برمی‌گرداند. فقط-خواندنی [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | قالب برچسب داده را برمی‌گرداند. فقط-خواندنی [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ارتفاع عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. خواندنی **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | مقدار False به این معناست که برچسب داده قابل مشاهده نیست (و بنابراین تمام پرچم‌های Show* (ShowValue, ...) نیز False هستند). فقط-خواندنی **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ارائه را برمی‌گرداند. فقط-خواندنی [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | سمت راست عنصر نمودار را به عنوان کسری از عرض نمودار دریافت می‌کند. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | قالب متن نمودار را برمی‌گرداند. فقط-خواندنی [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | می‌تواند متن قالب‌بندی‌شدهٔ غنی را شامل شود. اگر این ویژگی null نباشد، مقدار متن قالب‌بندی‌شده این ویژگی متن تولید خودکار را بازنویسی می‌کند. متن تولید خودکار یک ویژگی ضمنی برچسب داده، برچسب واحد نمایش محور مقدار، عنوان محور، عنوان نمودار، برچسب خط روند است. متن تولید خودکار با ویژگی [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) قالب‌بندی می‌شود. فقط-خواندنی [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | سلول دادهٔ کارنامه را دریافت می‌کند. اگر ویژگی IDataLabelFormat::get(set)_ShowLabelValueFromCell برابر با true باشد اعمال می‌شود. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | عرض عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. خواندنی **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | موقعیت x (چپ) عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. خواندنی **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. خواندنی **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | متن واقعی برچسب را بر اساس تنظیمات [DataLabelFormat](../datalabelformat/) یا مقدار TextFrameForOverriding.Text برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | برچسب داده را با تنظیم تمام پرچم‌های Show* (ShowValue, ...) به وضعیت false مخفی می‌کند. بعد از این IsVisible برابر false خواهد بود. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری توسط عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان ایجاد نسخهٔ کپی از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ارتفاع عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. نوشتنی **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | سلول دادهٔ کارنامه را تنظیم می‌کند. اگر ویژگی IDataLabelFormat::get(set)_ShowLabelValueFromCell برابر با true باشد اعمال می‌شود. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | عرض عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. نوشتنی **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | موقعیت x (چپ) عنصر نمودار را به عنوان کسری از عرض نمودار مشخص می‌کند. نوشتنی **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | بالای عنصر نمودار را به عنوان کسری از ارتفاع نمودار مشخص می‌کند. نوشتنی **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگو n'th را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل توسط عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را حذف می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [ILayoutable](../ilayoutable/)
* کلاس [IOverridableText](../ioverridabletext/)
* کلاس [IActualLayout](../iactuallayout/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)