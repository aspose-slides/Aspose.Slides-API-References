---
title: Tab
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک تب برای متن.
type: docs
url: /fa/com.aspose.slides/tab/
---
**وارثی:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**همهٔ رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ITab](../../com.aspose.slides/itab)  
```
public final class Tab extends PVIObject implements ITab
```

نمایانگر یک جدولی برای متن است.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | یک تب جدید ایجاد می‌کند |

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | موقعیت یک تب را برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(double value)](#setPosition-double-) | موقعیت یک تب را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | سبک تراز یک تب را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlignment(int value)](#setAlignment-int-) | سبک تراز یک تب را برمی‌گرداند یا تنظیم می‌کند. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | نمونهٔ فعلی را با شیء دیگری از همان نوع مقایسه می‌کند. |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

یک تب جدید ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | double | موقعیت تب. |
| align | int | تراز. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازگشت:**
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

موقعیت یک تب را برمی‌گرداند یا تنظیم می‌کند. اختصاص این ویژگی می‌تواند شاخص تب را در مجموعه تغییر دهد و Enumerator را نامعتبر کند. خواندنی/قابل نوشتن double.

**بازگشت:**
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

موقعیت یک تب را برمی‌گرداند یا تنظیم می‌کند. اختصاص این ویژگی می‌تواند شاخص تب را در مجموعه تغییر دهد و Enumerator را نامعتبر کند. خواندنی/قابل نوشتن double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

سبک تراز یک تب را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TabAlignment](../../com.aspose.slides/tabalignment).

**بازگشت:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

سبک تراز یک تب را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [TabAlignment](../../com.aspose.slides/tabalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

نمونهٔ فعلی را با شیء دیگری از همان نوع مقایسه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیئی برای مقایسه با این نمونه. |

**بازگشت:**
int - یک عدد صحیح ۳۲ بیتی که ترتیب نسبی مقایسه‌کنندگان را نشان می‌دهد. مقدار بازگشتی معانی زیر را دارد:

 *  < 0 - این نمونه کمتر از obj است.
 *  = 0 - این نمونه برابر با obj است.
 *  > 0 - این نمونه بزرگتر از obj است.