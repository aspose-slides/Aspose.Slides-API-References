---
title: IParagraphFormat
second_title: Aspose.Sildes برای مرجع API .NET
description: این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. بر خلاف IParagraphFormatEffectiveData./iparagraphformateffectivedata، همه ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 6610
url: /fa/aspose.slides/iparagraphformat/
---
## IParagraphFormat رابط

این کلاس شامل ویژگی‌های قالب‌بندی پاراگراف است. برخلاف [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public interface IParagraphFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | مقدار یا تنظیم می‌کند هم‌راستایی متن در یک پاراگراف بدون ارث‌بری. قابلیت خواندن/نوشتن [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | قالب گلوله‌ای پاراگراف را برمی‌گرداند. فقط خواندنی [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | قالب پیش‌فرض بخش یک پاراگراف را برمی‌گرداند. بدون اعمال ارث‌بری. فقط خواندنی [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | مقدار یا تنظیم می‌کند اندازه پیش‌فرض تب بدون ارث‌بری. قابلیت خواندن/نوشتن Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | مقدار یا تنظیم می‌کند عمق پاراگراف. مقدار 0 به معنی مقدار نامتعین است. قابلیت خواندن/نوشتن Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | تعیین می‌کند آیا شکست خط آسیای شرقی در یک پاراگراف استفاده می‌شود. بدون اعمال ارث‌بری. قابلیت خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | مقدار یا تنظیم می‌کند هم‌راستایی قلم در یک پاراگراف بدون ارث‌بری. قابلیت خواندن/نوشتن [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | تعیین می‌کند آیا نقطه‌گذاری آویزان در یک پاراگراف استفاده می‌شود. بدون اعمال ارث‌بری. قابلیت خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | مقدار یا تنظیم می‌کند تورفتگی خط اول/تورفتگی آویزان پاراگراف بدون ارث‌بری. تورفتگی آویزان می‌تواند با مقادیر منفی تعیین شود. قابلیت خواندن/نوشتن Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | تعیین می‌کند آیا شکست خط لاتین در یک پاراگراف استفاده می‌شود. بدون اعمال ارث‌بری. قابلیت خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | مقدار یا تنظیم می‌کند حاشیهٔ چپ در یک پاراگراف بدون ارث‌بری. قابلیت خواندن/نوشتن Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | مقدار یا تنظیم می‌کند حاشیهٔ راست در یک پاراگراف بدون ارث‌بری. قابلیت خواندن/نوشتن Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | تعیین می‌کند آیا نوشتار از راست به چپ در یک پاراگراف استفاده می‌شود. بدون اعمال ارث‌بری. قابلیت خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | مقدار یا تنظیم می‌کند فاصله پس از خط آخر در یک پاراگراف بدون ارث‌بری. مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به واحد نقطه تعیین می‌کند. قابلیت خواندن/نوشتن Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | مقدار یا تنظیم می‌کند فاصله پیش از خط اول در یک پاراگراف بدون ارث‌بری. مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را به واحد نقطه تعیین می‌کند. قابلیت خواندن/نوشتن Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | مقدار یا تنظیم می‌کند فاصله بین خطوط پایه در یک پاراگراف. مقدار مثبت به معنی درصد، منفی به معنی اندازه به نقطه است. بدون اعمال ارث‌بری. قابلیت خواندن/نوشتن Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | تب‌های یک پاراگراف را برمی‌گرداند. بدون اعمال ارث‌بری. فقط خواندنی [`ITabCollection`](../itabcollection). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال ارث‌بری دریافت می‌کند. |

### توضیحات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این بدان معنی است که هنگام دریافت مقادیر، هیچ ارث‌بری اعمال نمی‌شود، بنابراین در بیشتر موارد مقادیر "نامتعین" دریافت می‌کنید.

برای دریافت مقادیر پارامترهای قالب‌بندی مؤثر شامل ارث‌بری، باید از متد [`GetEffective`](./geteffective) استفاده کنید که یک نمونهٔ [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) را بر می‌گرداند.

### موارد مرتبط

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->