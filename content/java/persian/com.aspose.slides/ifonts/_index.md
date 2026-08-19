---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: نمایندهٔ مجموعهٔ قلم‌ها.
type: docs
url: /fa/com.aspose.slides/ifonts/
---```
public interface IFonts
```

نمایندهٔ مجموعهٔ قلم‌ها.
## متدها

| متد | توضحیح |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | بازگرداندن یا تنظیم فونت لاتین. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت لاتین. |
| [getEastAsianFont()](#getEastAsianFont--) | بازگرداندن یا تنظیم فونت شرق آسیا. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت شرق آسیا. |
| [getComplexScriptFont()](#getComplexScriptFont--) | بازگرداندن یا تنظیم فونت اسکریپت پیچیده. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت اسکریپت پیچیده. |
| [getScriptFontMap()](#getScriptFontMap--) | بازگرداندن یک فرهنگ‌نامه از تمام تعاریف قلم اسکریپت در ارائه. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | دریافت نام قلم مرتبط با یک برچسب اسکریپت خاص از تم ارائه. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | اختصاص نام قلم به یک برچسب اسکریپت خاص، که نحوه رندر متن آن اسکریپت را در ارائه تعریف می‌کند. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | حذف تنظیم قلم مرتبط با یک برچسب اسکریپت خاص از مجموعهٔ قلم‌های تم. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


بازگرداندن یا تنظیم فونت لاتین. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گردد:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


بازگرداندن یا تنظیم فونت لاتین. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


بازگرداندن یا تنظیم فونت شرق آسیا. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گردد:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


بازگرداندن یا تنظیم فونت شرق آسیا. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


بازگرداندن یا تنظیم فونت اسکریپت پیچیده. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**بازمی‌گردد:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


بازگرداندن یا تنظیم فونت اسکریپت پیچیده. خواندن/نوشتن [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


بازگرداندن یک فرهنگ‌نامه از تمام تعاریف قلم اسکریپت در ارائه.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**بازمی‌گردد:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - یک فرهنگ‌نامه که کدهای اسکریپت را به نام‌های قلم نگاشت می‌کند.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


دریافت نام قلم مرتبط با یک برچسب اسکریپت خاص از تم ارائه.

--------------------

> ```
> این مثال نشان می‌دهد چگونه قلم اختصاص داده شده به اسکریپت سیریلیک را در تم ارائه بازیابی کنید.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (به عنوان مثال، "Latn"، "Cyrl"، "Jpan") که برای شناسایی یک سیستم نوشتاری استفاده می‌شود. |

**بازمی‌گردد:**
java.lang.String - نام قلم استفاده شده برای اسکریپت مشخص‌شده، یا  null  اگر اسکریپت تعریف نشده باشد.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


اختصاص نام قلم به یک برچسب اسکریپت خاص، که نحوه رندر متن آن اسکریپت را در ارائه تعریف می‌کند.

--------------------

> ```
> این مثال نشان می‌دهد چگونه قلم برای اسکریپت عربی به "Segoe UI" تنظیم شود:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (به عنوان مثال، "Arab"، "Hebr"، "Hans") که سیستم نوشتاری را شناسایی می‌کند. |
| fontName | java.lang.String | نام قلمی که باید به اسکریپت مشخص‌شده اختصاص یابد. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


حذف تنظیم قلم مرتبط با یک برچسب اسکریپت خاص از مجموعهٔ قلم‌های تم.

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