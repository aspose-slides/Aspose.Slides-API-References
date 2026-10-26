---
title: LayoutSlideCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس پایه‌ای برای مجموعه‌ای از اسلایدهای چیدمان را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/layoutslidecollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

نمایانگر یک کلاس پایه برای مجموعه‌ای از اسلایدهای چیدمان است.
## متدها

| متد | توضیحات |
| --- | --- |
| [size()](#size--) | تعداد اسلایدهای چیدمان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | اسلاید چیدمان را بر اساس شاخص برمی‌گرداند. |
| [getByType(byte type)](#getByType-byte-) | اولین اسلاید چیدمان از نوع مشخص شده را برمی‌گرداند. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | اسلاید چیدمان را از مجموعه حذف می‌کند. |
| [removeUnused()](#removeUnused--) | اسلایدهای چیدمان استفاده نشده را حذف می‌کند (اسلایدهای چیدمانی که مقدار HasDependingSlides آن‌ها نادرست است). |
| [iterator()](#iterator--) | یک شمارنده (enumerator) که در تمام مجموعه مرور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن در برابر ریسه‌ها). |
| [getSyncRoot()](#getSyncRoot--) | ریشه‌ی همگام‌سازی را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

تعداد اسلایدهای چیدمان در یک مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

اسلاید چیدمان را بر اساس شاخص برمی‌گرداند. فقط‌خواندنی [LayoutSlide](../../com.aspose.slides/layoutslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

اولین اسلاید چیدمان از نوع مشخص شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | byte | نوعی از اسلاید چیدمان برای یافتن. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) با نوع مشخص یا null اگر هیچ چیدمانی یافت نشد.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

اسلاید چیدمان را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید چیدمان برای حذف از مجموعه.

--------------------

1) برای جلوگیری از پرتاب PptxEditException، قبل از آن ویژگی HasDependingSlides چیدمان را بررسی کنید. 2) می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) نیز برای ساده‌سازی کد استفاده کنید. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

اسلایدهای چیدمان استفاده نشده را حذف می‌کند (اسلایدهای چیدمانی که مقدار HasDependingSlides آن‌ها نادرست است).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

یک شمارنده (enumerator) که در تمام مجموعه مرور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - یک IGenericEnumerator که می‌تواند برای مرور کل مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه هدف کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | شاخص شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن در برابر ریسه‌ها). فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشه‌ی همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**بازگشت:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject