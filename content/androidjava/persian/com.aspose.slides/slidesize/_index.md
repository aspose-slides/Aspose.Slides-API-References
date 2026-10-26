---
title: SlideSize
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر اندازه و جهت اسلاید است.
type: docs
url: /fa/com.aspose.slides/slidesize/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

اندازه و جهت اسلاید را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getSize()](#getSize--) | ابعاد اسلاید را به واحد نقطه برمی‌گرداند. |
| [getType()](#getType--) | نوع اندازه اسلاید را برمی‌گرداند. |
| [getOrientation()](#getOrientation--) | جهت اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setOrientation(int value)](#setOrientation-int-) | جهت اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوای موجود را مقیاس می‌زند. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | ابعاد اسلاید را به‌صورت صریح تنظیم می‌کند و محتوای موجود را مقیاس می‌زند. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

ابعاد اسلاید را به واحد نقطه برمی‌گرداند.

--------------------

تخصیص مقدار جدید، ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید.

**بازگرداندن:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

نوع اندازه اسلاید را برمی‌گرداند.

--------------------

تخصیص هر مقدار غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس ابعاد پیش‌تعریف‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) فعلی حفظ می‌شود.

**بازگرداندن:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

جهت اسلاید را برمی‌گرداند یا تنظیم می‌کند.

--------------------

تغییر این مقدار، عرض و ارتفاع اسلاید را جابجا می‌کند.

**بازگرداندن:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

جهت اسلاید را برمی‌گرداند یا تنظیم می‌کند.

--------------------

تغییر این مقدار، عرض و ارتفاع اسلاید را جابجا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتوای موجود را مقیاس می‌زند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | اندازهٔ پیش‌تعریف‌شدهٔ اسلاید که باید اعمال شود. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

تخصیص هر مقدار غیر از [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)، \#getSize.getSize را بر اساس نوع انتخاب‌شده تنظیم می‌کند، در حالی که \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) حفظ می‌شود. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

ابعاد اسلاید را به‌صورت صریح تنظیم می‌کند و محتوای موجود را مقیاس می‌زند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | float | عرض جدید اسلاید، به واحد نقطه. |
| height | float | ارتفاع جدید اسلاید، به واحد نقطه. |
| scaleType | int | حالت مقیاس‌بندی محتوا برای استفاده. |

--------------------

این عملیات ویژگی \#getType.getType را به [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) بازنشانی می‌کند و \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) را تنظیم می‌نماید.