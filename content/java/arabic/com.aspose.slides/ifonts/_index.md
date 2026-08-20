---
title: IFonts
second_title: Aspose.Slides ل Java مرجع API
description: يمثل مجموعة الخطوط.
type: docs
url: /ar/com.aspose.slides/ifonts/
---```
public interface IFonts
```

يمثل مجموعة الخطوط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | إرجاع أو تعيين الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | إرجاع أو تعيين الخط الشرقي الآسيوي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط الشرقي الآسيوي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | إرجاع أو تعيين الخط المعقد. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط المعقد. |
| [getScriptFontMap()](#getScriptFontMap--) | إرجاع قاموس بجميع تعريفات خطوط النصوص في العرض التقديمي. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | يجلب اسم الخط المرتبط بعلامة نصية محددة من سمة العرض التقديمي. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | يُعيّن اسم خط إلى علامة نصية محددة، مما يحدد كيفية عرض النص الخاص بذلك النص في العرض التقديمي. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | يُزيل إعداد الخط المرتبط بعلامة نصية محددة من مجموعة خطوط السمة. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


إرجاع أو تعيين الخط اللاتيني. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


إرجاع أو تعيين الخط اللاتيني. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


إرجاع أو تعيين الخط الشرقي الآسيوي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


إرجاع أو تعيين الخط الشرقي الآسيوي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


إرجاع أو تعيين الخط المعقد. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


إرجاع أو تعيين الخط المعقد. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


إرجاع قاموس بجميع تعريفات خطوط النصوص في العرض التقديمي.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**الإرجاع:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - قاموس يربط رموز النصوص بأسماء الخطوط.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


يجلب اسم الخط المرتبط بعلامة نصية محددة من سمة العرض التقديمي.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز النص وفق BCP-47 (مثال، "Latn"، "Cyrl"، "Jpan") يُستخدم لتحديد نظام كتابة. |

**الإرجاع:**
java.lang.String - اسم الخط المستخدم للنص المحدد، أو  null  إذا لم يكن النص معرفًا.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


يُعيّن اسم خط إلى علامة نصية محددة، مما يحدد كيفية عرض النص الخاص بذلك النص في العرض التقديمي.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز النص وفق BCP-47 (مثال، "Arab"، "Hebr"، "Hans") يُحدد نظام الكتابة. |
| fontName | java.lang.String | اسم الخط الذي سيُعيّن إلى النص المحدد. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


يُزيل إعداد الخط المرتبط بعلامة نصية محددة من مجموعة خطوط السمة.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز النص وفق BCP-47 الذي يجب إزالة إعداد الخط الخاص به. |