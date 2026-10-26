---
title: IParagraphFormat
second_title: Aspose.Slides برای C++ مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف IParagraphFormatEffectiveData، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 3147
url: /fa/aspose.slides/iparagraphformat/
---
## IParagraphFormat کلاس


این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```cpp
class IParagraphFormat : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | هم‌راستایی متن را در پاراگراف بدون ارث‌بری برمی‌گرداند. بخوانید [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | قالب گلولهٔ پاراگراف را برمی‌گرداند. فقط-خواندنی [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | قالب پیش‌فرض بخش از یک پاراگراف را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | اندازه پیش‌فرض تبولاسیون را بدون ارث‌بری برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | عمق پاراگراف را برمی‌گرداند. مقدار 0 به معنای مقدار نامعین است. فقط-خواندنی **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | تعیین می‌کند که آیا شکستن خط آسیای شرقی در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | هم‌راستایی قلم را در پاراگراف بدون ارث‌بری برمی‌گرداند. بخوانید [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون ارث‌بری برمی‌گرداند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. فقط-خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | حاشیهٔ چپ را در پاراگراف بدون ارث‌بری برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | حاشیهٔ راست را در پاراگراف بدون ارث‌بری برمی‌گرداند. فقط-خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | تعیین می‌کند که آیا نوشتن راست به چپ در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | مقدار فضای خالی پس از خط آخر در یک پاراگراف را بدون ارث‌بری برمی‌گرداند. مقدار مثبت درصدی از اندازهٔ قلم را که فضای سفید باید باشد تعیین می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. فقط-خواندنی **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | مقدار فضای خالی پیش از اولین خط در یک پاراگراف را بدون ارث‌بری برمی‌گرداند. مقدار مثبت درصدی از اندازهٔ قلم را که فضای سفید باید باشد تعیین می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. فقط-خواندنی **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | مقدار فضای خالی بین خطوط پایه در یک پاراگراف را برمی‌گرداند. مقدار مثبت به معنای درصد، منفی به معنای اندازه بر حسب نقطه است. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | تبولاسیون یک پاراگراف را در اندیس مشخص برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | تبولاسیون‌های یک پاراگراف را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | دادهٔ قالب‌بندی مؤثر پاراگراف را با اعمال ارث‌بری دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | مقدار شمارندهٔ ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | هم‌راستایی متن را در پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتهٔ [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | اندازه پیش‌فرض تبولاسیون را بدون ارث‌بری تنظیم می‌کند. نوشتهٔ **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | عمق پاراگراف را تنظیم می‌کند. مقدار 0 به معنای مقدار نامعین است. نوشتهٔ **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا شکستن خط آسیای شرقی در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتهٔ [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | هم‌راستایی قلم را در پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتهٔ [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتهٔ [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | تورفتگی خط اول/تورفتگی معلق پاراگراف را بدون ارث‌بری تنظیم می‌کند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. نوشتهٔ **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتهٔ [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | حاشیهٔ چپ را در پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتهٔ **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | حاشیهٔ راست را در پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتهٔ **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا نوشتن راست به چپ در پاراگراف استفاده می‌شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتهٔ [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | مقدار فضای خالی پس از خط آخر در یک پاراگراف را بدون ارث‌بری تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم ... مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه ... نوشتهٔ **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | مقدار فضای خالی پیش از اولین خط در یک پاراگراف را بدون ارث‌بری تنظیم می‌کند. مقدار مثبت درصدی از اندازهٔ قلم ... مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه ... نوشتهٔ **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | مقدار فضای خالی بین خطوط پایه در یک پاراگراف را تنظیم می‌کند. مقدار مثبت به معنای درصد، منفی به معنای اندازه بر حسب نقطه است. هیچ ارث‌بری اعمال نمی‌شود. نوشتهٔ **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان جابجایی اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از هوشمندها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از هوشمندها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## توجه

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این بدان معناست که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اغلب موارد مقادیری دریافت می‌کنید که به معنای «نامعین» هستند.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [IParagraphFormat::GetEffective](./geteffective/) استفاده کنید که یک نمونهٔ [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) برمی‌گرداند.

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)