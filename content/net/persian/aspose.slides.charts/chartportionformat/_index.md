---
title: ChartPortionFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی قسمت نمودار است که در نمودارها استفاده می‌شود. برخلاف IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 1440
url: /fa/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat کلاس

این کلاس شامل ویژگی‌های قالب‌بندی قسمت نمودار است که در نمودارها استفاده می‌شود. برخلاف [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## خواص

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | مقدار Id یک زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازه می‌دهد تا رابط IPresentationComponent پایه دریافت شود. فقط-خواندنی [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنی این است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم شرق آسیایی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنی این است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن بالانویس یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (بالانویس). **float.NaN** به معنی این است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | مشخص می‌کند آیا قلم بولد است یا خیر. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک قسمت را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی این است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | مشخص می‌کند آیا قلم ایتالیک است یا خیر. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای هایلایت متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | مشخص می‌کند آیا سبک زیرخط ویژگی‌های FillFormat خود را دارد یا از ویژگی‌های FillFormat متن ارث می‌برد. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | مشخص می‌کند آیا سبک زیرخط ویژگی‌های LineFormat خود را دارد یا از ویژگی‌های LineFormat متن ارث می‌برد. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم که برای آن کرنینگ فعال شود را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی این است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | مشخص می‌کند آیا اعداد باید چیدمان عمودی متن مخصوص زبان‌های شرق آسیایی را نادیده بگیرند یا خیر. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Id یک زبان اصلاحی را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املا و گرامر استفاده می‌شود. قابل خواندن/نوشتن String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنی این است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای خطوط دور متن را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | مشخص می‌کند آیا ارتفاع متن باید نرمال شود یا خیر. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | مشخص می‌کند آیا متن نباید اصلاح شود یا خیر. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایش فاصله بین حروف را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به معنی این است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقداری که نشان می‌دهد آیا بررسی املای متن فعال باشد یا نه را دریافت یا تنظیم می‌کند. وقتی این ویژگی به false تنظیم شود، بررسی املا برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املا مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به معنی این است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. هیچ وراثتی اعمال نمی‌شود. قابل خواندن/نوشتن [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده‌شده برای دور خط زیرخط را برمی‌گرداند. هیچ وراثتی اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص شده مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### توضیحات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی قسمت متن که برای بخش خاص تعریف شده‌اند، استفاده می‌شود. این به این معناست که هنگام دریافت مقادیر هیچ وراثتی اعمال نمی‌شود، بنابراین در اکثر موارد مقادیری دریافت می‌کنید که به معنی «تعریف‌نشده» است.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، لازم است از متد [`GetEffective`](../../aspose.slides/portionformat/geteffective) استفاده کنید که یک نمونه [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) را برمی‌گرداند.

### موارد مرتبط

* کلاس [BasePortionFormat](../../aspose.slides/baseportionformat)
* رابط [IChartPortionFormat](../ichartportionformat)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* مجموعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->