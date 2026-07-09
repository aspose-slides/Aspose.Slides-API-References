---
title: Hyperlink
second_title: مرجع API Aspose.Sildes برای .NET
description: یک پیوند را نمایان می‌کند.
type: docs
weight: 5120
url: /fa/aspose.slides/hyperlink/
---
## Hyperlink کلاس

نمایشگر یک پیوند.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | نمونه‌ای از پیوند را می‌سازد که به اسلاید خاصی اشاره دارد. توجه: پیوند ایجاد شده باید به شیء‌ای از همان ارائه اختصاص یابد، در غیر این صورت لینک به‌عنوان NoAction ذخیره می‌شود. |
| [Hyperlink](hyperlink#constructor_2)(string) | نمونه‌ای از پیوند را می‌سازد. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | نمونه‌ای از پیوند را با استفاده از پیوند دیگر به عنوان منبع، ویژگی‌های ثانویه را بازنویسی می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | یک پیوند که نمایش را خاتمه می‌دهد را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | یک پیوند به اسلاید اول ارائه را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | یک پیوند به اسلاید آخر ارائه را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | یک پیوند به آخرین اسلاید دیده شده را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | یک پیوند ویژه «play mediafile» را برمی‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | یک پیوند به اسلاید بعدی را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | یک پیوند ویژه «do nothing» را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | یک پیوند به اسلاید قبلی را برمی‌گرداند. فقط‌خواندنی [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | نوع عملیات پیوند را برمی‌گرداند. فقط‌خواندنی [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | از اینترفیس پایه IPresentationComponent می‌توان دریافت کرد. فقط‌خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | منبع رنگ پیوند را نشان می‌دهد - یا سبک‌ها یا قالب‌بندی بخش. خواندن/نوشتن [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | آدرس URL خارجی را مشخص می‌کند. فقط‌خواندنی String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون توجه به محتوای واقعی بخش. PowerPoint رفتار خاصی برای پیوندها و متن مربوط به آن‌ها در یک بخش دارد. این امکان را می‌دهد که متن پیوند را به شکل URL معتبر ایجاد کنید، که متفاوت از آدرس واقعی پیوند است. در این حالت، هنگام مشاهده پیوند در پنجره ویرایش، به متن بخش تغییر می‌کند. این ویژگی مقدار اصلی پیوند را نمایان می‌کند. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | مشخص می‌کند آیا پیوند هنگام کلیک برجسته شود یا نه. خواندن/نوشتن Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | مشخص می‌کند آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا نه. خواندن/نوشتن Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | صداهای پخش‌شده توسط پیوند را نشان می‌دهد. خواندن/نوشتن [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | مشخص می‌کند آیا صدا باید هنگام کلیک بر پیوند متوقف شود. خواندن/نوشتن Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | فریم داخل مجموعه فریم‌های HTML والد برای هدف پیوند والد را برمی‌گرداند. خواندن/نوشتن String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | اگر پیوند به اسلاید خاصی هدف داشته باشد، آن اسلاید را برمی‌گرداند. فقط‌خواندنی [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | رشته‌ای را که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود، برمی‌گرداند. خواندن/نوشتن String. |

## متدها

| نام | توضیح |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | تعیین می‌کند که آیا دو نمونه Hyperlink برابر هستند یا نه. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | تعیین می‌کند که آیا دو نمونه Hyperlink برابر هستند یا نه. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | به عنوان تابع هش برای یک نوع خاص عمل می‌کند که برای الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | دو پیوند را برای برابری آزمایش می‌کند. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | دو پیوند را برای نابرابری آزمایش می‌کند. |

### مراجع

* کلاس [PVIObject](../pviobject)
* اینترفیس [IHyperlink](../ihyperlink)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->