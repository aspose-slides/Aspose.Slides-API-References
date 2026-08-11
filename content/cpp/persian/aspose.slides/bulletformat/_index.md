---
title: BulletFormat
second_title: Aspose.Slides برای مرجع API C++
description: ویژگی‌های قالب‌بندی گلوله‌های پاراگراف را نمایش می‌دهد.
type: docs
weight: 248
url: /fa/aspose.slides/bulletformat/
---
## BulletFormat کلاس

نمایش‌دهندهٔ ویژگی‌های قالب‌بندی گلوله‌های پاراگراف.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## متدها

| Method | Description |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | مقادیر پیش‌فرض جابجایی‌های غیرصفر برای Indent و MarginLeft مؤثر پاراگراف تنظیم می‌کند زمانی که bullets فعال باشد (مانند کاری که PowerPoint هنگام فعال‌سازی گلوله‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). اگر bullets غیرفعال باشد، فقط Indent و MarginLeft پاراگراف را بازنشانی می‌کند (مانند کاری که PowerPoint هنگام غیرفعال‌سازی گلوله‌ها/شماره‌گذاری پاراگراف انجام می‌دهد). جابجایی‌های توانی نسبت به زمینهٔ فعلی گلوله اعمال می‌شوند - IBulletFormat::get(set)_Type، .NumberedBulletStyle و FontHeight اولین بخش. جابجایی‌های غیرصفر به Indent و MarginLeft مؤثر پاراگراف فعلی اعمال می‌شوند (مقدارهای نتیجه به‌صورت مقادیر محلی خواهند بود). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مقایسه با شیء مشخص‌شده. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناهای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| char16_t [get_Char](./get_char/)() override | کاراکتر گلولهٔ پاراگراف را بدون وراثت برمی‌گرداند. خواندنی **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | قالب رنگ گلولهٔ پاراگراف را بدون وراثت برمی‌گرداند. فقط خواندنی [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | قلم گلولهٔ پاراگراف را بدون وراثت برمی‌گرداند. خواندنی [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | ارتفاع گلولهٔ پاراگراف را بدون وراثت برمی‌گرداند. مقدار std::numeric_limits<float>::quiet_NaN() نشان می‌دهد که گلوله ارتفاعش را از اولین بخش پاراگراف به ارث می‌برد. خواندنی **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر گلوله رنگ خود را دارد و **[NullableBool::False](../nullablebool/)** اگر رنگ را از اولین بخش به ارث می‌برد. خواندنی [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر گلوله قلم خود را دارد و **[NullableBool::False](../nullablebool/)** اگر قلم را از اولین بخش به ارث می‌برد. خواندنی [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | اولین عددی که برای گروهی از گلوله‌های شماره‌دار بدون وراثت استفاده می‌شود را برمی‌گرداند. خواندنی **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | سبک گلولهٔ شماره‌دار را بدون وراثت برمی‌گرداند. خواندنی [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | تصویر استفاده‌شده به‌عنوان گلوله در پاراگراف را بدون وراثت برمی‌گرداند. فقط خواندنی [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | نوع گلولهٔ پاراگراف را بدون وراثت برمی‌گرداند. خواندنی [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | داده‌های قالب‌بندی مؤثر گلوله را با اعمال وراثت دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمامی ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت نسخهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_Char](./set_char/)(char16_t) override | کاراکتر گلولهٔ پاراگراف را بدون وراثت تنظیم می‌کند. نوشتنی **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | قلم گلولهٔ پاراگراف را بدون وراثت تنظیم می‌کند. نوشتنی [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | ارتفاع گلولهٔ پاراگراف را بدون وراثت تنظیم می‌کند. مقدار std::numeric_limits<float>::quiet_NaN() نشان می‌دهد که گلوله ارتفاعش را از اولین بخش پاراگراف به ارث می‌برد. نوشتنی **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا گلوله رنگ خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر گلوله رنگ خود را دارد و **[NullableBool::False](../nullablebool/)** اگر رنگ را از اولین بخش به ارث می‌برد. نوشتنی [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا گلوله قلم خود را دارد یا از اولین بخش پاراگراف به ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر گلوله قلم خود را دارد و **[NullableBool::False](../nullablebool/)** اگر قلم را از اولین بخش به ارث می‌برد. نوشتنی [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | اولین عددی که برای گروهی از گلوله‌های شماره‌دار بدون وراثت استفاده می‌شود را تنظیم می‌کند. نوشتنی **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | سبک گلولهٔ شماره‌دار را بدون وراثت تنظیم می‌کند. نوشتنی [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | نوع گلولهٔ پاراگراف را بدون وراثت تنظیم می‌کند. نوشتنی [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بازکردن بیان C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [PVIObject](../pviobject/)
* کلاس [IBulletFormat](../ibulletformat/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)