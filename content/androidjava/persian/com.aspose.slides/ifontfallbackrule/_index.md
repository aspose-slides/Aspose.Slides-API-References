---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: نمایش قاعده‌ی جایگزینی قلم
type: docs
url: /fa/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

نمایش قاعده‌ی جایگزینی قلم
## متدها

| متد | توضیح |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | یک قلم (یا چند قلم) جدید به فهرست قلم‌های FallBack اضافه می‌کند. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | قلم‌های جدیدی را به فهرست قلم‌های FallBack اضافه می‌کند. |
| [getRangeStartIndex()](#getRangeStartIndex--) | اولین شاخص بازهٔ یونیکد پیوسته را برمی‌گرداند. |
| [getRangeEndIndex()](#getRangeEndIndex--) | آخرین شاخص بازهٔ یونیکد پیوسته را برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد قلم‌های واقعاً تعریف‌شده برای بازه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نام قلم در شاخص مشخص‌شده را برمی‌گرداند. |
| [clear()](#clear--) | تمام قلم‌ها را از فهرست حذف می‌کند. |
| [remove(String fontName)](#remove-java.lang.String-) | اولین رخداد قلم FallBack خاص را از فهرست حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | قلم FallBack در شاخص مشخص‌شده در فهرست را حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام قلم‌های FallBack برای این قاعده ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام قلم‌های FallBack از بازهٔ مشخص‌شده در فهرست ایجاد و برمی‌گرداند. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | شاخص قاعدهٔ مشخص‌شده در مجموعه را برمی‌گرداند. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

یک قلم (یا چند قلم) جدید به فهرست قلم‌های FallBack اضافه می‌کند.

--------------------

> ```
> //ایجاد یک نمونه جدید از FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //یک قلم دوم به قاعده اضافه می‌کند 
>  newRule.addFallBackFonts("MS Gothic");
>  //دو قلم سوم و چهارم به قاعده اضافه می‌کند 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

قلم‌های جدیدی را به فهرست قلم‌های FallBack اضافه می‌کند.

--------------------

> ```
> //ایجاد نمونه جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //افزودن سه قلم دیگر به قاعده 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNames | java.lang.String[] | نام یا نام‌های قلم (جدا شده با کاما) برای FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

اولین شاخص بازهٔ یونیکد پیوسته را برمی‌گرداند.

**بازگشت:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

آخرین شاخص بازهٔ یونیکد پیوسته را برمی‌گرداند.

**بازگشت:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد قلم‌های واقعاً تعریف‌شده برای بازه را برمی‌گرداند.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

نام قلم در شاخص مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

تمام قلم‌ها را از فهرست حذف می‌کند.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

اولین رخداد قلم FallBack خاص را از فهرست حذف می‌کند.

--------------------

> ```
> // ایجاد قاعده‌ای حاوی فهرست قلم‌ها.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //حذف Tahoma از فهرست
>  newRule.remove("Tahoma");
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام قلم برای حذف از فهرست. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

قلم FallBack در شاخص مشخص‌شده در فهرست را حذف می‌کند.

--------------------

> ```
> // ایجاد قاعده‌ای که حاوی فهرست قلم‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // حذف Tahoma از فهرست
>  newRule.remove(2);
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفرپایه قلم برای حذف. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

یک آرایه شامل تمام قلم‌های FallBack برای این قاعده ایجاد و برمی‌گرداند.

--------------------

> ```
> // ایجاد قاعده‌ای که حاوی فهرست قلم‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت تمام نام‌های قلم‌ها به صورت آرایه
>  String[] fontNames = newRule.toArray();
```

**بازگشت:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام قلم‌های FallBack از بازهٔ مشخص‌شده در فهرست ایجاد و برمی‌گرداند.

--------------------

> ```
> // ایجاد قاعده‌ای که حاوی فهرست قلم‌ها است.
>  //دریافت دو نام قلم آخر به صورت آرایه
>  String[] fontNames = newRule.toArray(2,2);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | شاخص اولین قلم برای افزودن. |
| count | int | تعداد قلم‌های برای افزودن. |

**بازگشت:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

شاخص قاعدهٔ مشخص‌شده در مجموعه را برمی‌گرداند.

--------------------

> ```
> // یک قاعده ایجاد می‌کند که حاوی فهرست قلم‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت شاخص Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام قلم برای جستجو. |

**بازگشت:**
int - شاخص یک قلم یا -1 اگر قلم در فهرست یافت نشود.