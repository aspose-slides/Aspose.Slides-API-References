---
title: IPresentation
second_title: Aspose.Sildes برای .NET مرجع API
description: سند ارائه
type: docs
weight: 6750
url: /fa/aspose.slides/ipresentation/
---
## IPresentation رابط

سند ارائه

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## ویژگی‌ها

| نام | توضیح |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | برمی‌گرداند تمام بخش‌های داده سفارشی در ارائه. فقط-خواندنی [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | برمی‌گرداند رابط IDisposable. فقط-خواندنی IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | اجازه می‌دهد رابط پایه IPresentationComponent را دریافت کند. فقط-خواندنی [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | برمی‌گرداند مجموعه تمام فایل‌های صوتی جاسازی‌شده در ارائه. فقط-خواندنی [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | برمی‌گرداند مجموعه نویسندگان نظرات. فقط-خواندنی [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | برمی‌گرداند یا تنظیم می‌کند تاریخ و زمان که محتوی فیلدهای datetime را جایگزین می‌کند. زمان ایجاد شی Presentation به‌صورت پیش‌فرض. خواندنی-نوشتنی DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | برمی‌گرداند داده‌های سفارشی ارائه. فقط-خواندنی [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | برمی‌گرداند سبک متن پیش‌فرض برای اشکال. فقط-خواندنی [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | برمی‌گرداند مجموعه امضاهایی که برای امضای ارائه استفاده شده‌اند. فقط-خواندنی [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | برمی‌گرداند شی DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است. فقط-خواندنی [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | نمایش‌دهنده شماره اولین اسلاید در ارائه. خواندنی-نوشتنی Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | برمی‌گرداند مدیر قلم‌ها. فقط-خواندنی [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | برمی‌گرداند مدیر HeaderFooter ارائه. فقط-خواندنی [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | دسترسی آسان به تمام هایپرلینک‌های موجود در تمام اسلایدهای ارائه (به‌جز اسلایدهای master، layout، notes). فقط-خواندنی [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | برمی‌گرداند مجموعه تمام تصاویر در ارائه. فقط-خواندنی [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | برمی‌گرداند فهرست تمام اسلایدهای layout که در ارائه تعریف شده‌اند. فقط-خواندنی [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | برمی‌گرداند مدیر handout master. فقط-خواندنی [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | برمی‌گرداند مدیر notes master. فقط-خواندنی [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | برمی‌گرداند فهرست تمام اسلایدهای master که در ارائه تعریف شده‌اند. فقط-خواندنی [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | برمی‌گرداند تم master ارائه. فقط-خواندنی [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | برمی‌گرداند شی اندازه اسلاید notes. فقط-خواندنی [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | دریافت می‌کند مدیر مجوزها برای این ارائه. فقط-خواندنی [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | برمی‌گرداند فهرست تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند. فقط-خواندنی [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | برمی‌گرداند مجموعه برچسب‌های حساسیتی اعمال‌شده به سند ارائه. فقط-خواندنی [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | برمی‌گرداند فهرست تمام اسلایدهای تعریف‌شده در ارائه. فقط-خواندنی [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | برمی‌گرداند شی اندازه اسلاید. فقط-خواندنی [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | برمی‌گرداند اطلاعات دربارهٔ قالبی که ارائه از آن بارگذاری شده است. فقط-خواندنی [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | دریافت می‌کند پروژه VBA با ماکروهای ارائه. خواندنی-نوشتنی [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | برمی‌گرداند مجموعه تمام فایل‌های ویدئویی جاسازی‌شده در ارائه. فقط-خواندنی [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | دریافت می‌کند ویژگی‌های نمای گسترده ارائه. فقط-خواندنی [`IViewProperties`](../iviewproperties). |

## متدها

| نام | توضیح |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | برمی‌گرداند یک شی تصویر بند انگشتی برای تمام اسلایدهای ارائه. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | برمی‌گرداند یک شی Bitmap بند انگشتی برای اسلایدهای مشخص شده از ارائه. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | برمی‌گرداند یک شی تصویر بند انگشتی برای تمام اسلایدهای ارائه با اندازهٔ مشخص‌شده. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | برمی‌گرداند یک شی تصویر بند انگشتی برای تمام اسلایدهای ارائه با مقیاس‌گذاری دلخواه. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | برمی‌گرداند یک شی تصویر بند انگشتی برای اسلایدهای مشخص‌شده از ارائه با اندازهٔ مشخص. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | برمی‌گرداند یک شی تصویر بند انگشتی برای اسلایدهای مشخص‌شده از ارائه با مقیاس‌گذاری دلخواه. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | برمی‌گرداند یک Slide، MasterSlide یا LayoutSlide بر پایهٔ شناسه. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | برجسته می‌کند تمام موارد منطبق با عبارت منظم با رنگ مشخص‌شده. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | برجسته می‌کند تمام موارد متن نمونه با رنگ مشخص‌شده. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | برجسته می‌کند تمام موارد متن نمونه با رنگ مشخص‌شده. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | اتصالات قطعات متن با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول در همه اسلایدها را ترکیب می‌کند. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | جایگزین می‌کند تمام موارد منطبق با عبارت منظم با رشتهٔ مشخص‌شده. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | جایگزین می‌کند تمام occurrences متن مشخص‌شده با متن دیگری که مشخص شده است. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | ذخیره می‌کند تمام اسلایدهای یک ارائه به مجموعه‌ای از فایل‌ها که نشانگر نشانه‌گذاری XAML هستند. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | ذخیره می‌کند تمام اسلایدهای یک ارائه به یک جریان (Stream) در قالب مشخص‌شده. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | ذخیره می‌کند تمام اسلایدهای یک ارائه به یک فایل با قالب مشخص‌شده. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه به یک جریان در قالب مشخص‌شده. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | ذخیره می‌کند تمام اسلایدهای یک ارائه به یک جریان در قالب مشخص‌شده و با گزینه‌های اضافی. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه به یک فایل با قالب مشخص‌شده. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | ذخیره می‌کند تمام اسلایدهای یک ارائه به یک فایل با قالب مشخص‌شده و با گزینه‌های اضافی. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه به یک جریان در قالب مشخص‌شده. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه به یک فایل با قالب مشخص‌شده. |

### مراجع

* رابط [IPresentationComponent](../ipresentationcomponent)
* فضای‌نام [Aspose.Slides](../../aspose.slides)
* مجمع [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->