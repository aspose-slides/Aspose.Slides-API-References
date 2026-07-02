---
title: IDocumentProperties
second_title: Aspose.Sildes برای مرجع API .NET
description: نمایش‌دهندهٔ ویژگی‌های یک ارائه.
type: docs
weight: 5710
url: /fa/aspose.slides/idocumentproperties/
---
## IDocumentProperties رابط

نمایش‌دهندهٔ ویژگی‌های یک ارائه.

```csharp
public interface IDocumentProperties
```

## خصوصیات

| نام | توضیح |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | نسخهٔ برنامه را برمی‌گرداند. فقط-خواندنی String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | نویسندهٔ یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | دسته‌بندی یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | توضیحات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | تعداد ویژگی‌های سفارشی موجود در مجموعه را برمی‌گرداند. فقط-خواندنی Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | تاریخ ایجاد یک ارائه را برمی‌گرداند. مقادیر بر حسب UTC هستند. خواندنی/نوشتنی DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. فقط-خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | تعداد اسلایدهای پنهان در سند ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | ویژگی HyperlinkBase سند را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | مشخص می‌کند که یک یا چند لینک در این بخش به‌طور انحصاری توسط یک تولیدکننده به‌روز شده‌اند. تولیدکنندهٔ بعدی که این سند را باز می‌کند باید روابط لینک‌ها را با لینک‌های جدید مشخص شده در این بخش به‌روز کند. خواندنی/نوشتنی Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | ویژگی سفارشی مرتبط با نام مشخص شده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | تاریخ چاپ آخرین بار یک ارائه را برمی‌گرداند. خواندنی/نوشتنی DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | نام آخرین شخصی که یک ارائه را تغییر داده است را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | تاریخ آخرین تغییر یک ارائه را برمی‌گرداند. مقادیر بر حسب UTC هستند. فقط-خواندنی در صورتی که از Presentation.DocumentProperties استفاده شود (زیرا در فرایند ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روز می‌شود). می‌توان آن را از طریق نمونهٔ DocumentProperties که توسط متد [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) برگردانده می‌شود، تغییر داد. لطفاً مثال در خلاصهٔ متد [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | نشان می‌دهد آیا لینک‌ها در یک سند بروز هستند یا خیر. برای نشان دادن بروز بودن لینک‌ها این عنصر را **true** تنظیم کنید. برای نشان دادن که لینک‌ها منقضی شده‌اند این عنصر را **false** تنظیم کنید. خواندنی/نوشتنی Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | تعداد کل کلیپ‌های صوتی یا تصویری موجود در سند را مشخص می‌کند. فقط-خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | تعداد اسلایدهای شامل یادداشت در یک ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | تعداد کل پاراگراف‌های موجود در سند را در صورت امکان مشخص می‌کند. فقط-خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | قالب مطلوب یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | شمارهٔ بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | حالت نمایش تصویر بندانگشتی سند را مشخص می‌کند. برای فعال‌سازی مقیاس‌گذاری تصویر بندانگشتی به نمایش این عنصر را **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشتی به‌گونه‌ای که فقط قسمت‌های متناسب با نمایش نشان داده شوند این عنصر را **false** تنظیم کنید. خواندنی/نوشتنی Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | تعیین می‌کند آیا ارائه بین چندین نفر به‌اشتراک گذاشته شده است یا خیر. خواندنی/نوشتنی Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | تعداد کل اسلایدهای موجود در سند ارائه را مشخص می‌کند. فقط-خواندنی Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه نمایشی مفهومی از بخش‌های سند هستند. فقط-خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | زمان کل ویرایش یک ارائه. خواندنی/نوشتنی TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | تعداد کل کلمات موجود در یک سند را مشخص می‌کند. فقط-خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | تمام ویژگی‌های توکار را پاک‌سازی و مقادیر پیش‌فرض تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | همه ویژگی‌های سفارشی را حذف می‌کند. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | وجود یک ویژگی سفارشی با نام مشخص شده را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | نام ویژگی سفارشی در اندیس مشخص شده را برمی‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | مقدار بولین نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | مقدار DateTime نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | مقدار double نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | مقدار float نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | مقدار عدد صحیح نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | مقدار رشته‌ای نام‌دار را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | آرایه‌ای از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Metadata Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | ویژگی سفارشی مرتبط با نام مشخص شده را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک ویژگی بولین سفارشی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک ویژگی DateTime سفارشی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک ویژگی double سفارشی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک ویژگی float سفارشی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک ویژگی عدد صحیح سفارشی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک ویژگی رشته‌ای سفارشی با نام مشخص را تنظیم می‌کند. |

### موارد مرتبط

* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->