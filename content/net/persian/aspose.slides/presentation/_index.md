---
title: Presentation
second_title: Aspose.Sildes برای .NET مرجع API
description: یک ارائهٔ Microsoft PowerPoint را نمایش می‌دهد.
type: docs
weight: 9590
url: /fa/aspose.slides/presentation/
---
## کلاس Presentation

یک ارائهٔ Microsoft PowerPoint را نمایش می‌دهد.

```csharp
public sealed class Presentation : IPresentation
```

## سازنده‌ها

| نام | توضیح |
| --- | --- |
| [Presentation](presentation#constructor)() | این سازنده یک ارائه جدید از ابتدا ایجاد می‌کند. ارائهٔ ایجاد شده یک اسلاید خالی دارد. |
| [Presentation](presentation#constructor_1)(LoadOptions) | این سازنده یک ارائه جدید از ابتدا ایجاد می‌کند. ارائهٔ ایجاد شده یک اسلاید خالی دارد. |
| [Presentation](presentation#constructor_2)(Stream) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_4)(string) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای Presentation از آن خوانده می‌شود. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای Presentation از آن خوانده می‌شود. |

## خواص

| نام | توضیح |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | همهٔ بخش‌های دادهٔ سفارشی در ارائه را بر می‌گرداند. فقط خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | مجموعهٔ تمام فایل‌های صوتی تعبیه‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | مجموعهٔ نویسندگان نظرات را بر می‌گرداند. فقط خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | تاریخ و زمان را که محتوای فیلدهای datetime را جایگزین می‌کند بر می‌گرداند یا تنظیم می‌کند. به طور پیش‌فرض زمان ایجاد شیء Presentation است. خواندن/نوشتن DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | دادهٔ سفارشی ارائه را بر می‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | سبک متن پیش‌فرض برای شکل‌ها را بر می‌گرداند. فقط خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | مجموعهٔ امضاهایی که برای امضای ارائه استفاده می‌شوند را بر می‌گرداند. فقط خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | شیء DocumentProperties را که شامل ویژگی‌های استاندارد و سفارشی سند است بر می‌گرداند. فقط خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | مدیر فونت‌ها را بر می‌گرداند. فقط خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | مدیر HeaderFooter واقعی را بر می‌گرداند. فقط خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام پیوندهای موجود در تمام اسلایدهای ارائه (به جز اسلایدهای master، layout، notes) را فراهم می‌کند. فقط خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | مجموعهٔ تمام تصاویر در ارائه را بر می‌گرداند. فقط خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | فهرستی از تمام اسلایدهای layout تعریف‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | مدیر handout master را بر می‌گرداند. فقط خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | مدیر notes master را بر می‌گرداند. فقط خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | فهرستی از تمام اسلایدهای master تعریف‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | تم master را بر می‌گرداند. فقط خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | شیء اندازه اسلاید notes را بر می‌گرداند. فقط خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | مدیر دسترسی‌های این ارائه را دریافت می‌کند. فقط خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | مجموعهٔ برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را بر می‌گرداند. فقط خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | تنظیمات نمایش اسلاید برای ارائه را بر می‌گرداند. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | شیء اندازه اسلاید را بر می‌گرداند. فقط خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | اطلاعات دربارهٔ فرمت منبعی که ارائه از آن بارگذاری شده است را بر می‌گرداند. فقط خواندنی [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. خواندن/نوشتن [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | مجموعهٔ تمام فایل‌های ویدیویی تعبیه‌شده در ارائه را بر می‌گرداند. فقط خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیح |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | یک شیء Image برای تمام اسلایدهای یک ارائه بر می‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | یک شیء Thumbnail Image برای اسلایدهای مشخص‌شدهٔ یک ارائه بر می‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص شده بر می‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | یک شیء Thumbnail Image برای تمام اسلایدهای یک ارائه با مقیاس‌بندی سفارشی بر می‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | یک شیء Thumbnail Image برای اسلایدهای مشخص‌شدهٔ یک ارائه با اندازهٔ مشخص شده بر می‌گرداند. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | یک شیء Thumbnail Image برای اسلایدهای مشخص‌شدهٔ یک ارائه با مقیاس‌بندی سفارشی بر می‌گرداند. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها، بخش‌های متنی با قالب‌بندی یکسان را ترکیب می‌کند. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | تمام رخدادهای متن مشخص‌شده را با متن دیگری که مشخص شده جایگزین می‌کند. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمایانگر نشانه‌گذاری XAML هستند، ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | تمام اسلایدهای یک ارائه را به یک فایل با قالب مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک جریان در قالب مشخص‌شده با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص‌شده و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک فایل با قالب مشخص‌شده و حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک جریان در قالب مشخص‌شده با حفظ شماره صفحه ذخیره می‌کند. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شدهٔ یک ارائه را به یک فایل با قالب مشخص‌شده و حفظ شماره صفحه ذخیره می‌کند. |

### مثال‌ها

مثال زیر نشان می‌دهد چگونه یک PowerPoint Presentation ایجاد شود.

```csharp
[C#]
// یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
using (Presentation presentation = new Presentation())
{
    // اولین اسلاید را دریافت کنید
    ISlide slide = presentation.Slides[0];
    // یک شکل خودکار از نوع خط اضافه کنید
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// فایل ارائه را ذخیره می‌کند.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

مثال زیر نشان می‌دهد چگونه یک Presentation باز و ذخیره شود.

```csharp
[C#]
// فایل پشتیبانی‌شده‌ای را در Presentation بارگذاری کنید، مانند ppt، pptx، odp و غیره.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// فایل ارائه را ذخیره کنید.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### مراجع

* رابط [IPresentation](../ipresentation)
* فضای نام [Aspose.Slides](../../aspose.slides)
* اسمبلی [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->