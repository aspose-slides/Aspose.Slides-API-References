---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: يمثل قاعدة احتياطي الخط
type: docs
url: /ar/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

يمثل قاعدة احتياطي الخط
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | يضيف خطًا (أو خطوطًا) جديدًا إلى قائمة الخطوط الاحتياطية. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | يضيف خطوطًا جديدة إلى قائمة الخطوط الاحتياطية. |
| [getRangeStartIndex()](#getRangeStartIndex--) | يحصل على الفهرس الأول لنطاق يونيكود المتصل. |
| [getRangeEndIndex()](#getRangeEndIndex--) | يحصل على الفهرس الأخير لنطاق يونيكود المتصل. |
| [getCount()](#getCount--) | يحصل على عدد الخطوط المعرفة فعليًا للنطاق. |
| [get_Item(int index)](#get-Item-int-) | يحصل على اسم الخط في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الخطوط من القائمة. |
| [remove(String fontName)](#remove-java.lang.String-) | يزيل أول ظهور لخط احتياطي محدد من القائمة. |
| [removeAt(int index)](#removeAt-int-) | يزيل الخط الاحتياطي في الفهرس المحدد من القائمة. |
| [toArray()](#toArray--) | ينشئ ويُرجِع مصفوفة تحتوي على جميع الخطوط الاحتياطية لهذه القاعدة. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | ينشئ ويُرجِع مصفوفة تحتوي على جميع الخطوط الاحتياطية من النطاق المحدد في القائمة. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | يعطي فهرس القاعدة المحددة في المجموعة. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

يضيف خطًا (أو خطوطًا) جديدًا إلى قائمة الخطوط الاحتياطية.

--------------------

> ```
> //إنشاء نسخة جديدة من FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة خط ثانٍ إلى القاعدة 
>  newRule.addFallBackFonts("MS Gothic");
>  //إضافة الخط الثالث والرابع إلى القاعدة 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط أو الأسماء (مفصولة بفواصل) للاحتياطي |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

يضيف خطوطًا جديدة إلى قائمة الخطوط الاحتياطية.

--------------------

> ```
> //إنشاء نسخة جديدة من FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //إضافة ثلاثة خطوط أخرى إلى القاعدة 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontNames | java.lang.String[] | اسم الخط أو الأسماء (مفصولة بفواصل) للاحتياطي |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

يحصل على الفهرس الأول لنطاق يونيكود المتصل.

**القيمة المرجعة:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

يحصل على الفهرس الأخير لنطاق يونيكود المتصل.

**القيمة المرجعة:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد الخطوط المعرفة فعليًا للنطاق.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

يحصل على اسم الخط في الفهرس المحدد.

**المُعاملات:**
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

يزيل أول ظهور لخط احتياطي محدد من القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // إزالة Tahoma من القائمة
>  newRule.remove("Tahoma");
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط المراد إزالته من القائمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل الخط الاحتياطي في الفهرس المحدد من القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // إزالة Tahoma من القائمة
>  newRule.remove(2);
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للخط المراد إزالته. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

ينشئ ويُرجِع مصفوفة تحتوي على جميع الخطوط الاحتياطية لهذه القاعدة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //الحصول على جميع أسماء الخطوط كمصفوفة
>  String[] fontNames = newRule.toArray();
> ```

**القيمة المرجعة:**
java.lang.String[] - مصفوفة من سلاسل النصوص
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

ينشئ ويُرجِع مصفوفة تحتوي على جميع الخطوط الاحتياطية من النطاق المحدد في القائمة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // الحصول على اسمي الخط الأخيرين كمصفوفة
>  String[] fontNames = newRule.toArray(2,2);
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| startIndex | int | فهرس أول خط ليُضاف. |
| count | int | عدد الخطوط المراد إضافتها. |

**القيمة المرجعة:**
java.lang.String[] - مصفوفة من سلاسل النصوص
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

يعطي فهرس القاعدة المحددة في المجموعة.

--------------------

> ```
> // إنشاء قاعدة تحتوي على قائمة من الخطوط.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //الحصول على فهرس Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**المُعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontName | java.lang.String | اسم الخط للبحث عنه. |

**القيمة المرجعة:**
int - فهرس الخط أو -1 إذا لم يُعثر على الخط في القائمة.