---
title: IBasePortionFormat
second_title: Aspose.Slides برای C++ مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 1457
url: /fa/aspose.slides/ibaseportionformat/
---
## کلاس IBasePortionFormat

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [IPortionFormatEffectiveData](../iportionformateffectivedata/)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | شناسهٔ یک زبان جایگزین را برمی‌گرداند. مطالعه کنید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. مطالعه کنید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | اطلاعات قلم شرق آسیا را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. مطالعه کنید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | ویژگی‌های [EffectFormat](../effectformat/) متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | متن بالانویس یا زیرنویس را برمی‌گرداند. مقدار از -۱۰۰٪ (زیرنویس) تا ۱۰۰٪ (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. فقط خواندنی **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | ویژگی‌های [FillFormat](../fillformat/) متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | تشخیص می‌دهد که قلم بولد است یا نه. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | ارتفاع قلم یک بخش را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. فقط خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | تشخیص می‌دهد که قلم ایتالیک است یا نه. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | نوع زیرخط متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | رنگ استفاده‌شده برای روشن‌سازی متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | تشخیص می‌دهد که سبک زیرخط ویژگی‌های خود [FillFormat](../fillformat/) را دارد یا از ویژگی‌های [FillFormat](../fillformat/) متن به ارث می‌برد. خواندنی [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | تشخیص می‌دهد که سبک زیرخط ویژگی‌های خود [LineFormat](../lineformat/) را دارد یا از ویژگی‌های [LineFormat](../lineformat/) متن به ارث می‌برد. خواندنی [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | حداقل اندازهٔ قلم را برمی‌گرداند که برای آن کرنینگ فعال می‌شود. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. فقط خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | تشخیص می‌دهد که اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | شناسهٔ یک زبان بازبینی را برمی‌گرداند. برای بررسی املایی و دستوری استفاده می‌شود. مطالعه کنید [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | اطلاعات قلم لاتین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. مطالعه کنید [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | ویژگی‌های [LineFormat](../lineformat/) برای خط‌کشی متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | تشخیص می‌دهد که ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | تشخیص می‌دهد که متن نباید بازبینی شود. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | افزایش فاصلهٔ بین‌نویسه‌ها را برمی‌گرداند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. فقط خواندنی **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | مقدار نشان‌دهندهٔ فعال بودن بررسی املایی برای بخش متن را برمی‌گرداند. وقتی این ویژگی به false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی به true تنظیم شود، بررسی املایی امکان‌پذیر است. مقدار پیش‌فرض **false** است. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | نوع خط‌خوردهٔ یک متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | اطلاعات قلم نمادین را برمی‌گرداند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. مطالعه کنید [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | نوع بزرگ/کوچک کردن حروف متن را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. خواندنی [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | ویژگی‌های زیرخط [FillFormat](../fillformat/) را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | ویژگی‌های [LineFormat](../lineformat/) استفاده‌شده برای خط‌کشی زیرخط را برمی‌گرداند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. فقط خواندنی [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. مشابه فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا نه. مشابه عملگر C# `is`. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان C# lock() . مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی (کلون) انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها به صورت کپی را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها به صورت کپی را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع shared را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | شناسهٔ یک زبان جایگزین را تنظیم می‌کند. بنویسید [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم اسکریپت پیچیده را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم شرق آسیا را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | متن بالانویس یا زیرنویس را تنظیم می‌کند. مقدار از -۱۰۰٪ (زیرنویس) تا ۱۰۰٪ (بالانویس). **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | تعیین می‌کند که قلم بولد باشد یا نه. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | ارتفاع قلم یک بخش را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | تعیین می‌کند که قلم ایتالیک باشد یا نه. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | نوع زیرخط متن را تنظیم می‌کند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | تعیین می‌کند که سبک زیرخط ویژگی‌های خود [FillFormat](../fillformat/) را دارد یا از ویژگی‌های [FillFormat](../fillformat/) متن به ارث می‌برد. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | تعیین می‌کند که سبک زیرخط ویژگی‌های خود [LineFormat](../lineformat/) را دارد یا از ویژگی‌های [LineFormat](../lineformat/) متن به ارث می‌برد. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | حداقل اندازهٔ قلم را تنظیم می‌کند که برای آن کرنینگ فعال می‌شود. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | تعیین می‌کند که اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | شناسهٔ یک زبان بازبینی را تنظیم می‌کند. برای بررسی املایی و دستوری استفاده می‌شود. بنویسید [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم لاتین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | تعیین می‌کند که ارتفاع متن باید نرمال‌سازی شود. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | تعیین می‌کند که متن نباید بازبینی شود. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | افزایش فاصلهٔ بین‌نویسه‌ها را تنظیم می‌کند. **std::numeric_limits<float>::quiet_NaN()** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. بنویسید **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | مقدار نشان‌دهندهٔ فعال بودن بررسی املایی برای بخش متن را تنظیم می‌کند. وقتی این ویژگی به false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شوند. وقتی به true تنظیم شود، بررسی املایی امکان‌پذیر است. مقدار پیش‌فرض **false** است. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | نوع خط‌خوردهٔ یک متن را تنظیم می‌کند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | اطلاعات قلم نمادین را تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. بنویسید [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | نوع بزرگ/کوچک کردن حروف متن را تنظیم می‌کند. هیچ ارث‌برداری‌ای اعمال نمی‌شود. بنویسید [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع shared را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع shared را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع shared را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بیانیهٔ قفل‌گذاری C# lock() برای آزادسازی. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع weak را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع weak را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## ملاحظات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر، هیچ ارث‌برداری‌ای اعمال نمی‌شود، بنابراین در بیشتر موارد مقادیر «تعریف‌نشده» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌برداری، باید از متد [IPortionFormat::GetEffective](../iportionformat/geteffective/) استفاده کنید که یک نمونهٔ [IPortionFormatEffectiveData](../iportionformateffectivedata/) را برمی‌گرداند.

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)