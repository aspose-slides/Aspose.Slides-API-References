---
title: FontsLoader
second_title: مرجع API Aspose.Slides برای جاوا
description: کلاسی برای بارگذاری فونت‌های سفارشی تعریف‌شده توسط کاربر.
type: docs
url: /fa/com.aspose.slides/fontsloader/
---
**Inheritance:**  
وراثت:

java.lang.Object

**All Implemented Interfaces:**  
همه اینترفیس‌های پیاده‌سازی‌شده:

[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

کلاسی برای بارگذاری فونت‌های سفارشی تعریف‌شده توسط کاربر. باید قبل از ایجاد هر شیء ارائه‌ای استفاده شود.

## متدها

| متد | توضیح |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | پوشه‌های اضافی برای جستجو فونت‌ها را اضافه می‌کند. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | فونت را از داده‌های باینری اضافه می‌کند |
| [getFontFolders()](#getFontFolders--) | پوشه‌های فونت را دریافت می‌کند. |
| [clearCache()](#clearCache--) | تمام فونت‌های سفارشی تعریف‌شده توسط کاربر را آزاد می‌کند |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

پوشه‌های اضافی برای جستجو فونت‌ها را اضافه می‌کند.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // پوشه‌ها برای جستجوی فونت‌ها
>  String[] folders = new String[] { dataDir };
>  // بارگذاری فونت‌های پوشه سفارشی
>  FontsLoader.loadExternalFonts(folders);
>  // انجام کارهایی و رندر کردن ارائه/اسلایدها
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // حذف کش فونت
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| directories | java.lang.String[] | پوشه‌هایی که برای خواندن فونت‌های اضافی استفاده می‌شوند. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

فونت را از داده‌های باینری اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های فونت |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

پوشه‌های فونت را دریافت می‌کند. پوشه‌هایی را که با متد LoadExternalFonts اضافه شده‌اند به‌همراه پوشه‌های فونت سیستمی برمی‌گرداند

**بازگشت:**
java.lang.String[] - آرایه‌ای شامل نام پوشه‌ها

### clearCache() {#clearCache--}
```
public static void clearCache()
```

تمام فونت‌های سفارشی تعریف‌شده توسط کاربر را آزاد می‌کند

--------------------

این متد نیاز دارد کش را با فونت‌های سفارشی تعریف‌شده توسط کاربر پاک‌سازی کند.