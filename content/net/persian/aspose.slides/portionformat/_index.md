---
title: PortionFormat
second_title: Aspose.Sildes برای .NET – مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata، تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 9490
url: /fa/aspose.slides/portionformat/
---
## PortionFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. بر خلاف [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | مقدار یا تنظیم Id یک زبان جایگزین. خواندنی/نوشتنی String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | مقدار یا تنظیم شناسهٔ بوکمارک. خواندنی/نوشتنی String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | مقدار یا تنظیم اطلاعات قلم اسکریپت پیچیده. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | مقدار یا تنظیم اطلاعات قلم شرق آسیا. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | مقدار یا تنظیم متن نمای فوقانی یا زیرنویس. مقدار بین -100٪ (زیرنویس) تا 100٪ (نمای فوقانی). **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | تعیین می‌کند آیا قلم بولد است یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | مقدار یا تنظیم ارتفاع قلم یک بخش. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | تعیین می‌کند آیا قلم ایتالیک است یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | مقدار یا تنظیم نوع زیرخط متن. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ استفاده‌شده برای هایلایت متن را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | مقدار یا تنظیم لینک تعریف‌شده برای کلیک موس. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | مدیر لینک‌ها. فقط-خواندنی [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | مقدار یا تنظیم لینک تعریف‌شده برای عبور موس. خواندنی/نوشتنی [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای خصوصیات FillFormat خود است یا از خصوصیات FillFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند آیا سبک زیرخط دارای خصوصیات LineFormat خود است یا از خصوصیات LineFormat متن به ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | مقدار یا تنظیم حداقل اندازه قلم که برای آن کرنینگ فعال می‌شود. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | تعیین می‌کند آیا اعداد باید چیدمان عمودی متن خاص زبان‌های شرقی را نادیده بگیرند یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | مقدار یا تنظیم Id یک زبان proofing. برای بررسی املا و دستور زبان استفاده می‌شود. خواندنی/نوشتنی String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | مقدار یا تنظیم اطلاعات قلم لاتین. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای محدوده متن را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | تعیین می‌کند آیا ارتفاع متن باید نرمال شود یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | تعیین می‌کند آیا متن نباید proof شود یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | تعیین می‌کند آیا برچسب هوشمند باید پاک شود یا خیر. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | مقدار یا تنظیم افزایش فاصله بین کاراکترها. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | دریافت یا تنظیم مقداری که نشان می‌دهد آیا بررسی املای متن فعال است یا خیر. وقتی این ویژگی به false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املای مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | مقدار یا تنظیم نوع خط‌خورده متن. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | مقدار یا تنظیم اطلاعات قلم نمادین. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برسد. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | مقدار یا تنظیم نوع حروف بزرگ/کوچک متن. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. خواندنی/نوشتنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat مورد استفاده برای محدوده خط زیرخط را برمی‌گرداند. هیچ ارث‌بخشی‌ای اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | مقایسه با شیء مشخص‌شده. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | داده‌های قالب‌بندی مؤثر بخش را با اعمال ارث‌بخشی دریافت می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### توضیحات

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر، هیچ ارث‌بخشی‌ای اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر «تعریف نشده» دریافت می‌کنید.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بسته، باید از متد [`GetEffective`](./geteffective) استفاده کنید که یک نمونهٔ [`IPortionFormatEffectiveData`](../iportionformateffectivedata) را برمی‌گرداند.

### مثال‌ها

مثال‌های زیر نشان می‌دهند چگونه قلم لاتین را به بخش یک پاراگراف در ارائهٔ PowerPoint اختصاص دهید.

```csharp
[C#]
//یک شیء ارائه ایجاد کنید که نمایانگر یک فایل ارائه است
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides از این شناسه‌های خاص استفاده می‌کند (مشابه آنچه در PowerPoint استفاده می‌شود):
// +mn-lt - قلم بدنه لاتین (قلم لاتین فرعی)
// +mj-lt - قلم عنوان لاتین (قلم لاتین اصلی)
// +mn-ea - قلم بدنه آسیایی شرقی (قلم آسیای شرقی فرعی)
// +mj-ea - قلم بدنه آسیایی شرقی (قلم آسیای شرقی فرعی)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### موارد مرتبط

* کلاس [BasePortionFormat](../baseportionformat)
* واسط [IPortionFormat](../iportionformat)
* فضای‌نامی [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->