---
title: CellCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهنده یک مجموعه از سلول‌ها.
type: docs
url: /fa/com.aspose.slides/cellcollection/
---
**ارث‌برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

نمایش‌دهنده یک مجموعه از سلول‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | تعداد سلول‌ها در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | یک سلول را بر اساس موقعیت آن برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد یک CellCollection را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک CellCollection را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```

تعداد سلول‌ها در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**باز می‌گرداند:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

یک سلول را بر اساس موقعیت آن برمی‌گرداند. فقط خواندنی [Cell](../../com.aspose.slides/cell).

--------------------

یک شیء Cell می‌تواند برای چند ایندکس برگردانده شود در صورتی که سلول ترکیب شده باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

یک enumerator را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

یک java iterator برای کل مجموعه را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - یک java.util.Iterator برای کل مجموعه.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک CellCollection را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک CellCollection را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. فقط خواندنی boolean.

**باز می‌گرداند:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**باز می‌گرداند:**
java.lang.Object