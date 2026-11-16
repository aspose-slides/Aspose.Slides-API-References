---
title: DocumentProperties
second_title: مرجع API Aspose.Sildes برای .NET
description: خصوصیات یک ارائه را نشان می‌دهد.
type: docs
weight: 2810
url: /fa/aspose.slides/documentproperties/
---
## DocumentProperties کلاس

نمایش‌دهندهٔ خصوصیات یک ارائه.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## سازنده‌ها

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | نمونهٔ جدیدی از کلاس [`DocumentProperties`](../documentproperties) را مقداردهی اولیه می‌کند. |

## خصوصیات

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | نسخهٔ برنامه را برمی‌گرداند. فقط-خواندنی String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | نویسندهٔ یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | دستهٔ یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | توضیحات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | ویژگی شرکت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | وضعیت محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | نوع محتوای یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | تعداد خصوصیات سفارشی موجود در یک مجموعه را برمی‌گرداند. فقط-خواندنی Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | تاریخی که یک ارائه ایجاد شده است را برمی‌گرداند. مقادیر به ساعت هماهنگ جهانی (UTC) هستند. قابل خواندن/نوشتن DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | گروه‌بندی قسمت‌های سند و تعداد قسمت‌ها در هر گروه را نشان می‌دهد. فقط-خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | تعداد اسلایدهای مخفی در یک سند ارائه را برمی‌گرداند. فقط-خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | ویژگی سند HyperlinkBase را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | مشخص می‌کند که یک یا چند پیوند در این قسمت به‌صورت انحصاری توسط تولیدکننده به‌روز شده‌اند. تولیدکنندهٔ بعدی که این سند را باز می‌کند، روابط پیوند را با پیوندهای جدید مشخص‌شده در این قسمت به‌روز می‌کند. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | ویژگی سفارشی مرتبط با نام مشخص را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | کلیدواژه‌های یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | تاریخی که ارائه برای آخرین بار چاپ شده است را برمی‌گرداند. قابل خواندن/نوشتن DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | نام آخرین شخصی که یک ارائه را اصلاح کرده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; } | تاریخی که یک ارائه آخرین بار اصلاح شده است را برمی‌گرداند. مقادیر به ساعت هماهنگ جهانی (UTC) هستند. فقط-خواندنی در صورت استفاده از Presentation.DocumentProperties (زیرا در هنگام ذخیره‌سازی شیء IPresentation به‌طور داخلی به‌روز می‌شود). می‌توان از طریق نمونهٔ DocumentProperties که توسط متد [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) برگردانده می‌شود، تغییر داد. لطفاً مثال در خلاصهٔ متد [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | نشان می‌دهد آیا پیوندها در یک سند به‌روز هستند یا خیر. این عنصر را به **true** تنظیم کنید تا نشان دهد پیوندها به‌روز هستند. این عنصر را به **false** تنظیم کنید تا نشان دهد پیوندها منقضی شده‌اند. قابل خواندن/نوشتن Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | ویژگی مدیر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | کل تعداد کلیپ‌های صوتی یا ویدیویی موجود در سند را برمی‌گرداند. فقط-خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | تعداد اسلایدهای یک ارائه که شامل یادداشت هستند را برمی‌گرداند. فقط-خواندنی Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | کل تعداد پاراگراف‌های یافت‌شده در یک سند (در صورت وجود) را برمی‌گرداند. فقط-خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | قالب مورد نظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | شمارهٔ بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | حالت نمایش بندانگشتی سند را نشان می‌دهد. این عنصر را به **true** تنظیم کنید تا مقیاس‌بندی بندانگشتی به نمایش فعال شود. این عنصر را به **false** تنظیم کنید تا برش بندانگشتی به‌گونه‌ای انجام شود که فقط بخش‌های متناسب با نمایش نشان داده شوند. قابل خواندن/نوشتن Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | تشخیص می‌دهد آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا خیر. قابل خواندن/نوشتن Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | کل تعداد اسلایدهای یک سند ارائه را برمی‌گرداند. فقط-خواندنی Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | عنوان هر بخش از سند را مشخص می‌کند. این بخش‌ها بخش‌های واقعی سند نیستند، بلکه بازنمایی‌های مفهومی از بخش‌های سند هستند. فقط-خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | کل زمان ویرایش یک ارائه. قابل خواندن/نوشتن TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | کل تعداد کلمات موجود در یک سند را برمی‌گرداند. فقط-خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | تمام خصوصیات داخلی را پاک کرده و مقادیر پیش‌فرض را تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | تمام خصوصیات سفارشی را حذف می‌کند. |
| [Clone](../../aspose.slides/documentproperties/clone)() | شیء کنونی را کلون می‌کند |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | شیء کنونی را کلون می‌کند |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | وجود یک خصوصیت سفارشی با نام مشخص را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | نام یک خصوصیت سفارشی را در ایندکس مشخص برمی‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | مقدار بولی با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | مقدار DateTime با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | مقدار double با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | مقدار float با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | مقدار عدد صحیح با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | مقدار رشته‌ای با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | آرایه‌ای از برچسب‌های حساسیت را از خصوصیات سفارشی سند دریافت می‌کند (متادیتای Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | یک خصوصیت سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک خصوصیت سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک خصوصیت سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک خصوصیت سفارشی double با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک خصوصیت سفارشی float با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک خصوصیت سفارشی عدد صحیح با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک خصوصیت سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه به خصوصیات پیش‌ساختهٔ ارائهٔ PowerPoint دسترسی پیدا کنیم.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر ارائه است را ایجاد می‌کند
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// ایجاد یک ارجاع به شیء IDocumentProperties مرتبط با Presentation
	// نمایش خصوصیات پیش‌ساخته
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

مثال زیر نشان می‌دهد چگونه خصوصیات پیش‌ساختهٔ ارائهٔ PowerPoint را اصلاح کنیم.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر ارائه است را ایجاد می‌کند
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// ایجاد یک ارجاع به شیء IDocumentProperties مرتبط با Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// خصوصیات پیش‌ساخته را تنظیم می‌کند
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// ارائه خود را در یک فایل ذخیره کنید
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IDocumentProperties](../idocumentproperties)
* رابط [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مونتاژ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->