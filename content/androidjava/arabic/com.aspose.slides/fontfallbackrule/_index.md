---
title: FontFallBackRule
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل قاعدة الاحتياطي للخط
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

يمثل قاعدة الاحتياطي للخط
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | ينشئ مثيلاً جديداً. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | ينشئ مثيلاً جديداً. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | يضيف خطاً جديداً إلى قائمة خطوط الاحتياطي. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | يضيف خطوطاً جديدة إلى قائمة خطوط الاحتياطي. |
| [getRangeStartIndex()](#getRangeStartIndex--) | يحصل على الفهرس الأول لنطاق Unicode المتصل. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | يحصل على الفهرس الأول لنطاق Unicode المتصل. |
| [getRangeEndIndex()](#getRangeEndIndex--) | يحصل على الفهرس الأخير لنطاق Unicode المتصل. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | يحصل على الفهرس الأخير لنطاق Unicode المتصل. |
| [getCount()](#getCount--) | يحصل على عدد الخطوط المعرفة فعليًا للنطاق. |
| [get_Item(int index)](#get-Item-int-) | يحصل على اسم الخط عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الخطوط من القائمة. |
| [remove(String fontName)](#remove-java.lang.String-) | يزيل أول ظهور لخط احتياطي محدد من القائمة. |
| [removeAt(int index)](#removeAt-int-) | يزيل الخط الاحتياطي عند الفهرس المحدد في القائمة. |
| [toArray()](#toArray--) | ينشئ ويرجع مصفوفة تحتوي على جميع خطوط الاحتياطي لهذا القاعدة. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويرجع مصفوفة تحتوي على جميع خطوط الاحتياطي من النطاق المحدد في القائمة. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | يرجع فهرس القاعدة المحددة في المجموعة. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

ينشئ مثيلاً جديداً.

--------------------

> ```
> // إنشاء مثيل جديد من FantFallBackRule بخط واحد.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // إنشاء مثيل جديد من FantFallBackRule بعدة خطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | long | فهرس البداية لنطاق Unicode |
| endIndex | long | فهرس النهاية لنطاق Unicode |
| fontNames | java.lang.String | اسم الخط أو الأسماء (مفصولة بفواصل) للخط الاحتياطي |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

ينشئ مثيلاً جديداً.

--------------------

> ```
> // إنشاء مثيل جديد من FantFallBackRule بخطين
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // إنشاء مثيل جديد من FantFallBackRule بعدة خطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | long | فهرس البداية لنطاق Unicode |
| endIndex | long | فهرس النهاية لنطاق Unicode |
| fontNames | java.lang.String[] | اسم الخط أو الأسماء (مفصولة بفواصل) للخط الاحتياطي |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

يضيف خطاً جديداً إلى قائمة خطوط الاحتياطي.

--------------------

> ```
> // إنشاء مثيل جديد من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة خط ثانٍ إلى القاعدة 
>  newRule.addFallBackFonts("MS Gothic");
>  //إضافة الخط الثالث والرابع إلى القاعدة 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط أو الأسماء (مفصولة بفواصل) للخط الاحتياطي |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

يضيف خطوطاً جديدة إلى قائمة خطوط الاحتياطي.

--------------------

> ```
> //إنشاء مثيل جديد من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة ثلاثة خطوط أخرى إلى القاعدة 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontNames | java.lang.String[] | اسم الخط أو الأسماء (مفصولة بفواصل) للخط الاحتياطي |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

يحصل على الفهرس الأول لنطاق Unicode المتصل.

**القيمة المرجعة:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

يحصل على الفهرس الأول لنطاق Unicode المتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

يحصل على الفهرس الأخير لنطاق Unicode المتصل.

**القيمة المرجعة:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

يحصل على الفهرس الأخير لنطاق Unicode المتصل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد الخطوط المعرفة فعليًا للنطاق. للقراءة فقط int.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

يحصل على اسم الخط عند الفهرس المحدد. للقراءة فقط [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الخطوط من القائمة.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

يزيل أول ظهور لخط احتياطي محدد من القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // إزالة Tahoma من القائمة.
>  newRule.remove("Tahoma");
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط لإزالته من القائمة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل الخط الاحتياطي عند الفهرس المحدد في القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // إزالة Tahoma من القائمة.
>  newRule.remove(2);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخط المراد إزالته. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

ينشئ ويرجع مصفوفة تحتوي على جميع خطوط الاحتياطي لهذا القاعدة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على جميع أسماء الخطوط كمصفوفة.
>  String[] fontNames = newRule.toArray();
> ```

**القيمة المرجعة:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

ينشئ ويرجع مصفوفة تحتوي على جميع خطوط الاحتياطي من النطاق المحدد في القائمة.

```
// إنشاء قاعدة تحتوي على قائمة من الخطوط.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // الحصول على آخر اسمي خط كمصفوفة.
 String[] fontNames = newRule.toArray(2, 2);
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول خط للإضافة. |
| count | int | عدد الخطوط للإضافة. |

**القيمة المرجعة:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

يرجع فهرس القاعدة المحددة في المجموعة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على فهرس Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط للبحث عنه. |

**القيمة المرجعة:**
int - Index of a font or -1 if font not found in list.