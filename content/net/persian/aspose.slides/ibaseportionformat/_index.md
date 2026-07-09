---
title: IBasePortionFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata، همه ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 5310
url: /fa/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat رابط

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، همه ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public interface IBasePortionFormat
```

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | شناسه Id یک زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | متن سوپر‌اسکریپت یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (سوپر‌اسکریپت). **float.NaN** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | تعیین می‌کند آیا قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | تعیین می‌کند آیا قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای هایلایت متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن به ارث می‌برد. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن به ارث می‌برد. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را که برای آن کرنینگ فعال شود، برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | شناسه Id یک زبان تصحیح را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و دستورات استفاده می‌شود. خواندنی/قابل نوشتن String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای پیرامون متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | تعیین می‌کند آیا ارتفاع متن باید نرمالیزه شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | تعیین می‌کند آیا متن نباید تصحیح شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | افزایشت فواصل بین حروف را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | دریافت یا تنظیم مقدار نشان‌دهنده این که آیا بررسی املایی برای بخش متن فعال باشد یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | نوع خط خورده متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده است و باید از Master به ارث برده شود. خواندنی/قابل نوشتن [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/قابل نوشتن [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده شده برای پیرامون خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../ilineformat). |

### نکات

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که به معنی «تعریف نشده» هستند.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از روش [`GetEffective`](../iportionformat/geteffective) استفاده کنید که یک نمونه [`IPortionFormatEffectiveData`](../iportionformateffectivedata) را برمی‌گرداند.

### موارد مرتبط

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->