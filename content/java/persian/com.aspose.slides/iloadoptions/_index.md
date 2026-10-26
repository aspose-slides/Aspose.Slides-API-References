---
title: ILoadOptions
second_title: Aspose.Slides for Java API Reference
description: امکان تعیین گزینه‌های اضافی مانند قالب یا فونت پیش‌فرض را هنگام بارگذاری یک ارائه فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

امکان تعیین گزینه‌های اضافی (مانند قالب یا فونت پیش‌فرض) هنگام بارگذاری یک ارائه را فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | فرمت ارائه‌ای که بارگذاری می‌شود را بازگردانده یا تنظیم می‌کند. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | فرمت ارائه‌ای که بارگذاری می‌شود را بازگردانده یا تنظیم می‌کند. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | فونت Regular را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | فونت Regular را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | فونت Asian را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | فونت Asian را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. |
| [getPassword()](#getPassword--) | رمز عبور را دریافت یا تنظیم می‌کند. |
| [setPassword(String value)](#setPassword-java.lang.String-) | رمز عبور را دریافت یا تنظیم می‌کند. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | این ویژگی در صورتی که فایل ارائه با رمز محافظت شده باشد معنا دارد. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | این ویژگی در صورتی که فایل ارائه با رمز محافظت شده باشد معنا دارد. |
| [getWarningCallback()](#getWarningCallback--) | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، بازگردانده یا تنظیم می‌شود. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، بازگردانده یا تنظیم می‌شود. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | گزینه‌هایی که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOB در حافظه، بازگردانده یا تنظیم می‌شود. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | گزینه‌هایی که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOB در حافظه، بازگردانده یا تنظیم می‌شود. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، تعیین می‌کند. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، تعیین می‌کند. |
| [getInterruptionToken()](#getInterruptionToken--) | نشانه‌ای برای پایش درخواست‌های قطع. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | نشانه‌ای برای پایش درخواست‌های قطع. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | یک رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند، بازگردانده یا تنظیم می‌شود. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | یک رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند، بازگردانده یا تنظیم می‌شود. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | گزینه‌هایی که می‌توانند برای مشخص کردن رفتار اضافی spreadsheets استفاده شوند، بازگردانده یا تنظیم می‌شود. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | گزینه‌هایی که می‌توانند برای مشخص کردن رفتار اضافی spreadsheets استفاده شوند، بازگردانده یا تنظیم می‌شود. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | زبان پیش‌فرض برای متن ارائه را بازگردانده یا تنظیم می‌کند. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | زبان پیش‌فرض برای متن ارائه را بازگردانده یا تنظیم می‌کند. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | مشخص می‌کند آیا Aspose.Slides همه اشیاء دودویی جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | مشخص می‌کند آیا Aspose.Slides همه اشیاء دودویی جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

فرمت ارائه‌ای که بارگذاری می‌شود را بازگردانده یا تنظیم می‌کند. خواندن/نوشتن [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

فرمت ارائه‌ای که بارگذاری می‌شود را بازگردانده یا تنظیم می‌کند. خواندن/نوشتن [LoadFormat](../../com.aspose.slides/loadformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

فونت Regular را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**بازگشت:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

فونت Regular را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**بازگشت:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

فونت Symbol را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

فونت Asian را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**بازگشت:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

فونت Asian را که در صورت عدم یافتن فونت منبع استفاده می‌شود، بازگردانده یا تنظیم می‌کند. خواندن-نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

رمز عبور را دریافت یا تنظیم می‌کند. خواندن-نوشتن String.

Value: رمز عبور.

**بازگشت:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

رمز عبور را دریافت یا تنظیم می‌کند. خواندن-نوشتن String.

Value: رمز عبور.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

این ویژگی در صورتی که فایل ارائه با رمز محافظت شده باشد معنا دارد. مقدار true به این معنی است که فقط ویژگی‌های سند از یک فایل ارائهٔ رمزگذاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائهٔ رمزگذاری‌شده با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند قابل بارگذاری نیستند و استثنایی پرتاب می‌شود. خواندن-نوشتن boolean.

**بازگشت:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

این ویژگی در صورتی که فایل ارائه با رمز محافظت شده باشد معنا دارد. مقدار true به این معنی است که فقط ویژگی‌های سند از یک فایل ارائهٔ رمزگذاری‌شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به این معنی است که کل ارائهٔ رمزگذاری‌شده با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری‌شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند قابل بارگذاری نیستند و استثنایی پرتاب می‌شود. خواندن-نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، بازگردانده یا تنظیم می‌شود. خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

یک شیء که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا لغو شود، بازگردانده یا تنظیم می‌شود. خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

گزینه‌هایی که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOB در حافظه، بازگردانده یا تنظیم می‌شود. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای محیط یا نیازهای خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) دادهٔ باینری است که به‌صورت یک واحد ذخیره می‌شود؛ به‌عبارت دیگر BLOB می‌تواند یک صوت، ویدئو یا خود ارائه باشد.

**بازگشت:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

گزینه‌هایی که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت BLOB در حافظه، بازگردانده یا تنظیم می‌شود. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای محیط یا نیازهای خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) دادهٔ باینری است که به‌صورت یک واحد ذخیره می‌شود؛ به‌عبارت دیگر BLOB می‌تواند یک صوت، ویدئو یا خود ارائه باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، تعیین می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به‌اشتراک گذاشته نمی‌شوند.

**بازگشت:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شوند، تعیین می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با سایر ارائه‌ها به‌اشتراک گذاشته نمی‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

نشانه‌ای برای پایش درخواست‌های قطع.

--------------------

این نشانه تمام دورهٔ حیات نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیرهٔ ارائه، با فراخوانی متد [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) از [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) قطع می‌شود.

**بازگشت:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

نشانه‌ای برای پایش درخواست‌های قطع.

--------------------

این نشانه تمام دورهٔ حیات نمونهٔ [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیرهٔ ارائه، با فراخوانی متد [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) از [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) قطع می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

یک رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند، بازگردانده یا تنظیم می‌شود. خواندن/نوشتن [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**بازگشت:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

یک رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند، بازگردانده یا تنظیم می‌شود. خواندن/نوشتن [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

گزینه‌هایی که می‌توانند برای مشخص کردن رفتار اضافی spreadsheets استفاده شوند، بازگردانده یا تنظیم می‌شود.

**بازگشت:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

گزینه‌هایی که می‌توانند برای مشخص کردن رفتار اضافی spreadsheets استفاده شوند، بازگردانده یا تنظیم می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

زبان پیش‌فرض برای متن ارائه را بازگردانده یا تنظیم می‌کند. خواندن/نوشتن String.

--------------------

> ``` 
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعریف فرهنگ پیش‌فرض متن استفاده کنید
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
public abstract void setDefaultTextLanguage(String value)
```

زبان پیش‌فرض برای متن ارائه را بازگردانده یا تنظیم می‌کند. خواندن/نوشتن String.

--------------------

> ``` 
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعریف فرهنگ پیش‌فرض متن استفاده کنید
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // افزودن شکل مستطیل جدید با متن
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
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

مشخص می‌کند آیا Aspose.Slides همه اشیاء دودویی جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیاء دودویی جاسازی‌شده:

 *  
 *  
 *  

خواندن/نوشتن boolean.

--------------------

> ``` 
> مثال زیر نشان می‌دهد چگونه می‌توان ارائه را بدون هیچ شیء دودویی جاسازی‌شده‌ای بارگذاری کرد.
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
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

مشخص می‌کند آیا Aspose.Slides همه اشیاء دودویی جاسازی‌شده را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیاء دودویی جاسازی‌شده:

 *  
 *  
 *  

خواندن/نوشتن boolean.

--------------------

> ``` 
> مثال زیر نشان می‌دهد چگونه می‌توان ارائه را بدون هیچ شیء دودویی جاسازی‌شده‌ای بارگذاری کرد.
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