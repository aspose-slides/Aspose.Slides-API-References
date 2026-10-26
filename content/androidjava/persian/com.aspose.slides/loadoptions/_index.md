---
title: LoadOptions
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: به شما امکان می‌دهد گزینه‌های اضافی مانند قالب یا قلم پیش‌فرض را هنگام بارگذاری یک ارائه مشخص کنید.
type: docs
url: /fa/com.aspose.slides/loadoptions/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

به شما امکان می‌دهد گزینه‌های اضافی (مانند قالب یا قلم پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | گزینه‌های بارگذاری پیش‌فرض جدیدی ایجاد می‌کند. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | گزینه‌های بارگذاری جدیدی ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | مقدار format ارائه‌ای که بارگذاری می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | مقدار format ارائه‌ای که بارگذاری می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | قلم Regular را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | قلم Regular را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | قلم Asian را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | قلم Asian را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getPassword()](#getPassword--) | کلمه عبور را دریافت یا تنظیم می‌کند. |
| [setPassword(String value)](#setPassword-java.lang.String-) | کلمه عبور را دریافت یا تنظیم می‌کند. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | این ویژگی در صورتی معنا دارد که فایل ارائه دارای رمز عبور باشد. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | این ویژگی در صورتی معنا دارد که فایل ارائه دارای رمز عبور باشد. |
| [getWarningCallback()](#getWarningCallback--) | شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOBها در حافظه، نشان می‌دهد. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOBها در حافظه، نشان می‌دهد. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | منابع فونت‌های خارجی مورد استفاده توسط ارائه را مشخص می‌کند. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | منابع فونت‌های خارجی مورد استفاده توسط ارائه را مشخص می‌کند. |
| [getInterruptionToken()](#getInterruptionToken--) | توکن برای نظارت بر درخواست‌های قطع عملیات. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | توکن برای نظارت بر درخواست‌های قطع عملیات. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند را برمی‌گرداند یا تنظیم می‌کند. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند را برمی‌گرداند یا تنظیم می‌کند. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

گزینه‌های بارگذاری پیش‌فرض جدیدی ایجاد می‌کند.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

گزینه‌های بارگذاری جدیدی ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| loadFormat | int | قالب ارائه‌ای که بارگذاری می‌شود. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

مقدار format ارائه‌ای که بارگذاری می‌شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

مقدار format ارائه‌ای که بارگذاری می‌شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [LoadFormat](../../com.aspose.slides/loadformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

قلم Regular را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // از گزینه‌های بارگذاری برای تعریف قلم‌های پیش‌فرض معمولی و آسیایی استفاده کنید
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // ارائه را بارگذاری کنید
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // تصویر کوچک اسلاید تولید کنید
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF تولید کنید
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS تولید کنید
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

قلم Regular را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // از گزینه‌های بارگذاری برای تعریف قلم‌های پیش‌فرض معمولی و آسیایی استفاده کنید
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // ارائه را بارگذاری کنید
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // تصویر کوچک اسلاید تولید کنید
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // PDF تولید کنید
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // XPS تولید کنید
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

قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

قلم Symbol را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

قلم Asian را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

قلم Asian را که در صورت عدم یافتن قلم منبع استفاده می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

کلمه عبور را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // با ارائه‌ی رمزگشایی‌شده کار کنید
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

مقدار: کلمه عبور.

**بازگشت:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

کلمه عبور را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // با ارائه‌ٔ رمزگشایی‌شده کار کنید
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


مقدار: کلمه عبور.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

این ویژگی در صورتی معنا دارد که فایل ارائه دارای رمز عبور باشد. مقدار true به این معنی است که تنها ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شود و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد این ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار این ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنا پرتاب خواهد شد. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

این ویژگی در صورتی معنا دارد که فایل ارائه دارای رمز عبور باشد. مقدار true به این معنی است که تنها ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شود و رمز عبور نادیده گرفته شود. مقدار false به اینکه کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد این ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار این ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنا پرتاب خواهد شد. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گذارد آیا فرآیند بارگذاری ادامه یابد یا لغو شود را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOBها در حافظه، نشان می‌دهد. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای محیط یا نیازهای خاص در نظر گرفته شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده‌ای باینری است که به‌صورت یک واحد ذخیره می‌شود - یعنی BLOB می‌تواند صدا، ویدیو یا خود ارائه باشد.

**بازگشت:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

گزینه‌هایی را که می‌توان برای مدیریت رفتار پردازش Binary Large Objects (BLOBها) استفاده کرد، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOBها در حافظه، نشان می‌دهد. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای محیط یا نیازهای خاص در نظر گرفته شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده‌ای باینری است که به‌صورت یک واحد ذخیره می‌شود - یعنی BLOB می‌تواند صدا، ویدیو یا خود ارائه باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

منابع فونت‌های خارجی که برای ارائه استفاده می‌شوند را مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با دیگر ارائه‌ها به‌اشتراک گذاشته نمی‌شوند.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // با ارائه کار کنید
>  //CustomFont1، CustomFont2 به علاوه قلم‌های موجود در پوشه‌های assets\\fonts و global\\fonts و زیرفولدرهای آن‌ها برای ارائه در دسترس هستند
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

منابع فونت‌های خارجی که برای ارائه استفاده می‌شوند را مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با دیگر ارائه‌ها به‌اشتراک گذاشته نمی‌شوند.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // با ارائه کار کنید
>  // CustomFont1، CustomFont2 به علاوه قلم‌های موجود در پوشه‌های assets\fonts و global\fonts و زیرفولدرهای آن‌ها برای ارائه در دسترس هستند
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

توکن برای نظارت بر درخواست‌های قطع عملیات.

--------------------

این توکن تمام زمان‌زندگی نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) از [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) قطع خواهد شد.

**بازگشت:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

توکن برای نظارت بر درخواست‌های قطع عملیات.

--------------------

این توکن تمام زمان‌زندگی نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) از [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) قطع خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

شیئی که رابط callback برای مدیریت بارگذاری منابع خارجی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**بازگشت:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

شیئی که رابط callback برای مدیریت بارگذاری منابع خارجی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. برای مثال، این گزینه‌ها بر محاسبه فرمول‌های نمودارها تأثیر می‌گذارند.

**بازگشت:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

گزینه‌های مربوط به صفحات گسترده را دریافت می‌کند. برای مثال، این گزینه‌ها بر محاسبه فرمول‌های نمودارها تأثیر می‌گذارند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعیین فرهنگ متنی پیش‌فرض استفاده کنید
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

زبان پیش‌فرض متن ارائه را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعریف فرهنگ متنی پیش‌فرض استفاده کنید
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

تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیای باینری توکار:

خواندنی/نوشتنی boolean.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ شیء باینری توکار لود کنید.
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

پیش‌فرض **false** است.

**بازگشت:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیای باینری توکار:

خواندنی/نوشتنی boolean.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه ارائه را بدون هیچ شیء باینری توکار بارگذاری کنید.
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

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |