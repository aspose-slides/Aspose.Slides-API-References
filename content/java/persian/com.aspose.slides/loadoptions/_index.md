---
title: LoadOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: به شما اجازه می‌دهد گزینه‌های اضافی مانند فرمت یا قلم پیش‌فرض را هنگام بارگذاری یک ارائه مشخص کنید.
type: docs
url: /fa/com.aspose.slides/loadoptions/
---
**وراثت:**
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

به شما اجازه می‌دهد گزینه‌های اضافی (مانند فرمت یا قلم پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | یک گزینه بارگذاری پیش‌فرض جدید ایجاد می‌کند. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | یک گزینه بارگذاری جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | فرمت ارائه‌ای که باید بارگذاری شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | فرمت ارائه‌ای که باید بارگذاری شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | قلم Regular را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | قلم Regular را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | قلم Symbol را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | قلم Symbol را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | قلم Asian را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | قلم Asian را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getPassword()](#getPassword--) | رمز عبور را دریافت یا تنظیم می‌کند. |
| [setPassword(String value)](#setPassword-java.lang.String-) | رمز عبور را دریافت یا تنظیم می‌کند. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | این ویژگی زمانی معنا دارد که فایل ارائه با رمز محافظت شده باشد. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | این ویژگی زمانی معنا دارد که فایل ارائه با رمز محافظت شده باشد. |
| [getWarningCallback()](#getWarningCallback--) | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | نمایانگر گزینه‌هایی است که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | نمایانگر گزینه‌هایی است که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | منابع قلم‌های خارجی که توسط ارائه استفاده می‌شوند را مشخص می‌کند. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | منابع قلم‌های خارجی که توسط ارائه استفاده می‌شوند را مشخص می‌کند. |
| [getInterruptionToken()](#getInterruptionToken--) | توکن برای نظارت بر درخواست‌های قطع. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | توکن برای نظارت بر درخواست‌های قطع. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند را برمی‌گرداند یا تنظیم می‌کند. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا نه. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا نه. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

یک گزینه بارگذاری پیش‌فرض جدید ایجاد می‌کند.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

یک گزینه بارگذاری جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| loadFormat | int | فرمت ارائه‌ای که باید بارگذاری شود. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

فرمت ارائه‌ای که باید بارگذاری شود را برمی‌گرداند یا تنظیم می‌کند. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

فرمت ارائه‌ای که باید بارگذاری شود را برمی‌گرداند یا تنظیم می‌کند. Read/write [LoadFormat](../../com.aspose.slides/loadformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

قلم Regular را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // از گزینه‌های بارگذاری برای تعریف قلم‌های regular و asian پیش‌فرض استفاده کنید
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // بارگذاری ارائه
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // تولید تصویر بندانگشتی اسلاید
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // تولید PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // تولید XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

قلم Regular را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // از گزینه‌های بارگذاری برای تعریف قلم‌های پیش‌فرض regular و asian استفاده کنید
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // بارگذاری ارائه
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // تولید تصویر بندانگشتی اسلاید
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // تولید PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // تولید XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

قلم Symbol را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

**بازگشت:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

قلم Symbol را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

قلم Asian را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

**بازگشت:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

قلم Asian را که در صورت یافت نشدن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. Read/write String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

رمز عبور را دریافت یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // کار با ارائه رمزگشایی شده
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


مقدار: رمز عبور.

**بازگشت:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

رمز عبور را دریافت یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // کار با ارائه رمزگشایی شده
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


مقدار: رمز عبور.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

این ویژگی زمانی معنا دارد که فایل ارائه با رمز محافظت شده باشد. مقدار true به این معنی است که فقط ویژگی‌های سند باید از فایل ارائه رمزگذاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائه رمزگذاری‌شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند بارگذاری نمی‌شوند و استثنا پرتاب می‌شود. Read/write boolean.

**بازگشت:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

این ویژگی زمانی معنا دارد که فایل ارائه با رمز محافظت شده باشد. مقدار true به این معنی است که فقط ویژگی‌های سند باید از فایل ارائه رمزگذاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائه رمزگذاری‌شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند بارگذاری نمی‌شوند و استثنا پرتاب می‌شود. Read/write boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

شیئی را برمی‌گرداند یا تنظیم می‌کند که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

نمایانگر گزینه‌هایی است که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم نسبت بهترین عملکرد/مصرف حافظه برای محیط یا نیازهای خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده باینری است که به عنوان یک واحد ذخیره می‌شود - به عنوان مثال BLOB می‌تواند یک صوت، ویدئو یا خود ارائه باشد.

**بازگشت:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

نمایانگر گزینه‌هایی است که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم نسبت بهترین عملکرد/مصرف حافظه برای محیط یا نیازهای خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده باینری است که به عنوان یک واحد ذخیره می‌شود - به عنوان مثال BLOB می‌تواند یک صوت، ویدئو یا خود ارائه باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

منابع قلم‌های خارجی که توسط ارائه استفاده می‌شوند را مشخص می‌کند. این قلم‌ها در تمام طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // کار با ارائه
>  //CustomFont1، CustomFont2 و همچنین قلم‌های موجود در پوشه‌های assets\fonts و global\fonts و زیرپوشه‌های آنها برای ارائه در دسترس هستند
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**بازگشت:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

منابع قلم‌های خارجی که توسط ارائه استفاده می‌شوند را مشخص می‌کند. این قلم‌ها در تمام طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // کار با ارائه
>  // CustomFont1، CustomFont2 و همچنین قلم‌های موجود در پوشه‌های assets\fonts و global\fonts و زیرپوشه‌های آن‌ها برای ارائه در دسترس هستند
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

توکن برای نظارت بر درخواست‌های قطع.

--------------------

این توکن طول عمر کل نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) از [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) قطع می‌شود.

**بازگشت:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

توکن برای نظارت بر درخواست‌های قطع.

--------------------

این توکن طول عمر کل نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) از [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) قطع می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

رابط callback را برمی‌گرداند یا تنظیم می‌کند که بارگذاری منابع خارجی را مدیریت می‌کند. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**بازگشت:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

رابط callback را برمی‌گرداند یا تنظیم می‌کند که بارگذاری منابع خارجی را مدیریت می‌کند. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. به عنوان مثال، این گزینه‌ها محاسبه فرمول‌ها برای نمودارها را تحت تأثیر قرار می‌دهند.

**بازگشت:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. به عنوان مثال، این گزینه‌ها محاسبه فرمول‌ها برای نمودارها را تحت تأثیر قرار می‌دهند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعریف فرهنگ متن پیش‌فرض استفاده کنید
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // اضافه کردن شکل مستطیل جدید با متن
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // بررسی زبان اولین بخش
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. Read/write String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعریف فرهنگ متن پیش‌فرض استفاده کنید
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // اضافه کردن شکل مستطیل جدید با متن
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // بررسی زبان اولین بخش
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا نه.

انواع اشیاء باینری جاسازی‌شده:

Read/write boolean .

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ شیء باینری جاسازی‌شده‌ای بارگذاری کنید.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

به طور پیش‌فرض **false** است.

**بازگشت:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

تعیین می‌کند آیا Aspose.Slides تمام اشیاء باینری جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد یا نه.

انواع اشیاء باینری جاسازی‌شده:

Read/write boolean .

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ شیء باینری جاسازی‌شده‌ای بارگذاری کنید.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

به طور پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |