---
title: PortionFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 9510
url: /fa/aspose.slides/portionformat/
---
## PortionFormat کلاس

این کلاس ویژگی‌های قالب‌بندی بخش متن را شامل می‌شود. بر خلاف [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## سازنده‌ها

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | یک نمونه جدید از کلاس [`PortionFormat`](../portionformat) را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | مقدار یا تنظیم Id یک زبان جایگزین. فقط خواندنی/نوشتنی String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | امکان دریافت رابط base IPresentationComponent را فراهم می‌کند. فقط خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | مقدار یا تنظیم شناسهٔ نشانک. فقط خواندنی/نوشتنی String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | مقدار یا تنظیم اطلاعات فونت اسکریپت پیچیده. مقدار Null به معنای عدم تعریف فونت و ارث‌بری از Master است. فقط خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | مقدار یا تنظیم اطلاعات فونت شرق آسیا. مقدار Null به معنای عدم تعریف فونت و ارث‌بری از Master است. فقط خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | مقدار یا تنظیم متن فوقانی یا زیرنویس. مقدار بین -100٪ (زیرنویس) تا 100٪ (فوق‌نویس). **float.NaN** به معنای عدم تعریف مقدار و ارث‌بری از Master است. فقط خواندنی/نوشتنی Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تعیین می‌کند آیا فونت بولد باشد یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | مقدار یا تنظیم ارتفاع فونت یک بخش. **float.NaN** به معنای عدم تعریف ارتفاع و ارث‌بری از Master است. فقط خواندنی/نوشتنی Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تعیین می‌کند آیا فونت ایتالیک باشد یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | مقدار یا تنظیم نوع زیرخط متن. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای هایلایت متن را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | مقدار یا تنظیم پیوند هیپرتکست تعریف‌شده برای کلیک ماوس. فقط خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدیر پیوندهای هیپرتکست. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | مقدار یا تنظیم پیوند هیپرتکست تعریف‌شده برای حرکت ماوس بر روی آن. فقط خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن ارث می‌برد. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن ارث می‌برد. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | مقدار یا تنظیم حداقل اندازهٔ فونت که کرنینگ باید فعال شود. **float.NaN** به معنای عدم تعریف مقدار و ارث‌بری از Master است. فقط خواندنی/نوشتنی Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تعیین می‌کند آیا اعداد باید چینش عمودی متن خاص زبان‌های شرقی را نادیده بگیرند یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | مقدار یا تنظیم Id یک زبان بررسی املایی. برای چک کردن املاء و دستور استفاده می‌شود. فقط خواندنی/نوشتنی String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | مقدار یا تنظیم اطلاعات فونت لاتین. مقدار Null به معنای عدم تعریف فونت و ارث‌بری از Master است. فقط خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای حاشیه‌کشی متن را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تعیین می‌کند آیا متن نباید بازبینی شود یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | تعیین می‌کند آیا برچسب هوشمند باید پاک شود یا نه. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | مقدار یا تنظیم میزان افزایش فاصله بین حروف. **float.NaN** به معنای عدم تعریف مقدار و ارث‌بری از Master است. فقط خواندنی/نوشتنی Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | دریافت یا تنظیم مقدار نشان‌دهنده فعال بودن بررسی املایی برای بخش متن. وقتی این ویژگی به false تنظیم شود، بررسی‌های املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | مقدار یا تنظیم نوع خط‌خطی (Strikethrough) متن. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | مقدار یا تنظیم اطلاعات فونت نمادین. مقدار Null به معنای عدم تعریف فونت و ارث‌بری از Master است. فقط خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | مقدار یا تنظیم نوع حروف بزرگ/کوچک متن. ارث‌بری اعمال نمی‌شود. فقط خواندنی/نوشتنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat مورد استفاده برای حاشیه‌کشی خط زیرخط را بازمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط خواندنی [`ILineFormat`](../ilineformat). |

## متدها

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص‌شده مقایسه می‌کند. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | داده‌های قالب‌بندی بخش مؤثر را با در نظر گرفتن ارث‌بری دریافت می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### یادداشت‌ها

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاصی استفاده می‌شود. به این معنی که هنگام دریافت مقادیر، ارث‌بری اعمال نمی‌شود؛ بنابراین در اکثر موارد مقدار «تعریف‌نشده» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی به‌همراه مقادیر ارث‌برده، باید از متد [`GetEffective`](./geteffective) استفاده کنید که یک نمونهٔ [`IPortionFormatEffectiveData`](../iportionformateffectivedata) را برمی‌گرداند.

### مثال‌ها

مثال‌های زیر نشان می‌دهند چگونه فونت لاتین را به بخش یک پاراگراف در ارائهٔ PowerPoint اختصاص دهید.

```csharp
[C#]
//یک شی ارائه (Presentation) ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides از این شناسه‌های خاص استفاده می‌کند (مشابه آن‌هایی که در PowerPoint به کار می‌روند):
// +mn-lt - قلم بدن لاتین (قلم لاتین کوچک)
// +mj-lt -قلم عنوان لاتین (قلم لاتین بزرگ)
// +mn-ea - قلم بدن شرق آسیایی (قلم شرق آسیایی کوچک)
// +mj-ea - قلم بدن شرق آسیایی (قلم شرق آسیایی کوچک)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### مراجع مرتبط

* کلاس [BasePortionFormat](../baseportionformat)
* اینترفیس [IPortionFormat](../iportionformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->