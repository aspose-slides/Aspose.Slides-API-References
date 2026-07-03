---
title: IBasePortionFormat
second_title: Aspose.Sildes برای .NET مرجع API
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. برخلاف IPortionFormatEffectiveData./iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 5310
url: /fa/aspose.slides/ibaseportionformat/
---
## رابط IBasePortionFormat

این کلاس شامل ویژگی‌های قالب‌بندی بخش متن است. متفاوت از [`IPortionFormatEffectiveData`](../iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public interface IBasePortionFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | مقدار Id یک زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. Read/write String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | اطلاعات فونت اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که فونت تعریف نشده و باید از Master به ارث برسد. Read/write [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | اطلاعات فونت شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که فونت تعریف نشده و باید از Master به ارث برسد. Read/write [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | متن به صورت سوپر اسکریپت یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار بین -100% (زیرنویس) تا 100% (سوپر اسکریپت) است. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. Read/write Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | تعیین می‌کند که فونت بولد باشد یا نه. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | ارتفاع فونت یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برسد. Read/write Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | تعیین می‌کند که فونت ایتالیک باشد یا نه. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | نوع خط زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | رنگ استفاده شده برای هایلایت متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | تعیین می‌کند که سبک زیرخط دارای FillFormat خود باشد یا از FillFormat متن به ارث ببرد. Read/write [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | تعیین می‌کند که سبک زیرخط دارای LineFormat خود باشد یا از LineFormat متن به ارث ببرد. Read/write [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه فونت را که کرنینگ برای آن فعال شود، برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. Read/write Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | تعیین می‌کند که اعداد باید چیدمان عمودی مخصوص زبان‌های شرقی را نادیده بگیرند یا نه. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Id یک زبان اصلاحی را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املایی و گرامری استفاده می‌شود. Read/write String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | اطلاعات فونت لاتین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که فونت تعریف نشده و باید از Master به ارث برسد. Read/write [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای خطوط مرزبندی متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | تعیین می‌کند که ارتفاع متن نرمال شود یا نه. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | تعیین می‌کند که متن تحت بررسی املایی قرار نگیرد یا نه. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | افزایش فاصله بین حروف را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برسد. Read/write Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | تعیین می‌کند که آیا بررسی املایی برای این بخش متن فعال باشد یا نه. وقتی این ویژگی به false تنظیم شود، بررسی املایی برای عناصر متن غیرفعال می‌شود. وقتی به true تنظیم شود، بررسی املایی مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | نوع خط خط‌خطی (strikethrough) متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | اطلاعات فونت نمادین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که فونت تعریف نشده و باید از Master به ارث برسد. Read/write [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | نوع بزرگ‌نویسی متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. Read/write [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده‌شده برای مرزبندی خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. Read-only [`ILineFormat`](../ilineformat). |

### نکات

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. به این معنی است که هنگام دریافت مقادیر هیچ ارث‌بری اعمال نمی‌شود و در بیشتر موارد مقادیر به معنای «تعریف‌نشده» بازگردانده می‌شود.

برای دریافت مقادیر موثر پارامترهای قالب‌بندی شامل مقادیری که به ارث رسیده‌اند، باید از روش [`GetEffective`](../iportionformat/geteffective) استفاده کنید که یک نمونه [`IPortionFormatEffectiveData`](../iportionformateffectivedata) بازمی‌گرداند.

### موارد مرتبط

* فضای نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->