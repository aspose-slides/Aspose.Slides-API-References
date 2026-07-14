---
title: FontSubstitutionInfo
second_title: Aspose.Slides برای Android از طریق مستندات API جاوا
description: این ساختار اطلاعات مربوط به جایگزینی قلم را در زمانی که رندر می‌شود، نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**  
java.lang.Object  
```
public class FontSubstitutionInfo
```

این ساختار اطلاعات درباره جایگزینی قلم را زمانی که رندر می‌شود، نشان می‌دهد.

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
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | یک نمونه از [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) کلاس ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | نام قلم منبع در ارائه را نشان می‌دهد. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | نام قلم جایگزین برای قلم اصلی را نشان می‌دهد. |

### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

یک نمونه از [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) کلاس ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| originFontName | java.lang.String | نام قلم منبع در ارائه String |
| substFontName | java.lang.String | نام قلم جایگزین برای قلم اصلی String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

نام قلم منبع در ارائه را نشان می‌دهد. فقط خواندنی String

**بازگرداندن مقدار:**  
java.lang.String

### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

نام قلم جایگزین برای قلم اصلی را نشان می‌دهد. فقط خواندنی String

**بازگرداندن مقدار:**  
java.lang.String