---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides برای C++ مرجع API
description: رابط پایه برای اشیاء غیرقابل تغییر که ویژگی‌های فرمت‌بندی بخش متن مؤثر را شامل می‌شوند.
type: docs
weight: 1470
url: /fa/aspose.slides/ibaseportionformateffectivedata/
---
## کلاس IBasePortionFormatEffectiveData

Base interface for immutable objects which contain effective text portion formatting properties.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | شناسه (Id) یک زبان جایگزین را برمی‌گرداند. فقط خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. فقط خواندنی [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | اطلاعات قلم شرق آسیا را برمی‌گرداند. فقط خواندنی [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | ویژگی‌های متن [EffectFormat](../effectformat/) را برمی‌گرداند. فقط خواندنی [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | متن بالانویس یا زیرنویس را برمی‌گرداند. مقدار بین -100٪ (زیرنویس) تا 100٪ (بالانویس). فقط خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | ویژگی‌های متن [FillFormat](../fillformat/) را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | تعیین می‌کند آیا قلم پررنگ (bold) است یا خیر. فقط خواندنی **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | ارتفاع قلم بخش متن را به نقطه (points) برمی‌گرداند. فقط خواندنی **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | تعیین می‌کند آیا قلم ایتالیک است یا خیر. فقط خواندنی **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | نوع زیرخط متن را برمی‌گرداند. فقط خواندنی [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | رنگ مورد استفاده برای برجسته‌سازی متن را برمی‌گرداند. فقط خواندنی [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [FillFormat](../fillformat/) خود است یا از ویژگی‌های [FillFormat](../fillformat/) متن ارث می‌گیرد. فقط خواندنی **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [LineFormat](../lineformat/) خود است یا از ویژگی‌های [LineFormat](../lineformat/) متن ارث می‌گیرد. فقط خواندنی **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | حداقل اندازه قلم که برای آن کرنینگ باید فعال شود را برمی‌گرداند. فقط خواندنی **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. فقط خواندنی **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | شناسه یک زبان را برمی‌گرداند. فقط خواندنی [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | اطلاعات قلم لاتین را برمی‌گرداند. فقط خواندنی [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | ویژگی‌های [LineFormat](../lineformat/) برای حاشیه‌کشی متن را برمی‌گرداند. فقط خواندنی [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا خیر. فقط خواندنی **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | تعیین می‌کند آیا متن نباید تصحیح شود یا خیر. فقط خواندنی **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | تعیین می‌کند آیا برچسب هوشمند باید پاک شود یا خیر. فقط خواندنی **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | افزایش فاصله بین حروف را به نقطه (points) برمی‌گرداند. فقط خواندنی **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | نوع خط‌خورده (strikethrough) متن را برمی‌گرداند. فقط خواندنی [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | اطلاعات قلم نمادین را برمی‌گرداند. فقط خواندنی [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | نوع حروف بزرگ‌نویسی متن را برمی‌گرداند. فقط خواندنی [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | ویژگی‌های خط زیرخط [FillFormat](../fillformat/) را برمی‌گرداند. فقط خواندنی [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | ویژگی‌های [LineFormat](../lineformat/) مورد استفاده برای حاشیه‌کشی خط زیرخط را برمی‌گرداند. فقط خواندنی [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا زده شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر (clone) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و بازمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | سازماندهی typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا زده شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن از هوشمندها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)