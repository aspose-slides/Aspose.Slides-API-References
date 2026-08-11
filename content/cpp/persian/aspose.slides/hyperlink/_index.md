---
title: Hyperlink
second_title: Aspose.Slides برای مرجع API C++
description: نمایانگر یک پیوند.
type: docs
weight: 1236
url: /fa/aspose.slides/hyperlink/
---
## Hyperlink کلاس

نمایانگر یک پیوند.

```cpp
class Hyperlink : public Aspose::Slides::PVIObject,
                  public Aspose::Slides::IHyperlink
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تعیین می‌کند آیا دو نمونه [Hyperlink](./) برابر هستند یا نه. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [HyperlinkActionType](../hyperlinkactiontype/) [get_ActionType](./get_actiontype/)() override | نوع عمل [Hyperlink](./) را برمی‌گرداند. فقط-خواندنی [HyperlinkActionType](../hyperlinkactiontype/). |
| [HyperlinkColorSource](../hyperlinkcolorsource/) [get_ColorSource](./get_colorsource/)() override | منبع رنگ پیوند را نشان می‌دهد - یا سبک‌ها یا قالب‌بندی بخش. خواندنی [HyperlinkColorSource](../hyperlinkcolorsource/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_EndShow](./get_endshow/)() | یک پیوند که نمایش را پایان می‌دهد برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| [System::String](../../system/string/) [get_ExternalUrl](./get_externalurl/)() override | URL خارجی را مشخص می‌کند. فقط-خواندنی [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ExternalUrlOriginal](./get_externalurloriginal/)() override | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون در نظر گرفتن محتوای واقعی بخش. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_FirstSlide](./get_firstslide/)() | یک پیوند به اولین اسلاید ارائه را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| **bool** [get_HighlightClick](./get_highlightclick/)() override | تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود یا نه. خواندنی **bool**. |
| **bool** [get_History](./get_history/)() override | تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. خواندنی **bool**. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastSlide](./get_lastslide/)() | یک پیوند به آخرین اسلاید ارائه را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_LastVievedSlide](./get_lastvievedslide/)() | یک پیوند به آخرین اسلاید مشاهده‌شده را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_Media](./get_media/)() | یک پیوند ویژه "play mediafile" را برمی‌گرداند. در [AudioFrame](../audioframe/) و [VideoFrame](../videoframe/) استفاده می‌شود. فقط-خواندنی [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NextSlide](./get_nextslide/)() | یک پیوند به اسلاید بعدی را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_NoAction](./get_noaction/)() | یک پیوند ویژه "do nothing" را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | پدر [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\> [get_PreviousSlide](./get_previousslide/)() | یک پیوند به اسلاید قبلی را برمی‌گرداند. فقط-خواندنی [Hyperlink](./). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() override | صدای پخش پیوند را نشان می‌دهد. خواندنی [IAudio](../iaudio/). |
| **bool** [get_StopSoundOnClick](./get_stopsoundonclick/)() override | تعیین می‌کند آیا صدا باید هنگام کلیک بر پیوند متوقف شود. خواندنی **bool**. |
| [System::String](../../system/string/) [get_TargetFrame](./get_targetframe/)() override | قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را برمی‌گرداند وقتی که وجود داشته باشد. خواندن/نوشتن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | اگر [Hyperlink](./) به اسلاید خاصی هدف بگیرد این اسلاید را برمی‌گرداند. فقط-خواندنی [ISlide](../islide/). |
| [System::String](../../system/string/) [get_Tooltip](./get_tooltip/)() override | رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. خواندنی [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | به‌عنوان تابع هش برای نوع خاصی عمل می‌کند، مناسب برای استفاده در الگوریتم‌ها و ساختارهای داده‌ای مانند جدول هش. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Hyperlink](./hyperlink/)([System::String](../../system/string/)) | یک نمونه از پیوند ایجاد می‌کند. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | یک نمونه از پیوند که به اسلاید خاصی اشاره می‌کند ایجاد می‌کند. توجه: پیوند ایجاد شده باید به شی‌ای از همان ارائه اختصاص یابد، در غیر این صورت لینک به‌عنوان NoAction ذخیره خواهد شد. |
|  [Hyperlink](./hyperlink/)([System::SharedPtr](../../system/sharedptr/)\<[Hyperlink](./)\>, [System::String](../../system/string/), [System::String](../../system/string/), **bool**, **bool**, **bool**) | یک نمونه از پیوند با استفاده از پیوند دیگری به‌عنوان منبع ایجاد می‌کند و ویژگی‌های ثانوی را بازنویسی می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نماینده نمونه‌ای از نوعی است که توسط targetType توصیف شده. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | عملیات قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شی نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و ساخت کپی از زیرکلاس‌ها را امکان‌پذیر می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی می‌کند و ساخت کپی از زیرکلاس‌ها را امکان‌پذیر می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به میزان مشخص شده کاهش می‌دهد. |
| void [set_ColorSource](./set_colorsource/)([HyperlinkColorSource](../hyperlinkcolorsource/)) override | منبع رنگ پیوند را نشان می‌دهد - یا سبک‌ها یا قالب‌بندی بخش. نوشتنی [HyperlinkColorSource](../hyperlinkcolorsource/). |
| void [set_HighlightClick](./set_highlightclick/)(**bool**) override | تعیین می‌کند آیا پیوند هنگام کلیک برجسته شود یا نه. نوشتنی **bool**. |
| void [set_History](./set_history/)(**bool**) override | تعیین می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. نوشتنی **bool**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | صدای پخش پیوند را نشان می‌دهد. نوشتنی [IAudio](../iaudio/). |
| void [set_StopSoundOnClick](./set_stopsoundonclick/)(**bool**) override | تعیین می‌کند آیا صدا باید هنگام کلیک بر پیوند متوقف شود یا نه. نوشتنی **bool**. |
| void [set_TargetFrame](./set_targetframe/)([System::String](../../system/string/)) override | قاب داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را برمی‌گرداند وقتی که وجود داشته باشد. خواندن/نوشتن [System::String](../../system/string/). |
| void [set_Tooltip](./set_tooltip/)([System::String](../../system/string/)) override | رشته‌ای که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود را برمی‌گرداند. نوشتنی [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت C# typeof([System.Object](../../system/object/)) را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملیات رفع قفل عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شی نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [PVIObject](../pviobject/)
* کلاس [IHyperlink](../ihyperlink/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)