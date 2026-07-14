---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to specify additional options such as format or default font when loading a presentation.
type: docs
url: /fa/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

به شما اجازه می‌دهد گزینه‌های اضافی (مانند قالب یا فونت پیش‌فرض) را هنگام بارگذاری یک ارائه مشخص کنید.

## متدها

| Method | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | بازمی‌گرداند یا تنظیم می‌کند قالب ارائه‌ای که باید بارگذاری شود. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | بازمی‌گرداند یا تنظیم می‌کند قالب ارائه‌ای که باید بارگذاری شود. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | بازمی‌گرداند یا تنظیم می‌کند فونت Regular که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | بازمی‌گرداند یا تنظیم می‌کند فونت Regular که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | بازمی‌گرداند یا تنظیم می‌کند فونت Symbol که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | بازمی‌گرداند یا تنظیم می‌کند فونت Symbol که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | بازمی‌گرداند یا تنظیم می‌کند فونت Asian که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | بازمی‌گرداند یا تنظیم می‌کند فونت Asian که در صورت عدم یافتن فونت منبع استفاده می‌شود. |
| [getPassword()](#getPassword--) | دریافت یا تنظیم رمز عبور. |
| [setPassword(String value)](#setPassword-java.lang.String-) | دریافت یا تنظیم رمز عبور. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | این ویژگی دارای معنایی است، اگر فایل ارائه با رمز عبور محافظت شود. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | این ویژگی دارای معنایی است، اگر فایل ارائه با رمز عبور محافظت شود. |
| [getWarningCallback()](#getWarningCallback--) | بازمی‌گرداند یا تنظیم می‌کند شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | بازمی‌گرداند یا تنظیم می‌کند شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | نمایش‌دهنده گزینه‌هایی است که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | نمایش‌دهنده گزینه‌هایی است که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شود مشخص می‌کند. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شود مشخص می‌کن‌د. |
| [getInterruptionToken()](#getInterruptionToken--) | توکنی برای نظارت بر درخواست‌های قطع. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | توکنی برای نظارت بر درخواست‌های قطع. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | بازمی‌گرداند یا تنظیم می‌کند رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | بازمی‌گرداند یا تنظیم می‌کند رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | نمایش می‌دهد گزینه‌هایی که می‌توانند برای مشخص کردن رفتارهای اضافی صفحه‌گسترده‌ها استفاده شوند. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | نمایش می‌دهد گزینه‌هایی که می‌توانند برای مشخص کردن رفتارهای اضافی صفحه‌گسترده‌ها استفاده شوند. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | بازمی‌گرداند یا تنظیم می‌کند زبان پیش‌فرض برای متن ارائه. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | بازمی‌گرداند یا تنظیم می‌کند زبان پیش‌فرض برای متن ارائه. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

بازمی‌گرداند یا تنظیم می‌کند قالب ارائه‌ای که باید بارگذاری شود. قابل خواندن/نوشتن [LoadFormat](../../com.aspose.slides/loadformat).

**بازگشت:**  
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

بازمی‌گرداند یا تنظیم می‌کند قالب ارائه‌ای که باید بارگذاری شود. قابل خواندن/نوشتن [LoadFormat](../../com.aspose.slides/loadformat).

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

بازمی‌گرداند یا تنظیم می‌کند فونت Regular که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

بازمی‌گرداند یا تنظیم می‌کند فونت Regular که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

بازمی‌گرداند یا تنظیم می‌کند فونت Symbol که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

بازمی‌گرداند یا تنظیم می‌کند فونت Symbol که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

بازمی‌گرداند یا تنظیم می‌کند فونت Asian که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**بازگشت:**  
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

بازمی‌گرداند یا تنظیم می‌کند فونت Asian که در صورت عدم یافتن فونت منبع استفاده می‌شود. قابل خواندن/نوشتن String.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

دریافت یا تنظیم رمز عبور. قابل خواندن/نوشتن String.

Value: The password.

**بازگشت:**  
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

دریافت یا تنظیم رمز عبور. قابل خواندن/نوشتن String.

Value: The password.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

این ویژگی دارای معنایی است، اگر فایل ارائه با رمز عبور محافظت شود. مقدار true به معنای این است که فقط ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به معنای این است که کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنا رخ می‌دهد. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

این ویژگی دارای معنایی است، اگر فایل ارائه با رمز عبور محافظت شود. مقدار true به معنای این است که فقط ویژگی‌های سند باید از یک فایل ارائه رمزگذاری شده بارگذاری شوند و رمز عبور نادیده گرفته شود. مقدار false به معنای این است که کل ارائه رمزگذاری شده باید با استفاده از رمز صحیح بارگذاری شود. اگر ارائه رمزگذاری نشده باشد، مقدار ویژگی همیشه نادیده گرفته می‌شود. اگر ویژگی‌های سند یک فایل رمزگذاری شده عمومی نباشند و مقدار ویژگی true باشد، ویژگی‌های سند نمی‌توانند بارگذاری شوند و استثنا رخ می‌دهد. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

بازمی‌گرداند یا تنظیم می‌کند شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**بازگشت:**  
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

بازمی‌گرداند یا تنظیم می‌کند شیئی که هشدارها را دریافت می‌کند و تصمیم می‌گیرد آیا فرآیند بارگذاری ادامه یابد یا متوقف شود. قابل خواندن/نوشتن [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

نمایش‌دهنده گزینه‌هایی است که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیاز خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده باینری است که به عنوان یک واحد ذخیره می‌شود — یعنی BLOB می‌تواند صوت، ویدئو یا خود ارائه باشد.

**بازگشت:**  
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

نمایش‌دهنده گزینه‌هایی است که می‌توانند برای مدیریت رفتار پردازش Binary Large Objects (BLOBs) استفاده شوند، مانند استفاده از فایل‌های موقت یا حداکثر بایت‌های BLOB در حافظه. این گزینه‌ها برای تنظیم بهترین نسبت عملکرد/مصرف حافظه برای یک محیط یا نیاز خاص طراحی شده‌اند.

--------------------

یک Binary Large Object (BLOB) داده باینری است که به عنوان یک واحد ذخیره می‌شود — یعنی BLOB می‌تواند صوت، ویدئو یا خود ارائه باشد.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شود مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند.

**بازگشت:**  
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

منابع فونت‌های خارجی را که توسط ارائه استفاده می‌شود مشخص می‌کند. این فونت‌ها در طول عمر ارائه در دسترس هستند و با ارائه‌های دیگر به اشتراک گذاشته نمی‌شوند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

توکنی برای نظارت بر درخواست‌های قطع.

--------------------

این توکن کل عمر نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) از [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) قطع می‌شود.

**بازگشت:**  
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

توکنی برای نظارت بر درخواست‌های قطع.

--------------------

این توکن کل عمر نمونه [IPresentation](../../com.aspose.slides/ipresentation) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) از [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) قطع می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

بازمی‌گرداند یا تنظیم می‌کند رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند. قابل خواندن/نوشتن [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**بازگشت:**  
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

بازمی‌گرداند یا تنظیم می‌کند رابط callback که بارگذاری منابع خارجی را مدیریت می‌کند. قابل خواندن/نوشتن [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

نمایش می‌دهد گزینه‌هایی که می‌توانند برای مشخص کردن رفتارهای اضافی صفحه‌گسترده‌ها استفاده شوند.

**بازگشت:**  
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

نمایش می‌دهد گزینه‌هایی که می‌توانند برای مشخص کردن رفتارهای اضافی صفحه‌گسترده‌ها استفاده شوند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

بازمی‌گرداند یا تنظیم می‌کند زبان پیش‌فرض برای متن ارائه. قابل خواندن/نوشتن String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعیین فرهنگ متنی پیش‌فرض استفاده کنید
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // یک شکل مستطیل جدید با متن اضافه کنید
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // زبان اولین بخش را بررسی کنید
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

بازمی‌گرداند یا تنظیم می‌کند زبان پیش‌فرض برای متن ارائه. قابل خواندن/نوشتن String.

--------------------

> ```
> Example:
>   
>  // از گزینه‌های بارگذاری برای تعیین فرهنگ متنی پیش‌فرض استفاده کنید
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // یک شکل مستطیل جدید با متن اضافه کنید
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // زبان اولین بخش را بررسی کنید
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیای باینری توکار:

 *  
 *  
 *  

قابل خواندن/نوشتن boolean .

--------------------

> ```
> مثال زیر نشان می‌دهد که چگونه ارائه را بدون هیچ شیء باینری توکار بارگذاری کنید.
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

پیش‌فرض **false** .

**بازگشت:**  
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

تعیین می‌کند آیا Aspose.Slides تمام اشیای باینری توکار را هنگام بارگذاری ارائه حذف خواهد کرد.

انواع اشیای باینری توکار:

 *  
 *  
 *  

قابل خواندن/نوشتن boolean .

--------------------

> ```
> مثال زیر نشان می‌دهد که چگونه ارائه را بدون هیچ شیء باینری توکار بارگذاری کنید.
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

پیش‌فرض **false** .

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |