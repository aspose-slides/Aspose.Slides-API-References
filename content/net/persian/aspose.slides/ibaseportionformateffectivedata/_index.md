---
title: IBasePortionFormatEffectiveData
second_title: مرجع API Aspose.Sildes برای .NET
description: رابط پایه برای اشیای غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر بخش متن هستند.
type: docs
weight: 5320
url: /fa/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData رابط

رابط پایه برای اشیای غیرقابل تغییر که دارای ویژگی‌های قالب‌بندی مؤثر بخش متن هستند.

```csharp
public interface IBasePortionFormatEffectiveData
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | شناسه یک زبان جایگزین را برمی‌گرداند. فقط خواندنی String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند. فقط خواندنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | اطلاعات قلم شرق آسیا را برمی‌گرداند. فقط خواندنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | خواص EffectFormat متن را برمی‌گرداند. فقط خواندنی [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | متن بالانویس یا زیرنویس را برمی‌گرداند. مقدار از -100٪ (زیرنویس) تا 100٪ (بالانویس). فقط خواندنی Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | خواص FillFormat متن را برمی‌گرداند. فقط خواندنی [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | تعیین می‌کند که آیا قلم Bold است یا خیر. فقط خواندنی Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | ارتفاع قلم بخش متن را به نقطه (pt) برمی‌گرداند. فقط خواندنی Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | تعیین می‌کند که آیا قلم Italic است یا خیر. فقط خواندنی Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | نوع زیرخط متن را برمی‌گرداند. فقط خواندنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | رنگ استفاده‌شده برای برجسته‌سازی متن را برمی‌گرداند. فقط خواندنی Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات FillFormat خود است یا از خصوصیات FillFormat متن به ارث می‌برد. فقط خواندنی Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | تعیین می‌کند که آیا سبک زیرخط دارای خصوصیات LineFormat خود است یا از خصوصیات LineFormat متن به ارث می‌برد. فقط خواندنی Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | حداقل اندازه قلم را که کرنینگی برای آن فعال می‌شود برمی‌گرداند. فقط خواندنی Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | تعیین می‌کند که آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. فقط خواندنی Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | شناسه یک زبان را برمی‌گرداند. فقط خواندنی String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | اطلاعات قلم لاتین را برمی‌گرداند. فقط خواندنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | خواص LineFormat برای حاشیه‌کشی متن را برمی‌گرداند. فقط خواندنی [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | تعیین می‌کند که آیا ارتفاع متن باید نرمال شود یا خیر. فقط خواندنی Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | تعیین می‌کند که آیا متن نباید تصحیح شود یا خیر. فقط خواندنی Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | تعیین می‌کند که آیا برچسب هوشمند باید پاک شود یا خیر. فقط خواندنی Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | تفاوت فاصله بین حروف را به نقطه برمی‌گرداند. فقط خواندنی Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | نوع خط‌خورده متن را برمی‌گرداند. فقط خواندنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | اطلاعات قلم نمادین را برمی‌گرداند. فقط خواندنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | نوع حروف بزرگ متن را برمی‌گرداند. فقط خواندنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | خواص FillFormat خط زیرخط را برمی‌گرداند. فقط خواندنی [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | خواص LineFormat که برای حاشیه‌کشی خط زیرخط استفاده می‌شود را برمی‌گرداند. فقط خواندنی [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### همچنین ببینید

* فضای‌نامی [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->