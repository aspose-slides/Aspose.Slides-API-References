---
title: SlideSize
second_title: مرجع API Aspose.Slides برای جاوا
description: اندازه و جهتٔ یک اسلاید را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/slidesize/
---
**وراثت:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)  
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

نمایانگر اندازه و جهت اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getSize()](#getSize--) | ابعاد اسلاید را بر حسب پوینت دریافت می‌کند. |
| [getType()](#getType--) | نوع اندازه اسلاید را دریافت می‌کند. |
| [getOrientation()](#getOrientation--) | جهت اسلاید را دریافت یا تنظیم می‌کند. |
| [setOrientation(int value)](#setOrientation-int-) | جهت اسلاید را دریافت یا تنظیم می‌کند. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتویات موجود را مقیاس می‌دهد. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | ابعاد اسلاید را به صورت صریح تنظیم می‌کند و محتویات موجود را مقیاس می‌دهد. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

ابعاد اسلاید را بر حسب پوینت دریافت می‌کند.

--------------------

تخصیص مقدار جدید ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید.

**بازده:**  
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

نوع اندازه اسلاید را دریافت می‌کند.

--------------------

تخصیص هر مقدار غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس ابعاد پیش‌تعریف‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) جاری حفظ می‌شود.

**بازده:**  
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار عرض و ارتفاع اسلاید را معاوضه می‌کند.

**بازده:**  
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

جهت اسلاید را دریافت یا تنظیم می‌کند.

--------------------

تغییر این مقدار عرض و ارتفاع اسلاید را معاوضه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتویات موجود را مقیاس می‌دهد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | اندازه اسلاید پیش‌تعریف‌شده‌ای که باید اعمال شود. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

تخصیص هر مقدار غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) حفظ می‌شود. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

ابعاد اسلاید را به صورت صریح تنظیم می‌کند و محتویات موجود را مقیاس می‌دهد.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض جدید اسلاید، بر حسب پوینت. |
| height | float | ارتفاع جدید اسلاید، بر حسب پوینت. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

این کار ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید. |