---
title: Presentation
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک ارائه Microsoft PowerPoint را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/presentation/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

یک ارائه Microsoft PowerPoint را نشان می‌دهد.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // یک شیء Presentation را که نشانگر یک فایل ارائه است ایجاد می‌کند
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید را دریافت کنید
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک شکل خودکار از نوع خط اضافه کنید
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // فایل ارائه را ذخیره کنید
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // هر فایل پشتیبانی‌شده‌ای را در Presentation بارگذاری کنید، مثلاً ppt، pptx، odp و غیره
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // فایل ارائه را ذخیره کنید
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Presentation()](#Presentation--) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است. |
| [Presentation(String file)](#Presentation-java.lang.String-) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود. |

## متدها

| متد | توضیح |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | تاریخ و زمانی را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | تاریخ و زمانی را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر HeaderFooter واقعی را برمی‌گرداند. |
| [getProtectionManager()](#getProtectionManager--) | مدیر مجوزهای این ارائه را دریافت می‌کند. |
| [getSlides()](#getSlides--) | لیستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. |
| [getSections()](#getSections--) | لیستی از تمام بخش‌های اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. |
| [getSlideSize()](#getSlideSize--) | شیء اندازه اسلاید را برمی‌گرداند. |
| [getNotesSize()](#getNotesSize--) | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. |
| [getLayoutSlides()](#getLayoutSlides--) | لیستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند را برمی‌گرداند. |
| [getMasters()](#getMasters--) | لیستی از تمام اسلایدهای مستر که در ارائه تعریف شده‌اند را برمی‌گرداند. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | مدیر مستر یادداشت‌ها را برمی‌گرداند. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | مدیر مستر برگه‌های توزیع را برمی‌گرداند. |
| [getFontsManager()](#getFontsManager--) | مدیر قلم‌ها را برمی‌گرداند. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. |
| [getCommentAuthors()](#getCommentAuthors--) | مجموعهٔ نویسندگان نظرات را برمی‌گرداند. |
| [getDocumentProperties()](#getDocumentProperties--) | شیء DocumentProperties را که شامل خصوصیات استاندارد و سفارشی سند است، برمی‌گرداند. |
| [getImages()](#getImages--) | مجموعهٔ تمام تصاویر در ارائه را برمی‌گرداند. |
| [getAudios()](#getAudios--) | مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. |
| [getVideos()](#getVideos--) | مجموعهٔ تمام فایل‌های ویدیویی جاسازی‌شده در ارائه را برمی‌گرداند. |
| [getSlideShowSettings()](#getSlideShowSettings--) | تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند. |
| [getDigitalSignatures()](#getDigitalSignatures--) | مجموعهٔ امضایی‌ها را که برای امضای ارائه استفاده می‌شوند، برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | دادهٔ سفارشی ارائه را برمی‌گرداند. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | تمام بخش‌های دادهٔ سفارشی در ارائه را برمی‌گرداند. |
| [getVbaProject()](#getVbaProject--) | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به تمام پیوندهای موجود در اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت) را فراهم می‌کند. |
| [getViewProperties()](#getViewProperties--) | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | شماره اولین اسلاید در ارائه را نشان می‌دهد |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | شماره اولین اسلاید در ارائه را نشان‌دهد |
| [getSensitivityLabels()](#getSensitivityLabels--) | مجموعهٔ برچسب‌های حساسیت اعمال‌شده بر سند ارائه را برمی‌گرداند. |
| [getSlideById(long id)](#getSlideById-long-) | یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند. |
| [getSourceFormat()](#getSourceFormat--) | اطلاعاتی درباره فرمت بارگذاری ارائه را برمی‌گرداند. |
| [getMasterTheme()](#getMasterTheme--) | مستر تم را برمی‌گرداند. |
| [save(String fname, int format)](#save-java.lang.String-int-) | تمام اسلایدهای یک ارائه را به فایلی با فرمت مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص ذخیره می‌کند. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای یک ارائه را به فایلی با فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمای XAML هستند ذخیره می‌کند. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | شیء Image برای تمام اسلایدهای یک ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه را با مقیاس سفارشی برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را با مقیاس سفارشی برمی‌گرداند. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه را با اندازهٔ مشخص برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را با اندازهٔ مشخص برمی‌گرداند. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | اسلایدهای مشخص شده از یک ارائه را به فایلی با فرمت مشخص ذخیره می‌کند در حالی که شمارهٔ صفحات حفظ می‌شود. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص شده از یک ارائه را به فایلی با فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند در حالی که شمارهٔ صفحات حفظ می‌شود. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص و با حفظ شمارهٔ صفحات ذخیره می‌کند. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند در حالی که شمارهٔ صفحات حفظ می‌شود. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متنی با فرمت یکسان را در تمام پاراگراف‌های تمام اشکال قابل قبول در تمام اسلایدها ترکیب می‌کند. |
| [dispose()](#dispose--) | تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند. |
| [getPresentation()](#getPresentation--) | ارائهٔ اصلی متن را برمی‌گرداند. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام رخدادهای متن مشخص‌شده را با متن دیگری که مشخص می‌شود جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام تطبیق‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند. |

### Presentation() {#Presentation--}
```
public Presentation()
```

این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد‌شده دارای یک اسلاید خالی است.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

این سازنده یک ارائه جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد‌شده دارای یک اسلاید خالی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافه. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

این سازنده مکانیزم اصلی برای خواندن یک Presentation موجود است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافه. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

این سازنده مسیر فایل منبع را دریافت می‌کند که محتویات Presentation از آن خوانده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافه. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

تاریخ و زمان را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. قابل خواندن/نوشتن java.util.Date.

**بازمی‌گرداند:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

تاریخ و زمان را که محتویات فیلدهای datetime را جایگزین می‌کند، برمی‌گرداند یا تنظیم می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. قابل خواندن/نوشتن java.util.Date.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

مدیر HeaderFooter واقعی را برمی‌گرداند. فقط خواندنی [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // ویژگی IsFooterVisible برای نشان دادن عدم وجود جایگاه نگهدارندهٔ پاورقی اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setFooterVisibility(true); // متد SetFooterVisibility برای قابل‌نمایش کردن جایگاه نگهدارندهٔ پاورقی اسلاید استفاده می‌شود.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // ویژگی IsSlideNumberVisible برای نشان دادن عدم وجود جایگاه نگهدارندهٔ شمارهٔ صفحه اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // متد SetSlideNumberVisibility برای قابل‌نمایش کردن جایگاه نگهدارندهٔ شمارهٔ صفحه اسلاید استفاده می‌شود.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // ویژگی IsDateTimeVisible برای نشان دادن عدم وجود جایگاه نگهدارندهٔ تاریخ-زمان اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // متد SetFooterVisibility برای قابل‌نمایش کردن جایگاه نگهدارندهٔ تاریخ-زمان اسلاید استفاده می‌شود.
>      }
>      headerFooterManager.setFooterText("Footer text"); // متد SetFooterText برای تنظیم متن به جایگاه نگهدارندهٔ پاورقی اسلاید استفاده می‌شود.
>      headerFooterManager.setDateTimeText("Date and time text"); // متد SetDateTimeText برای تنظیم متن به جایگاه نگهدارندهٔ تاریخ-زمان اسلاید استفاده می‌شود.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // متد SetFooterAndChildFootersVisibility برای قابل‌نمایش کردن اسلاید مستر و تمام جایگاه‌های نگهدارندهٔ پاورقی فرزندان استفاده می‌شود.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // متد SetSlideNumberAndChildSlideNumbersVisibility برای قابل‌نمایش کردن اسلاید مستر و تمام جایگاه‌های نگهدارندهٔ شمارهٔ صفحه فرزندان استفاده می‌شود.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // متد SetDateTimeAndChildDateTimesVisibility برای قابل‌نمایش کردن اسلاید مستر و تمام جایگاه‌های نگهدارندهٔ تاریخ-زمان فرزندان استفاده می‌شود.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // متد SetFooterAndChildFootersText برای تنظیم متن به اسلاید مستر و تمام جایگاه‌های نگهدارندهٔ پاورقی فرزندان استفاده می‌شود.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // متد SetDateTimeAndChildDateTimesText برای تنظیم متن به اسلاید مستر و تمام جایگاه‌های نگهدارندهٔ تاریخ-زمان فرزندان استفاده می‌شود.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

مدیر مجوزهای این ارائه را دریافت می‌کند. فقط خواندنی [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**بازمی‌گرداند:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

لیستی از تمام اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط خواندنی [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // یک شیء Presentation را که نمایانگر فایل ارائه است ایجاد کنید
>  Presentation pres = new Presentation();
>  try
>  {
>      // پس‌زمینه اولین ISlide را به آبی تنظیم کنید
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // یک شیء Presentation را که نمایانگر فایل ارائه است ایجاد کنید
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // پس‌زمینه را با تصویر تنظیم کنید
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // تصویر را تنظیم کنید
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // تصویر را به مجموعهٔ تصاویر ارائه اضافه کنید
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // ارائه را بر روی دیسک بنویسید
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // یک شیء Presentation را برای بارگذاری فایل ارائه منبع ایجاد کنید
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // انتقال نوع دایره‌ای را روی اسلاید ۱ اعمال کنید
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // انتقال نوع comb را روی اسلاید ۲ اعمال کنید
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // ارائه را بر روی دیسک بنویسید
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است ایجاد کنید
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // انتقال نوع دایره‌ای را روی اسلاید ۱ اعمال کنید
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // زمان انتقال را به ۳ ثانیه تنظیم کنید
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // انتقال نوع comb را روی اسلاید ۲ اعمال کنید
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // زمان انتقال را به ۵ ثانیه تنظیم کنید
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // انتقال نوع زوم را روی اسلاید ۳ اعمال کنید
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // زمان انتقال را به ۷ ثانیه تنظیم کنید
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // ارائه را بر روی دیسک بنویسید
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

لیستی از تمام بخش‌های اسلایدهایی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط خواندنی [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 در newSlide2 خاتمه می‌یابد و پس از آن section2 شروع می‌شود
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

شیء اندازه اسلاید را برمی‌گرداند. فقط خواندنی [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است ایجاد کنید
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // اندازهٔ اسلاید ارائه‌های تولید شده را برابر با منبع تنظیم کنید
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // متد SetSize برای تنظیم اندازهٔ اسلاید با مقیاس محتوا به‌منظور اطمینان از قرار مناسب استفاده می‌شود
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // متد SetSize برای تنظیم اندازهٔ اسلاید با حداکثر کردن اندازهٔ محتوا استفاده می‌شود
>          // ارائه را بر روی دیسک ذخیره کنید
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // اندازهٔ کاغذ A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. فقط خواندنی [INotesSize](../../com.aspose.slides/inotessize).

**بازمی‌گرداند:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

لیستی از تمام اسلایدهای طرح‌بندی که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط خواندنی [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

می‌توانید به API جایگزین برای افزودن/درج/حذف/شبیه‌سازی اسلایدهای طرح‌بندی از طریق ویژگی IMasterSlide.LayoutSlides دسترسی داشته باشید.

**بازمی‌گرداند:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

لیستی از تمام اسلایدهای مستر که در ارائه تعریف شده‌اند را برمی‌گرداند. فقط خواندنی [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

مدیر مستر یادداشت‌ها را برمی‌گرداند. فقط خواندنی [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**بازمی‌گرداند:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

مدیر مستر برگه‌های توزیع را برمی‌گرداند. فقط خواندنی [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**بازمی‌گرداند:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

مدیر قلم‌ها را برمی‌گرداند. فقط خواندنی [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // ارائه را بارگذاری کنید
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // فونت منبعی که باید جایگزین شود را بارگذاری کنید
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // ارائه را ذخیره کنید
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

سبک متن پیش‌فرض برای اشکال را برمی‌گرداند. فقط خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**بازمی‌گرداند:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

مجموعهٔ نویسندگان نظرات را برمی‌گرداند. فقط خواندنی [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**بازمی‌گرداند:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocument Properties get Document Properties () 
```

شیء DocumentProperties را که شامل خصوصیات استاندارد و سفارشی سند است، برمی‌گرداند. فقط خواندنی [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**بازمی‌گرداند:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

مجموعهٔ تمام تصاویر در ارائه را برمی‌گرداند. فقط خواندنی [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // یک ارائه جدید ایجاد می‌کند که تصویر به آن اضافه خواهد شد.
>  Presentation pres = new Presentation();
>  try
>  {
>      // فرض می‌کنیم فایل تصویر بزرگ که می‌خواهیم در ارائه گنجانده شود را داشته‌ایم
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // بگذارید تصویر را به ارائه اضافه کنیم - رفتار KeepLocked را انتخاب می‌کنیم زیرا ما
>          // قصد نداریم به فایل "largeImage.png" دسترسی داشته باشیم.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // ارائه را ذخیره می‌کند. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
>          // در طول دورهٔ حیات شیء pres کم می‌ماند
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // تصویر را به ارائه اضافه می‌کند
>          IPPImage image = pres.getImages().addImage(fos);
>          // فریم تصویری را در اسلاید ۱ بر اساس تصویر قبلاً اضافه‌شده ایجاد می‌کند
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. فقط خواندنی [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

مجموعهٔ تمام فایل‌های ویدیویی جاسازی‌شده در ارائه را برمی‌گرداند. فقط خواندنی [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازمی‌گرداند:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند.

**بازمی‌گرداند:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

مجموعهٔ امضاهایی که برای امضای ارائه استفاده می‌شوند، برمی‌گرداند. فقط خواندنی [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

دادهٔ سفارشی ارائه را برمی‌گرداند. فقط خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازمی‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

تمام بخش‌های دادهٔ سفارشی در ارائه را برمی‌گرداند. فقط خواندنی ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // تمام بخش‌های XML سفارشی را بگردید
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازمی‌گرداند:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**بازمی‌گرداند:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. قابل خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به تمام پیوندهای موجود در اسلایدهای ارائه (نه در مستر، طرح‌بندی یا اسلایدهای یادداشت) را فراهم می‌کند. فقط خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازمی‌گرداند:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public       



مو



```

ویژگی‌های نمای کلی ارائه را دریافت می‌کند. فقط خواندنی [IViewProperties](../../com.aspose.slides/iviewproperties).

**بازمی‌گرداند:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

شماره اولین اسلاید در ارائه را نشان می‌دهد

**بازمی‌گرداند:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

شماره اولین اسلاید در ارائه را نشان می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

مجموعهٔ برچسب‌های حساسیتی که بر سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط خواندنی [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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


**بازمی‌گرداند:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

یک Slide، MasterSlide یا LayoutSlide را بر اساس Id برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | long | Id یک اسلاید. |

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

اطلاعاتی درباره فرمت بارگذاری ارائه را برمی‌گرداند. فقط خواندنی [SourceFormat](../../com.aspose.slides/sourceformat).

**بازمی‌گرداند:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

مستر تم را برمی‌گرداند. فقط خواندنی [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است ایجاد کنید
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازمی‌گرداند:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

تمام اسلایدهای یک ارائه را به فایلی با فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد شده. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را به فایلی با فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد شده. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافه. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را به یک جریان در فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافه. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمای XAML هستند ذخیره می‌کند.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | گزینه‌های فرمت XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

شیء Image برای تمام اسلایدهای یک ارائه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه را با مقیاس سفارشی برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| scaleX | float | مقدار مقیاس این بندانگشتی در جهت محور x. |
| scaleY | float | مقدار مقیاس این بندانگشتی در جهت محور y. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را با مقیاس سفارشی برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| scaleX | float | مقدار مقیاس این بندانگشتی در جهت محور x. |
| scaleY | float | مقدار مقیاس این بندانگشتی در جهت محور y. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

تصاویر بندانگشتی برای تمام اسلایدهای یک ارائه را با اندازهٔ مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازهٔ تصویری که باید ایجاد شود. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

تصاویر بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را با اندازهٔ مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | اندازهٔ تصویری که باید ایجاد شود. |

**بازمی‌گرداند:**
com.aspose.slides.IImage[] - شیء Image.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

اسلایدهای مشخص شده از یک ارائه را به فایلی با فرمت مشخص و با حفظ شمارهٔ صفحات ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده از یک ارائه را به فایلی با فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند و شمارهٔ صفحات حفظ می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر به فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافه. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص و با حفظ شمارهٔ صفحات ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده از یک ارائه را به یک جریان در فرمت مشخص و با گزینه‌های اضافه ذخیره می‌کند و شمارهٔ صفحات حفظ می‌شود.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای از موقعیت اسلایدها، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های فرمت اضافه. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

بخش‌های متنی با فرمت یکسان را در تمام پاراگراف‌های تمام اشکال قابل قبول در تمام اسلایدها ترکیب می‌کند.

### dispose() {#dispose--}
```
public final void dispose()
```

تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائهٔ اصلی یک متن را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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
| highlightColor | java.lang.Integer | رنگی که متن باید برجسته شود. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام تطبیق‌های متن نمونه را با رنگ مشخص شده برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // برجسته‌سازی تمام موارد جداگانهٔ 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متنی که باید برجسته شود. |
| highlightColor | java.lang.Integer | رنگی که متن باید برجسته شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخورد برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

تمام تطبیق‌های عبارت منظم را با رنگ مشخص شده برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // برجسته‌سازی تمام کلماتی که ۱۰ نماد یا بیشتر دارند
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های برجسته. |
| highlightColor | java.lang.Integer | رنگی که متن باید برجسته شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخورد برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public  



ن



ن

 



💢







```

تمام رخدادهای متن مشخص‌شده را با متن دیگری که مشخص می‌شود جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تمام موارد جداگانهٔ 'the' را با '***' جایگزین کنید
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخورد برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام تطبیق‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // تمام کلمات با ۱۰ نماد یا بیشتر را با '***' جایگزین کنید
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌های جایگزین. |
| newText | java.lang.String | رشته‌ای که تمام رخدادهای رشته‌های جایگزین شده را جایگزین می‌کند. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخورد برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |