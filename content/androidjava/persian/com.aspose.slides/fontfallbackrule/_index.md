---
title: FontFallBackRule
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: قانون جایگزینی فونت را نمایندگی می‌کند
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

قانون جایگزینی فونت را نمایندگی می‌کند
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | یک نمونه جدید ایجاد می‌کند. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | یک نمونه جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | یک فونت(ها) جدید را به لیست فونت‌های FallBack اضافه می‌کند. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | یک فونت(ها) جدید را به لیست فونت‌های FallBack اضافه می‌کند. |
| [getRangeStartIndex()](#getRangeStartIndex--) | اولین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | اولین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند. |
| [getRangeEndIndex()](#getRangeEndIndex--) | آخرین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | آخرین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد فونت‌های واقعاً تعریف‌شده برای بازه را بر می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نام فونت در اندیس مشخص‌شده را بر می‌گرداند. |
| [clear()](#clear--) | تمام فونت‌ها را از لیست حذف می‌کند. |
| [remove(String fontName)](#remove-java.lang.String-) | اولین رخداد یک فونت FallBack خاص را از لیست حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | فونت FallBack را در اندیس مشخص‌شده از لیست حذف می‌کند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد و بر می‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام فونت‌های FallBack از بازهٔ مشخص‌شده در لیست ایجاد و بر می‌گرداند. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | ایندکس قانون مشخص‌شده در مجموعه را بر می‌گرداند. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

یک نمونه جدید ایجاد می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FantFallBackRule با یک فونت.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // ایجاد یک نمونه جدید از FantFallBackRule با چند فونت.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | long | شاخص شروع محدودهٔ یونی‌کد |
| endIndex | long | شاخص پایان محدودهٔ یونی‌کد |
| fontNames | java.lang.String | نام یا نام‌های فونت (جداشده با کاما) برای FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

یک نمونه جدید ایجاد می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FantFallBackRule با دو فونت
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // ایجاد یک نمونه جدید از FantFallBackRule با چند فونت.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | long | شاخص شروع محدودهٔ یونی‌کد |
| endIndex | long | شاخص پایان محدودهٔ یونی‌کد |
| fontNames | java.lang.String[] | نام یا نام‌های فونت (جداشده با کاما) برای FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

یک فونت(ها) جدید را به لیست فونت‌های FallBack اضافه می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // افزودن یک فونت دوم به قانون 
>  newRule.addFallBackFonts("MS Gothic");
>  // افزودن فونت‌های سوم و چهارم به قانون 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام یا نام‌های فونت (جداشده با کاما) برای FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

یک فونت جدید را به لیست فونت‌های FallBack اضافه می‌کند.

--------------------

> ```
> // ایجاد یک نمونه جدید از FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // افزودن سه فونت دیگر به قانون 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNames | java.lang.String[] | نام یا نام‌های فونت (جداشده با کاما) برای FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

اولین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند.

**بازگشت:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

اولین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

آخرین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند.

**بازگشت:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

آخرین شاخص محدودهٔ یونی‌کد پیوسته را دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد فونت‌های واقعاً تعریف‌شده برای بازه را بر می‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

نام فونت در اندیس مشخص‌شده را بر می‌گرداند. فقط-خواندنی [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

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

تمام فونت‌ها را از لیست حذف می‌کند.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

اولین رخداد یک فونت FallBack خاص را از لیست حذف می‌کند.

--------------------

> ```
> // ایجاد یک قانون که شامل لیستی از فونت‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // حذف Tahoma از لیست.
>  newRule.remove("Tahoma");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام فونت برای حذف از لیست. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

فونت FallBack را در اندیس مشخص‌شده از لیست حذف می‌کند.

--------------------

> ```
> // ایجاد یک قانون که شامل لیستی از فونت‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //حذف Tahoma از لیست.
>  newRule.remove(2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر‌پایه‌ی فونت برای حذف. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

یک آرایه شامل تمام فونت‌های FallBack برای این قانون ایجاد و بر می‌گرداند.

--------------------

> ```
> // ایجاد یک قانون که شامل لیستی از فونت‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت تمام نام‌های فونت به صورت آرایه.
>  String[] fontNames = newRule.toArray();
> ```

**بازگشت:**
java.lang.String[] - آرایه‌ای از رشته‌ها
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام فونت‌های FallBack از بازهٔ مشخص‌شده در لیست ایجاد و بر می‌گرداند.

```
// ایجاد یک قانون که شامل لیستی از فونت‌ها است.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // دریافت دو نام آخر فونت به صورت آرایه.
 String[] fontNames = newRule.toArray(2, 2);
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | اندیس اولین فونت برای افزودن. |
| count | int | تعداد فونت‌های برای افزودن. |

**بازگشت:**
java.lang.String[] - آرایه‌ای از رشته‌ها
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

ایندکس قانون مشخص‌شده در مجموعه را بر می‌گرداند.

--------------------

> ```
> // ایجاد یک قانون که شامل لیستی از فونت‌ها است.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // دریافت ایندکس Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontName | java.lang.String | نام فونت برای جستجو. |

**بازگشت:**
int - ایندکس یک فونت یا -1 اگر فونت در لیست یافت نشود.