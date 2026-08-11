---
title: HtmlGenerator
second_title: مرجع API Aspose.Slides برای C++
description: مولد HTML.
type: docs
weight: 105
url: /fa/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator کلاس

Html generator.

```cpp
class HtmlGenerator : public Aspose::Slides::Export::IHtmlGenerator
```

## متدها

| Method | Description |
| --- | --- |
| void [AddAttributeValue](./addattributevalue/)([System::String](../../system/string/)) override | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌نماید. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌نماید. |
| void [AddAttributeValue](./addattributevalue/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | مقدار ویژگی را نقل قول می‌کند و به فایل html اضافه می‌نماید. |
| void [AddHtml](./addhtml/)([System::String](../../system/string/)) override | متن قالب شدهٔ HTML را اضافه می‌کند. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | متن قالب شدهٔ HTML را اضافه می‌کند. |
| void [AddHtml](./addhtml/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | متن قالب شدهٔ HTML را اضافه می‌کند. |
| void [AddText](./addtext/)([System::String](../../system/string/)) override | متن ساده را به فایل‌های html اضافه می‌کند؛ کاراکترهای خاص را با موجودیت‌های html جایگزین می‌نماید. شکستن خطوط و فاصله‌های خالی جایگزین نمی‌شوند. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>) override | متن ساده را به فایل‌های html اضافه می‌کند؛ کاراکترهای خاص را با موجودیت‌های html جایگزین می‌نماید. شکستن خطوط و فاصله‌های خالی جایگزین نمی‌شوند. |
| void [AddText](./addtext/)([System::ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | متن ساده را به فایل‌های html اضافه می‌کند؛ کاراکترهای خاص را با موجودیت‌های html جایگزین می‌نماید. شکستن خطوط و فاصله‌های خالی جایگزین نمی‌شوند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **int32_t** [get_NextSlideIndex](./get_nextslideindex/)() override | اندیس یک اسلاید را که پس از اسلاید جاری رندر خواهد شد برمی‌گرداند یا -1 اگر اسلاید آخر در حال رندر باشد. فقط‌خواندنی **int32_t**. |
| **int32_t** [get_PreviousSlideIndex](./get_previousslideindex/)() override | اندیس اسلاید قبلاً رندر شده را برمی‌گرداند یا -1 اگر اولین اسلاید در حال رندر باشد. فقط‌خواندنی **int32_t**. |
| [System::Drawing::SizeF](../../system.drawing/sizef/) [get_SlideImageSize](./get_slideimagesize/)() override | اندازهٔ تصویر اسلاید را برمی‌گرداند. فقط‌خواندنی [System::Drawing::SizeF](../../system.drawing/sizef/). |
| [SvgCoordinateUnit](../svgcoordinateunit/) [get_SlideImageSizeUnit](./get_slideimagesizeunit/)() override | واحدی که اندازهٔ تصویر اسلاید با آن مشخص می‌شود را برمی‌گرداند. فقط‌خواندنی [SvgCoordinateUnit](../svgcoordinateunit/). |
| [System::String](../../system/string/) [get_SlideImageSizeUnitCode](./get_slideimagesizeunitcode/)() override | کد css واحدی که اندازهٔ تصویر اسلاید با آن مشخص می‌شود را برمی‌گرداند. فقط‌خواندنی [System::String](../../system/string/). |
| **int32_t** [get_SlideIndex](./get_slideindex/)() override | اندیس اسلایدی که در حال رندر است را برمی‌گرداند. فقط‌خواندنی **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را برمی‌گیرد. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر C# `is`. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌کردن بیان C# `lock()` را انجام می‌دهد. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی‌ سازهای زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی‌ سازهای زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساز‌مانند C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل بیان C# `lock()` را انجام می‌دهد. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |
## همچنین ببینید

* کلاس [IHtmlGenerator](../ihtmlgenerator/)
* فضای‌نام [Aspose::Slides::Export](../)
* کتابخانه [Aspose.Slides](../../)