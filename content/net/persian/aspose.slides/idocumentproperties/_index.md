---
title: IDocumentProperties
second_title: Aspose.Sildes برای .NET مرجع API
description: خواص یک ارائه را نشان می‌دهد.
type: docs
weight: 5710
url: /fa/aspose.slides/idocumentproperties/
---
## IDocumentProperties رابط

خواص یک ارائه را نشان می‌دهد.

```csharp
public interface IDocumentProperties
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | نسخه برنامه را بر می‌گرداند. فقط-خواندنی String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | نویسنده یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | دسته‌بندی یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | نظرات یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | ویژگی شرکت را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | وضعیت محتوا یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | نوع محتوا یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | تعداد ویژگی‌های سفارشی موجود در مجموعه را بر می‌گرداند. فقط-خواندنی Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | تاریخ ایجاد یک ارائه. مقدارها به زمان UTC هستند. خواندنی/نوشتنی DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. فقط-خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | تعداد اسلایدهای مخفی در سند ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | ویژگی HyperlinkBase سند را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | مشخص می‌کند که یک یا چند پیوند در این بخش به‌صورت انحصاری توسط تولیدکننده به‌روزرسانی شده‌اند. خواندنی/نوشتنی Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | ویژگی سفارشی مرتبط با نام مشخص را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | کلیدواژه‌های یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | تاریخ آخرین چاپ ارائه را بر می‌گرداند. خواندنی/نوشتنی DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | نام آخرین فردی که ارائه را ویرایش کرده است را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | تاریخ آخرین تغییر ارائه. مقدارها به زمان UTC هستند. فقط-خواندنی برای Presentation.DocumentProperties (چون در فرایند ذخیره‌سازی شیء IPresentation به‌روزرسانی داخلی می‌شود). می‌توان آن را از طریق نمونه DocumentProperties که توسط متد [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) برگردانده می‌شود، تغییر داد. لطفاً مثال در خلاصهٔ متد [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | نشان می‌دهد آیا پیوندهای سند به‌روز هستند یا خیر. برای نشان دادن به‌روزرسانی تنظیم مقدار **true** کنید؛ برای نشان دادن منقضی بودن تنظیم مقدار **false** کنید. خواندنی/نوشتنی Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | ویژگی مدیر را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | تعداد کل کلیپ‌های صوتی یا تصویری موجود در سند را مشخص می‌کند. فقط-خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | نام برنامه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | تعداد اسلایدهای دارای یادداشت در ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | تعداد کل پاراگراف‌های موجود در سند (در صورت موجود بودن) را مشخص می‌کند. فقط-خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | قالب مورد نظر ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | شماره بازنگری ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | حالت نمایش تصویر کوچک سند را مشخص می‌کند. برای فعال کردن مقیاس‌بندی تصویر کوچک به‌صورت **true** تنظیم کنید؛ برای برش تصویر به‌صورت **false** تنظیم کنید. خواندنی/نوشتنی Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | تعیین می‌کند آیا ارائه بین چند نفر به‌اشتراک گذاشته شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | تعداد کل اسلایدهای موجود در سند ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | موضوع یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | عنوان یک ارائه را بر می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | عنوان هر قسمت سند را مشخص می‌کند. این قسمت‌ها بخش‌های واقعی سند نیستند، بلکه نمایش مفهومی از بخش‌های سند هستند. فقط-خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | زمان کل ویرایش یک ارائه. خواندنی/نوشتنی TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | تعداد کل کلمات موجود در سند را مشخص می‌کند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | تمام ویژگی‌های توکار را پاک کرده و مقادیر پیش‌فرض را تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | همه ویژگی‌های سفارشی را حذف می‌کند. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | وجود یک ویژگی سفارشی با نام مشخص را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | نام ویژگی سفارشی را در ایندکس مشخص بر می‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | مقدار بولی با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | مقدار DateTime با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | مقدار double با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | مقدار float با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | مقدار integer با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | مقدار string با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک ویژگی سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک ویژگی سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک ویژگی سفارشی double با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک ویژگی سفارشی float با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک ویژگی سفارشی integer با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک ویژگی سفارشی string با نام مشخص را تنظیم می‌کند. |

### همچنین ببینید

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->