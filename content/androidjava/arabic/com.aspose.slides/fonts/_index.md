---
title: Fonts
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: مجموعة الخطوط.
type: docs
url: /ar/com.aspose.slides/fonts/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

مجموعة الخطوط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | يعيد قاموسًا يحتوي على جميع تعريفات خطوط النص في العرض التقديمي. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | يحصل على اسم الخط المرتبط بعلامة نصية معينة من سمة العرض التقديمي. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | يعين اسم الخط لعلامة نصية معينة، مما يحدد كيفية عرض نص تلك اللغة في العرض التقديمي. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | يزيل إعداد الخط المرتبط بعلامة نصية معينة من مجموعة خطوط السمة. |
| [getLatinFont()](#getLatinFont--) | يعيد أو يعيّن الخط اللاتيني. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | يعيد أو يعيّن الخط اللاتيني. |
| [getEastAsianFont()](#getEastAsianFont--) | يعيد أو يعيّن الخط شرق آسيوي. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | يعيد أو يعيّن الخط شرق آسيوي. |
| [getComplexScriptFont()](#getComplexScriptFont--) | يعيد أو يعيّن الخط النصي المعقد. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | يعيد أو يعيّن الخط النصي المعقد. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

يعيد قاموسًا يحتوي على جميع تعريفات خطوط النص في العرض التقديمي.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - قاموس يطابق رموز النص إلى أسماء الخطوط.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

يحصل على اسم الخط المرتبط بعلامة نصية معينة من سمة العرض التقديمي.

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
| script | java.lang.String | رمز النص وفق BCP-47 (مثال: "Latn"، "Cyrl"، "Jpan") يُستخدم لتحديد نظام كتابة. |

**الإرجاع:**
java.lang.String - اسم الخط المستخدم للنص المحدد، أو  null  إذا لم يتم تعريف النص.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

يعين اسم الخط لعلامة نصية معينة، مما يحدد كيفية عرض نص تلك اللغة في العرض التقديمي.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز النص وفق BCP-47 (مثال: "Arab"، "Hebr"، "Hans") يُستخدم لتحديد نظام كتابة. |
| fontName | java.lang.String | اسم الخط الذي سيتم تعيينه للنص المحدد. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

يزيل إعداد الخط المرتبط بعلامة نصية معينة من مجموعة خطوط السمة.

--------------------

> ```
> هذا المثال يوضح كيفية إزالة تعيين الخط للنص العبري:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | java.lang.String | رمز النص وفق BCP-47 الذي يجب إزالة إعداد الخط الخاص به. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

يعيد أو يعيّن الخط اللاتيني. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

يعيد أو يعيّن الخط اللاتيني. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

يعيد أو يعيّن الخط شرق آسيوي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

يعيد أو يعيّن الخط شرق آسيوي. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

يعيد أو يعيّن الخط النصي المعقد. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

يعيد أو يعيّن الخط النصي المعقد. قراءة/كتابة [IFontData](../../com.aspose.slides/ifontdata).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |