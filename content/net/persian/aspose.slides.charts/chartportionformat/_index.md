---
title: ChartPortionFormat
second_title: مرجع API Aspose.Sildes برای .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی بخش نمودار است که در نمودارها استفاده می‌شود. بر خلاف IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 1430
url: /fa/aspose.slides.charts/chartportionformat/
---
## کلاس ChartPortionFormat

این کلاس شامل ویژگی‌های قالب‌بندی بخش نمودار است که در نمودارها استفاده می‌شود. بر خلاف [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | شناسه‌ی زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط‌خواندنی [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | ویژگی‌های EffectFormat متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن فوق‌کرستی یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100% (زیرنویس) تا 100% (فوق‌کرستی). **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | ویژگی‌های FillFormat متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | مشخص می‌کند آیا قلم پررنگ است یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | مشخص می‌کند آیا قلم ایتالیک است یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ مورد استفاده برای هایلایت متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های FillFormat خود است یا آن را از ویژگی‌های FillFormat متن به ارث می‌برد. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای ویژگی‌های LineFormat خود است یا آن را از ویژگی‌های LineFormat متن به ارث می‌برد. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را برمی‌گرداند یا تنظیم می‌کند که برای آن کرنینگ باید فعال شود. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | مشخص می‌کند آیا اعداد باید چیدمان عمودی متن مربوط به زبان‌های شرقی را نادیده بگیرند یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | شناسه‌ی یک زبان اصلاح‌کننده را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و گرامر استفاده می‌شود. قابل خواندن/نوشتن String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | ویژگی‌های LineFormat برای حاشیه‌کشی متن را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | مشخص می‌کند آیا ارتفاع متن باید نرمال‌سازی شود یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | مشخص می‌کند آیا متن نباید اصلاح شود یا خیر. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقدار نشان‌دهنده اینکه آیا املاء برای بخش متن فعال است یا خیر را می‌گیرد یا تنظیم می‌کند. وقتی این ویژگی به false تنظیم شود، بررسی املاء برای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، املاء مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط‌خورده متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. قابل خواندن/نوشتن [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع حروف بزرگ/کوچک متن را برمی‌گرداند یا تنظیم می‌کند. ارث‌بری اعمال نمی‌شود. قابل خواندن/نوشتن [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | ویژگی‌های FillFormat خط زیرخط را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | ویژگی‌های LineFormat استفاده شده برای حاشیه‌کشی خط زیرخط را برمی‌گرداند. ارث‌بری اعمال نمی‌شود. فقط‌خواندنی [`ILineFormat`](../../aspose.slides/ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با شیء مشخص مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### ملاحظات

این کلاس برای برگرداندن و دستکاری ویژگی‌های قالب‌بندی بخش متن تعریف‌شده برای بخش خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر ارث‌بری اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر «تعریف نشده» دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل ارث‌بری، باید از روش [`GetEffective`](../../aspose.slides/portionformat/geteffective) استفاده کنید که یک نمونهٔ [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) را برمی‌گرداند.

### موارد مرتبط

* کلاس [BasePortionFormat](../../aspose.slides/baseportionformat)
* اینترفیس [IChartPortionFormat](../ichartportionformat)
* فضای‌نام [Aspose.Slides.Charts](../../aspose.slides.charts)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->