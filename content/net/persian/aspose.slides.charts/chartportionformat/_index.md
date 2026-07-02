---
title: ChartPortionFormat
second_title: Aspose.Sildes برای .NET مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش نمودار است که در نمودارها استفاده می‌شود. برخلاف IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 1430
url: /fa/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی بخش نمودار است که در نمودارها استفاده می‌شوند. برخلاف [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | شناسه یک زبان جایگزین را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی برای دریافت رابط IPresentationComponent پایه را فراهم می‌کند. فقط‌خواندنی [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را دریافت یا تنظیم می‌کند. Null به این معناست که قلم تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم شرق آسیا را دریافت یا تنظیم می‌کند. Null به این معناست که قلم تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن بالا/پایین نمایی را دریافت یا تنظیم می‌کند. مقدار از -100٪ (پایین) تا 100٪ (بالا) است. **float.NaN** به این معناست که مقدار تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تعیین می‌کند که آیا قلم bold باشد. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را دریافت یا تنظیم می‌کند. **float.NaN** به این معناست که ارتفاع تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تعیین می‌کند که آیا قلم itallic باشد. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را دریافت یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای برجسته‌سازی متن را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن ارث می‌برد. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند که آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن ارث می‌برد. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را که برای آن کرنینگ فعال می‌شود دریافت یا تنظیم می‌کند. **float.NaN** به این معناست که مقدار تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | شناسه یک زبان اصلاحی را دریافت یا تنظیم می‌کند. برای بررسی املا و دستور زبان استفاده می‌شود. خواندنی/قابل نوشتن String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را دریافت یا تنظیم می‌کند. Null به این معناست که قلم تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای حاشیه‌گذاری متن را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تعیین می‌کند که آیا متن نباید اصلاح شود. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایشی برای فاصله بین کاراکترها دریافت یا تنظیم می‌کند. **float.NaN** به این معناست که مقدار تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقدار نشان‌دهنده این که آیا بررسی املای متن برای این بخش فعال باشد را دریافت یا تنظیم می‌کند. وقتی این ویژگی به false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط خورده (strikethrough) متن را دریافت یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را دریافت یا تنظیم می‌کند. Null به این معناست که قلم تعریف نشده و باید از Master ارث‌بری شود. خواندنی/قابل نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را دریافت یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده شده برای حاشیه‌گذاری خط زیرخط را دریافت می‌کند. هیچ وراثتی اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص‌شده مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را باز می‌گرداند. |

### یادداشت‌ها

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخشی از متن که برای بخش خاصی تعریف شده‌اند، استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ وراثتی اعمال نمی‌شود، به‌طوری‌که در اکثر موارد مقادیر «تعریف‌نشده» بازگردانده می‌شود.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل مقادیر ارث‌بری، باید از متد [`GetEffective`](../../aspose.slides/portionformat/geteffective) استفاده کنید که یک نمونه [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) برمی‌گرداند.

### موارد مرتبط

* کلاس [BasePortionFormat](../../aspose.slides/baseportionformat)
* رابط [IChartPortionFormat](../ichartportionformat)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->