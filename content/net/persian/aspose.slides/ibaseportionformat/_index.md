---
title: IBasePortionFormat
second_title: Aspose.Sildes برای .NET مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 5330
url: /fa/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat رابط

این کلاس شامل ویژگی‌های فرمت‌بندی بخش متن است. بر خلاف [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public interface IBasePortionFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | مقدار Id یک زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | متن بالانویس یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (بالانویس). **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | مشخص می‌کند آیا قلم ضخیم است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | مشخص می‌کند آیا قلم ایتالیک است یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | رنگ استفاده‌شده برای برجسته‌سازی متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | مشخص می‌کند آیا سبک زیرخط ویژگی‌های FillFormat خود را دارد یا آنها را از ویژگی‌های FillFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | مشخص می‌کند آیا سبک زیرخط ویژگی‌های LineFormat خود را دارد یا آنها را از ویژگی‌های LineFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را که کرنینگ باید برای آن فعال شود، برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | مشخص می‌کند آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Id یک زبان تصحیح را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املا و دستور زبان استفاده می‌شود. خواندنی/نوشتنی String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای مرزدهی متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | مشخص می‌کند آیا ارتفاع متن باید نرمالیزه شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | مشخص می‌کند آیا متن نباید تصحیح شود یا خیر. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | مقدار افزایشی فاصله بین حروف را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | مقداری را بر می‌گرداند یا تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی اجازه داده می‌شود. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | نوع بزرگ‌نویسی متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. خواندنی/نوشتنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat مورد استفاده برای مرزبندی خط زیرخط را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |

### یادداشت‌ها

از این کلاس برای برگرداندن و دستکاری ویژگی‌های فرمت‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ وراثتی اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که به معنای «تعریف‌نشده» هستند.

برای دریافت مقادیر پارامترهای فرمت‌بندی مؤثر شامل مقادیر ارث‌بری، باید از روش [`GetEffective`](../iportionformat/geteffective) استفاده کنید که یک نمونه [`IPortionFormatEffectiveData`](../iportionformateffectivedata) را برمی‌گرداند.

### مراجع

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->