---
title: IHtml5Options
second_title: مرجع API Aspose.Slides برای C++
description: نماینده گزینه‌های صادرات HTML5 است.
type: docs
weight: 170
url: /fa/aspose.slides.export/ihtml5options/
---
## IHtml5Options کلاس

نماینده گزینه‌های صادرات HTML5 است.

```cpp
class IHtml5Options : public virtual Aspose::Slides::Export::ISaveOptions
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AnimateShapes](./get_animateshapes/)() | گزینهٔ انیمیشن اشکال را باز می‌گرداند. خواندن **bool**. |
| virtual **bool** [get_AnimateTransitions](./get_animatetransitions/)() | گزینهٔ انیمیشن انتقال‌ها را باز می‌گرداند. خواندن **bool**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | قلم استفاده‌شده در صورتی که قلم منبع یافت نشود را باز می‌گرداند. [System::String](../../system/string/) را می‌خواند. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر می‌شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی برابر **false** است. |
| virtual **bool** [get_EmbedImages](./get_embedimages/)() | گزینهٔ جاسازی تصاویر را باز می‌گرداند. خواندن **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | سبک بصری گرادیان را باز می‌گرداند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌خواند. |
| virtual [System::String](../../system/string/) [get_OutputPath](./get_outputpath/)() | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. [System::String](../../system/string/) را می‌خواند. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | سطح فشرده‌سازی تصاویر را نمایان می‌کند. [PicturesCompression](../picturescompression/) را می‌خواند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | یک شیء بازخوانی برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. رجوع به [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | مشخص می‌کند آیا لینک‌های ابرمتن با فراخوانی‌های JavaScript هنگام ذخیره‌سازی ارائه‌نامه رد شوند یا نه. خواندن **bool**. مقدار پیش‌فرض **false** است. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را برمی‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | شیئی را برمی‌گرداند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌سازی اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن کپی برای زیرکلاس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع برای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای موارد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کمتر می‌کند. |
| virtual void [set_AnimateShapes](./set_animateshapes/)(**bool**) | گزینهٔ انیمیشن اشکال را تنظیم می‌کند. نوشتن **bool**. |
| virtual void [set_AnimateTransitions](./set_animatetransitions/)(**bool**) | گزینهٔ انیمیشن انتقال‌ها را تنظیم می‌کند. نوشتن **bool**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | قلم استفاده‌شده در صورتی که قلم منبع یافت نشود را تنظیم می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگاتورها رندر شود یا نه. وقتی به **true** تنظیم شود، لیگاتورها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض، این ویژگی برابر **false** است. |
| virtual void [set_EmbedImages](./set_embedimages/)(**bool**) | گزینهٔ جاسازی تصاویر را تنظیم می‌کند. نوشتن **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | سبک بصری گرادیان را تنظیم می‌کند. [GradientStyle](../../aspose.slides/gradientstyle/) را می‌نویسد. |
| virtual void [set_OutputPath](./set_outputpath/)([System::String](../../system/string/)) | محل ذخیره‌سازی منابع خارجی را تعیین می‌کند. [System::String](../../system/string/) را می‌نویسد. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | سطح فشرده‌سازی تصاویر را نشان می‌دهد. [PicturesCompression](../picturescompression/) را می‌نویسد. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | یک شیء بازخوانی برای ذخیره‌سازی به‌روزرسانی‌های پیشرفت به درصد را نشان می‌دهد. رجوع به [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | مشخص می‌کند آیا لینک‌های ابرمتن با فراخوانی‌های JavaScript هنگام ذخیره‌سازی ارائه‌نامه رد شوند یا نه. **bool** را می‌نویسد. مقدار پیش‌فرض **false** است. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../islideslayoutoptions/) را تنظیم می‌کند. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | شیئی را تنظیم می‌کند که هشدارها را دریافت کرده و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و باز می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## ملاحظات

مثال: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-shapes-and-transitions.html", SaveFormat::Html5, options);
```

## مراجع

* کلاس [ISaveOptions](../isaveoptions/)
* فضای نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)