---
title: LayoutSlideCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک کلاس پایه برای مجموعه‌ای از اسلایدهای چیدمان است.
type: docs
url: /fa/com.aspose.slides/layoutslidecollection/
---
**ارث‌بری:**  
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

نمایانگر یک کلاس پایه برای مجموعه‌ای از اسلایدهای چیدمان است.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد اسلایدهای چیدمان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | اسلاید چیدمان را بر اساس ایندکس برمی‌گرداند. |
| [getByType(byte type)](#getByType-byte-) | اولین اسلاید چیدمان از نوع مشخص‌شده را برمی‌گرداند. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | یک چیدمان را از مجموعه حذف می‌کند. |
| [removeUnused()](#removeUnused--) | اسلایدهای چیدمان استفاده‌نشده (اسلایدهایی که HasDependingSlides آن‌ها false است) را حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه مرور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چندین رشته) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

تعداد اسلایدهای چیدمان در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازمی‌گرداند:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

اسلاید چیدمان را بر اساس ایندکس برمی‌گرداند. فقط خواندنی [LayoutSlide](../../com.aspose.slides/layoutslide).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

اولین اسلاید چیدمان از نوع مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | byte | یک نوع از اسلاید چیدمان برای پیدا کردن. |

**بازمی‌گرداند:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) با نوع مشخص یا null اگر هیچ چیدمانی یافت نشد.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

یک چیدمان را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید چیدمان برای حذف از مجموعه. |

--------------------
1) برای جلوگیری از پرتاب PptxEditException قبل از آن ویژگی HasDependingSlides چیدمان را بررسی کنید. 2) همچنین می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) برای ساده‌سازی کد استفاده کنید. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

اسلایدهای چیدمان استفاده‌نشده (اسلایدهایی که HasDependingSlides آن‌ها false است) را حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

یک شمارنده که از طریق مجموعه مرور می‌کند را برمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - یک IGenericEnumerator که می‌تواند برای مرور مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف. |
| index | int | ایندکس شروع در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن برای چندین رشته) است. فقط خواندنی boolean.

**بازمی‌گرداند:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازمی‌گرداند:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازمی‌گرداند:**  
com.aspose.slides.IDOMObject