---
title: RenderingOptions
second_title: مرجع API Aspose.Slides برای C++
description: گزینه‌هایی را فراهم می‌کند که نحوهٔ رندر ارائه/اسلاید را کنترل می‌کند.
type: docs
weight: 638
url: /fa/aspose.slides.export/renderingoptions/
---
## کلاس RenderingOptions

گزینه‌هایی را فراهم می‌کند که نحوهٔ رندر کردن ارائه/اسلاید را کنترل می‌کند.

```cpp
class RenderingOptions : public Aspose::Slides::Export::SaveOptions,
                         public Aspose::Slides::Export::IRenderingOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | فونت مورد استفاده در صورت عدم پیدا شدن فونت منبع را بازمی‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | مقداری را بازمی‌گرداند که نشان می‌دهد متن بدون استفاده از لیگارفی‌ها رندر شود. وقتی به **true** تنظیم شود، لیگارفی‌ها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی به **false** تنظیم شده است. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | سبک بصری گرادیانت را بازمی‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء [Ink](../../aspose.slides.ink/) را در سند صادرشده کنترل می‌کند. [IInkOptions](../iinkoptions/) فقط-خواندنی |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | شیء callbackی را برای ذخیره‌سازی بروز‌رسانی‌های پیشرفت به درصد نمایندگی می‌کند. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فرام hyper با فراخوانی‌های JavaScript حذف شوند یا نه. **bool** را می‌خواند. مقدار پیش‌فرض **false** است. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را بازمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا لغو شود، بازمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را بازمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را بازمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده‌ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
|  [RenderingOptions](./renderingoptions/)() | سازنده پیش‌فرض. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | فونت مورد استفاده در صورت عدم پیدا شدن فونت منبع را تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگارفی‌ها رندر شود یا نه. وقتی به **true** تنظیم شود، لیگارفی‌ها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی به **false** تنظیم شده است. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | سبک بصری گرادیانت را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | شیء callbackی را برای ذخیره‌سازی بروز‌رسانی‌های پیشرفت به درصد نمایندگی می‌کند. به [IProgressCallback](../../aspose.slides/iprogresscallback/) مراجعه کنید. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | مشخص می‌کند آیا هنگام ذخیره‌سازی ارائه، پیوندهای فرام hyper با فراخوانی‌های JavaScript حذف شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادر کردن ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را تنظیم می‌کند. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرایند بارگذاری ادامه یابد یا لغو شود، بازمی‌گرداند یا تنظیم می‌کند. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده‌ مرجع مشترک را بازمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساخت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده‌ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده‌ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |
## توضیحات



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IRenderingOptions> renderingOpts = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
renderingOpts->set_SlidesLayoutOptions(slidesLayoutOptions);

System::SharedPtr<ISlide> slide = pres->get_Slide(0);

slide->GetImage(renderingOpts)->Save(u"pres-Original.png", ImageFormat::Png);

renderingOpts->set_DefaultRegularFont(u"Arial Black");
slide->GetImage(renderingOpts)->Save(u"pres-ArialBlackDefault.png", ImageFormat::Png);

renderingOpts->set_DefaultRegularFont(u"Arial Narrow");
slide->GetImage(renderingOpts)->Save(u"pres-ArialNarrowDefault.png", ImageFormat::Png);
```




## موارد مرتبط

* کلاس [SaveOptions](../saveoptions/)
* کلاس [IRenderingOptions](../irenderingoptions/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)