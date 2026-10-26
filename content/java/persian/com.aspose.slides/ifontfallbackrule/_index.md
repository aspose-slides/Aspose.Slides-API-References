---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: نمایانگر قانون fallback فونت
type: docs
url: /fa/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

نمایانگر قانون fallback فونت
## متدها

| متد | توضیح |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | یک یا چند فونت جدید را به لیست فونت‌های FallBack اضافه می‌کند. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | یک یا چند فونت جدید را به لیست فونت‌های FallBack اضافه می‌کند. |
| [getRangeStartIndex()](#getRangeStartIndex--) | اولین ایندکس بازه یونیکد پیوسته را دریافت می‌کند. |
| [getRangeEndIndex()](#getRangeEndIndex--) | آخرین ایندکس بازه یونیکد پیوسته را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد فونت‌هایی که واقعاً برای بازه تعریف شده‌اند را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | نام فونت در ایندکس مشخص شده را دریافت می‌کند. |
| [clear()](#clear--) | تمام فونت‌ها را از لیست حذف می‌کند. |
| [remove(String fontName)](#remove-java.lang.String-) | اولین رخداد یک فونت FallBack خاص را از لیست حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | فونت FallBack موجود در ایندکس مشخص شده لیست را حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام فونت‌های FallBack از بازه مشخص شده در لیست ایجاد و برمی‌گرداند. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | ایندکس قانون مشخص شده در مجموعه را برمی‌گرداند. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

یک یا چند فونت جدید را به لیست فونت‌های FallBack اضافه می‌کند.

--------------------

> ```
> //ایجاد یک نمونه جدید از FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //یک فونت دوم به قانون اضافه می‌کند
>  newRule.addFallBackFonts("MS Gothic");
>  //فونت‌های سوم و چهارم را به قانون اضافه می‌کند
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام یا نام‌های فونت (جدا شده توسط کاما) برای FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

یک یا چند فونت جدید را به لیست فونت‌های FallBack اضافه می‌کند.

--------------------

> ```
> //ایجاد یک نمونه جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //اضافه کردن سه فونت دیگر به قانون 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNames | java.lang.String[] | نام یا نام‌های فونت (جدا شده توسط کاما) برای FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

اولین ایندکس بازه یونیکد پیوسته را دریافت می‌کند.

**بازمی‌گرداند:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

آخرین ایندکس بازه یونیکد پیوسته را دریافت می‌کند.

**بازمی‌گرداند:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد فونت‌هایی که واقعاً برای بازه تعریف شده‌اند را دریافت می‌کند.

**بازمی‌گرداند:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

نام فونت در ایندکس مشخص شده را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

تمام فونت‌ها را از لیست حذف می‌کند.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

اولین رخداد یک فونت FallBack خاص را از لیست حذف می‌کند.

--------------------

> ```
> // یک قانون شامل فهرستی از فونت‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //حذف Tahoma از لیست
>  newRule.remove("Tahoma");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام فونت برای حذف از لیست. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

فونت FallBack موجود در ایندکس مشخص شده لیست را حذف می‌کند.

--------------------

> ```
> // یک قانون شامل فهرستی از فونت‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //حذف Tahoma از لیست
>  newRule.remove(2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفرپایه فونت برای حذف. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد و برمی‌گرداند.

--------------------

> ```
> // یک قانون شامل فهرستی از فونت‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //تمام نام‌های فونت را به صورت آرایه دریافت می‌کند
>  String[] fontNames = newRule.toArray();
> ```


**بازمی‌گرداند:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام فونت‌های FallBack از بازه مشخص شده در لیست ایجاد و برمی‌گرداند.

--------------------

> ```
> // یک قانون شامل فهرستی از فونت‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // آخرین دو نام فونت را به صورت آرایه دریافت می‌کند
>  String[] fontNames = newRule.toArray(2,2);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | اندیس اولین فونت برای افزودن. |
| count | int | تعداد فونت‌های برای افزودن. |

**بازمی‌گرداند:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

ایندکس قانون مشخص شده در مجموعه را برمی‌گرداند.

--------------------

> ```
> // یک قانون شامل فهرستی از فونت‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت ایندکس Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام فونت برای جستجو. |

**بازمی‌گرداند:**
int - ایندکس فونت یا -1 اگر فونت در لیست یافت نشد.