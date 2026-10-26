---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes برای .NET مرجع API
description: رابط پایه برای اشیای غیرقابل تغییر که ویژگی‌های قالب‌بندی مؤثر بخش متن را شامل می‌شوند.
type: docs
weight: 5320
url: /fa/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData رابط

رابط پایه برای اشیای غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی مؤثر بخش متن می‌باشند.

```csharp
public interface IBasePortionFormatEffectiveData
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | شناسه یک زبان جایگزین را برمی‌گرداند. فقط-خواندنی String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | اطلاعات فونت اسکریپت پیچیده را برمی‌گرداند. فقط-خواندنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | اطلاعات فونت آسیای شرقی را برمی‌گرداند. فقط-خواندنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. فقط-خواندنی [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | متن بالانوشته یا زیرنوشته را برمی‌گرداند. مقدار بین -100٪ (زیرنوشته) تا 100٪ (بالانوشته). فقط-خواندنی Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. فقط-خواندنی [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | تعیین می‌کند آیا فونت بولد است یا خیر. فقط-خواندنی Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | ارتفاع فونت بخش متن را به نقطه برمی‌گرداند. فقط-خواندنی Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | تعیین می‌کند آیا فونت ایتالیک است یا خیر. فقط-خواندنی Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | نوع زیرخط متن را برمی‌گرداند. فقط-خواندنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | رنگ مورد استفاده برای هایلایت متن را برمی‌گرداند. فقط-خواندنی Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | تعیین می‌کند آیا سبک زیرخط ویژگی‌های FillFormat خود را دارد یا از ویژگی‌های FillFormat متن به ارث می‌برد. فقط-خواندنی Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | تعیین می‌کند آیا سبک زیرخط ویژگی‌های LineFormat خود را دارد یا از ویژگی‌های LineFormat متن به ارث می‌برد. فقط-خواندنی Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | حداقل اندازه فونت که کرنینگ برای آن فعال می‌شود را برمی‌گرداند. فقط-خواندنی Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند یا خیر. فقط-خواندنی Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | شناسه یک زبان را برمی‌گرداند. فقط-خواندنی String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | اطلاعات فونت لاتین را برمی‌گرداند. فقط-خواندنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | ویژگی‌های LineFormat برای حاشیه‌کشی متن را برمی‌گرداند. فقط-خواندنی [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا خیر. فقط-خواندنی Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | تعیین می‌کند آیا متن باید بازبینی نشود. فقط-خواندنی Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | تعیین می‌کند آیا برچسب هوشمند باید پاک شود یا خیر. فقط-خواندنی Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | افزایش فاصله بین حروف را به نقطه برمی‌گرداند. فقط-خواندنی Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | نوع خط‌خورده متن را برمی‌گرداند. فقط-خواندنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | اطلاعات فونت نمادین را برمی‌گرداند. فقط-خواندنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | نوع بزرگ‌نویسی متن را برمی‌گرداند. فقط-خواندنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. فقط-خواندنی [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | ویژگی‌های LineFormat مورد استفاده برای حاشیه‌کشی خط زیرخط را برمی‌گرداند. فقط-خواندنی [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### مراجع

* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->