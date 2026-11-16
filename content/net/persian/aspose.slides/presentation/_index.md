---
title: Presentation
second_title: مرجع API Aspose.Sildes برای .NET
description: یک ارائه Microsoft PowerPoint را نمایندگی می‌کند.
type: docs
weight: 9610
url: /fa/aspose.slides/presentation/
---
## Presentation کلاس

یک ارائه Microsoft PowerPoint را نمایش می‌دهد.

```csharp
public sealed class Presentation : IPresentation
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [Presentation](presentation#constructor)() | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائه‌ی ایجاد شده یک اسلاید خالی دارد. |
| [Presentation](presentation#constructor_1)(LoadOptions) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائه‌ی ایجاد شده یک اسلاید خالی دارد. |
| [Presentation](presentation#constructor_2)(Stream) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_4)(string) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |

## خواص

| نام | توضیح |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | تمام بخش‌های دادهٔ سفارشی در ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | مجموعهٔ تمام فایل‌های صوتی توکار در ارائه را برمی‌گرداند. فقط-خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | مجموعهٔ تمام نویسندگان نظرات را برمی‌گرداند. فقط-خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | تاریخ و زمان را که محتویات فیلدهای datetime را جایگزین می‌کند برمی‌گرداند یا تنظیم می‌کند. به طور پیش‌فرض زمان ایجاد این شیء Presentation است. خواندنی/نوشتنی DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | دادهٔ سفارشی ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | مجموعهٔ امضاهایی که برای امضای ارائه استفاده می‌شوند را برمی‌گرداند. فقط-خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | شیء DocumentProperties را که شامل ویژگی‌های استاندارد و سفارشی سند است برمی‌گرداند. فقط-خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | شمارهٔ اولین اسلاید در ارائه را نمایندگی می‌کند. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | مدیر قلم‌ها را برمی‌گرداند. فقط-خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | مدیر واقعی HeaderFooter را برمی‌گرداند. فقط-خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام پیوندهای موجود در همه اسلایدهای ارائه (نه در اسلایدهای ماستر، طرح‌بندی، یادداشت) را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | مجموعهٔ تمام تصاویر در ارائه را برمی‌گرداند. فقط-خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | فهرستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | مدیر ماستر پخش‌کننده را برمی‌گرداند. فقط-خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | مدیر ماستر یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | فهرستی از تمام اسلایدهای ماستر که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | قالب ماستر را برمی‌گرداند. فقط-خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | شیء اندازهٔ اسلاید یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | مدیر دسترسی‌های این ارائه را دریافت می‌کند. فقط-خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | مجموعهٔ برچسب‌های حساسیتی که بر سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط-خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | تنظیمات نمایش اسلایدهای ارائه را برمی‌گرداند. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | شیء اندازهٔ اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | اطلاعاتی دربارهٔ فرمت‌گذاری که ارائه از آن بارگذاری شده است را برمی‌گرداند. فقط-خواندنی [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | پروژهٔ VBA با ماکروهای ارائه را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | مجموعهٔ تمام فایل‌های ویدئویی توکار در ارائه را برمی‌گرداند. فقط-خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط-خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیح |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | شیء Image را برای تمام اسلایدهای یک ارائه برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | شیء Thumbnail Image را برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | شیء Thumbnail Image را برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه با اندازهٔ مشخص برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | شیء Thumbnail Image را برای اسلایدهای مشخص‌شدهٔ یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | دنباله‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام اشکال قابل قبول در همه اسلایدها با هم ترکیب می‌کند. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | داده‌های تمام نمودارهای موجود در ارائه را از کتاب‌کارهای منبعشان بازخوانی می‌کند. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | تمام تطبیق‌های عبارت منظم را با رشتهٔ مشخص شده جایگزین می‌کند. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | تمام رخدادهای متن مشخص‌شده را با متن دیگری که مشخص شده جایگزین می‌کند. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر XAML هستند ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | تمام اسلایدهای یک ارائه را به یک فایل با قالب مشخص ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک جریان در قالب مشخص با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک فایل با قالب مشخص و با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک جریان در قالب مشخص با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک فایل با قالب مشخص و با حفظ شماره صفحه ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه یک PowerPoint Presentation ایجاد می‌شود.

```csharp
[C#]
// یک شیء Presentation که نمایانگر یک فایل ارائه است را ایجاد می‌کند
using (Presentation presentation = new Presentation())
{
    // اولین اسلاید را دریافت می‌کند
    ISlide slide = presentation.Slides[0];
    // یک شکل خودکار از نوع خط اضافه می‌کند
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// فایل ارائه را ذخیره می‌کند.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد چگونه Presentation را باز و ذخیره می‌کنید.

```csharp
[C#]
// هر فایل پشتیبانی‌شده را در Presentation بارگذاری کنید، به عنوان مثال ppt، pptx، odp و غیره.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// فایل ارائه را ذخیره می‌کند.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### موارد مرتبط

* رابط [IPresentation](../ipresentation)
* فضای نام [Aspose.Slides](../../aspose.slides)
* مجوعه [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->