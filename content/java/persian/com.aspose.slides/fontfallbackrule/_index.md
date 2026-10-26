---
title: FontFallBackRule
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهندهٔ قانون جایگزینی قلم
type: docs
url: /fa/com.aspose.slides/fontfallbackrule/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

قانون جایگزینی قلم
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | یک نمونه جدید ایجاد می‌کند. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | یک نمونه جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | یک قلم(ها) جدید به لیست قلم‌های FallBack اضافه می‌کند. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | یک قلم(ها) جدید به لیست قلم‌های FallBack اضافه می‌کند. |
| [getRangeStartIndex()](#getRangeStartIndex--) | اولین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | اولین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند. |
| [getRangeEndIndex()](#getRangeEndIndex--) | آخرین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | آخرین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد قلم‌های واقعاً تعریف‌شده برای محدوده را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | نام قلم در شاخص مشخص‌شده را دریافت می‌کند. |
| [clear()](#clear--) | تمام قلم‌ها را از لیست حذف می‌کند. |
| [remove(String fontName)](#remove-java.lang.String-) | اولین رخداد قلم FallBack خاص را از لیست حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | قلم FallBack در شاخص مشخص‌شده در لیست را حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه حاوی تمام قلم‌های FallBack برای این قانون ایجاد و بر می‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه حاوی تمام قلم‌های FallBack از محدودهٔ مشخص‌شده در لیست ایجاد و بر می‌گرداند. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | یک شاخص از قانون مشخص‌شده در مجموعه را بر می‌گرداند. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


یک نمونه جدید ایجاد می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FantFallBackRule با یک قلم.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // ایجاد یک نمونه جدید از FantFallBackRule با چند قلم.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | long | شاخص شروع محدوده یونیکد |
| endIndex | long | شاخص پایان محدوده یونیکد |
| fontNames | java.lang.String | نام یا نام‌های قلم (جداساز با کاما) برای FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


یک نمونه جدید ایجاد می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FantFallBackRule با دو قلم
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // ایجاد یک نمونه جدید از FantFallBackRule با چند قلم.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | long | شاخص شروع محدوده یونیکد |
| endIndex | long | شاخص پایان محدوده یونیکد |
| fontNames | java.lang.String[] | نام یا نام‌های قلم (جداساز با کاما) برای FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


یک قلم(ها) جدید به لیست قلم‌های FallBack اضافه می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //افزودن قلم دوم به قانون 
>  newRule.addFallBackFonts("MS Gothic");
>  //افزودن قلم‌های سوم و چهارم به قانون 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام یا نام‌های قلم (جداساز با کاما) برای FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


یک قلم جدید به لیست قلم‌های FallBack اضافه می‌کند.

--------------------

> ```
> // ایجاد نمونهٔ جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // افزودن سه قلم دیگر به قانون 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNames | java.lang.String[] | نام یا نام‌های قلم (جداساز با کاما) برای FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


اولین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند.

**بازگشت:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


اولین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


آخرین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند.

**بازگشت:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


آخرین شاخص محدوده‌ی یونیکد پیوسته را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


تعداد قلم‌های واقعاً تعریف‌شده برای محدوده را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


نام قلم در شاخص مشخص‌شده را دریافت می‌کند. فقط-خواندنی [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


تمام قلم‌ها را از لیست حذف می‌کند.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


اولین رخداد قلم FallBack خاص را از لیست حذف می‌کند.

--------------------

> ```
> // یک قانون شامل فهرست قلم‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // حذف Tahoma از فهرست.
>  newRule.remove("Tahoma");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام قلمی که باید از لیست حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


قلم FallBack در شاخص مشخص‌شده در لیست را حذف می‌کند.

--------------------

> ```
> // یک قانون شامل فهرست قلم‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //حذف Tahoma از فهرست.
>  newRule.remove(2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-مبنا برای قلمی که باید حذف شود. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


یک آرایه حاوی تمام قلم‌های FallBack برای این قانون ایجاد و بر می‌گرداند.

--------------------

> ```
> // یک قانون شامل فهرست قلم‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت تمام نام‌های قلم به صورت آرایه.
>  String[] fontNames = newRule.toArray();
```

**بازگشت:**
java.lang.String[] - آرایه‌ای از رشته‌ها
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


یک آرایه حاوی تمام قلم‌های FallBack از محدودهٔ مشخص‌شده در لیست ایجاد و بر می‌گرداند.

```
 // یک قانون شامل فهرست قلم‌ها ایجاد می‌کند.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // دریافت دو نام قلم آخر به صورت آرایه.
 String[] fontNames = newRule.toArray(2, 2);
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | شاخص اولین قلم برای افزودن. |
| count | int | تعداد قلم‌های برای افزودن. |

**بازگشت:**
java.lang.String[] - آرایه‌ای از رشته‌ها
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


یک شاخص از قانون مشخص‌شده در مجموعه را بر می‌گرداند.

--------------------

> ```
> // یک قانون شامل فهرست قلم‌ها ایجاد می‌کند.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت شاخص Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام قلم برای جستجو. |

**بازگشت:**
int - شاخص قلم یا -1 اگر قلم در لیست یافت نشود.