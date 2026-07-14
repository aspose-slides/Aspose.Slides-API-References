---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
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
| [getLatinFont()](#getLatinFont--) | إرجاع أو تعيين الخط Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | إرجاع أو تعيين الخط East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | إرجاع أو تعيين الخط complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | إرجاع أو تعيين الخط complex script. |
| [getScriptFontMap()](#getScriptFontMap--) | إرجاع قاموس يحتوي على جميع تعريفات خطوط script في العرض التقديمي. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | إرجاع اسم الخط المرتبط بوسم script محدد من سمة العرض التقديمي. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | تعيين اسم الخط لوسم script محدد، مما يحدد كيفية عرض النص لهذا script في العرض التقديمي. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | إزالة إعداد الخط المرتبط بوسم script محدد من مجموعة خطوط السمة. |

### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

إرجاع أو تعيين الخط Latin. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

إرجاع أو تعيين الخط Latin. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

إرجاع أو تعيين الخط East Asian. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

إرجاع أو تعيين الخط East Asian. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

إرجاع أو تعيين الخط complex script. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

إرجاع أو تعيين الخط complex script. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

إرجاع قاموس يحتوي على جميع تعريفات خطوط script في العرض التقديمي.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - قاموس يربط رموز script بأسماء الخطوط.

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

إرجاع اسم الخط المرتبط بوسم script محدد من سمة العرض التقديمي.

--------------------

> ```
> يوضح هذا المثال كيفية استرجاع الخط المعيّن لسكربت السيريلي في سمة العرض التقديمي.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز script وفق BCP-47 (مثال: "Latn"، "Cyrl"، "Jpan") المستخدم لتحديد نظام الكتابة. |

**الإرجاع:**
java.lang.String - اسم الخط المستخدم للسكريبت المحدد، أو  null  إذا لم يكن script معرفًا.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

تعيين اسم الخط لوسم script محدد، مما يحدد كيفية عرض النص لهذا script في العرض التقديمي.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز script وفق BCP-47 (مثال: "Arab"، "Hebr"، "Hans") المستخدم لتحديد نظام الكتابة. |
| fontName | java.lang.String | اسم الخط لتعيينه للسكريبت المحدد. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

إزالة إعداد الخط المرتبط بوسم script محدد من مجموعة خطوط السمة.

--------------------

> ```
> يوضح هذا المثال كيفية حذف ربط الخط لسكريبت العبرية:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز script وفق BCP-47 الذي يجب إزالة إعداد الخط الخاص به. |