---
title: IPresentation
second_title: Aspose.Sildes برای مرجع API .NET
description: سند ارائه
type: docs
weight: 6770
url: /fa/aspose.slides/ipresentation/
---
## رابط IPresentation

سند ارائه

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## خواص

| نام | توضیحات |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | تمام بخش‌های داده سفارشی در ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | رابط IDisposable را برمی‌گرداند. فقط-خواندنی IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | دسترسی به رابط پایه IPresentationComponent را فراهم می‌کند. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | مجموعه تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | مجموعه نویسندگان نظرات را برمی‌گرداند. فقط-خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | تاریخ و زمان را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. به‌طور پیش‌فرض زمان ایجاد این شیء Presentation است. قابل‌نوشتن DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | داده‌های سفارشی ارائه را برمی‌گرداند. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | مجموعه امضاهای استفاده‌شده برای امضای ارائه را برمی‌گرداند. فقط-خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است را برمی‌گرداند. فقط-خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | شماره اولین اسلاید در ارائه را نشان می‌دهد. قابل‌نوشتن Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | مدیر قلم‌ها را برمی‌گرداند. فقط-خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | مدیر سرصفحه/پاصفحه ارائه را برمی‌گرداند. فقط-خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام پیوندهای موجود در همه اسلایدهای ارائه (نه در اسلایدهای مستر، چیدمان یا یادداشت) را فراهم می‌کند. فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | مجموعه تمام تصاویر در ارائه را برمی‌گرداند. فقط-خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | فهرستی از تمام اسلایدهای چیدمان تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | مدیر مستر جزوه را برمی‌گرداند. فقط-خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | مدیر مستر یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | فهرستی از تمام اسلایدهای مستر تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | تم مستر ارائه را برمی‌گرداند. فقط-خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | مدیر مجوزهای این ارائه را دریافت می‌کند. فقط-خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | مجموعه برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را برمی‌گرداند. فقط-خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | شیء اندازه اسلاید را برمی‌گرداند. فقط-خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | اطلاعات درباره فرمتی که ارائه از آن بارگذاری شده است را برمی‌گرداند. فقط-خواندنی [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | پروژه VBA همراه ماکروهای ارائه را دریافت می‌کند. قابل‌نوشتن [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | مجموعه تمام فایل‌های ویدئویی جاسازی‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط-خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیحات |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | یک شیء bitmap بندانگشتی برای اسلایدهای مشخص شده از یک ارائه برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | یک شیء تصویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با اندازه مشخص برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | یک شیء تصویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با مقیاس‌گذاری سفارشی برمی‌گرداند. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | یک Slide، MasterSlide یا LayoutSlide بر اساس Id برمی‌گرداند. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | قطعات متن با فرمت یکسان در تمام پاراگراف‌ها در تمام اشکال قابل‌استفاده در همه اسلایدها را به هم می‌چسباند. |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | داده‌های تمام نمودارهای موجود در ارائه را از کتاب‌کاغذهای منبع خود بازخوانی می‌کند. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | تمام مطابقت‌های عبارت منظم را با رشته مشخص شده جایگزین می‌کند. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | تمام رخدادهای متن مشخص شده را با متن دیگر مشخص شده جایگزین می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | تمام اسلایدهای یک ارائه را در مجموعه‌ای از فایل‌های نشان‌گذاری XAML ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | تمام اسلایدهای یک ارائه را در فایلی با قالب مشخص شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | اسلایدهای مشخص‌شده از یک ارائه را به یک جریان در قالب مشخص شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک جریان در قالب مشخص شده و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | اسلایدهای مشخص‌شده از یک ارائه را در فایلی با قالب مشخص شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را در فایلی با قالب مشخص شده و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شده از یک ارائه را به یک جریان در قالب مشخص شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شده از یک ارائه را در فایلی با قالب مشخص شده ذخیره می‌کند. |

### موارد مرتبط

* رابط [IPresentationComponent](../ipresentationcomponent)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->