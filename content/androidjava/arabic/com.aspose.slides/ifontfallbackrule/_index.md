---
title: IFontFallBackRule
second_title: Aspose.Slides لأجهزة Android عبر Java API Reference
description: يمثل قاعدة التراجع عن الخط
type: docs
url: /ar/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

يمثل قاعدة التراجع عن الخط
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | يضيف خطوطًا جديدة إلى قائمة خطوط التراجع. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | يضيف خطوطًا جديدة إلى قائمة خطوط التراجع. |
| [getRangeStartIndex()](#getRangeStartIndex--) | يحصل على الفهرس الأول لنطاق Unicode المتصل. |
| [getRangeEndIndex()](#getRangeEndIndex--) | يحصل على الفهرس الأخير لنطاق Unicode المتصل. |
| [getCount()](#getCount--) | يحصل على عدد الخطوط المحددة فعليًا للنطاق. |
| [get_Item(int index)](#get-Item-int-) | يحصل على اسم الخط في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الخطوط من القائمة. |
| [remove(String fontName)](#remove-java.lang.String-) | يزيل أول تواجد لخط تراجع محدد من القائمة. |
| [removeAt(int index)](#removeAt-int-) | يزيل خط التراجع في الفهرس المحدد بالقائمة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع خطوط التراجع لهذا القاعدة. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويعيد مصفوفة تحتوي على جميع خطوط التراجع من النطاق المحدد في القائمة. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | يعيد فهرس القاعدة المحددة في المجموعة. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

يضيف خطوطًا جديدة إلى قائمة خطوط التراجع.

--------------------

> ```
> //إنشاء نسخة جديدة من FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة خط ثانٍ إلى القاعدة
>  newRule.addFallBackFonts("MS Gothic");
>  //إضافة الخط الثالث والرابع إلى القاعدة
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط أو أسماء الخطوط (مفصولة بفواصل) للتراجع |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

يضيف خطوطًا جديدة إلى قائمة خطوط التراجع.

--------------------

> ```
> //إنشاء نسخة جديدة من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة ثلاثة خطوط أخرى إلى القاعدة 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontNames | java.lang.String[] | اسم الخط أو أسماء الخطوط (مفصولة بفواصل) للتراجع |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

يحصل على الفهرس الأول لنطاق Unicode المتصل.

**القيمة المرجعة:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

يحصل على الفهرس الأخير لنطاق Unicode المتصل.

**القيمة المرجعة:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد الخطوط المحددة فعليًا للنطاق.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

يحصل على اسم الخط في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع الخطوط من القائمة.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

يزيل أول تواجد لخط تراجع محدد من القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //إزالة Tahoma من القائمة
>  newRule.remove("Tahoma");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط لإزالته من القائمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل خط التراجع في الفهرس المحدد بالقائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //إزالة Tahoma من القائمة
>  newRule.remove(2);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخط المراد إزالته. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع خطوط التراجع لهذا القاعدة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على جميع أسماء الخطوط كمصفوفة
>  String[] fontNames = newRule.toArray();
> ```


**القيمة المرجعة:**
java.lang.String[] - مصفوفة من سلاسل النص
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

ينشئ ويعيد مصفوفة تحتوي على جميع خطوط التراجع من النطاق المحدد في القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على آخر اسمين للخط كـمصفوفة
>  String[] fontNames = newRule.toArray(2,2);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس الخط الأول للإضافة. |
| count | int | عدد الخطوط للإضافة. |

**القيمة المرجعة:**
java.lang.String[] - مصفوفة من سلاسل النص
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

يعيد فهرس القاعدة المحددة في المجموعة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //احصل على فهرس Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط للبحث عنه. |

**القيمة المرجعة:**
int - فهرس الخط أو -1 إذا لم يُعثر على الخط في القائمة.