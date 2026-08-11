---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides برای C++ مرجع API
description: شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر پاراگراف است.
type: docs
weight: 3160
url: /fa/aspose.slides/iparagraphformateffectivedata/
---
## IParagraphFormatEffectiveData کلاس

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر پاراگراف است.

```cpp
class IParagraphFormatEffectiveData : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | هم‌راستایی متن را در یک پاراگراف برمی‌گرداند. فقط-خواندنی [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [get_Bullet](./get_bullet/)() | قالب گلوله‌ای یک پاراگراف را برمی‌گرداند. فقط-خواندنی [IBulletFormatEffectiveData](../ibulletformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | قالب بخش پیش‌فرض یک پاراگراف را برمی‌گرداند. فقط-خواندنی [IPortionFormatEffectiveData](../iportionformateffectivedata/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | اندازه پیش‌فرض تب را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | عمق یک پاراگراف را برمی‌گرداند. فقط-خواندنی **int16_t**. |
| virtual **bool** [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا نه. فقط-خواندنی **bool**. |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | هم‌راستایی قلم را در یک پاراگراف برمی‌گرداند. فقط-خواندنی [Slides::FontAlignment](../fontalignment/). |
| virtual **bool** [get_HangingPunctuation](./get_hangingpunctuation/)() | تعیین می‌کند که آیا نقطه‌گذاری معلق در پاراگراف استفاده می‌شود یا نه. فقط-خواندنی **bool**. |
| virtual **float** [get_Indent](./get_indent/)() | تو رفتگی خط اول/تو رفتگی معلق پاراگراف را برمی‌گرداند. تو رفتگی معلق می‌تواند با مقادیر منفی تعریف شود. فقط-خواندنی **float**. |
| virtual **bool** [get_LatinLineBreak](./get_latinlinebreak/)() | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا نه. فقط-خواندنی **bool**. |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | حاشیه چپ در یک پاراگراف را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | حاشیه راست در یک پاراگراف را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا نه. فقط-خواندنی **bool**. |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | مقدار فضای پس از آخرین خط در یک پاراگراف را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | مقدار فضای قبل از اولین خط در یک پاراگراف را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | مقدار فضای بین خطوط پایه در یک پاراگراف را برمی‌گرداند. فقط-خواندنی **float**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ITabEffectiveData](../itabeffectivedata/)\>\> [get_Tabs](./get_tabs/)() | تب‌های یک پاراگراف را برمی‌گرداند. فقط-خواندنی [ITabEffectiveData](../itabeffectivedata/)[]. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# ‘is’. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌کردن بیان C# lock() . مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr مقایسه مرجعی انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای مشترک). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازکردن قفل بیان C# lock() . مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌نماید. |

## ملاحظات

این رابط همراه با رابط [IParagraphFormat](../iparagraphformat/) برای بازگرداندن مقادیر قالب‌بندی مؤثر با به‌کارگیری ارث‌بری استفاده می‌شود. 

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)