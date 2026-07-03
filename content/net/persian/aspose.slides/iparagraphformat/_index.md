---
title: IParagraphFormat
second_title: Aspose.Sildes برای .NET مرجع API
description: این کلاس ویژگی‌های قالب‌بندی پاراگراف را شامل می‌شود. برخلاف IParagraphFormatEffectiveData./iparagraphformateffectivedata تمام ویژگی‌های این کلاس قابل نوشتن هستند.
type: docs
weight: 6590
url: /fa/aspose.slides/iparagraphformat/
---
## IParagraphFormat رابط

این کلاس ویژگی‌های قالب‌بندی پاراگراف را شامل می‌شود. برخلاف [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)، تمام ویژگی‌های این کلاس قابل نوشتن هستند.

```csharp
public interface IParagraphFormat
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | مقدار یا تنظیم تراز متن در یک پاراگراف بدون وراثت را برمی‌گرداند. قابل خواندن/نوشتن [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | قالب گلوله پاراگراف را برمی‌گرداند. فقط-خواندنی [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | قالب بخش پیش‌فرض یک پاراگراف را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | اندازه پیش‌فرض تبولیشن را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | عمق پاراگراف را برمی‌گرداند یا تنظیم می‌کند. مقدار 0 به معنی مقدار تعریف‌نشده است. قابل خواندن/نوشتن Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | تعیین می‌کند که آیا شکست خط شرق آسیا در پاراگراف استفاده می‌شود یا نه. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | تراز قلم در یک پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | تعیین می‌کند که آیا نقطه‌گذاری آویزان در پاراگراف استفاده می‌شود یا نه. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | تورفتگی خط اول/تورفتگی آویزان پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. تورفتگی آویزان می‌تواند با مقادیر منفی تعریف شود. قابل خواندن/نوشتن Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | تعیین می‌کند که آیا شکست خط لاتین در پاراگراف استفاده می‌شود یا نه. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | حاشیه چپ در یک پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | حاشیه راست در یک پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | تعیین می‌کند که آیا نوشتار راست به چپ در پاراگراف استفاده می‌شود یا نه. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | مقدار فضای پس از آخرین خط در یک پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را بر حسب پوینت مشخص می‌کند. قابل خواندن/نوشتن Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | مقدار فضای قبل از اولین خط در یک پاراگراف را بدون وراثت برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت درصد اندازه قلم را که فضای سفید باید باشد مشخص می‌کند. مقدار منفی اندازه فضای سفید را بر حسب پوینت مشخص می‌کند. قابل خواندن/نوشتن Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | مقدار فضای بین خطوط پایه در یک پاراگراف را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت به معنای درصد، مقدار منفی به معنای اندازه بر حسب پوینت است. وراثت اعمال نمی‌شود. قابل خواندن/نوشتن Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | تبولیشن‌های یک پاراگراف را برمی‌گرداند. وراثت اعمال نمی‌شود. فقط-خواندنی [`ITabCollection`](../itabcollection). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | داده‌های قالب‌بندی مؤثر پاراگراف را با اعمال وراثت دریافت می‌کند. |

### توضیحات

این کلاس برای بازگرداندن و دستکاری ویژگی‌های قالب‌بندی پاراگراف تعریف‌شده برای پاراگراف خاص استفاده می‌شود. این به این معنی است که هنگام دریافت مقادیر وراثت اعمال نمی‌شود، بنابراین در اکثر موارد مقادیر "تعریف‌نشده" دریافت می‌کنید.

برای دریافت مقادیر مؤثر پارامترهای قالب‌بندی شامل وراثت، لازم است از متد [`GetEffective`](./geteffective) استفاده کنید که یک نمونهٔ [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) را برمی‌گرداند.

### مطالعه بیشتر

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->