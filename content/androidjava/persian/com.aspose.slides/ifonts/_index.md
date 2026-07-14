---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش مجموعه‌ی فونت‌ها.
type: docs
url: /fa/com.aspose.slides/ifonts/
---```
public interface IFonts
```

نمایش مجموعه‌ی فونت‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | بازگرداندن یا تنظیم فونت لاتین. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت لاتین. |
| [getEastAsianFont()](#getEastAsianFont--) | بازگرداندن یا تنظیم فونت آسیای شرقی. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت آسیای شرقی. |
| [getComplexScriptFont()](#getComplexScriptFont--) | بازگرداندن یا تنظیم فونت اسکریپت پیچیده. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | بازگرداندن یا تنظیم فونت اسکریپت پیچیده. |
| [getScriptFontMap()](#getScriptFontMap--) | بازگرداندن یک دیکشنری از تمام تعاریف فونت اسکریپت در ارائه. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | دریافت نام فونتی که به یک برچسب اسکریپت خاص در تم ارائه مرتبط است. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | اختصاص نام فونت به یک برچسب اسکریپت خاص که تعیین می‌کند متن آن اسکریپت در ارائه چگونه رندر شود. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | حذف تنظیم فونت مرتبط با یک برچسب اسکریپت خاص از مجموعه فونت‌های تم. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

بازگرداندن یا تنظیم فونت لاتین. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

بازگرداندن یا تنظیم فونت لاتین. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

بازگرداندن یا تنظیم فونت آسیای شرقی. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

بازگرداندن یا تنظیم فونت آسیای شرقی. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

بازگرداندن یا تنظیم فونت اسکریپت پیچیده. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**بازگشت:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

بازگرداندن یا تنظیم فونت اسکریپت پیچیده. خواندنی/نوشتنی [IFontData](../../com.aspose.slides/ifontdata).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

بازگرداندن یک دیکشنری از تمام تعاریف فونت اسکریپت در ارائه.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

دریافت نام فونتی که به یک برچسب اسکریپت خاص در تم ارائه مرتبط است.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (مانند "Latn"، "Cyrl"، "Jpan") که برای شناسایی یک سیستم نوشتاری استفاده می‌شود. |

**بازگشت:**
java.lang.String - نام فونتی که برای اسکریپت مشخص شده استفاده می‌شود، یا  null  اگر اسکریپت تعریف نشده باشد.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

اختصاص نام فونت به یک برچسب اسکریپت خاص که تعیین می‌کند متن آن اسکریپت در ارائه چگونه رندر شود.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segue UI");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 (مانند "Arab"، "Hebr"، "Hans") که سیستم نوشتاری را شناسایی می‌کند. |
| fontName | java.lang.String | نام فونتی که باید به اسکریپت مشخص شده اختصاص داده شود. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

حذف تنظیم فونت مرتبط با یک برچسب اسکریپت خاص از مجموعه فونت‌های تم.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | java.lang.String | کد اسکریپت BCP-47 که تنظیم فونت آن باید حذف شود. |