---
title: FontFallBackRule
second_title: مرجع API Aspose.Slides لـ Java
description: يمثل قاعدة تراجع الخط
type: docs
url: /ar/com.aspose.slides/fontfallbackrule/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

يمثل قاعدة تراجع الخط
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Creates new instance. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Creates new instance. |
## الأساليب

| الأسلوب | الوصف |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adds a new fonts to the list of FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Creates new instance.

--------------------

> ```
> // إنشاء نسخة جديدة من FantFallBackRule بخط واحد.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // إنشاء نسخة جديدة من FantFallBackRule بعدة خطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Creates new instance.

--------------------

> ```
> // إنشاء نسخة جديدة من FantFallBackRule مع خطين
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // إنشاء نسخة جديدة من FantFallBackRule مع عدة خطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | long | Start index of unicode range |
| endIndex | long | End index of unicode range |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Adds a new font(s) to the list of FallBack fonts.

--------------------

> ```
> // إنشاء نسخة جديدة من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة خط ثانٍ إلى القاعدة 
>  newRule.addFallBackFonts("MS Gothic");
>  //إضافة الخط الثالث والرابع إلى القاعدة 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | Font's name or names (delimited by comma) for FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Adds a new fonts to the list of FallBack fonts.

--------------------

> ```
> //إنشاء نسخة جديدة من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة ثلاثة خطوط أخرى إلى القاعدة 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontNames | java.lang.String[] | Font's name or names (delimited by comma) for FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Get first index of continuous unicode range.

**الإرجاع:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Get first index of continuous unicode range.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Get last index of continuous unicode range.

**الإرجاع:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Get last index of continuous unicode range.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Gets the number of fonts actually defined for range. Read-only int.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Gets the font name at the specified index. Read-only [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Removes all fonts from the list.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Removes the first occurrence of a specific FallBack font from the list.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // إزالة Tahoma من القائمة.
>  newRule.remove("Tahoma");
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | The font's name to remove from the list. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the FallBack font at the specified index of the list.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //إزالة Tahoma من القائمة.
>  newRule.remove(2);
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | The zero-based index of the font to remove. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Creates and returns an array with all FallBack fonts for this rule.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على جميع أسماء الخطوط كمصفوفة.
>  String[] fontNames = newRule.toArray();
```

**الإرجاع:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Creates and returns an array with all FallBack fonts from the specified range in list.

```
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // الحصول على اسمين أخيرين كمصفوفة.
 String[] fontNames = newRule.toArray(2, 2);
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | An index of a first font to add. |
| count | int | A number of fonts to add. |

**الإرجاع:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Returns an index of the specified rule in the collection.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على فهرس Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | Font's name to find. |

**الإرجاع:**
int - Index of a font or -1 if font not found in list.