---
title: IDocumentProperties
second_title: مرجع API Aspose.Sildes برای .NET
description: خواص یک ارائه را نشان می‌دهد.
type: docs
weight: 5730
url: /fa/aspose.slides/idocumentproperties/
---
## IDocumentProperties رابط

خواص یک ارائه را نشان می‌دهد.

```csharp
public interface IDocumentProperties
```

## ویژگی‌ها

| نام | توضیحات |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | نسخه برنامه را بر می‌گرداند. فقط خواندنی String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | نویسنده یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | دسته‌بندی یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | توضیحات یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | ویژگی شرکت را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | وضعیت محتوا یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | نوع محتوا یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | تعداد ویژگی‌های سفارشی موجود در مجموعه را بر می‌گرداند. فقط خواندنی Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | تاریخ ایجاد یک ارائه را بر می‌گرداند. مقادیر به زمان UTC هستند. خواندنی/قابل نوشتن DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | گروه‌بندی قسمت‌های سند و تعداد قسمت‌ها در هر گروه را نشان می‌دهد. فقط خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | تعداد اسلایدهای مخفی در سند ارائه را مشخص می‌کند. فقط خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | ویژگی HyperlinkBase سند را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | نشان می‌دهد که یک یا چند پیوند در این قسمت به‌صورت انحصاری توسط یک تولیدکننده به‌روزرسانی شده‌اند. خواندنی/قابل نوشتن Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | ویژگی سفارشی مرتبط با نام مشخص را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | کلمات کلیدی یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | تاریخ آخرین چاپ یک ارائه را بر می‌گرداند. خواندنی/قابل نوشتن DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | نام آخرین شخصی که یک ارائه را اصلاح کرده است را بر می‌گرداند. خواندنی/قابل نوشتن String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | تاریخ آخرین اصلاح یک ارائه را بر می‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در مورد Presentation.DocumentProperties (زیرا در هنگام ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روزرسانی می‌شود). می‌توان از طریق نمونه DocumentProperties برگردانده‌شده توسط متد [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) تغییر داد. لطفاً مثال در خلاصهٔ متد [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | نشان می‌دهد که پیوندهای موجود در سند به‌روز هستند. برای نشان دادن به‌روزرسانی پیوندها این عنصر را **true** قرار دهید. برای نشان دادن که پیوندها منقضی شده‌اند این عنصر را **false** قرار دهید. خواندنی/قابل نوشتن Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | ویژگی مدیر را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | مجموع تعداد کلیپ‌های صوتی یا ویدئویی موجود در سند را مشخص می‌کند. فقط خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | نام برنامه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | تعداد اسلایدهای حاوی یادداشت‌ها در ارائه را نشان می‌دهد. فقط خواندنی Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | مجموع تعداد پاراگراف‌های موجود در سند (در صورت وجود) را مشخص می‌کند. فقط خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | فرمت مورد نظر یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | شمارهٔ تجدید نظر ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی تصویر بندانگشتی به نمایش این عنصر را **true** قرار دهید. برای فعال‌سازی برش تصویر بندانگشتی به‌گونه‌ای که فقط بخش‌های متناسب با نمایش نشان داده شود این عنصر را **false** قرار دهید. خواندنی/قابل نوشتن Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | تعیین می‌کند که آیا ارائه بین چندین نفر به‌اشتراک‌گذاری شده است یا نه. خواندنی/قابل نوشتن Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | مجموع تعداد اسلایدهای موجود در سند ارائه را مشخص می‌کند. فقط خواندنی Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | موضوع یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | عنوان یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | عنوان هر قسمت سند را مشخص می‌کند. این قسمت‌ها بخش‌های سند نیستند بلکه نمایه‌های مفهومی از بخش‌های سند هستند. فقط خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | کل زمان ویرایش یک ارائه. خواندنی/قابل نوشتن TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | مجموع تعداد کلمات موجود در سند را مشخص می‌کند. فقط خواندنی Int32. |

## متدها

| نام | توضیحات |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | مقادیر پیش‌فرض همه ویژگی‌های builtIn را پاک کرده و تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | تمام ویژگی‌های سفارشی را حذف می‌کند. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | نام ویژگی سفارشی در شاخص مشخص‌شده را بر می‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | مقدار بولی نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | مقدار DateTime نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | مقدار double نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | مقدار float نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | مقدار عدد صحیح نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | مقدار رشته‌ای نام‌گذاری‌شده را از ویژگی‌های سفارشی می‌گیرد. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک ویژگی سفارشی بولی نام‌گذاری‌شده را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک ویژگی سفارشی DateTime نام‌گذاری‌شده را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک ویژگی سفارشی double نام‌گذاری‌شده را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک ویژگی سفارشی float نام‌گذاری‌شده را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک ویژگی سفارشی عدد صحیح نام‌گذاری‌شده را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک ویژگی سفارشی رشته‌ای نام‌گذاری‌شده را تنظیم می‌کند. |

### همچنین ببینید

* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->