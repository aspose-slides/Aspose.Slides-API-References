---
title: Hyperlink
second_title: مرجع API Aspose.Sildes برای .NET
description: یک پیوند را نمایندگی می‌کند.
type: docs
weight: 5120
url: /fa/aspose.slides/hyperlink/
---
## کلاس Hyperlink

یک پیوند را نشان می‌دهد.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## سازنده‌ها

| نام | توضیحات |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | یک نمونه از پیوندی را می‌سازد که به اسلاید خاصی اشاره دارد. توجه: پیوند ساخته‌شده باید به یک شیء از همان ارائه اختصاص داده شود، در غیر این صورت لینک به عنوان NoAction ذخیره می‌شود. |
| [Hyperlink](hyperlink#constructor_2)(string) | یک نمونه از پیوند را می‌سازد. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | یک نمونه از پیوند را با استفاده از پیوند دیگری به عنوان منبع می‌سازد و ویژگی‌های ثانویه را بازنویسی می‌کند. |

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | یک پیوند را برمی‌گرداند که نمایش را پایان می‌دهد. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | یک پیوند را برمی‌گرداند که به اولین اسلاید ارائه اشاره دارد. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | یک پیوند را برمی‌گرداند که به آخرین اسلاید ارائه اشاره دارد. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | یک پیوند را برمی‌گرداند که به آخرین اسلاید مشاهده‌شده اشاره دارد. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | یک پیوند مخصوص "play mediafile" را برمی‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | یک پیوند به اسلاید بعدی را برمی‌گرداند. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | یک پیوند مخصوص "do nothing" را برمی‌گرداند. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | یک پیوند به اسلاید قبلی را برمی‌گرداند. فقط-خواندنی [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | نوع اقدام Hyperlink را برمی‌گرداند. فقط-خواندنی [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | اجازۀ دسترسی به رابط پایه IPresentationComponent را می‌دهد. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | منبع رنگ پیوند را نشان می‌دهد - یا سبک‌ها یا قالب بخش. خواندن/نوشتن [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | آدرس URL خارجی را مشخص می‌کند. فقط-خواندنی String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون توجه به محتوای واقعی بخش. PowerPoint برای لینک‌ها و متن متناظر آن‌ها در یک بخش رفتار خاصی دارد. این امکان را می‌دهد که متن پیوند را به صورت یک URL معتبر ایجاد کنید که متفاوت از آدرس واقعی لینک باشد. در این حالت، هنگام مشاهده لینک در پنجره ویرایش، متن آن به منظور تطبیق با بخش متن تغییر می‌یابد. این ویژگی مقدار اصلی پیوند را نمایان می‌کند. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | مشخص می‌کند که آیا پیوند هنگام کلیک برجسته شود یا نه. خواندن/نوشتن Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | مشخص می‌کند که آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده‌شده اضافه شود یا خیر. خواندن/نوشتن Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | صوت پخش‌شده توسط پیوند را نشان می‌دهد. خواندن/نوشتن [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | مشخص می‌کند که آیا صوت هنگام کلیک بر پیوند متوقف شود. خواندن/نوشتن Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | قاب داخل چارچوب HTML والد را برای هدف پیوند والد که وجود دارد برمی‌گرداند. خواندن/نوشتن String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | اگر Hyperlink به اسلاید خاصی هدف داشته باشد، آن اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | رشته‌ای را برمی‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. خواندن/نوشتن String. |

## متدها

| نام | توضیحات |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | مشخص می‌کند که آیا دو نمونه Hyperlink برابر هستند یا نه. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | مشخص می‌کند که آیا دو نمونه Hyperlink برابر هستند یا نه. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | به عنوان تابع هش برای یک نوع خاص عمل می‌کند و برای الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | دو پیوند را برای برابری تست می‌کند. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | دو پیوند را برای نابرابری تست می‌کند. |

### موارد مرتبط

* کلاس [PVIObject](../pviobject)
* رابط [IHyperlink](../ihyperlink)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجتمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->