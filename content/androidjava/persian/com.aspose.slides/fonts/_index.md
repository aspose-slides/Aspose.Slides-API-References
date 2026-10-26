---
title: Fonts
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مجموعه فونت‌ها.
type: docs
url: /fa/com.aspose.slides/fonts/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

مجموعه فونت‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | یک دیکشنری از تمام تعاریف قلم اسکریپت در ارائه را برمی‌گرداند. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | نام قلم مرتبط با یک برچسب اسکریپت خاص را از تم ارائه دریافت می‌کند. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | نام قلم را به یک برچسب اسکریپت خاص اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت در ارائه چگونه نمایش داده شود. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | تنظیمات قلم مرتبط با یک برچسب اسکریپت خاص را از مجموعه قلم‌های تم حذف می‌کند. |
| [getLatinFont()](#getLatinFont--) | قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. |
| [getEastAsianFont()](#getEastAsianFont--) | قلم شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | قلم شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. |
| [getComplexScriptFont()](#getComplexScriptFont--) | قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

یک دیکشنری از تمام تعاریف قلم اسکریپت در ارائه را برمی‌گرداند.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**بازگشت:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - یک دیکشنری که کدهای اسکریپت را به نام‌های قلم نگاشت می‌کند.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

نام قلم مرتبط با یک برچسب اسکریپت خاص را از تم ارائه دریافت می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد چگونه می‌توان قلم اختصاص یافته به اسکریپت سیریلیک را در تم ارائه بازیابی کرد.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (مثلاً "Latn", "Cyrl", "Jpan") که برای شناسایی یک سیستم نوشتاری استفاده می‌شود. |

**بازگشت:**
java.lang.String - نام قلم مورد استفاده برای اسکریپت مشخص‌شده، یا  null  اگر اسکریپت تعریف نشده باشد.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

نام قلم را به یک برچسب اسکریپت خاص اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت در ارائه چگونه نمایش داده شود.

--------------------

> ```
> این مثال نشان می‌دهد چگونه قلم برای اسکریپت عربی به "Segoe UI" تنظیم شود:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (مثلاً "Arab", "Hebr", "Hans") که سیستم نوشتاری را شناسایی می‌کند. |
| fontName | java.lang.String | نام قلم برای اختصاص به اسکریپت مشخص‌شده. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

تنظیمات قلم مرتبط با یک برچسب اسکریپت خاص را از مجموعه قلم‌های تم حذف می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد چگونه نگاشت قلم برای اسکریپت عبری حذف شود:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 که تنظیم قلم آن باید حذف شود. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

قلم لاتین را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

قلم شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

قلم شرق آسیا را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

قلم اسکریپت پیچیده را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |