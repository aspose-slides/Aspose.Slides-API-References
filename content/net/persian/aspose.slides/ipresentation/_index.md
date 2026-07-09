---
title: IPresentation
second_title: Aspose.Sildes برای .NET مرجع API
description: سند ارائه
type: docs
weight: 6750
url: /fa/aspose.slides/ipresentation/
---
## رابط IPresentation

سند ارائه

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | تمام بخش‌های داده سفارشی موجود در ارائه را برمی‌گرداند. فقط خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | رابط IDisposable را برمی‌گرداند. فقط خواندنی IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | مجوز دسترسی به رابط پایه IPresentationComponent را می‌دهد. فقط خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | مجموعه تمام فایل‌های صوتی داخلی در ارائه را برمی‌گرداند. فقط خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | مجموعه نویسندگان نظرات را برمی‌گرداند. فقط خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | تاریخ و زمان را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. به‌طور پیش‌فرض زمان ایجاد این شیء Presentation است. قابل خواندن/نوشتن DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | داده‌های سفارشی ارائه را برمی‌گرداند. فقط خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. فقط خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | مجموعه امضاهای استفاده‌شده برای امضای ارائه را برمی‌گرداند. فقط خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | شیء DocumentProperties را که شامل خصوصیات استاندارد و سفارشی سند است، برمی‌گرداند. فقط خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | شماره اسلاید اول در ارائه را نشان می‌دهد. قابل خواندن/نوشتن Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | مدیر قلم‌ها را برمی‌گرداند. فقط خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | مدیر HeaderFooter ارائه را برمی‌گرداند. فقط خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام هایپرلینک‌های موجود در تمام اسلایدهای ارائه (نه در اسلایدهای مستر، طرح‌بندی، یادداشت) را فراهم می‌کند. فقط خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | مجموعه تمام تصاویر موجود در ارائه را برمی‌گرداند. فقط خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند. فقط خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | مدیر Handout master را برمی‌گرداند. فقط خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | مدیر Notes master را برمی‌گرداند. فقط خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | فهرستی از تمام اسلایدهای مستر تعریف‌شده در ارائه را برمی‌گرداند. فقط خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | تم مستر ارائه را برمی‌گرداند. فقط خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. فقط خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | مدیر مجوزهای این ارائه را دریافت می‌کند. فقط خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | مجموعه برچسب‌های حساسیتی اعمال‌شده به سند ارائه را برمی‌گرداند. فقط خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | شیء اندازه اسلاید را برمی‌گرداند. فقط خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | اطلاعاتی درباره فرمت منبعی که ارائه از آن بارگذاری شده است را برمی‌گرداند. فقط خواندنی [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | پروژه VBA با ماکروهای ارائه را دریافت می‌کند. قابل خواندن/نوشتن [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | مجموعه تمام فایل‌های ویدئویی داخلی در ارائه را برمی‌گرداند. فقط خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه را برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | اشیاء Bitmap بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص را برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس‌بندی سفارشی را برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | اشیاء تصویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با اندازه مشخص را برمی‌گرداند. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | اشیاء تصویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با مقیاس‌بندی سفارشی را برمی‌گرداند. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | تمام تطابق‌های عبارات باقاعده را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | تمام تطابق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | تمام تطابق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | بخش‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها ادغام می‌کند. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | تمام تطابق‌های عبارات باقاعده را با رشته مشخص شده جایگزین می‌کند. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | تمام وقوع‌های متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌های نمایانگر علامت‌گذاری XAML ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | تمام اسلایدهای یک ارائه را به یک فایل با فرمت مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | اسلایدهای مشخص‌شده از یک ارائه را به یک جریان در فرمت مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص‌شده و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | اسلایدهای مشخص‌شده از یک ارائه را به یک فایل با فرمت مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | تمام اسلایدهای یک ارائه را به یک فایل با فرمت مشخص‌شده و با گزینه‌های اضافی ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شده از یک ارائه را به یک جریان در فرمت مشخص‌شده ذخیره می‌کند. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | اسلایدهای مشخص‌شده از یک ارائه را به یک فایل با فرمت مشخص‌شده ذخیره می‌کند. |

### مراجع

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->