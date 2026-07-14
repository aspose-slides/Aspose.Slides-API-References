---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /fa/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

نمایانگر اندازه و جهت اسلاید است.
## Methods

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | اندازه‌های اسلاید را بر حسب نقطه دریافت می‌کند. |
| [getType()](#getType--) | نوع اندازه اسلاید را دریافت می‌کند. |
| [getOrientation()](#getOrientation--) | جهت اسلاید را دریافت یا تنظیم می‌کند. |
| [setOrientation(int value)](#setOrientation-int-) | جهت اسلاید را دریافت یا تنظیم می‌کند. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوا را مقیاس‌بندی می‌نماید. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | ابعاد اسلاید را به صورت صریح تنظیم می‌کند و محتوا را مقیاس‌بندی می‌نماید. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


اندازه‌های اسلاید را بر حسب نقطه دریافت می‌کند.

--------------------

انتساب یک مقدار جدید ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی کرده و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌کند.

**بازگشت:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```


نوع اندازه اسلاید را دریافت می‌کند.

--------------------

هر مقداری به جز [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ویژگی \#getSize.getSize را بر اساس ابعاد پیش‌ تعریف‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) جاری را حفظ می‌کند.

**بازگشت:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```


جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار عرض و ارتفاع اسلاید را جابجا می‌کند.

**بازگشت:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```


جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار عرض و ارتفاع اسلاید را جابجا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```


اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوا را مقیاس‌بندی می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | اندازه پیش‌تعریف‌شده اسلاید برای اعمال. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

هر مقداری به جز [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ویژگی \#getSize.getSize را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را حفظ می‌نماید. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```


ابعاد اسلاید را به صورت صریح تنظیم می‌کند و محتوا را مقیاس‌بندی می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض جدید اسلاید، بر حسب نقطه. |
| height | float | ارتفاع جدید اسلاید، بر حسب نقطه. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

این ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و {\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید. |