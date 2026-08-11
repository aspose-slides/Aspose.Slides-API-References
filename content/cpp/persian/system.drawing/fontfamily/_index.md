---
title: FontFamily
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر گروهی از فونت‌ها است که طرح پایهٔ مشابهی دارند. شی‌های این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونهٔ این نوع را بر روی پشته یا با اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 105
url: /fa/system.drawing/fontfamily/
---
## FontFamily کلاس

Represents a group of type faces that share a similar basic design. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FontFamily : public System::Object
```

## متدها

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [Clone](./clone/)() | یک کپی از شی [FontFamily](./) فعلی را برمی‌گرداند. |
| void [Dispose](./dispose/)() | همهٔ منابع سیستم‌عامل که توسط شی فعلی به‌دست آمده‌اند را آزاد می‌کند. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تعیین می‌کند آیا شی‌های فعلی و مشخص شده یکسان هستند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شی‌ها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شی‌های نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&) | یک نمونهٔ جدید از کلاس [FontFamily](./) که نمایانگر یک خانوادهٔ قلم با نام مشخص شده است، می‌سازد. |
| [FontFamily](./fontfamily/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::FontCollection](../../system.drawing.text/fontcollection/)\>\&) | یک نمونهٔ جدید از [FontFamily](./) را در FontCollection مشخص شده با نام تعیین شده می‌سازد. |
| [FontFamily](./fontfamily/)([Text::GenericFontFamilies](../../system.drawing.text/genericfontfamilies/)) | یک نمونهٔ جدید از [FontFamily](./) را از خانوادهٔ قلم عمومی مشخص شده می‌سازد. |
| static [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\>\> [get_Families](./get_families/)() | یک آرایه حاوی تمام شی‌های [FontFamily](./) مرتبط با زمینهٔ گرافیکی فعلی را برمی‌گرداند. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericMonospace](./get_genericmonospace/)() | یک شی [FontFamily](./) را برمی‌گرداند که نمایانگر یک خانوادهٔ قلم Generic Monospace است. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSansSerif](./get_genericsansserif/)() | یک شی [FontFamily](./) را برمی‌گرداند که نمایانگر یک خانوادهٔ قلم Generic Sans Serif است. |
| static [SharedPtr](../../system/sharedptr/)\<[FontFamily](./)\> [get_GenericSerif](./get_genericserif/)() | یک شی [FontFamily](./) را برمی‌گرداند که نمایانگر یک خانوادهٔ قلم Generic Serif است. |
| [String](../../system/string/) [get_Name](./get_name/)() const | نام خانوادهٔ قلم نمایانگر توسط شی فعلی را برمی‌گرداند. |
| int [GetCellAscent](./getcellascent/)([FontStyle](../fontstyle/)) | بالا رفتن سلولی خانوادهٔ قلم نمایانگر توسط شی فعلی برای سبک قلم مشخص‌شده را برمی‌گرداند. |
| int [GetCellDescent](./getcelldescent/)([FontStyle](../fontstyle/)) | پایین رفتن سلولی خانوادهٔ قلم نمایانگر توسط شی فعلی برای سبک قلم مشخص‌شده را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| int [GetEmHeight](./getemheight/)([FontStyle](../fontstyle/)) | ارتفاع مربع em را در واحدهای طراحی قلم برای سبک مشخص‌شده برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری شی‌های سفارشی را فراهم می‌کند. |
| int [GetLineSpacing](./getlinespacing/)([FontStyle](../fontstyle/)) | فاصله خطوط خانوادهٔ قلم نمایانگر توسط شی فعلی برای سبک قلم مشخص‌شده را برمی‌گرداند. |
| [String](../../system/string/) [GetName](./getname/)(int) const | نام خانوادهٔ قلم نمایانگر توسط شی فعلی را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| **bool** [IsStyleAvailable](./isstyleavailable/)([FontStyle](../fontstyle/)) | تعیین می‌کند آیا سبک قلم مشخص‌شده در دسترس است. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شی را ایجاد می‌کند. همهٔ ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شی‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شی‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شی نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه قوی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل شی‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بازکردن قفل عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual  [~FontFamily](./~fontfamily/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شی را تخریب می‌کند. همهٔ ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)