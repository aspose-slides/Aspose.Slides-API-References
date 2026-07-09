---
title: Presentation
second_title: Aspose.Sildes برای .NET مرجع API
description: یک ارائه Microsoft PowerPoint را نمایندگی می‌کند.
type: docs
weight: 9590
url: /fa/aspose.slides/presentation/
---
## کلاس Presentation

یک ارائه Microsoft PowerPoint را نمایندگی می‌کند.

```csharp
public sealed class Presentation : IPresentation
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [Presentation](presentation#constructor)() | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائه‌ی ایجاد شده شامل یک اسلاید خالی است. |
| [Presentation](presentation#constructor_1)(LoadOptions) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائه‌ی ایجاد شده شامل یک اسلاید خالی است. |
| [Presentation](presentation#constructor_2)(Stream) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_4)(string) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | تمام قسمت‌های داده سفارشی در ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | مجموعه‌ای از تمام پرونده‌های صوتی جاسازی شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | مجموعه‌ای از مؤلفین نظرات را برمی‌گرداند. فقط-خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | تاریخ و زمانی را برمی‌گرداند یا تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. به‌طور پیش‌فرض زمان ایجاد این شیء Presentation. قابل‌نوشتن DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | داده‌های سفارشی ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | مجموعه‌ای از امضاهایی که برای امضای ارائه استفاده می‌شوند را برمی‌گرداند. فقط-خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است را برمی‌گرداند. فقط-خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | شماره اسلاید اول در ارائه را نشان می‌دهد. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | مدیر قلم‌ها را برمی‌گرداند. فقط-خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | مدیر HeaderFooter فعلی را برمی‌گرداند. فقط-خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام پیوندهای موجود در اسلایدهای ارائه (نه در مستر، طرح‌بندی، اسلایدهای یادداشت) را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | مجموعه‌ای از تمام تصاویر موجود در ارائه را برمی‌گرداند. فقط-خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | فهرستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | مدیر مستر توزیع جزوات را برمی‌گرداند. فقط-خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | مدیر مستر یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | فهرستی از تمام اسلایدهای مستر که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | تم مستر را برمی‌گرداند. فقط-خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | مدیر مجوزهای این ارائه را دریافت می‌کند. فقط-خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | مجموعه‌ای از برچسب‌های حساسیتی که به سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط-خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | فهرستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط-خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | شیء اندازه اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | اطلاعاتی درباره فرمت منبعی که ارائه از آن بارگذاری شده را برمی‌گرداند. فقط-خواندنی [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | پروژه VBA شامل ماکروهای ارائه را دریافت یا تنظیم می‌کند. قابل‌نوشتن [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | مجموعه‌ای از تمام پرونده‌های ویدئویی جاسازی شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط-خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیح |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | یک شیء Image برای تمام اسلایدهای یک ارائه را برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | یک شیء Thumbnail Image برای اسلایدهای مشخص شده از یک ارائه را برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با اندازه مشخص را برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با مقیاس سفارشی را برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | یک شیء Thumbnail Image برای اسلایدهای مشخص شده از یک ارائه با اندازه مشخص را برمی‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | یک شیء Thumbnail Image برای اسلایدهای مشخص شده از یک ارائه با مقیاس سفارشی را برمی‌گرداند. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | یک Slide، MasterSlide یا LayoutSlide را با Id برمی‌گرداند. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | اجراهای (runs) با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل‌قبول در تمام اسلایدها ترکیب می‌کند. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رشته مشخص شده جایگزین می‌کند. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | تمام رخدادهای متن مشخص شده را با متن دیگری که مشخص می‌شود جایگزین می‌کند. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌های نمایانگر XAML ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | تمام اسلایدهای یک ارائه را به یک فایل با فرمت مشخص ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | اسلایدهای مشخص شده از یک ارائه را به یک فایل با فرمت مشخص با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص شده از یک ارائه را به یک فایل با فرمت مشخص با حفظ شماره صفحه ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه یک ارائه PowerPoint ایجاد کنیم.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
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

مثال زیر نشان می‌دهد چگونه Presentation را باز و ذخیره کنید.

```csharp
[C#]
// هر فایل پشتیبانی‌شده‌ای را در Presentation بارگذاری می‌کند، مانند ppt، pptx، odp و غیره.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// فایل ارائه را ذخیره می‌کند.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IPresentation](../ipresentation)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->