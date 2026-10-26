---
title: DocumentProperties
second_title: مرجع API Aspose.Sildes برای .NET
description: خواص یک ارائه را نمایندگی می‌کند.
type: docs
weight: 2790
url: /fa/aspose.slides/documentproperties/
---
## کلاس DocumentProperties

خصائص یک ارائه را نمایندگی می‌کند.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [DocumentProperties](documentproperties)() | یک نمونه جدید از کلاس [`DocumentProperties`](../documentproperties) را مقداردهی اولیه می‌کند. |

## خصوصیات

| نام | توضیح |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | نسخه برنامه را باز می‌گرداند. فقط خواندنی String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | نویسنده یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | دسته‌بندی یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | نظرات یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | مقدار ویژگی شرکت را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | وضعیت محتوای یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | نوع محتوای یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | تعداد خواص سفارشی موجود در یک مجموعه را باز می‌گرداند. فقط خواندنی Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | تاریخ ایجاد یک ارائه را باز می‌گرداند. مقادیر به زمان UTC هستند. قابل خواندن/قابل نوشتن DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | گروه‌بندی قسمت‌های سند و تعداد قسمت‌ها در هر گروه را نشان می‌دهد. فقط خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | تعداد اسلایدهای مخفی در سند ارائه را باز می‌گرداند. فقط خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | ویژگی HyperlinkBase سند را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | مشخص می‌کند که یک یا چند پیوند در این بخش به‌طور اختصاصی توسط تولیدکننده به‌روز شده‌اند. تولیدکننده بعدی که این سند را باز می‌کند باید روابط پیوند را با پیوندهای جدید مشخص‌شده در این بخش به‌روز نماید. قابل خواندن/قابل نوشتن Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | خاصیت سفارشی مرتبط با نام مشخص‌شده را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | کلیدواژه‌های یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | تاریخی که ارائه آخرین بار چاپ شده بود را باز می‌گرداند. قابل خواندن/قابل نوشتن DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | نام آخرین شخصی که یک ارائه را تغییر داده است را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | تاریخ ارائه به‌آخرین بار تغییر یافته است را باز می‌گرداند. مقادیر به زمان UTC هستند. فقط خواندنی در مورد Presentation.DocumentProperties (زیرا در فرایند ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روز می‌شود). می‌توان از طریق نمونه DocumentProperties که توسط روش [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) برگردانده می‌شود، تغییر داد. لطفاً مثال در خلاصه روش [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | نشان می‌دهد که آیا پیوندها در سند به‌روز هستند یا خیر. این عنصر را به **true** تنظیم کنید تا پیوندها به‌روز باشند. این عنصر را به **false** تنظیم کنید تا پیوندها قدیمی باشند. قابل خواندن/قابل نوشتن Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | ویژگی مدیر را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | تعداد کل صدا یا کلیپ‌های ویدئویی موجود در سند را باز می‌گرداند. فقط خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | نام برنامه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | تعداد اسلایدهای شامل یادداشت در یک ارائه را باز می‌گرداند. فقط خواندنی Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | تعداد کل پاراگراف‌های موجود در سند (در صورت امکان) را باز می‌گرداند. فقط خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | قالب موردنظر یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | شماره تجدید نظر ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | حالت نمایش تصویر بند انگشت سند را نشان می‌دهد. این عنصر را به **true** تنظیم کنید تا مقیاس‌بندی تصویر بند انگشت به نمایشگر فعال شود. این عنصر را به **false** تنظیم کنید تا برش تصویر بند انگشت به‌طوری که فقط بخش‌های مناسب نمایشگر نشان داده شوند، فعال شود. قابل خواندن/قابل نوشتن Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | تعیین می‌کند که آیا ارائه بین چندین نفر به اشتراک گذاشته شده است یا خیر. قابل خواندن/قابل نوشتن Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | کل تعداد اسلایدهای موجود در سند ارائه را باز می‌گرداند. فقط خواندنی Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | موضوع یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | عنوان یک ارائه را باز می‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه بازنمایی‌های مفهومی از بخش‌های سند هستند. فقط خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | کل زمان ویرایش یک ارائه. قابل خواندن/قابل نوشتن TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | کل تعداد کلمات موجود در سند را باز می‌گرداند. فقط خواندنی Int32. |

## متدها

| نام | توضیح |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | تمام خصوصیات پیش‌فرض را پاک‌سازی و مقادیر پیش‌فرض تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | تمام خصوصیات سفارشی را حذف می‌کند. |
| [Clone](../../aspose.slides/documentproperties/clone)() | شیء فعلی را کلون می‌کند. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | شیء فعلی را کلون می‌کند. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | وجود یک خاصیت سفارشی با نام مشخص‌شده را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | نام یک خاصیت سفارشی در شاخص مشخص‌شده را باز می‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | یک مقدار بولی با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | یک مقدار DateTime با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | یک مقدار double با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | یک مقدار float با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | یک مقدار عدد صحیح با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | یک مقدار رشته‌ای با نام مشخص را از خصوصیات سفارشی دریافت می‌کند. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | یک آرایه از برچسب‌های حساسیت را از خصوصیات سفارشی سند دریافت می‌کند (Metadata SDK حفاظت از اطلاعات مایکروسافت). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | یک خاصیت سفارشی مرتبط با نام مشخص‌شده را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک خاصیت سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک خاصیت سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک خاصیت سفارشی double با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک خاصیت سفارشی float با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک خاصیت سفارشی integer با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک خاصیت سفارشی string با نام مشخص را تنظیم می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه به خصوصیات پیش‌فرض یک ارائه PowerPoint دسترسی پیدا کنید.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر ارائه است ایجاد کنید
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد کنید
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// خواص داخلی را نمایش دهید
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

مثال زیر نشان می‌دهد چگونه خصوصیات پیش‌فرض یک ارائه PowerPoint را اصلاح کنید.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایندهٔ ارائه است ایجاد کنید
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد کنید
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// تنظیم خواص داخلی
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// ارائه خود را در یک فایل ذخیره کنید
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### همچنین ببینید

* رابط [IDocumentProperties](../idocumentproperties)
* رابط [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->