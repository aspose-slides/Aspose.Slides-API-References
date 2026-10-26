---
title: BasePortionFormat
second_title: Aspose.Sildes برای .NET - مرجع API
description: ویژگی‌های عمومی فرمت‌بندی بخش متن.
type: docs
weight: 970
url: /fa/aspose.slides/baseportionformat/
---
## کلاس BasePortionFormat

ویژگی‌های فرمت‌بندی بخش متن عمومی.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | مقدار Id یک زبان جایگزین را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازه می‌دهد تا رابط پایه IPresentationComponent را دریافت کند. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | اطلاعات قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. مقدار Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | اطلاعات قلم آسیای شرقی را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | خواص EffectFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | متن فوقانی یا زیرنویس را برمی‌گرداند یا تنظیم می‌کند. مقدار از -100٪ (زیرنویس) تا 100٪ (فوق‌نویس). **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | خواص FillFormat متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | مشخص می‌کند آیا قلم بولد (ضخیم) است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | ارتفاع قلم یک بخش را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که ارتفاع تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | مشخص می‌کند آیا قلم ایتالیک است یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | نوع زیرخط متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | رنگ استفاده‌شده برای هایلایت متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای خواص FillFormat خود است یا از خواص FillFormat متن ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | مشخص می‌کند آیا سبک زیرخط دارای خواص LineFormat خود است یا از خواص LineFormat متن ارث می‌برد. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | حداقل اندازه قلم را که کرنینگ باید فعال شود، برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | مشخص می‌کند آیا اعداد باید چینش عمودی متن مخصوص زبان‌های شرقی را نادیده بگیرند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Id یک زبان اصلاح‌نویسی را برمی‌گرداند یا تنظیم می‌کند. برای بررسی املاء و دستور زبان استفاده می‌شود. خواندنی/نوشتنی String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | اطلاعات قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | خواص LineFormat برای پیرامون‌گذاری متن را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | مشخص می‌کند آیا ارتفاع متن باید نرمال‌سازی شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | مشخص می‌کند آیا متن نباید تصحیح شود یا خیر. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | افزایش فاصله بین کاراکترها را برمی‌گرداند یا تنظیم می‌کند. **float.NaN** به این معنی است که مقدار تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | مقداری را دریافت یا تنظیم می‌کند که نشان دهنده فعال بودن بررسی املای بخش متن است. وقتی این ویژگی به false تنظیم شود، بررسی املای عناصر متن سرکوب می‌شود. وقتی به true تنظیم شود، بررسی املای مجاز است. مقدار پیش‌فرض `false` است. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | نوع خط خورده متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | اطلاعات قلم نمادین را برمی‌گرداند یا تنظیم می‌کند. Null به این معنی است که قلم تعریف نشده و باید از Master به ارث برده شود. خواندنی/نوشتنی [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | نوع بزرگ‌نویسی متن را برمی‌گرداند یا تنظیم می‌کند. هیچ ارث‌بری اعمال نمی‌شود. خواندنی/نوشتنی [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | خواص FillFormat خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | خواص LineFormat استفاده‌شده برای پیرامون‌گذاری خط زیرخط را برمی‌گرداند. هیچ ارث‌بری اعمال نمی‌شود. فقط-خواندنی [`ILineFormat`](../ilineformat). |

## متدها

| نام | توضیح |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | با object مشخص‌شده مقایسه می‌کند. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | کد هش را برمی‌گرداند. |

### مشاهده نیز

* کلاس [PVIObject](../pviobject)
* رابط [IBasePortionFormat](../ibaseportionformat)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->