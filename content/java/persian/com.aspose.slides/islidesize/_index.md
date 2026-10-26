---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /fa/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

اندازه و جهت اسلاید را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getSize()](#getSize--) | Gets the slide dimensions in points. |
| [getType()](#getType--) | Gets the slide size type. |
| [getOrientation()](#getOrientation--) | Gets or sets the slide orientation. |
| [setOrientation(int value)](#setOrientation-int-) | Gets or sets the slide orientation. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Sets the slide size by type and scales existing content. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Sets the slide dimensions explicitly and scales existing content. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

ابعاد اسلاید را بر حسب نقاط دریافت می‌کند.

--------------------

تخصیص مقدار جدید، ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید.

**بازگشت:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

نوع اندازه اسلاید را دریافت می‌کند.

--------------------

تخصیص هر مقداری غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس ابعاد از پیش تعریف‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) فعلی را حفظ می‌نماید.

**بازگشت:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار، عرض و ارتفاع اسلاید را معاوضه می‌کند.

**بازگشت:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار، عرض و ارتفاع اسلاید را معاوضه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | اندازهٔ پیش‌تعریف‌شدهٔ اسلاید که باید اعمال شود. |
| scaleType | int | حالت مقیاس‌بندی محتوا که باید استفاده شود. |

--------------------

تخصیص هر مقداری غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را حفظ می‌کند.

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض جدید اسلاید، بر حسب نقاط. |
| height | float | ارتفاع جدید اسلاید، بر حسب نقاط. |
| scaleType | int | حالت مقیاس‌بندی محتوا که باید استفاده شود. |

--------------------

این، ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید.