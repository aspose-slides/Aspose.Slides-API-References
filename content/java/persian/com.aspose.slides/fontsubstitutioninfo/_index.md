---
title: FontSubstitutionInfo
second_title: مرجع API Aspose.Slides برای جاوا
description: این ساختار اطلاعات مربوط به جایگزینی قلم را زمانی که رندر می‌شود، نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/fontsubstitutioninfo/
---
**ارث‌بری:**  
java.lang.Object  
```
public class FontSubstitutionInfo
```

این ساختار اطلاعات مربوط به جایگزینی قلم را زمانی که رندر می‌شود، نمایان می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | یک نمونه از کلاس [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | نام قلم منبع را در ارائه نشان می‌دهد. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | نام قلم جایگزین برای قلم اصلی را نشان می‌دهد. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

یک نمونه از کلاس [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| originFontName | java.lang.String | نام قلم منبع در ارائه String |
| substFontName | java.lang.String | نام قلم جایگزین برای قلم اصلی String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

نام قلم منبع را در ارائه نشان می‌دهد. رشته فقط-خواندنی

**بازگشت:**  
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

نام قلم جایگزین برای قلم اصلی را نشان می‌دهد. رشته فقط-خواندنی

**بازگشت:**  
java.lang.String