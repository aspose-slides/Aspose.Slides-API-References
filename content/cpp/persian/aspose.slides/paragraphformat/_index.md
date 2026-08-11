---
title: ParagraphFormat
second_title: مرجع API Aspose.Slides برای C++
description: این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. برخلاف IParagraphFormatEffectiveData، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 4668
url: /fa/aspose.slides/paragraphformat/
---
## ParagraphFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```cpp
class ParagraphFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::IParagraphFormat,
                        public Aspose::Slides::Charts::IChartParagraphFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه با شیء مشخص‌شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | مقایسهٔ اشیاء با استفاده از معنای C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | مقایسهٔ اشیاء از نوع مرجع به سبک C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسهٔ اعداد شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر مطابق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسهٔ عدد شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر مطابق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() override | ترازبندی متن را در یک پاراگراف بدون ارث‌بری باز می‌گرداند. خواندن [TextAlignment](../textalignment/). |
| **float** [get_DefaultTabSize](./get_defaulttabsize/)() override | اندازه پیش‌فرض جداساز (tabulation) را بدون ارث‌بری باز می‌گرداند. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() override | تعیین می‌کند آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. خواندن [NullableBool](../nullablebool/). |
| [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() override | ترازبندی قلم را در یک پاراگراف بدون ارث‌بری باز می‌گرداند. خواندن [Slides::FontAlignment](../fontalignment/). |
| [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() override | تعیین می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. خواندن [NullableBool](../nullablebool/). |
| **float** [get_Indent](./get_indent/)() override | تورفتگی اولین خط/تورفتگی معلق پاراگراف را بدون ارث‌بری باز می‌گرداند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() override | تعیین می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. خواندن [NullableBool](../nullablebool/). |
| **float** [get_MarginLeft](./get_marginleft/)() override | حاشیهٔ چپ را در یک پاراگراف بدون ارث‌بری باز می‌گرداند. خواندن **float**. |
| **float** [get_MarginRight](./get_marginright/)() override | حاشیهٔ راست را در یک پاراگراف بدون ارث‌بری باز می‌گرداند. خواندن **float**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شیء Parent_Immediate را باز می‌گرداند. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را باز می‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() override | تعیین می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. خواندن [NullableBool](../nullablebool/). |
| **float** [get_SpaceAfter](./get_spaceafter/)() override | مقدار فضای پس از خط آخر در یک پاراگراف بدون ارث‌بری را باز می‌گرداند. مقدار مثبت درصد اندازهٔ قلم را برای فضای سفید مشخص می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. خواندن **float**. |
| **float** [get_SpaceBefore](./get_spacebefore/)() override | مقدار فضای پیش از خط اول در یک پاراگراف بدون ارث‌بری را باز می‌گرداند. مقدار مثبت درصد اندازهٔ قلم را برای فضای سفید مشخص می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. خواندن **float**. |
| **float** [get_SpaceWithin](./get_spacewithin/)() override | مقدار فضای بین خطوط پایه در یک پاراگراف را باز می‌گرداند. مقدار مثبت به معنی درصد، مقدار منفی به معنی اندازه در نقطه است. بدون اعمال ارث‌بری. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) override | جداساز (tabulation) یک پاراگراف را در اندیس مشخص‌شده باز می‌گرداند. بدون اعمال ارث‌بری. فقط-خواندنی [Aspose::Slides::ITab](../itab/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() override | جداسازهای یک پاراگراف را باز می‌گرداند. بدون اعمال ارث‌بری. فقط-خواندنی [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() override | داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال ارث‌بری دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را باز می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل (lock) در بیان C# را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها به‌صورت کپی را فراهم می‌کند. |
|  [ParagraphFormat](./paragraphformat/)() | یک نمونهٔ جدید از کلاس [ParagraphFormat](./) را مقداردهی اولیه می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به‌صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) override | ترازبندی متن را در یک پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتن [TextAlignment](../textalignment/). |
| void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) override | اندازه پیش‌فرض جداساز را بدون ارث‌بری تنظیم می‌کند. نوشتن **float**. |
| void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. نوشتن [NullableBool](../nullablebool/). |
| void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) override | ترازبندی قلم را در یک پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتن [Slides::FontAlignment](../fontalignment/). |
| void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. نوشتن [NullableBool](../nullablebool/). |
| void [set_Indent](./set_indent/)(**float**) override | تورفتگی اولین خط/تورفتگی معلق پاراگراف را بدون ارث‌بری تنظیم می‌کند. تورفتگی معلق می‌تواند با مقادیر منفی تعریف شود. نوشتن **float**. |
| void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. نوشتن [NullableBool](../nullablebool/). |
| void [set_MarginLeft](./set_marginleft/)(**float**) override | حاشیهٔ چپ را در یک پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتن **float**. |
| void [set_MarginRight](./set_marginright/)(**float**) override | حاشیهٔ راست را در یک پاراگراف بدون ارث‌بری تنظیم می‌کند. نوشتن **float**. |
| void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا خیر. بدون اعمال ارث‌بری. نوشتن [NullableBool](../nullablebool/). |
| void [set_SpaceAfter](./set_spaceafter/)(**float**) override | مقدار فضای پس از خط آخر در یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را برای فضای سفید مشخص می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. نوشتن **float**. |
| void [set_SpaceBefore](./set_spacebefore/)(**float**) override | مقدار فضای پیش از خط اول در یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. مقدار مثبت درصد اندازهٔ قلم را برای فضای سفید مشخص می‌کند. مقدار منفی اندازهٔ فضای سفید را بر حسب نقطه تعیین می‌کند. نوشتن **float**. |
| void [set_SpaceWithin](./set_spacewithin/)(**float**) override | مقدار فضای بین خطوط پایه در یک پاراگراف را تنظیم می‌کند. مقدار مثبت به معنی درصد، منفی به معنی اندازه در نقطه است. بدون اعمال ارث‌بری. نوشتن **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری (unlock) بیان C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## توضیحات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر، هیچ ارث‌بری‌ای اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که معنای «نامشخص» دارند.

برای به‌دست‌آوردن مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [ParagraphFormat::GetEffective](./geteffective/) استفاده کنید که یک نمونهٔ [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) را باز می‌گرداند.

## مراجع

* کلاس [PVIObject](../pviobject/)
* کلاس [IParagraphFormat](../iparagraphformat/)
* کلاس [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)