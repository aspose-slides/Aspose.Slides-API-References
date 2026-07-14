---
title: Size
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: کلاسی برای توصیف ابعاد عرض و ارتفاع در یک واحد دلخواه.
type: docs
url: /fa/com.aspose.slides.android/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

کلاسی برای توصیف ابعاد عرض و ارتفاع در یک واحد دلخواه.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | ایجاد یک نمونه جدید از Size. |
## متدها

| متد | توضیح |
| --- | --- |
| [getWidth()](#getWidth--) | دریافت عرض اندازه. |
| [getHeight()](#getHeight--) | دریافت ارتفاع اندازه. |
| [equals(Object obj)](#equals-java.lang.Object-) | بررسی می‌کند که آیا این اندازه با اندازه دیگری برابر است یا نه. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | بازگرداندن اندازه به صورت رشته‌ای با فرمت "WxH" |
### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

ایجاد یک نمونه جدید از Size.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | int | عرض اندازه |
| height | int | ارتفاع اندازه |

### getWidth() {#getWidth--}
```
public int getWidth()
```

دریافت عرض اندازه.

**بازگشت:**
int - width
### getHeight() {#getHeight--}
```
public int getHeight()
```

دریافت ارتفاع اندازه.

**بازگشت:**
int - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

بررسی می‌کند که آیا این اندازه با اندازه دیگری برابر است یا نه.

دو اندازه تنها در صورتی برابر هستند که هر دو عرض و ارتفاع آن‌ها برابر باشد.

یک شیء از نوع size هیچ‌وقت با هیچ‌نوع دیگری برابر نیست.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object |  |

**بازگشت:**
boolean - true اگر اشیاء برابر بودند، false در غیر این صورت
### hashCode() {#hashCode--}
```
public int hashCode()
```

**بازگشت:**
int
### toString() {#toString--}
```
public String toString()
```

بازگرداندن اندازه به صورت رشته‌ای با فرمت "WxH"

**بازگشت:**
java.lang.String - نمایه رشته‌ای از اندازه