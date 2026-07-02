---
title: BasePortionFormat
second_title: Aspose.Sildes برای .NET – مرجع API
description: ویژگی‌های عمومی قالب‌بندی بخش متن.
type: docs
weight: 970
url: /fa/aspose.slides/baseportionformat/
---
## کلاس BasePortionFormat

ویژگی‌های عمومی قالب‌بندی بخش متن.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | مقدار Id یک زبان جایگزین را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را بر می‌گرداند یا تنظیم می‌کند. مقدار Null به معنی عدم تعریف قلم است و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم شرق آسیا را بر می‌گرداند یا تنظیم می‌کند. مقدار Null به معنی عدم تعریف قلم است و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن فوقانی یا زیرنویس را بر می‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (فوقانی) است. **float.NaN** به معنی عدم تعریف مقدار است و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تعیین می‌کند آیا قلم ضخیم (bold) است یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را بر می‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی عدم تعریف ارتفاع است و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تعیین می‌کند آیا قلم ایتالیک است یا نه. هیچ ارث‌‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را بر می‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای برجسته‌سازی متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خودش است یا از ویژگی‌های FillFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خودش است یا از ویژگی‌های LineFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را که کرنینگی برای آن فعال شود، بر می‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی عدم تعریف مقدار است و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Id یک زبان تصحیح را بر می‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. خواندنی/نوشتنی String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را بر می‌گرداند یا تنظیم می‌کند. مقدار Null به معنی عدم تعریف قلم است و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای خط‌کشی متن را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تعیین می‌کند آیا ارتفاع متن باید نرمال‌سازی شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تعیین می‌کند آیا متن نباید تصحیح شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایش فاصله بین کاراکترها را بر می‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی عدم تعریف مقدار است و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقداری را که نشان می‌دهد آیا بررسی املای متن فعال است یا نه، دریافت یا تنظیم می‌کند. وقتی این ویژگی false باشد، بررسی‌های املایی برای عناصر متن سرکوب می‌شود. وقتی true باشد، بررسی املای متنی مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط‌کشی متن را بر می‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را بر می‌گرداند یا تنظیم می‌کند. مقدار Null به معنی عدم تعریف قلم است و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را بر می‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده شده برای خط‌کشی خط زیرخط را بر می‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |

## متدها

| نام | توضیحات |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را بر می‌گرداند. |

### موارد مرتبط

* کلاس [PVIObject](../pviobject)
* رابط [IBasePortionFormat](../ibaseportionformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->