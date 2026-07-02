---
title: DocumentProperties
second_title: Aspose.Sildes برای .NET مرجع API
description: نمایش‌دهندهٔ ویژگی‌های یک ارائه.
type: docs
weight: 2790
url: /fa/aspose.slides/documentproperties/
---
## کلاس DocumentProperties

نمایش‌دهندهٔ ویژگی‌های یک ارائه.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## سازندگان

| Name | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | یک نمونهٔ جدید از کلاس [`DocumentProperties`](../documentproperties) را مقداردهی اولیه می‌کند. |

## ویژگی‌ها

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | قالب یک برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | نسخهٔ برنامه را برمی‌گرداند. فقط خواندنی String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | نویسندهٔ یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | دستهٔ یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | نظرات یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | خاصیت شرکت را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | وضعیت محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | نوع محتوا یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | تعداد ویژگی‌های سفارشی واقعاً موجود در یک مجموعه را برمی‌گرداند. فقط خواندنی Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | تاریخی که ارائه ایجاد شد را برمی‌گرداند. مقدارها به زمان UTC هستند. قابل خواندن/نوشتن DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | گروه‌بندی بخش‌های سند و تعداد بخش‌ها در هر گروه را نشان می‌دهد. فقط خواندنی IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | تعداد اسلایدهای مخفی در یک سند ارائه را برمی‌گرداند. فقط خواندنی Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | خاصیت سند HyperlinkBase را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | مشخص می‌کند که یک یا چند پیوند در این بخش صرفاً توسط یک تولیدکننده در این بخش به‌روزرسانی شده‌اند. تولیدکنندهٔ بعدی که این سند را باز می‌کند باید روابط پیوند را با پیوندهای جدیدی که در این بخش مشخص شده‌اند به‌روزرسانی کند. قابل خواندن/نوشتن Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | خاصیت سفارشی مرتبط با نام مشخصی را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | کلیدواژگان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | تاریخ آخرین چاپ ارائه را برمی‌گرداند. قابل خواندن/نوشتن DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | نام آخرین شخصی که یک ارائه را ویرایش کرده است را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | تاریخی که ارائه آخرین بار ویرایش شد را برمی‌گرداند. مقدارها به زمان UTC هستند. فقط خواندنی در مورد Presentation.DocumentProperties (به‌این دلیل که در فرآیند ذخیره‌سازی شیء IPresentation به‌صورت داخلی به‌روز می‌شود). می‌تواند از طریق نمونهٔ DocumentProperties که توسط متد [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) برگردانده می‌شود تغییر یابد. لطفاً مثال در خلاصهٔ متد [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) را ببینید. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | نشان می‌دهد آیا پیوندهای موجود در یک سند به‌روز هستند یا نه. برای نشان دادن به‌روز بودن پیوندها این عنصر را **true** تنظیم کنید. برای نشان دادن که پیوندها منقضی شده‌اند این عنصر را **false** تنظیم کنید. قابل خواندن/نوشتن Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | خاصیت مدیر را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | کل تعداد کلیپ‌های صوتی یا ویدئویی موجود در سند را برمی‌گرداند. فقط خواندنی Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | نام برنامه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | تعداد اسلایدهای یک ارائه که حاوی یادداشت هستند را برمی‌گرداند. فقط خواندنی Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | کل تعداد پاراگراف‌های موجود در سند (در صورت وجود) را برمی‌گرداند. فقط خواندنی Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | قالب موردنظر یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | شمارهٔ بازنگری ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | حالت نمایش تصویر بندانگشتی سند را نشان می‌دهد. برای فعال‌سازی مقیاس‌بندی تصویر بندانگشتی به نمایش این عنصر را **true** تنظیم کنید. برای فعال‌سازی برش تصویر بندانگشتی به‌گونه‌ای که فقط بخش‌های متناسب با نمایش نشان داده شوند این عنصر را **false** تنظیم کنید. قابل خواندن/نوشتن Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | تعیین می‌کند آیا ارائه بین چند نفر به اشتراک گذاشته شده است یا خیر. قابل خواندن/نوشتن Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | کل تعداد اسلایدهای یک سند ارائه را برمی‌گرداند. فقط خواندنی Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | موضوع یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | عنوان یک ارائه را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | عنوان هر بخش سند را مشخص می‌کند. این بخش‌ها بخش‌های سند نیستند بلکه نمایه‌های مفهومی بخش‌های سند هستند. فقط خواندنی string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | کل زمان ویرایش یک ارائه. قابل خواندن/نوشتن TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | کل تعداد کلمات موجود در سند را برمی‌گرداند. فقط خواندنی Int32. |

## متدها

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | تمام ویژگی‌های داخلی را پاک‌سازی و مقادیر پیش‌فرضشان را تنظیم می‌کند. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | تمام ویژگی‌های سفارشی را حذف می‌کند. |
| [Clone](../../aspose.slides/documentproperties/clone)() | شیء کنونی را کپی می‌کند. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | شیء کنونی را کپی می‌کند. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | وجود یک ویژگی سفارشی با نام مشخص شده را بررسی می‌کند. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | نام یک ویژگی سفارشی را در ایندکس مشخص‌شده برمی‌گرداند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | مقدار بولی با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | مقدار DateTime با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | مقدار double با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | مقدار float با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | مقدار عددی (int) با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | مقدار رشته‌ای با نام مشخص را از ویژگی‌های سفارشی دریافت می‌کند. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند دریافت می‌کند (Metadata SDK محافظت از اطلاعات مایکروسافت). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | یک ویژگی سفارشی مرتبط با نام مشخص را حذف می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | یک ویژگی سفارشی بولی با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | یک ویژگی سفارشی DateTime با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | یک ویژگی سفارشی double با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | یک ویژگی سفارشی float با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | یک ویژگی سفارشی عددی (int) با نام مشخص را تنظیم می‌کند. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | یک ویژگی سفارشی رشته‌ای با نام مشخص را تنظیم می‌کند. |

### مثال‌ها

The following example shows how to access built-in Properties of PowerPoint Presentation.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر ارائه است
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد می‌کند
	// ویژگی‌های داخلی را نمایش می‌دهد
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

The following example shows how to modify built-in Properties of PowerPoint Presentation.

```csharp
[C#]
// یک نمونه از کلاس Presentation که نمایانگر ارائه است
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// یک مرجع به شیء IDocumentProperties مرتبط با Presentation ایجاد می‌کند
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// خصوصیات داخلی را تنظیم می‌کند
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// ارائه خود را در یک فایل ذخیره می‌کند
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### همچنین ببینید

* رابط [IDocumentProperties](../idocumentproperties)
* رابط [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->