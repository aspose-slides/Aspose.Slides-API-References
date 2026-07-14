---
title: IPresentation
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
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

| متد | توضیح |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | بازمی‌گرداند یا تنظیم می‌کند تاریخ و زمان که محتوای فیلدهای datetime را جایگزین می‌کند. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | بازمی‌گرداند یا تنظیم می‌کند تاریخ و زمان که محتوای فیلدهای datetime را جایگزین می‌کند. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | بازمی‌گرداند مدیر HeaderFooter ارائه. |
| [getProtectionManager()](#getProtectionManager--) | دریافت می‌کند مدیر مجوزها برای این ارائه. |
| [getSlides()](#getSlides--) | بازمی‌گرداند فهرستی از تمام اسلایدهای تعریف‌شده در ارائه. |
| [getSections()](#getSections--) | بازمی‌گرداند فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه. |
| [getSlideSize()](#getSlideSize--) | بازمی‌گرداند شیء اندازه اسلاید. |
| [getNotesSize()](#getNotesSize--) | بازمی‌گرداند شیء اندازه اسلاید یادداشت‌ها. |
| [getLayoutSlides()](#getLayoutSlides--) | بازمی‌گرداند فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه. |
| [getMasters()](#getMasters--) | بازمی‌گرداند فهرستی از تمام اسلایدهای اصلی تعریف‌شده در ارائه. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | بازمی‌گرداند مدیر اصلی یادداشت‌ها. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | بازمی‌گرداند مدیر اصلی برگه‌های پخش. |
| [getFontsManager()](#getFontsManager--) | بازمی‌گرداند مدیر قلم‌ها. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | بازمی‌گرداند سبک متن پیش‌فرض برای اشکال. |
| [getCommentAuthors()](#getCommentAuthors--) | بازمی‌گرداند مجموعهٔ نویسندگان نظرات. |
| [getDocumentProperties()](#getDocumentProperties--) | بازمی‌گرداند شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است. |
| [getImages()](#getImages--) | بازمی‌گرداند مجموعهٔ تمام تصاویر در ارائه. |
| [getAudios()](#getAudios--) | بازمی‌گرداند مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه. |
| [getVideos()](#getVideos--) | بازمی‌گرداند مجموعهٔ تمام فایل‌های ویدیویی جاسازی‌شده در ارائه. |
| [getCustomData()](#getCustomData--) | بازمی‌گرداند داده‌های سفارشی ارائه. |
| [getVbaProject()](#getVbaProject--) | دریافت می‌کند پروژه VBA همراه با ماکروهای ارائه. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | دریافت می‌کند پروژه VBA همراه با ماکروهای ارائه. |
| [getSourceFormat()](#getSourceFormat--) | بازمی‌گرداند اطلاعات دربارهٔ قالبی که ارائه از آن بارگذاری شده است. |
| [getMasterTheme()](#getMasterTheme--) | بازمی‌گرداند تم اصلی ارائه. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به تمام پیوندهای فراگیر موجود در تمام اسلایدهای ارائه (نه در اسلایدهای اصلی، طرح‌بندی یا یادداشت‌ها) را فراهم می‌کند. |
| [getViewProperties()](#getViewProperties--) | دریافت می‌کند ویژگی‌های نمای کلی ارائه. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | نشان‌دهندهٔ شمارهٔ اسلاید اول در ارائه است. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | نشان‌دهندهٔ شمارهٔ اسلاید اول در ارائه است. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | بازمی‌گرداند تمام بخش‌های دادهٔ سفارشی در ارائه. |
| [getDigitalSignatures()](#getDigitalSignatures--) | بازمی‌گرداند مجموعهٔ امضاهایی که برای امضای ارائه استفاده شده‌اند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | بازمی‌گرداند مجموعهٔ برچسب‌های حساسیتی که بر سند ارائه اعمال شده‌اند. |
| [save(String fname, int format)](#save-java.lang.String-int-) | ذخیره می‌کند تمام اسلایدهای یک ارائه به فایل با قالب مشخص. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | ذخیره می‌کند تمام اسلایدهای یک ارائه به جریان در قالب مشخص. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه به فایل با قالب مشخص و گزینه‌های اضافی. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه به جریان در قالب مشخص و گزینه‌های اضافی. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به فایل با قالب مشخص. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به فایل با قالب مشخص. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به جریان در قالب مشخص. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به جریان در قالب مشخص. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | ذخیره می‌کند تمام اسلایدهای یک ارائه به مجموعه‌ای از فایل‌ها که علامت‌گذاری XAML را نمایند. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی IImage برای اسلایدهای مشخص‌شدهٔ یک ارائه. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس سفارشی. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای اسلایدهای مشخص‌شدهٔ یک ارائه با مقیاس سفارشی. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | بازمی‌گرداند یک مجموعهٔ تصویر بندانگشت IImage برای اسلایدهای مشخص‌شدهٔ یک ارائه با اندازهٔ مشخص. |
| [getSlideById(long id)](#getSlideById-long-) | بازمی‌گرداند یک اسلاید، MasterSlide یا LayoutSlide بر اساس شناسه. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | ترکیب می‌کند قسمت‌های متن با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | برجسته می‌کند تمام تطابق‌های متن نمونه با رنگ مشخص‌شده. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | برجسته می‌کند تمام تطابق‌های متن نمونه با رنگ مشخص‌شده. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | برجسته می‌کند تمام تطابق‌های عبارت منظم با رنگ مشخص‌شده. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | جایگزین می‌کند تمام رخدادهای متن مشخص‌شده با متن دیگری که مشخص شده است. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | جایگزین می‌کند تمام تطابق‌های عبارت منظم با رشتهٔ مشخص‌شده. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

بازمی‌گرداند یا تنظیم می‌کند تاریخ و زمان که محتوای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شیء Presentation به طور پیش‌فرض. خواندن/نوشتن java.util.Date.

**بازمی‌گرداند:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

بازمی‌گرداند یا تنظیم می‌کند تاریخ و زمان که محتوای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شیء Presentation به طور پیش‌فرض. خواندن/نوشتن java.util.Date.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

بازمی‌گرداند مدیر HeaderFooter ارائه. فقط خواندنی [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**بازمی‌گرداند:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

دریافت می‌کند مدیر مجوزها برای این ارائه. فقط خواندنی [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**بازمی‌گرداند:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

بازمی‌گرداند فهرستی از تمام اسلایدهای تعریف‌شده در ارائه. فقط خواندنی [ISlideCollection](../../com.aspose.slides/islidecollection).

**بازمی‌گرداند:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

بازمی‌گرداند فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه. فقط خواندنی [ISectionCollection](../../com.aspose.slides/isectioncollection).

**بازمی‌گرداند:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

بازمی‌گرداند شیء اندازه اسلاید. فقط خواندنی [ISlideSize](../../com.aspose.slides/islidesize).

**بازمی‌گرداند:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

بازمی‌گرداند شیء اندازه اسلاید یادداشت‌ها. فقط خواندنی [INotesSize](../../com.aspose.slides/inotessize).

**بازمی‌گرداند:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

بازمی‌گرداند فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه. فقط خواندنی [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

می‌توانید به API جایگزین برای اضافه/درج/حذف/کلون کردن اسلایدهای طرح‌بندی از طریق ویژگی IMasterSlide.LayoutSlides دسترسی پیدا کنید.

**بازمی‌گرداند:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

بازمی‌گرداند فهرستی از تمام اسلایدهای اصلی تعریف‌شده در ارائه. فقط خواندنی [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**بازمی‌گرداند:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

بازمی‌گرداند مدیر اصلی یادداشت‌ها. فقط خواندنی [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**بازمی‌گرداند:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

بازمی‌گرداند مدیر اصلی برگه‌های پخش. فقط خواندنی [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**بازمی‌گرداند:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

بازمی‌گرداند مدیر قلم‌ها. فقط خواندنی [IFontsManager](../../com.aspose.slides/ifontsmanager).

**بازمی‌گرداند:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

بازمی‌گرداند سبک متن پیش‌فرض برای اشکال. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازمی‌گرداند:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

بازمی‌گرداند مجموعهٔ نویسندگان نظرات. فقط خواندنی [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**بازمی‌گرداند:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

بازمی‌گرداند شیء DocumentProperties که شامل ویژگی‌های استاندارد و سفارشی سند است. فقط خواندنی [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**بازمی‌گرداند:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

بازمی‌گرداند مجموعهٔ تمام تصاویر در ارائه. فقط خواندنی [IImageCollection](../../com.aspose.slides/iimagecollection).

**بازمی‌گرداند:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

بازمی‌گرداند مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه. فقط خواندنی [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**بازمی‌گرداند:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

بازمی‌گرداند مجموعهٔ تمام فایل‌های ویدیویی جاسازی‌شده در ارائه. فقط خواندنی [IVideoCollection](../../com.aspose.slides/ivideocollection).

**بازمی‌گرداند:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

بازمی‌گرداند داده‌های سفارشی ارائه. فقط خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازمی‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

دریافت می‌کند پروژه VBA همراه با ماکروهای ارائه. خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**بازمی‌گرداند:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

دریافت می‌کند پروژه VBA همراه با ماکروهای ارائه. خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

بازمی‌گرداند اطلاعات دربارهٔ فرم‌تی که ارائه از آن بارگذاری شده است. فقط خواندنی [SourceFormat](../../com.aspose.slides/sourceformat).

**بازمی‌گرداند:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

بازمی‌گرداند تم اصلی ارائه. فقط خواندنی [IMasterTheme](../../com.aspose.slides/imastertheme).

**بازمی‌گرداند:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به تمام پیوندهای فراگیر موجود در تمام اسلایدهای ارائه (نه در اسلایدهای اصلی، طرح‌بندی یا یادداشت‌ها) را فراهم می‌کند. فقط خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازمی‌گرداند:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

دریافت می‌کند ویژگی‌های نمای کلی ارائه. فقط خواندنی [IViewProperties](../../com.aspose.slides/iviewproperties).

**بازمی‌گرداند:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

نشان‌دهندهٔ شمارهٔ اسلاید اول در ارائه است. خواندن/نوشتن int.

**بازمی‌گرداند:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

نشان‌دهندهٔ شمارهٔ اسلاید اول در ارائه است. خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

بازمی‌گرداند تمام بخش‌های دادهٔ سفارشی در ارائه. فقط خواندنی ICustomXmlPart[].

**بازمی‌گرداند:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

بازمی‌گرداند مجموعهٔ امضاهایی که برای امضای ارائه استفاده شده‌اند. فقط خواندنی [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**بازمی‌گرداند:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

بازمی‌گرداند مجموعهٔ برچسب‌های حساسیتی که بر سند ارائه اعمال شده‌اند. فقط خواندنی [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print the applied labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Add the new label
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Get the sensitivity label Id from the policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Get the Azure AD site identifier from the policy
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
``` 
public abstract void save(String fname, int format)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه به فایل با قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد‌شده. |
| format | int | قالب داده‌های صادرشده. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه به جریان در قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | قالب داده‌های صادرشده. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه به فایل با قالب مشخص و گزینه‌های اضافی.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد‌شده. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافه. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

ذخیره می‌کند تمام اسلایدهای یک ارائه به جریان در قالب مشخص و گزینه‌های اضافی.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافه. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به فایل با قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد‌شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | قالب داده‌های صادرشده. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

ذخیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به فایل با قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد‌شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافه. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

ذیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به جریان در قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | قالب داده‌های صادرشده. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

ذیره می‌کند اسلایدهای مشخص‌شدهٔ یک ارائه به جریان در قالب مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | قالب داده‌های صادرشده. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های قالب اضافه. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

ذیره می‌کند تمام اسلایدهای یک ارائه به مجموعه‌ای از فایل‌ها که علامت‌گذاری XAML را نمایند.

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
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | گزینه‌های قالب XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

بازمی‌گرداند یک مجموعهٔ IImage تصویر بندانگشتی برای اسلایدهای مشخص‌شدهٔ یک ارائه.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس سفارشی.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقدار مقیاس این تصویر بندانگشتی در جهت محور X. |
| scaleY | float | مقدار مقیاس این تصویر بندانگشتی در جهت محور Y. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای اسلایدهای مشخص‌شدهٔ یک ارائه با مقیاس سفارشی.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| scaleX | float | مقدار مقیاس این تصویر بندانگشتی در جهت محور X. |
| scaleY | float | مقدار مقیاس این تصویر بندانگشتی در جهت محور Y. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازهٔ مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازهٔ تصویری که باید ایجاد شود. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

بازمی‌گرداند یک مجموعهٔ تصویر بندانگشتی برای اسلایدهای مشخص‌شدهٔ یک ارائه با اندازهٔ مشخص.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازهٔ تصویری که باید ایجاد شود. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getSlideById(long id) {#getSlideById-long-}
``` 
public abstract IBaseSlide getSlideById(long id)
```

بازمی‌گرداند یک اسلاید، MasterSlide یا LayoutSlide بر اساس شناسه.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| id | long | شناسهٔ اسلاید. |

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - شیء IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

ترکیب می‌کند قسمت‌های متن با قالب‌بندی یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

برجسته می‌کند تمام تطابق‌های متن نمونه با رنگ مشخص‌شده.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانه 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن را برجسته می‌کند. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

برجسته می‌کند تمام تطابق‌های متن نمونه با رنگ مشخص‌شده.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانه 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن را برجسته می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

برجسته می‌کند تمام تطابق‌های عبارت منظم با رنگ مشخص‌شده.

--------------------

> ``` 
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // برجسته‌سازی تمام موارد جداگانه 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های برجسته. |
| highlightColor | java.lang.Integer | رنگی که متن را برجسته می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

جایگزین می‌کند تمام رخدادهای متن مشخص‌شده با متن دیگری که مشخص شده است.

--------------------

> ``` 
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانه 'the' با '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| oldText | java.lang.String | رشته‌ای که باید جایگزین شود. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

جایگزین می‌کند تمام تطابق‌های عبارت منظم با رشتهٔ مشخص‌شده.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // جایگزینی تمام موارد جداگانه 'the' با '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های جایگزین. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای رشته‌های جایگزین را تغییر می‌دهد. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء فراخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |