---
title: PortionFormat
second_title: مرجع API Aspose.Slides برای C++
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. بر خلاف IPortionFormatEffectiveData، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 4811
url: /fa/aspose.slides/portionformat/
---
## PortionFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. بر خلاف [IPortionFormatEffectiveData](../iportionformateffectivedata/)، همه ویژگی‌های این کلاس قابل نوشتن هستند.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## متدها

| متد | توضیح |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | با شیء مشخص شده مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به-سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | شناسه یک زبان جایگزین را بر می‌گرداند. خواندن [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | شناسه نشانک را بر می‌گرداند. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | اطلاعات قلم اسکریپت پیچیده را بر می‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | اطلاعات قلم شرق آسیایی را بر می‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | ویژگی‌های متن [EffectFormat](../effectformat/) را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | متن بالانویس یا زیرنویس را بر می‌گرداند. مقدار از -100% (زیرنویس) تا 100% (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | ویژگی‌های متن [FillFormat](../fillformat/) را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | تعیین می‌کند آیا قلم بولد است یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | ارتفاع قلم یک بخش را بر می‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده است و باید از Master به ارث برده شود. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | تعیین می‌کند آیا قلم ایتالیک است یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | نوع زیرخط متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | رنگ استفاده شده برای برجسته‌سازی متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | پیوندهای فراموشی تعریف‌شده برای کلیک ماوس را بر می‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | مدیر پیوندهای فراموشی. فقط-خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | پیوندهای فراموشی تعریف‌شده برای شناورماوس را بر می‌گرداند. خواندن [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [FillFormat](../fillformat/) خود است یا از ویژگی‌های [FillFormat](../fillformat/) متن ارث می‌برد. خواندن [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [LineFormat](../lineformat/) خود است یا از ویژگی‌های [LineFormat](../lineformat/) متن ارث می‌برد. خواندن [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | حداقل اندازه قلم را بر می‌گرداند که برای آن کرنینگ باید فعال شود. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | شناسه یک زبان Proofing را بر می‌گرداند. برای بررسی املا و گرامر استفاده می‌شود. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | اطلاعات قلم لاتین را بر می‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | ویژگی‌های [LineFormat](../lineformat/) برای خط‌کشی متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شی Parent_Immediate را بر می‌گرداند. فقط-خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | والد [IPresentationComponent](../ipresentationcomponent/) را بر می‌گرداند. فقط-خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | تعیین می‌کند آیا متن نباید proof شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | تعیین می‌کند آیا تگ هوشمند باید پاک شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندن **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | افزایش فاصله بین حروف را بر می‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندن **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | مقداری را می‌گیرد که نشان می‌دهد آیا بررسی املای متن فعال است یا نه. وقتی این ویژگی به **false** تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به **true** تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض **false** است. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | نوع خط‌خورده متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | اطلاعات قلم نمادین را بر می‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | نوع بزرگ‌نویسی متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | ویژگی‌های خط زیرخط [FillFormat](../fillformat/) را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | ویژگی‌های [LineFormat](../lineformat/) استفاده‌شده برای خط‌کشی زیرخط را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را می‌گیرد. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | داده‌های قالب‌بندی مؤثر بخش را با اعمال ارث‌بری دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را بر می‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
|  [PortionFormat](./portionformat/)() | نمونهٔ جدیدی از کلاس [PortionFormat](./) را مقداردهی می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیءها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع به‌اشتراک‌گذاری‌شده را با مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | شناسه یک زبان جایگزین را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | شناسه نشانک را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم اسکریپت پیچیده را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم شرق آسیایی را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | متن بالانویس یا زیرنویس را تنظیم می‌کند. مقدار از -100% (زیرنویس) تا 100% (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا قلم بولد است یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | ارتفاع قلم یک بخش را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده است و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا قلم ایتالیک است یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | نوع زیرخط متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندهای فراموشی تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | پیوندهای فراموشی تعریف‌شده برای شناورماوس را تنظیم می‌کند. نوشتن [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [FillFormat](../fillformat/) خود است یا از ویژگی‌های [FillFormat](../fillformat/) متن ارث می‌برد. نوشتن [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های [LineFormat](../lineformat/) خود است یا از ویژگی‌های [LineFormat](../lineformat/) متن ارث می‌برد. نوشتن [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | حداقل اندازه قلم را که برای آن کرنینگ باید فعال شود تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | شناسه یک زبان proofing را تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. نوشتن [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم لاتین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | تعیین می‌کند آیا متن نباید proof شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | تعیین می‌کند آیا تگ هوشمند باید پاک شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. نوشتن **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | افزایش فاصله بین حروف را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | مقدار را تنظیم می‌کند که نشان می‌دهد آیا بررسی املای متن فعال است یا نه. وقتی به **false** تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به **true** تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض **false** است. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | نوع خط‌خورده متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم نمادین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | نوع بزرگ‌نویسی متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع به‌اشتراک‌گذاری‌شده را می‌گیرد. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را کاهش می‌دهد و بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را آزاد می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## ملاحظات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در بیشتر موارد مقادیری دریافت می‌کنید که به معنای «نامشخص» هستند.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از متد [PortionFormat::GetEffective](./geteffective/) استفاده کنید که یک نمونهٔ [IPortionFormatEffectiveData](../iportionformateffectivedata/) را بر می‌گرداند.

مثال‌های زیر نشان می‌دهند چگونه قلم لاتین را به بخش [Paragraph](../paragraph/) در PowerPoint [Presentation](../presentation/) اختصاص دهید.

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides از این شناسه‌های ویژه استفاده می‌کند (مشابه آن‌هایی که در PowerPoint استفاده می‌شود):
// +mn-lt - قلم بدنه لاتین (قلم لاتین مینور)
// +mj-lt - قلم سرعنوان لاتین (قلم لاتین ماژور)
// +mn-ea - قلم بدنه آسیای شرقی (قلم آسیای شرقی مینور)
// +mj-ea - قلم بدنه آسیای شرقی (قلم آسیای شرقی ماژور)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## همچنین ببینید

* کلاس [BasePortionFormat](../baseportionformat/)
* کلاس [IPortionFormat](../iportionformat/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)