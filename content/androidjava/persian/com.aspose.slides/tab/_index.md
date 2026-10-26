---
title: Tab
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک جدول‌بندی برای متن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/tab/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

یک جدول‌بندی برای متن را نشان می‌دهد.
## سازندگان

| سازنده | توضیح |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | یک Tab جدید ایجاد می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | مقدار یا موقعیت یک tab را برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(double value)](#setPosition-double-) | مقدار یا موقعیت یک tab را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlignment()](#getAlignment--) | سبک تراز یک tab را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlignment(int value)](#setAlignment-int-) | سبک تراز یک tab را برمی‌گرداند یا تنظیم می‌کند. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | نمونه فعلی را با شیء دیگری از همان نوع مقایسه می‌کند. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

یک Tab جدید ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | double | موقعیت Tab. |
| align | int | تراز. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**برمی‌گرداند:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

مقدار یا موقعیت یک tab را برمی‌گرداند یا تنظیم می‌کند. مقداردهی این ویژگی می‌تواند شاخص tab را در مجموعه تغییر دهد و Enumerator را نامعتبر کند. خواندنی/نوشتنی double.

**برمی‌گرداند:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

مقدار یا موقعیت یک tab را برمی‌گرداند یا تنظیم می‌کند. مقداردهی این ویژگی می‌تواند شاخص tab را در مجموعه تغییر دهد و Enumerator را نامعتبر کند. خواندنی/نوشتنی double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

سبک تراز یک tab را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TabAlignment](../../com.aspose.slides/tabalignment).

**برمی‌گرداند:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

سبک تراز یک tab را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [TabAlignment](../../com.aspose.slides/tabalignment).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

نمونه فعلی را با شیء دیگری از همان نوع مقایسه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیئی برای مقایسه با این نمونه. |

**برمی‌گرداند:**
int - یک عدد صحیح ۳۲ بیتی که ترتیب نسبی مقایسه‌شوندگان را نشان می‌دهد. مقدار بازگشت دارای معانی زیر است:

 * < 0 - این نمونه کمتر از obj است.
 * = 0 - این نمونه برابر با obj است.
 * > 0 - این نمونه بزرگتر از obj است.