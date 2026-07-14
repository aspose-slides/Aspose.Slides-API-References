---
title: FontsLoader
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: کلاسی برای بارگذاری قلم‌های سفارشی تعریف‌شده توسط کاربر.
type: docs
url: /fa/com.aspose.slides/fontsloader/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

کلاسی برای بارگذاری قلم‌های سفارشی تعریف‌شده توسط کاربر. باید قبل از ایجاد هر شیء ارائه مورد استفاده قرار گیرد.
## متدها

| متد | توضیح |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | پوشه‌های اضافی برای جستجوی قلم‌ها را اضافه می‌کند. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | قلم را از داده‌های باینری اضافه می‌کند |
| [getFontFolders()](#getFontFolders--) | قلم‌پوشه‌ها را دریافت می‌کند. |
| [clearCache()](#clearCache--) | تمام قلم‌های سفارشی تعریف‌شده توسط کاربر را آزاد می‌کند |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


پوشه‌های اضافی برای جستجوی قلم‌ها را اضافه می‌کند.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // پوشه‌ها برای جستجوی قلم‌ها
>  String[] folders = new String[] { dataDir };
>  // پوشه قلم سفارشی را بارگذاری کنید
>  FontsLoader.loadExternalFonts(folders);
>  // کارهای لازم را انجام داده و رندر ارائه/اسلایدها را اجرا کنید
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // کش قلم را پاک کنید
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| directories | java.lang.String[] | پوشه‌هایی برای خواندن قلم‌های اضافی. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


قلم را از داده‌های باینری اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های قلم |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


قلم‌پوشه‌ها را دریافت می‌کند. پوشه‌هایی که با متد LoadExternalFonts اضافه شده‌اند و همچنین پوشه‌های قلم سیستم را برمی‌گرداند

**بازگشت:**
java.lang.String[] - آرایه‌ای حاوی نام پوشه‌ها
### clearCache() {#clearCache--}
```
public static void clearCache()
```


تمام قلم‌های سفارشی تعریف‌شده توسط کاربر را آزاد می‌کند

--------------------

این متد نیاز دارد کش قلم‌های سفارشی تعریف‌شده توسط کاربر را پاک سازی کند.