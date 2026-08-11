---
title: IPortionFormat
second_title: Aspose.Slides برای مرجع API C++
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 3329
url: /fa/aspose.slides/iportionformat/
---
## کلاس IPortionFormat

این کلاس شامل ویژگی‌های قالب‌بندی بخشی متن است. برخلاف [IPortionFormatEffectiveData](../iportionformateffectivedata/)، تمام ویژگی‌های این کلاس قابلیت نوشتن دارند.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از قواعد [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | شناسه یک زبان جایگزین را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | شناسه بوکمارک را برمی‌گرداند. ببینید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. ببینید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | اطلاعات قلم شرق آسیا را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. ببینید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | خصوصیات متن [EffectFormat](../effectformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | متن فوقانی یا زیرنویس را برمی‌گرداند. مقدار از -100٪ (زیرنویس) تا 100٪ (فوقانی). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | خصوصیات متن [FillFormat](../fillformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | تشخیص می‌دهد آیا قلم بولد است. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | ارتفاع قلم یک بخش را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | تشخیص می‌دهد آیا قلم ایتالیک است. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | نوع زیرخط متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | رنگ استفاده‌شده برایهایلایت متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | پیوندهایی که برای کلیک ماوس تعریف شده‌اند را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | مدیر پیوندها فقط خواندنی [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | پیوندهایی که برای عبور ماوس تعریف شده‌اند را برمی‌گرداند. ببینید [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | تشخیص می‌دهد آیا سبک زیرخط دارای خصوصیات [FillFormat](../fillformat/) خاص خود است یا از خصوصیات [FillFormat](../fillformat/) متن به ارث می‌برد. ببینید [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | تشخیص می‌دهد آیا سبک زیرخط دارای خصوصیات [LineFormat](../lineformat/) خاص خود است یا از خصوصیات [LineFormat](../lineformat/) متن به ارث می‌برد. ببینید [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | حداقل اندازه قلم را که برای آن کرنینگ باید فعال شود برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | تشخیص می‌دهد آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | شناسه یک زبان تصحیح را برمی‌گرداند. برای بررسی املا و گرامر استفاده می‌شود. ببینید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | اطلاعات قلم لاتین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. ببینید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | خصوصیات [LineFormat](../lineformat/) برای خط‌کشی متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | تشخیص می‌دهد آیا ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | تشخیص می‌دهد آیا متن نباید تصحیح شود. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | تشخیص می‌دهد آیا تگ هوشمند باید پاک شود. هیچ ارث‌بری اعمال نمی‌شود. خواندنی **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | افزایش فاصله بین کاراکترها را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | مقداری را برمی‌گرداند که نشان می‌دهد آیا بررسی املای متن فعال است. وقتی این ویژگی به false تنظیم شود، بررسی املای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املای مجاز است. مقدار پیش‌فرض **false** است. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | نوع خط‌خورده متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. بخوانید [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | اطلاعات قلم نمادین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. ببینید [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | نوع حروف بزرگ/کوچک متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. ببینید [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | خصوصیات خط زیرخط [FillFormat](../fillformat/) را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | خصوصیات [LineFormat](../lineformat/) مورد استفاده برای خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | داده‌های قالب‌بندی بخش مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را با ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | شناسه یک زبان جایگزین را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | شناسه بوکمارک را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم اسکریپت پیچیده را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم شرق آسیا را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | متن فوقانی یا زیرنویس را تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (فوقانی). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا قلم بولد است. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | ارتفاع قلم یک بخش را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا قلم ایتالیک است. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | نوع زیرخط متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند تعریف‌شده برای کلیک ماوس را تنظیم می‌کند. بنویسید [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | پیوند تعریف‌شده برای عبور ماوس را تنظیم می‌کند. بنویسید [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا سبک زیرخط دارای خصوصیات [FillFormat](../fillformat/) خاص خود است یا از خصوصیات [FillFormat](../fillformat/) متن به ارث می‌برد. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا سبک زیرخط دارای خصوصیات [LineFormat](../lineformat/) خاص خود است یا از خصوصیات [LineFormat](../lineformat/) متن به ارث می‌برد. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | حداقل اندازه قلم را که برای آن کرنینگ باید فعال شود تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | شناسه یک زبان تصحیح را تنظیم می‌کند. برای بررسی املا و گرامر استفاده می‌شود. بنویسید [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم لاتین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | تشخیص می‌دهد آیا متن نباید تصحیح شود. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | تشخیص می‌دهد آیا تگ هوشمند باید پاک شود. هیچ ارث‌بری اعمال نمی‌شود. بنویسید **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | افزایش فاصله بین کاراکترها را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | مقداری را تنظیم می‌کند که نشان می‌دهد آیا بررسی املای متن فعال است. وقتی این ویژگی به false تنظیم شود، بررسی املای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املای مجاز است. مقدار پیش‌فرض **false** است. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | نوع خط‌خورده متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم نمادین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | نوع حروف بزرگ/کوچک متن را تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. بنویسید [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به عنوان اشاره‌گر ضعیف تنظیم می‌کند (به جای اشتراک). امکان تعویض اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بازمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل دستور C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## ملاحظات

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخشی متن که برای بخش خاص تعریف شده‌اند استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقدارهایی به معنای «تعریف نشده» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی به‌همراه ارث‌بری، باید از متد [IPortionFormat::GetEffective](./geteffective/) استفاده کنید که یک نمونه [IPortionFormatEffectiveData](../iportionformateffectivedata/) را برمی‌گرداند.

## مراجع

* کلاس [IBasePortionFormat](../ibaseportionformat/)
* کلاس [IHyperlinkContainer](../ihyperlinkcontainer/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)