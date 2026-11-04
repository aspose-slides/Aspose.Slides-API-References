---
title: Hyperlink
second_title: Aspose.Sildes برای .NET مرجع API
description: یک پیوند را نشان می‌دهد.
type: docs
weight: 5140
url: /fa/aspose.slides/hyperlink/
---
## کلاس Hyperlink

یک پیوند را نشان می‌دهد.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | یک نمونه از Hyperlink را ایجاد می‌کند که به اسلاید خاصی اشاره دارد. توجه: پیوند ایجاد شده باید به یک شیء از همان ارائه اختصاص یابد، در غیر این صورت لینک به‌عنوان NoAction ذخیره می‌شود. |
| [Hyperlink](hyperlink#constructor_2)(string) | یک نمونه از Hyperlink را ایجاد می‌کند. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | یک نمونه از Hyperlink را با استفاده از یک Hyperlink دیگر به‌عنوان منبع ایجاد می‌کند و ویژگی‌های ثانویه را بازنویسی می‌کند. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | یک پیوند را بر می‌گرداند که نمایش را پایان می‌دهد. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | یک پیوند به اسلاید اولین ارائه را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | یک پیوند به اسلاید آخرین ارائه را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | یک پیوند به آخرین اسلاید مشاهده‌شده را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | یک پیوند ویژه "play mediafile" را بر می‌گرداند. در AudioFrame و VideoFrame استفاده می‌شود. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | یک پیوند به اسلاید بعدی را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | یک پیوند ویژه "do nothing" را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | یک پیوند به اسلاید قبلی را بر می‌گرداند. فقط خواندنی [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | نوع عمل Hyperlink را بر می‌گرداند. فقط خواندنی [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | منبع رنگ پیوند را نشان می‌دهد - یا استایل‌ها یا قالب‌بندی بخش. قابل خواندن/نوشتن [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | URL خارجی را مشخص می‌کند. فقط خواندنی String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | یک پیوند را نشان می‌دهد که برای این بخش تنظیم شده است بدون توجه به محتوای واقعی بخش. PowerPoint رفتار خاصی نسبت به لینک‌ها و متن متناظر آن‌ها در یک بخش دارد. این امکان را می‌دهد که متن پیوند را به شکل یک URL معتبر ایجاد کنید که متفاوت از آدرس واقعی لینک باشد. در این حالت، وقتی لینک را در پنجره ویرایش مشاهده می‌کنید، به متن بخش تغییر می‌کند. این ویژگی مقدار اصلی پیوند را نمایان می‌کند. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | مشخص می‌کند که آیا پیوند هنگام کلیک به‌صورت برجسته نمایش داده شود یا خیر. قابل خواندن/نوشتن Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | مشخص می‌کند که آیا هدف پیوند والد هنگام فراخوانی به فهرست پیوندهای مشاهده شده اضافه شود یا خیر. قابل خواندن/نوشتن Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | صدای پخش شده توسط پیوند را نشان می‌دهد. قابل خواندن/نوشتن [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | مشخص می‌کند که آیا صدا باید هنگام کلیک بر پیوند متوقف شود یا خیر. قابل خواندن/نوشتن Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | فریم داخل مجموعه فریم‌های HTML والد را برای هدف پیوند والد بر می‌گرداند هنگامی که وجود داشته باشد. Read/wite String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | اگر Hyperlink به اسلاید خاصی هدف داشته باشد، آن اسلاید را بر می‌گرداند. فقط خواندنی [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | رشته‌ای را بر می‌گرداند که ممکن است در رابط کاربری به عنوان مرتبط با پیوند والد نمایش داده شود. قابل خواندن/نوشتن String. |

## متدها

| نام | توضیح |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | تعیین می‌کند که آیا دو نمونه Hyperlink برابر هستند یا خیر. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | تعیین می‌کند که آیا دو نمونه Hyperlink برابر هستند یا خیر. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | به‌عنوان تابع هش برای یک نوع خاص عمل می‌کند که مناسب استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش است. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | دو پیوند را برای برابری آزمایش می‌کند. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | دو پیوند را برای نابرابری آزمایش می‌کند. |

### موارد مرتبط

* کلاس [PVIObject](../pviobject)
* رابط [IHyperlink](../ihyperlink)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->