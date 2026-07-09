---
title: PortionFormat
second_title: Aspose.Sildes برای مرجع API .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 9490
url: /fa/aspose.slides/portionformat/
---
## PortionFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [PortionFormat](portionformat)() | یک نمونه جدید از کلاس [`PortionFormat`](../portionformat) را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | شناسه (Id) زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی برای دریافت رابط پایه IPresentationComponent را فراهم می‌کند. فقط خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | شناسهٔ نشانک را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن بالانس یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (بالانس) است. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | مشخص می‌کند آیا قلم بولد است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | مشخص می‌کند آیا قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ استفاده شده برای برجسته‌سازی متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | پیوندهای تعریف شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدیر پیوندها. فقط خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | پیوند تعریف شده برای مرور ماوس را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا از ویژگی‌های FillFormat متن ارث می‌برد. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا از ویژگی‌های LineFormat متن ارث می‌برد. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم که کرنینگ باید فعال شود را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | مشخص می‌کند آیا اعداد باید چینش عمودی متن خاص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | شناسهٔ زبان تصحیح (proofing) را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املایی و دستوری استفاده می‌شود. خواندن/نوشتن String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای مرزبندی متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | مشخص می‌کند آیا ارتفاع متن باید نرمال شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | مشخص می‌کند آیا متن نباید تصحیح شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | مشخص می‌کند آیا برچسب هوشمند باید پاک شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا بررسی املایی برای بخش متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندن/نوشتن [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندن/نوشتن [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده شده برای مرزبندی خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط خواندنی [`ILineFormat`](../ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص مقایسه می‌کند. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | داده‌های قالب‌بندی مؤثر بخش را با اعمال ارث‌بری دریافت می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### توضیحات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف شده برای بخش خاص استفاده می‌شود. این بدان معناست که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر "تعریف نشده" دریافت می‌کنید.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بری، باید از متد [`GetEffective`](./geteffective) استفاده کنید که یک نمونهٔ [`IPortionFormatEffectiveData`](../iportionformateffectivedata) را برمی‌گرداند.

### مثال‌ها

مثال‌های زیر نشان می‌دهند چگونه قلم لاتین را به بخشی از یک Paragraph در ارائه PowerPoint اختصاص دهید.

```csharp
[C#]
//یک شی Presentation که نمایانگر یک فایل ارائه است را نمونه‌سازی می‌کند
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides از این شناسه‌های ویژه استفاده می‌کند (مشابه شناسه‌های مورد استفاده در PowerPoint):
// +mn-lt - قلم بدنه لاتین (قلم لاتین ثانوی)
// +mj-lt -قلم سرعنوان لاتین (قلم لاتین اصلی)
// +mn-ea - قلم بدنه آسیای شرقی (قلم آسیای شرقی ثانوی)
// +mj-ea - قلم بدنه آسیای شرقی (قلم آسیای شرقی ثانوی)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### موارد مرتبط

* کلاس [BasePortionFormat](../baseportionformat)
* رابط [IPortionFormat](../iportionformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->