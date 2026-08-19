---
title: IPresentation
second_title: مرجع API Aspose.Slides برای جاوا
description: سند ارائه
type: docs
url: /fa/com.aspose.slides/ipresentation/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

سند ارائه
## متدها

| متد | توضیح |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter ارائه را برمی‌گرداند. |
| [getProtectionManager()](#getProtectionManager--) | مدیر مجوزهای این ارائه را دریافت می‌کند. |
| [getSlides()](#getSlides--) | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. |
| [getSections()](#getSections--) | فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. |
| [getSlideSize()](#getSlideSize--) | شیء اندازه اسلاید را برمی‌گرداند. |
| [getNotesSize()](#getNotesSize--) | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. |
| [getLayoutSlides()](#getLayoutSlides--) | فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند. |
| [getMasters()](#getMasters--) | فهرستی از تمام اسلایدهای مستر تعریف‌شده در ارائه را برمی‌گرداند. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | مدیر مستر یادداشت‌ها را برمی‌گرداند. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | مدیر مستر برگه‌های توزیعی را برمی‌گرداند. |
| [getFontsManager()](#getFontsManager--) | مدیر قلم‌ها را برمی‌گرداند. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. |
| [getCommentAuthors()](#getCommentAuthors--) | مجموعهٔ نویسندگان نظرات را برمی‌گرداند. |
| [getDocumentProperties()](#getDocumentProperties--) | شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است. |
| [getImages()](#getImages--) | مجموعهٔ تمام تصاویر موجود در ارائه را برمی‌گرداند. |
| [getAudios()](#getAudios--) | مجموعهٔ تمام فایل‌های صوتی توکار در ارائه را برمی‌گرداند. |
| [getVideos()](#getVideos--) | مجموعهٔ تمام فایل‌های ویدئویی توکار در ارائه را برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی ارائه را برمی‌گرداند. |
| [getVbaProject()](#getVbaProject--) | پروژه VBA حاوی ماکروهای ارائه را دریافت می‌کند. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | پروژه VBA حاوی ماکروهای ارائه را دریافت می‌کند. |
| [getSourceFormat()](#getSourceFormat--) | اطلاعاتی درباره فرمت منبعی که ارائه از آن بارگذاری شده است را برمی‌گرداند. |
| [getMasterTheme()](#getMasterTheme--) | طرح اصلی (master theme) ارائه را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به تمام پیوندهای موجود در تمامی اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت) را فراهم می‌کند. |
| [getViewProperties()](#getViewProperties--) | ویژگی‌های نمایش سراسری ارائه را دریافت می‌کند. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | تمام بخش‌های داده سفارشی در ارائه را برمی‌گرداند. |
| [getDigitalSignatures()](#getDigitalSignatures--) | مجموعهٔ امضایی که برای امضای ارائه استفاده شده‌اند را برمی‌گرداند. |
| [getSensitivityLabels()](#getSensitivityLabels--) | مجموعهٔ برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را برمی‌گرداند. |
| [save(String fname, int format)](#save-java.lang.String-int-) | تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص و گزینه‌های اضافی ذخیره می‌کند. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص و گزینه‌های اضافی ذخیره می‌کند. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | اسلایدهای مشخص‌شده یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص‌شده یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | اسلایدهای مشخص‌شده یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص‌شده یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که مارکاپ XAML را نشان می‌دهند ذخیره می‌کند. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس‌بندی سفارشی را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه با مقیاس‌بندی سفارشی را برمی‌گرداند. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | شیء تصویر بندانگشتی برای تمام اسلایدهای یک ارائه با سایز مشخص را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | شیء تصویر بندانگشتی برای اسلایدهای مشخص‌شده یک ارائه با سایز مشخص را برمی‌گرداند. |
| [getSlideById(long id)](#getSlideById-long-) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دسته‌های متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها ترکیب می‌کند. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام موارد متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمام موارد تطبیق عبارات منظم را با رنگ مشخص برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام رخدادهای متن مشخص‌شده را با متن دیگری که مشخص شده است جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام موارد تطبیق عبارات منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. قابل خواندن/قابل نوشتن java.util.Date.

**بازگشت:**  
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتوای فیلدهای datetime را جایگزین می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. قابل خواندن/قابل نوشتن java.util.Date.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter ارائه را برمی‌گرداند. **فقط خواندنی** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**بازگشت:**  
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

مدیر مجوزهای این ارائه را دریافت می‌کند. **فقط خواندنی** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**بازگشت:**  
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. **فقط خواندنی** [ISlideCollection](../../com.aspose.slides/islidecollection).

**بازگشت:**  
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

فهرستی از تمام بخش‌های اسلاید که در ارائه تعریف شده‌اند را برمی‌گرداند. **فقط خواندنی** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**بازگشت:**  
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

شیء اندازه اسلاید را برمی‌گرداند. **فقط خواندنی** [ISlideSize](../../com.aspose.slides/islidesize).

**بازگشت:**  
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. **فقط خواندنی** [INotesSize](../../com.aspose.slides/inotessize).

**بازگشت:**  
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند. **فقط خواندنی** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

می‌توانید از API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌بندی با استفاده از ویژگی IMasterSlide.LayoutSlides استفاده کنید.

**بازگشت:**  
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

فهرستی از تمام اسلایدهای مستر تعریف‌شده در ارائه را برمی‌گرداند. **فقط خواندنی** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**بازگشت:**  
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

مدیر مستر یادداشت‌ها را برمی‌گرداند. **فقط خواندنی** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**بازگشت:**  
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

مدیر مستر برگه‌های توزیعی را برمی‌گرداند. **فقط خواندنی** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**بازگشت:**  
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

مدیر قلم‌ها را برمی‌گرداند. **فقط خواندنی** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**بازگشت:**  
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. **فقط خواندنی** [ITextStyle](../../com.aspose.slides/itextstyle).

**بازگشت:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

مجموعهٔ نویسندگان نظرات را برمی‌گرداند. **فقط خواندنی** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**بازگشت:**  
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است. **فقط خواندنی** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**بازگشت:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

مجموعهٔ تمام تصاویر موجود در ارائه را برمی‌گرداند. **فقط خواندنی** [IImageCollection](../../com.aspose.slides/iimagecollection).

**بازگشت:**  
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

مجموعهٔ تمام فایل‌های صوتی توکار در ارائه را برمی‌گرداند. **فقط خواندنی** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**بازگشت:**  
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

مجموعهٔ تمام فایل‌های ویدئویی توکار در ارائه را برمی‌گرداند. **فقط خواندنی** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**بازگشت:**  
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

داده‌های سفارشی ارائه را برمی‌گرداند. **فقط خواندنی** [ICustomData](../../com.aspose.slides/icustomdata).

**بازگشت:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

پروژه VBA حاوی ماکروهای ارائه را دریافت می‌کند. **قابل خواندن/قابل نوشتن** [IVbaProject](../../com.aspose.slides/ivbaproject).

**بازگشت:**  
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

پروژه VBA حاوی ماکروهای ارائه را دریافت می‌کند. **قابل خواندن/قابل نوشتن** [IVbaProject](../../com.aspose.slides/ivbaproject).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

اطلاعاتی درباره فرمت منبعی که ارائه از آن بارگذاری شده است را برمی‌گرداند. **فقط خواندنی** [SourceFormat](../../com.aspose.slides/sourceformat).

**بازگشت:**  
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

طرح اصلی (master theme) ارائه را برمی‌گرداند. **فقط خواندنی** [IMasterTheme](../../com.aspose.slides/imastertheme).

**بازگشت:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

دسترس آسان به تمام پیوندهای موجود در تمامی اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت) را فراهم می‌کند. **فقط خواندنی** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازگشت:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

ویژگی‌های نمایش سراسری ارائه را دریافت می‌کند. **فقط خواندنی** [IViewProperties](../../com.aspose.slides/iviewproperties).

**بازگشت:**  
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد. **قابل خواندن/قابل نوشتن** int.

**بازگشت:**  
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

شمارهٔ اولین اسلاید در ارائه را نشان می‌دهد. **قابل خواندن/قابل نوشتن** int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

تمام بخش‌های داده سفارشی در ارائه را برمی‌گرداند. **فقط خواندنی** ICustomXmlPart[].

**بازگشت:**  
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

مجموعهٔ امضایی که برای امضای ارائه استفاده شده‌اند را برمی‌گرداند. **فقط خواندنی** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**بازگشت:**  
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

مجموعهٔ برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را برمی‌گرداند. **فقط خواندنی** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // چاپ برچسب‌های اعمال شده
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // افزودن برچسب جدید
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // دریافت شناسه برچسب حساسیت از سیاست
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // دریافت شناسه سایت Azure AD از سیاست
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص ذخیره می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجادشده. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

تمام اسلایدهای یک ارائه را در یک جریان با فرمت مشخص ذخیره می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را در فایلی با فرمت مشخص و گزینه‌های اضافی ذخیره می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجادشده. |
...
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافی. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را در فرمت مشخص شده و با گزینه‌های اضافی به یک Stream ذخیره می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | خروجی Stream. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافی. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

اسلایدهای مشخص شده‌ی یک ارائه را با فرمت مورد نظر به فایلی ذخیره می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده‌ی یک ارائه را با فرمت مورد نظر و گزینه‌های اضافی به فایلی ذخیره می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافی. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

اسلایدهای مشخص شده‌ی یک ارائه را در فرمت مورد نظر به یک Stream ذخیره می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | خروجی Stream. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده‌ی یک ارائه را در فرمت مورد نظر و با گزینه‌های اضافی به یک Stream ذخیره می‌کند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | خروجی Stream. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافی. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نشانگر قالب XAML هستند، ذخیره می‌کند.

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


**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | گزینه‌های قالب XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده‌ی یک ارائه باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس سفارشی باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| scaleX | float | مقدار مقیاس‌بندی در جهت محور X. |
| scaleY | float | مقدار مقیاس‌بندی در جهت محور Y. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده‌ی یک ارائه با مقیاس سفارشی باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| scaleX | float | مقدار مقیاس‌بندی در جهت محور X. |
| scaleY | float | مقدار مقیاس‌بندی در جهت محور Y. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| imageSize | java.awt.Dimension | اندازهٔ تصویری که باید ساخته شود. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده‌ی یک ارائه با اندازه مشخص باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| imageSize | java.awt.Dimension | اندازهٔ تصویری که باید ساخته شود. |

**Returns:**
com.aspose.slides.IImage[] - اشیاء IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

اسلاید، ماستر اسلاید یا لِیوت اسلاید را بر اساس شناسه باز می‌گرداند.

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | long | شناسهٔ اسلاید. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - شیء IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

قسمت‌های متنی با قالب‌بندی یکسان را در تمام پاراگراف‌های تمام اشکال قابل قبول در تمام اسلایدها ترکیب می‌کند.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام مطابقت‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء Callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

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


**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های مورد برجسته. |
| highlightColor | java.awt.Color | رنگی که متن با آن برجسته می‌شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء Callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام رخدادهای متن مشخص شده را با متن دیگر جایگزین می‌کند.

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

**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| oldText | java.lang.String | رشته‌ای که باید جایگزین شود. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء Callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص شده جایگزین می‌کند.

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


**Parameters:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های قابل جایگزینی. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای رشته‌های قابل جایگزینی را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء Callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |