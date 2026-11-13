---
title: IPresentation
second_title: مرجع API Aspose.Slides برای جاوا
description: سند ارائه
type: docs
url: /fa/com.aspose.slides/ipresentation/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

سند ارائه
## متدها

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | باز می‌گردد یا تنظیم می‌کند تاریخ و زمان که محتواهای فیلدهای datetime را جایگزین می‌کند. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | باز می‌گردد یا تنظیم می‌کند تاریخ و زمان که محتواهای فیلدهای datetime را جایگزین می‌کند. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | باز می‌گردد مدیر HeaderFooter ارائه. |
| [getProtectionManager()](#getProtectionManager--) | دست می‌گیرد مدیر مجوزها برای این ارائه. |
| [getSlides()](#getSlides--) | باز می‌گردد فهرستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند. |
| [getSections()](#getSections--) | باز می‌گردد فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند. |
| [getSlideSize()](#getSlideSize--) | باز می‌گردد شیء اندازه اسلاید. |
| [getNotesSize()](#getNotesSize--) | باز می‌گردد شیء اندازه اسلاید یادداشت‌ها. |
| [getLayoutSlides()](#getLayoutSlides--) | باز می‌گردد فهرستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند. |
| [getMasters()](#getMasters--) | باز می‌گردد فهرستی از تمام اسلایدهای مستر که در ارائه تعریف شده‌اند. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | باز می‌گردد مدیر یادداشت‌های مستر. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | باز می‌گردد مدیر توزیع‌های دست‌نویس مستر. |
| [getFontsManager()](#getFontsManager--) | باز می‌گردد مدیر قلم‌ها. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | باز می‌گردد سبک متن پیش‌فرض برای شکل‌ها. |
| [getCommentAuthors()](#getCommentAuthors--) | باز می‌گردد مجموعه‌ای از نویسندگان نظرات. |
| [getDocumentProperties()](#getDocumentProperties--) | باز می‌گردد شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است. |
| [getImages()](#getImages--) | باز می‌گردد مجموعه‌ای از تمام تصاویر موجود در ارائه. |
| [getAudios()](#getAudios--) | باز می‌گردد مجموعه‌ای از تمام فایل‌های صوتی توکار در ارائه. |
| [getVideos()](#getVideos--) | باز می‌گردد مجموعه‌ای از تمام فایل‌های ویدئویی توکار در ارائه. |
| [getCustomData()](#getCustomData--) | باز می‌گردد داده‌های سفارشی ارائه. |
| [getVbaProject()](#getVbaProject--) | دست می‌گیرد پروژه VBA با ماکروهای ارائه. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | دست می‌گیرد پروژه VBA با ماکروهای ارائه. |
| [getSourceFormat()](#getSourceFormat--) | باز می‌گردد اطلاعات درباره فرمت‌ّی که ارائه از آن بارگذاری شده است. |
| [getMasterTheme()](#getMasterTheme--) | باز می‌گردد تم مستر ارائه. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به تمام هایپرلینک‌های موجود در تمام اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت). |
| [getViewProperties()](#getViewProperties--) | دست می‌گیرد ویژگی‌های نمای کلی ارائه. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | نشان می‌دهد شماره اولین اسلاید در ارائه. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | نشان می‌دهد شماره اولین اسلاید در ارائه. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | باز می‌گردد تمام بخش‌های داده سفارشی در ارائه. |
| [getDigitalSignatures()](#getDigitalSignatures--) | باز می‌گردد مجموعه‌ای از امضاهایی که برای امضای ارائه استفاده می‌شوند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | باز می‌گردد مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده به سند ارائه. |
| [save(String fname, int format)](#save-java.lang.String-int-) | ذخیره می‌کند تمام اسلایدهای یک ارائه در فایلی با فرمت مشخص. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | ذخیره می‌کند تمام اسلایدهای یک ارائه در جریان (stream) با فرمت مشخص. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه در فایلی با فرمت مشخص و با گزینه‌های اضافی. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه در جریان (stream) با فرمت مشخص و با گزینه‌های اضافی. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه در فایلی با فرمت تعیین‌شده. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه در فایلی با فرمت تعیین‌شده. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه در یک جریان (stream) با فرمت تعیین‌شده. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند اسلایدهای مشخص‌شده از یک ارائه در یک جریان (stream) با فرمت تعیین‌شده. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه در مجموعه‌ای از فایل‌ها که markup XAML را نشان می‌دهند. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | باز می‌گردد اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | باز می‌گردد اشیاء IImage بندانگشتی برای اسلایدهای مشخص‌شده از یک ارائه. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | باز می‌گردد اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | باز می‌گردد اشیاء تصویر بندانگشتی برای اسلایدهای مشخص‌شده از یک ارائه با مقیاس‌گذاری سفارشی. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | باز می‌گردد اشیاء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | باز می‌گردد اشیاء تصویر بندانگشتی برای اسلایدهای مشخص‌شده از یک ارائه با اندازه مشخص. |
| [getSlideById(long id)](#getSlideById-long-) | باز می‌گردد اسلاید، MasterSlide یا LayoutSlide بر اساس شناسه. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ترکیب می‌کند ران‌های با فرمت‌گذاری مشابه در تمام پاراگراف‌های تمام شکل‌های قابل‌قبول در تمام اسلایدها. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | برجسته می‌کند تمام مطابقت‌های متن نمونه با رنگ مشخص‌شده. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | برجسته می‌کند تمام مطابقت‌های متن نمونه با رنگ مشخص‌شده. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | برجسته می‌کند تمام مطابقت‌های عبارت منظم با رنگ مشخص‌شده. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | جایگزین می‌کند تمام رخدادهای متن مشخص‌شده با متن دیگری. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | جایگزین می‌کند تمام مطابقت‌های عبارت منظم با رشتهٔ مشخص‌شده. |
| [refreshChartsData()](#refreshChartsData--) | بارگذاری مجدد داده‌ها برای تمام نمودارها در ارائه از کتاب‌کارهای منبعشان. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | بارگذاری مجدد داده‌ها برای تمام نمودارها در ارائه از کتاب‌کارهای منبعشان. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

باز می‌گردد یا تنظیم می‌کند تاریخ و زمان که محتواهای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شی Presentation به‌صورت پیش‌فرض. **قابل خواندن و نوشتن** java.util.Date.

**باز می‌گردد:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

باز می‌گردد یا تنظیم می‌کند تاریخ و زمان که محتواهای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شی Presentation به‌صورت پیش‌فرض. **قابل خواندن و نوشتن** java.util.Date.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

باز می‌گردد مدیر HeaderFooter ارائه. **فقط-خواندنی** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**باز می‌گردد:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

دست می‌گیرد مدیر مجوزها برای این ارائه. **فقط-خواندنی** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**باز می‌گردد:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

باز می‌گردد فهرستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند. **فقط-خواندنی** [ISlideCollection](../../com.aspose.slides/islidecollection).

**باز می‌گردد:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

باز می‌گردد فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند. **فقط-خواندنی** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**باز می‌گردد:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

باز می‌گردد شیء اندازه اسلاید. **فقط-خواندنی** [ISlideSize](../../com.aspose.slides/islidesize).

**باز می‌گردد:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

باز می‌گردد شیء اندازه اسلاید یادداشت‌ها. **فقط-خواندنی** [INotesSize](../../com.aspose.slides/inotessize).

**باز می‌گردد:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

باز می‌گردد فهرستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند. **فقط-خواندنی** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

می‌توانید به API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌بندی از طریق ویژگی IMasterSlide.LayoutSlides دسترسی پیدا کنید.

**باز می‌گردد:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

باز می‌گردد فهرستی از تمام اسلایدهای مستر که در ارائه تعریف شده‌اند. **فقط-خواندنی** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**باز می‌گردد:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

باز می‌گردد مدیر یادداشت‌های مستر. **فقط-خواندنی** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**باز می‌گردد:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

باز می‌گردد مدیر توزیع‌های دست‌نویس مستر. **فقط-خواندنی** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**باز می‌گردد:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

باز می‌گردد مدیر قلم‌ها. **فقط-خواندنی** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**باز می‌گردد:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

باز می‌گردد سبک متن پیش‌فرض برای شکل‌ها. **فقط-خواندنی** [ITextStyle](../../com.aspose.slides/itextstyle).

**باز می‌گردد:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

باز می‌گردد مجموعه‌ای از نویسندگان نظرات. **فقط-خواندنی** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**باز می‌گردد:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

باز می‌گردد شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است. **فقط-خواندنی** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**باز می‌گردد:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

باز می‌گردد مجموعه‌ای از تمام تصاویر موجود در ارائه. **فقط-خواندنی** [IImageCollection](../../com.aspose.slides/iimagecollection).

**باز می‌گردد:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

باز می‌گردد مجموعه‌ای از تمام فایل‌های صوتی توکار در ارائه. **فقط-خواندنی** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**باز می‌گردد:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

باز می‌گردد مجموعه‌ای از تمام فایل‌های ویدئویی توکار در ارائه. **فقط-خواندنی** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**باز می‌گردد:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

باز می‌گردد داده‌های سفارشی ارائه. **فقط-خواندنی** [ICustomData](../../com.aspose.slides/icustomdata).

**باز می‌گردد:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

دست می‌گیرد پروژه VBA با ماکروهای ارائه. **قابل خواندن و نوشتن** [IVbaProject](../../com.aspose.slides/ivbaproject).

**باز می‌گردد:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

دست می‌گیرد پروژه VBA با ماکروهای ارائه. **قابل خواندن و نوشتن** [IVbaProject](../../com.aspose.slides/ivbaproject).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

باز می‌گردد اطلاعات درباره فرمت‌ّی که ارائه از آن بارگذاری شده است. **فقط-خواندنی** [SourceFormat](../../com.aspose.slides/sourceformat).

**باز می‌گردد:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

باز می‌گردد تم مستر ارائه. **فقط-خواندنی** [IMasterTheme](../../com.aspose.slides/imastertheme).

**باز می‌گردد:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به تمام هایپرلینک‌های موجود در تمام اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت). **فقط-خواندنی** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**باز می‌گردد:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

دست می‌گیرد ویژگی‌های نمای کلی ارائه. **فقط-خواندنی** [IViewProperties](../../com.aspose.slides/iviewproperties).

**باز می‌گردد:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

نشان می‌دهد شماره اولین اسلاید در ارائه. **قابل خواندن و نوشتن** int.

**باز می‌گردد:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

نشان می‌دهد شماره اولین اسلاید در ارائه. **قابل خواندن و نوشتن** int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

باز می‌گردد تمام بخش‌های داده سفارشی در ارائه. **فقط-خواندنی** ICustomXmlPart[].

**باز می‌گردد:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

باز می‌گردد مجموعه‌ای از امضاهایی که برای امضای ارائه استفاده می‌شوند. **فقط-خواندنی** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

باز می‌گردد مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده به سند ارائه. **فقط-خواندنی** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // چاپ برچسب‌های اعمال‌شده
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // افزودن برچسب جدید
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // دریافت شناسهٔ برچسب حساسیت از سیاست
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // دریافت شناسهٔ سایت Azure AD از سیاست
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گردد:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه در فایلی با فرمت مشخص.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایلی که ایجاد می‌شود. |
| format | int | فرمت داده‌های صادرشده. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه در یک جریان (stream) با فرمت مشخص.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های صادرشده. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
تمام اسلایدهای یک ارائه را با فرمت مشخص و با گزینه‌های اضافی به یک فایل ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافی. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را با فرمت مشخص و با گزینه‌های اضافی به یک جریان ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافی. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

اسلایدهای مشخص‌شده یک ارائه را با فرمت تعیین‌شده به یک فایل ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| format | int | قالب داده‌های صادرشده. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص‌شده یک ارائه را با فرمت تعیین‌شده به یک فایل ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافی. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

اسلایدهای مشخص‌شده یک ارائه را با فرمت تعیین‌شده به یک جریان ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| format | int | قالب داده‌های صادرشده. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص‌شده یک ارائه را با فرمت تعیین‌شده به یک جریان ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافی. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر علامت‌نگاری XAML هستند، ذخیره می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | گزینه‌های قالب XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |

**بازگرداندن:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

یک شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |

**بازگرداندن:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس‌گذاری سفارشی بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

**بازگرداندن:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

یک شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه با مقیاس‌گذاری سفارشی بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| scaleX | float | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور x استفاده می‌شود. |
| scaleY | float | مقداری که برای مقیاس‌بندی این تصویر بندانگشتی در جهت محور y استفاده می‌شود. |

**بازگرداندن:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

یک شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | java.awt.Dimension | اندازه تصویر برای ساخت. |

**بازگرداندن:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

یک شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه با اندازه مشخص بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای شامل موقعیت اسلایدها، آغاز از 1. |
| imageSize | java.awt.Dimension | اندازه تصویر برای ساخت. |

**بازگرداندن:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

یک Slide، MasterSlide یا LayoutSlide را بر اساس Id بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | long | Id یک اسلاید. |

**بازگرداندن:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

قطعات متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول در همه اسلایدها ترکیب می‌کند.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانهٔ 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانهٔ 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگشتی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانهٔ 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های برجسته. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگشتی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام رخدادهای متن مشخص‌شده را با متن دیگری جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانهٔ 'the' با '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | java.lang.String | رشته‌ای که باید جایگزین شود. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگشتی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام تطابق‌های عبارت منظم را با رشته مشخص جایگزین می‌کند.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانهٔ 'the' با '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های جایگزین. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای رشته‌های جایگزین‌شده را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازگشتی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

داده‌های تمام نمودارهای موجود در ارائه را از کتاب‌کارهای منبع خود مجدداً بارگیری می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```

داده‌های تمام نمودارهای موجود در ارائه را از کتاب‌کارهای منبع خود مجدداً بارگیری می‌کند.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| skipFailedCharts | boolean | تعیین می‌کند که آیا فرآیند بروزرسانی در صورت شکست یک نمودار ادامه یابد یا نه. اگر true باشد، نمودارهای باعث استثنا صرف‌نظر می‌شوند؛ در غیر این صورت استثنا ادامه می‌یابد. |