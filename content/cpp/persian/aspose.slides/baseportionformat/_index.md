---
title: BasePortionFormat
second_title: مرجع API Aspose.Slides برای C++
description: خواص عمومی فرمت‌بندی بخش متن.
type: docs
weight: 144
url: /fa/aspose.slides/baseportionformat/
---
## BasePortionFormat کلاس

خواص فرمت‌بندی مشترک بخش متن.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## متدها

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | با شیء مشخص شده مقایسه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر مطابق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه ممیز شناور (double) به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | شناسه یک زبان جایگزین را برمی‌گرداند. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | اطلاعات قلم شرق آسیا را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | ویژگی‌های متن [EffectFormat](../effectformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | متن بالا یا زیرنویس را برمی‌گرداند. مقدار از -۱۰۰٪ (زیرنویس) تا ۱۰۰٪ (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | ویژگی‌های متن [FillFormat](../fillformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | تعیین می‌کند که آیا قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | ارتفاع قلم یک بخش را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | تعیین می‌کند که آیا قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | نوع زیرخط متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | رنگ مورد استفاده برای هایلایت متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های [FillFormat](../fillformat/) proprie است یا از ویژگی‌های [FillFormat](../fillformat/) متن به ارث می‌برد. خواندن [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های [LineFormat](../lineformat/) proprie است یا از ویژگی‌های [LineFormat](../lineformat/) متن به ارث می‌برد. خواندن [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | حداقل اندازه قلم را که برای آن کرنینگ باید فعال شود، برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | شناسه یک زبان اصلاح‌گر را برمی‌گرداند. برای بررسی املاء و دستور زبان استفاده می‌شود. خواندن [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | اطلاعات قلم لاتین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | ویژگی‌های [LineFormat](../lineformat/) برای خط‌کشی متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | شی Parent_Immediate را برمی‌گرداند. فقط‌خواندنی [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | پدر [IPresentationComponent](../ipresentationcomponent/) را برمی‌گرداند. فقط‌خواندنی [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | تعیین می‌کند که آیا متن نباید اصلاح شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | افزایش فاصله بین‌حروف را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | مقداری را دریافت می‌کند که نشان می‌دهد آیا بررسی املای متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض **false** است. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | نوع خط‌بردار متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | اطلاعات قلم نمادین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | نوع حروف بزرگ متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. خواندن [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | ویژگی‌های خط زیرخط [FillFormat](../fillformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | ویژگی‌های [LineFormat](../lineformat/) استفاده‌شده برای خط‌کشی خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | کد هش را برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C# را شبیه‌سازی می‌کند. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌های کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژه [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | شناسه یک زبان جایگزین را تنظیم می‌کند. نوشتن [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم اسکریپت پیچیده را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم شرق آسیا را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | متن بالا یا زیرنویس را تنظیم می‌کند. مقدار از -۱۰۰٪ (زیرنویس) تا ۱۰۰٪ (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | ارتفاع قلم یک بخش را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | نوع زیرخط متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های [FillFormat](../fillformat/) خود است یا از ویژگی‌های [FillFormat](../fillformat/) متن به ارث می‌برد. نوشتن [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های [LineFormat](../lineformat/) خود است یا از ویژگی‌های [LineFormat](../lineformat/) متن به ارث می‌برد. نوشتن [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | حداقل اندازه قلم را که برای آن کرنینگ باید فعال شود تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا اعداد باید چیدمان عمودی مخصوص زبان‌های شرقی متن را نادیده بگیرند یا خیر. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | شناسه یک زبان اصلاح‌گر را تنظیم می‌کند. برای بررسی املاء و دستور زبان استفاده می‌شود. نوشتن [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم لاتین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | تعیین می‌کند که آیا متن نباید اصلاح شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | افزایش فاصله بین‌حروف را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. نوشتن **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | مقداری را تنظیم می‌کند که نشان می‌دهد آیا بررسی املای متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض **false** است. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | نوع خط‌بردار متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | اطلاعات قلم نمادین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. نوشتن [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | نوع حروف بزرگ متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. نوشتن [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از Smart Pointerها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از Smart Pointerها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | متد [Object.ToString()](../../system/object/tostring/) C# را شبیه‌سازی می‌کند. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از Smart Pointerها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض از Smart Pointerها یا ThisProtector استفاده کنید. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [PVIObject](../pviobject/)
* کلاس [IBasePortionFormat](../ibaseportionformat/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)