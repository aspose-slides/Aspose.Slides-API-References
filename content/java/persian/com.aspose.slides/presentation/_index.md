---
title: Presentation
second_title: مرجع API جاوا Aspose.Slides
description: یک ارائه Microsoft PowerPoint را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/presentation/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject  
```
public final class Presentation implements IPresentation, IDOMObject
```

یک ارائهٔ Microsoft PowerPoint را نشان می‌دهد.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید را دریافت کنید
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک شکل خودکار از نوع خط اضافه کنید
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // فایل ارائه را ذخیره کنید.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // هر فایل پشتیبانی‌شده‌ای را در Presentation بارگذاری کنید، مانند ppt، pptx، odp و غیره
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // فایل ارائه را ذخیره کنید.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [Presentation()](#Presentation--) | این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | این سازنده مکانیزم اصلی برای خواندن یک ارائهٔ موجود است. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | این سازنده مکانیزم اصلی برای خواندن یک ارائهٔ موجود است. |
| [Presentation(String file)](#Presentation-java.lang.String-) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای ارائه از آن خوانده می‌شود. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای ارائه از آن خوانده می‌شود. |

## متدها

| متد | توضیح |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای تاریخ-زمان را جایگزین می‌کند. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای تاریخ-زمان را جایگزین می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | مدیر واقعی HeaderFooter را برمی‌گرداند. |
| [getProtectionManager()](#getProtectionManager--) | مدیر مجوزهای این ارائه را دریافت می‌کند. |
| [getSlides()](#getSlides--) | فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. |
| [getSections()](#getSections--) | فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. |
| [getSlideSize()](#getSlideSize--) | شیء اندازه اسلاید را برمی‌گرداند. |
| [getNotesSize()](#getNotesSize--) | شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. |
| [getLayoutSlides()](#getLayoutSlides--) | فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند. |
| [getMasters()](#getMasters--) | فهرستی از تمام اسلایدهای master تعریف‌شده در ارائه را برمی‌گرداند. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | مدیر master یادداشت‌ها را برمی‌گرداند. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | مدیر master جزوه را برمی‌گرداند. |
| [getFontsManager()](#getFontsManager--) | مدیر فونت‌ها را برمی‌گرداند. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | قالب پیش‌فرض متن برای اشکال را برمی‌گرداند. |
| [getCommentAuthors()](#getCommentAuthors--) | مجموعهٔ نویسندگان نظرات را برمی‌گرداند. |
| [getDocumentProperties()](#getDocumentProperties--) | شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است. |
| [getImages()](#getImages--) | مجموعهٔ تمام تصاویر موجود در ارائه را برمی‌گرداند. |
| [getAudios()](#getAudios--) | مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. |
| [getVideos()](#getVideos--) | مجموعهٔ تمام فایل‌های ویدئویی جاسازی‌شده در ارائه را برمی‌گرداند. |
| [getSlideShowSettings()](#getSlideShowSettings--) | تنظیمات نمایش اسلایدها برای ارائه را برمی‌گرداند. |
| [getDigitalSignatures()](#getDigitalSignatures--) | مجموعهٔ امضاهای استفاده‌شده برای امضای ارائه را برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی ارائه را برمی‌گرداند. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | تمام بخش‌های دادهٔ سفارشی در ارائه را برمی‌گرداند. |
| [getVbaProject()](#getVbaProject--) | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | پروژه VBA همراه با ماکروهای ارائه را دریافت یا تنظیم می‌کند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به تمام پیوندهای موجود در همهٔ اسلایدهای ارائه (نه در اسلایدهای master، layout، notes) را فراهم می‌کند. |
| [getViewProperties()](#getViewProperties--) | ویژگی‌های نمای کلی ارائه را دریافت می‌کند. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | نشانگر شماره اولین اسلاید در ارائه است. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | نشانگر شماره اولین اسلاید در ارائه است. |
| [getSensitivityLabels()](#getSensitivityLabels--) | مجموعهٔ برچسب‌های حساسیتی اعمال‌شده بر سند ارائه را برمی‌گرداند. |
| [getSlideById(long id)](#getSlideById-long-) | یک Slide، MasterSlide یا LayoutSlide را بر اساس شناسه برمی‌گرداند. |
| [getSourceFormat()](#getSourceFormat--) | اطلاعاتی دربارهٔ فرمت منبعی که ارائه از آن بارگذاری شده است را برمی‌گرداند. |
| [getMasterTheme()](#getMasterTheme--) | قالب master را برمی‌گرداند. |
| [save(String fname, int format)](#save-java.lang.String-int-) | تمام اسلایدهای ارائه را به فایلی با قالب مشخص ذخیره می‌کند. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | تمام اسلایدهای ارائه را به جریان (stream) در قالب مشخص ذخیره می‌کند. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای ارائه را به فایلی با قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | تمام اسلایدهای ارائه را به جریان (stream) در قالب مشخص و با گزینه‌های اضافی ذخیره می‌کند. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | تمام اسلایدهای ارائه را به مجموعه‌ای از فایل‌ها که نمای XAML هستند ذخیره می‌کند. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | اشیاء Image برای تمام اسلایدهای ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | اشیاء تصویر بندانگشتی برای اسلایدهای مشخص شده ارائه را برمی‌گرداند. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | اشیاء تصویر بندانگشتی برای تمام اسلایدهای ارائه با مقیاس سفارشی را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | اشیاء تصویر بندانگشتی برای اسلایدهای مشخص شده ارائه را با مقیاس سفارشی برمی‌گرداند. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | اشیاء تصویر بندانگشتی برای تمام اسلایدهای ارائه با اندازهٔ مشخص را برمی‌گرداند. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | اشیاء تصویر بندانگشتی برای اسلایدهای مشخص شده ارائه را با اندازهٔ مشخص برمی‌گرداند. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | اسلایدهای مشخص شده ارائه را به فایلی با قالب مشخص ذخیره می‌کند به‌طوری که شماره صفحه حفظ شود. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص شده ارائه را به فایلی با قالب مشخص ذخیره می‌کند به‌طوری که شماره صفحه حفظ شود. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | اسلایدهای مشخص شده ارائه را به جریان (stream) در قالب مشخص ذخیره می‌کند به‌طوری که شماره صفحه حفظ شود. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | اسلایدهای مشخص شده ارائه را به جریان (stream) در قالب مشخص ذخیره می‌کند به‌طوری که شماره صفحه حفظ شود. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | اجراهای متنی با قالب‌بندی یکسان در تمام پاراگراف‌های همهٔ اشکال قابل‌قبول در تمام اسلایدها را ترکیب می‌کند. |
| [dispose()](#dispose--) | تمام منابع استفاده‌شده توسط این شیء Presentation را آزاد می‌کند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک متن را برمی‌گرداند. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های متن نمونه را با رنگ مشخص برجسته می‌کند. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های عبارت منظم را با رنگ مشخص برجسته می‌کند. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | تمام رخدادهای متن مشخص‌شده را با متن دیگر مشخص شده جایگزین می‌کند. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | تمام تطابق‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند. |

### Presentation() {#Presentation--}
```
public Presentation()
```

این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد‌شده یک اسلاید خالی دارد.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

این سازنده یک ارائهٔ جدید را از ابتدا ایجاد می‌کند. ارائهٔ ایجاد‌شده یک اسلاید خالی دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافی. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

این سازنده مکانیزم اصلی برای خواندن یک ارائهٔ موجود است.

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

این سازنده مکانیزم اصلی برای خواندن یک ارائهٔ موجود است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان ورودی. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافی. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای ارائه از آن خوانده می‌شود.

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

این سازنده مسیر فایل منبع را دریافت می‌کند که محتوای ارائه از آن خوانده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| file | java.lang.String | فایل ورودی. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | گزینه‌های بارگذاری اضافی. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای تاریخ-زمان را جایگزین می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. فقط-خواندنی/نوشتنی java.util.Date.

**برمی‌گرداند:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

تاریخ و زمان را برمی‌گرداند یا تنظیم می‌کند که محتویات فیلدهای تاریخ-زمان را جایگزین می‌کند. زمان ایجاد این شیء Presentation به‌صورت پیش‌فرض. فقط-خواندنی/نوشتنی java.util.Date.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**برمی‌گرداند:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

مدیر واقعی HeaderFooter را برمی‌گرداند. فقط-خواندنی [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // ویژگی IsFooterVisible برای نشان دادن عدم وجود جای‌دار زیرنویس اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setFooterVisibility(true); // متد SetFooterVisibility برای قابل دیدن کردن جای‌دار زیرنویس اسلاید استفاده می‌شود.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // ویژگی IsSlideNumberVisible برای نشان دادن عدم وجود جای‌دار شماره صفحه اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // متد SetSlideNumberVisibility برای قابل دیدن کردن جای‌دار شماره صفحه اسلاید استفاده می‌شود.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // ویژگی IsDateTimeVisible برای نشان دادن عدم وجود جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // متد SetFooterVisibility برای قابل دیدن کردن جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
>      }
>      headerFooterManager.setFooterText("Footer text"); // متد SetFooterText برای تنظیم متن در جای‌دار زیرنویس اسلاید استفاده می‌شود.
>      headerFooterManager.setDateTimeText("Date and time text"); // متد SetDateTimeText برای تنظیم متن در جای‌دار تاریخ-زمان اسلاید استفاده می‌شود.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // متد SetFooterAndChildFootersVisibility برای قابل دیدن کردن اسلاید مستر و تمام جای‌دارهای زیرنویس فرزند استفاده می‌شود.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // متد SetSlideNumberAndChildSlideNumbersVisibility برای قابل دیدن کردن اسلاید مستر و تمام جای‌دارهای شماره صفحه فرزند استفاده می‌شود.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // متد SetDateTimeAndChildDateTimesVisibility برای قابل دیدن کردن اسلاید مستر و تمام جای‌دارهای تاریخ-زمان فرزند استفاده می‌شود.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // متد SetFooterAndChildFootersText برای تنظیم متن در اسلاید مستر و تمام جای‌دارهای زیرنویس فرزند استفاده می‌شود.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // متد SetDateTimeAndChildDateTimesText برای تنظیم متن در اسلاید مستر و تمام جای‌دارهای تاریخ-زمان فرزند استفاده می‌شود.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**برمی‌گرداند:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

مدیر مجوزهای این ارائه را دریافت می‌کند. فقط-خواندنی [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**برمی‌گرداند:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

فهرستی از تمام اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر فایل ارائه است
>  Presentation pres = new Presentation();
>  try
>  {
>      // رنگ پس‌زمینه اولین ISlide را به آبی تنظیم می‌کند
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
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر فایل ارائه است
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // پس‌زمینه را با تصویر تنظیم می‌کند
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // تصویر را تنظیم می‌کند
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // عكس را به مجموعه تصاویر ارائه اضافه می‌کند
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند تا فایل ارائه منبع را بارگذاری کند
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // انتقال نوع دایره‌ای را بر اسلاید 1 اعمال می‌کند
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // انتقال نوع شانه‌ای را بر اسلاید 2 اعمال می‌کند
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // انتقال نوع دایره‌ای را بر اسلاید 1 اعمال می‌کند
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // زمان انتقال را به 3 ثانیه تنظیم می‌کند
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // انتقال نوع شانه‌ای را بر اسلاید 2 اعمال می‌کند
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // زمان انتقال را به 5 ثانیه تنظیم می‌کند
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // انتقال نوع بزرگ‌نمایی را بر اسلاید 3 اعمال می‌کند
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // زمان انتقال را به 7 ثانیه تنظیم می‌کند
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**برمی‌گرداند:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

فهرستی از تمام بخش‌های اسلایدهای تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 در newSlide2 پایان می‌یابد و پس از آن section2 آغاز می‌شود
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


**برمی‌گرداند:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

شیء اندازه اسلاید را برمی‌گرداند. فقط-خواندنی [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // اندازه اسلاید ارائه‌های تولید شده را به اندازه منبع تنظیم می‌کند
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // متد SetSize برای تنظیم اندازه اسلاید با مقیاس محتوا به منظور اطمینان از مناسب بودن استفاده می‌شود
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // متد SetSize برای تنظیم اندازه اسلاید با حداکثر کردن اندازه محتوا استفاده می‌شود
>          // ذخیره Presentation بر روی دیسک
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


**برمی‌گرداند:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

شیء اندازه اسلاید یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [INotesSize](../../com.aspose.slides/inotessize).

**برمی‌گرداند:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

فهرستی از تمام اسلایدهای طرح‌بندی تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

می‌توانید با استفاده از ویژگی IMasterSlide.LayoutSlides به API جایگزین برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌بندی دسترسی پیدا کنید.

**برمی‌گرداند:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

فهرستی از تمام اسلایدهای master تعریف‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر فایل ارائه است
>  Presentation pres = new Presentation();
>  try
>  {
>      // رنگ پس‌زمینه اسلاید مستر ISlide را به سبز جنگلی تنظیم می‌کند
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // نوشتن ارائه بر روی دیسک
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // یک شیء از کلاس Presentation ایجاد می‌کند که نمایانگر فایل ارائه است
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // سعی در جستجو بر اساس نوع اسلاید چیدمان
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // موقعیتی که در آن یک ارائه برخی انواع چیدمان‌ها را شامل نمی‌شود.
>          // فایل ارائه تنها شامل انواع چیدمان Blank و Custom است.
>          // اما اسلایدهای چیدمان با انواع Custom نام‌های متفاوتی دارند،
>          // مانند "Title" ، "Title and Content" و غیره. و امکان استفاده از این‌ها
>          // نام‌ها برای انتخاب اسلاید چیدمان.
>          // همچنین می‌توان مجموعه‌ای از انواع اشکال جای‌دار را استفاده کرد. برای مثال،
>          // اسلاید عنوان باید فقط نوع جای‌دار Title را داشته باشد، و غیره.
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
>      // اضافه کردن اسلاید خالی با اسلاید چیدمان اضافه‌شده
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // ذخیره ارائه
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**برمی‌گرداند:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

مدیر master یادداشت‌ها را برمی‌گرداند. فقط-خواندنی [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**برمی‌گرداند:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

مدیر master جزوه را برمی‌گرداند. فقط-خواندنی [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**برمی‌گرداند:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

مدیر فونت‌ها را برمی‌گرداند. فقط-خواندنی [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // بارگذاری ارائه
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // بارگذاری فونت منبع برای جایگزینی
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
>      // ذخیرهٔ ارائه
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**برمی‌گرداند:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

قالب پیش‌فرض متن برای اشکال را برمی‌گرداند. فقط-خواندنی [ITextStyle](../../com.aspose.slides/itextstyle).

**برمی‌گرداند:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

مجموعهٔ نویسندگان نظرات را برمی‌گرداند. فقط-خواندنی [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**برمی‌گرداند:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

شیء DocumentProperties را برمی‌گرداند که شامل ویژگی‌های استاندارد و سفارشی سند است. فقط-خواندنی [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**برمی‌گرداند:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

مجموعهٔ تمام تصاویر موجود در ارائه را برمی‌گرداند. فقط-خواندنی [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // یک ارائه جدید ایجاد می‌کند که تصویر به آن اضافه خواهد شد.
>  Presentation pres = new Presentation();
>  try
>  {
>      // فرض می‌کنیم فایلی تصویر بزرگ داریم که می‌خواهیم در ارائه گنجانده شود
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // بیایید تصویر را به ارائه اضافه کنیم - رفتار KeepLocked را انتخاب می‌کنیم زیرا ما
>          // قصد دسترسی به فایل "largeImage.png" را نداریم.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // ارائه را ذخیره می‌کند. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
>          // در طول طول عمر شی pres کم می‌ماند
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
>      // تصویر را به ارائه اضافه می‌کند
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // قاب تصویر را در اسلاید 1 بر اساس تصویر اضافه شده قبلی ایجاد می‌کند
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**برمی‌گرداند:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

مجموعهٔ تمام فایل‌های صوتی جاسازی‌شده در ارائه را برمی‌گرداند. فقط-خواندنی [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**برمی‌گرداند:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
کلکسیونی از تمام فایل‌های ویدئویی توکار در ارائه را برمی‌گرداند. فقط-خواندنی [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // یک ارائه جدید ایجاد می‌کند که تصویر به آن اضافه خواهد شد.
>  Presentation pres = new Presentation();
>  try
>  {
>      // فرض می‌کنیم فایلی تصویر بزرگ داریم که می‌خواهیم در ارائه گنجانده شود
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // بیایید تصویر را به ارائه اضافه کنیم - رفتار KeepLocked را انتخاب می‌کنیم زیرا ما
>          // قصد دسترسی به فایل "largeImage.png" را نداریم.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // ارائه را ذخیره می‌کند. در حالی که یک ارائه بزرگ خروجی می‌شود، مصرف حافظه
>          // در طول چرخهٔ حیات شی pres کم می‌ماند
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
>      // تصویر را به ارائه اضافه می‌کند
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // قاب تصویر را در اسلاید 1 بر اساس تصویر اضافه‌شده قبلی ایجاد می‌کند
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  ```


**بازگشت:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

تنظیمات نمایش اسلاید برای ارائه را برمی‌گرداند.

**بازگشت:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

کلکسیونی از امضاهایی که برای امضای ارائه استفاده شده‌اند را برمی‌گرداند. فقط-خواندنی [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**بازگشت:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

داده‌های سفارشی ارائه را برمی‌گرداند. فقط-خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازگشت:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

تمام بخش‌های داده‌های سفارشی در ارائه را برمی‌گرداند. فقط-خواندنی ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // همه بخش‌های سفارشی XML را مرور کنید
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


**بازگشت:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

پروژه VBA را که شامل ماکروهای ارائه است دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**بازگشت:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

پروژه VBA را که شامل ماکروهای ارائه است دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [IVbaProject](../../com.aspose.slides/ivbaproject).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به تمام هایپرلینک‌های موجود در تمام اسلایدهای ارائه (نه در اسلایدهای اصلی، چیدمان یا یادداشت). فقط-خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازگشت:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

خاصیت‌های نمای کلی ارائه را دریافت می‌کند. فقط-خواندنی [IViewProperties](../../com.aspose.slides/iviewproperties).

**بازگشت:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

شماره اولین اسلاید در ارائه را نشان می‌دهد

**بازگشت:**
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

کلکسیونی از برچسب‌های حساسیتی که بر سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط-خواندنی [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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


**بازگشت:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

یک Slide، MasterSlide یا LayoutSlide را بر اساس شناسه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | long | شناسه یک اسلاید. |

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

اطلاعاتی درباره فرمت منبعی که ارائه از آن بارگذاری شده است را برمی‌گرداند. فقط-خواندنی [SourceFormat](../../com.aspose.slides/sourceformat).

**بازگشت:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

تم اصلی را برمی‌گرداند. فقط-خواندنی [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر فایل ارائه است
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


**بازگشت:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

تمام اسلایدهای یک ارائه را به یک فایل با فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

تمام اسلایدهای یک ارائه را به یک جریان با فرمت مشخص ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را به یک فایل با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی فرمت. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

تمام اسلایدهای یک ارائه را به یک جریان با فرمت مشخص و با گزینه‌های اضافی ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی فرمت. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

تمام اسلایدهای یک ارائه را به مجموعه‌ای از فایل‌ها که نمایانگر مارکاپ XAML هستند ذخیره می‌کند.

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

یک شیء Image برای تمام اسلایدهای یک ارائه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

یک شیء Image بندانگشتی برای اسلایدهای مشخص شده از یک ارائه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

یک شیء Image بندانگشتی برای تمام اسلایدهای یک ارائه با مقیاس سفارشی را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| scaleX | float | مقدار مقیاس در جهت محور X. |
| scaleY | float | مقدار مقیاس در جهت محور Y. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

یک شیء Image بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با مقیاس سفارشی را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| scaleX | float | مقدار مقیاس در جهت محور X. |
| scaleY | float | مقدار مقیاس در جهت محور Y. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

یک شیء Image بندانگشتی برای تمام اسلایدهای یک ارائه با اندازه مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| imageSize | java.awt.Dimension | اندازه تصویر برای ایجاد. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

یک شیء Image بندانگشتی برای اسلایدهای مشخص شده از یک ارائه با اندازه مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های Tiff. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| imageSize | java.awt.Dimension | اندازه تصویر برای ایجاد. |

**بازگشت:**
com.aspose.slides.IImage[] - شیء Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

اسلایدهای مشخص شده یک ارائه را به یک فایل با فرمت مشخص و با نگهداری شماره صفحه ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده یک ارائه را به یک فایل با فرمت مشخص و با نگهداری شماره صفحه ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fname | java.lang.String | مسیر فایل ایجاد شده. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی فرمت. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

اسلایدهای مشخص شده یک ارائه را به یک جریان با فرمت مشخص و با نگه‌داشتن شماره صفحه ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان خروجی. |
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

اسلایدهای مشخص شده یک ارائه را به یک جریان با فرمت مشخص و با نگه‌داشتن شماره صفحه ذخیره می‌کند.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
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
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
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
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
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
| slides | int[] | آرایه‌ای از شماره‌های اسلاید، شروع از 1. |
| format | int | فرمت داده‌های خروجی. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | گزینه‌های اضافی فرمت. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

قسمت‌های متن با فرمت یکسان در تمام پاراگراف‌ها در تمام اشکال قابل قبول در تمام اسلایدها را ترکیب می‌کند.

### dispose() {#dispose--}
```
public final void dispose()
```

تمام منابع مورد استفاده توسط این شیء Presentation را آزاد می‌کند.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

پیشنهاد ارائه والد یک متن را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

تمام موارد متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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
| highlightColor | java.awt.Color | رنگی که متن باید با آن برجسته شود. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن نمونه را با رنگ مشخص شده برجسته می‌کند.

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
| highlightColor | java.awt.Color | رنگی که متن باید با آن برجسته شود. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

تمام موارد تطابق عبارات منظم را با رنگ مشخص شده برجسته می‌کند.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // برجسته‌سازی تمام کلمات با ۱۰ کاراکتر یا بیشتر
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
| highlightColor | java.awt.Color | رنگی که متن باید با آن برجسته شود. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء بازخوانی برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

تمام موارد متن مشخص‌شده را با متن دیگری که مشخص می‌شود جایگزین می‌کند.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // تمام رخدادهای جداگانهٔ 'the' را با '***' جایگزین می‌کند
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
| newText | java.lang.String | رشته‌ای که تمام موارد oldText را جایگزین می‌کند. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | گزینه‌های جستجوی متن [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

تمام مطابقت‌های عبارت منظم را با رشتهٔ مشخص‌شده جایگزین می‌کند.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // تمام کلمات با ۱۰ علامت یا بیشتر را با '***' جایگزین می‌کند
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| regex | java.util.regex.Pattern | عبارت منظم java.util.regex.Pattern برای دریافت رشته‌هایی که باید جایگزین شوند. |
| newText | java.lang.String | رشته‌ای برای جایگزینی تمام موارد رشته‌های قابل جایگزینی. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | شیء callback برای دریافت نتایج جستجو [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |