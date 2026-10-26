---
title: CellCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده یک مجموعه از سلول‌ها است.
type: docs
url: /fa/com.aspose.slides/cellcollection/
---
**وارثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

یک مجموعه از سلول‌ها را نمایش می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | تعداد سلول‌ها در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | یک سلول را با توجه به موقعیت آن برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای تمام مجموعه را برمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد CellCollection را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد CellCollection را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان است (امنیت‌پذیر). |
| [getSyncRoot()](#getSyncRoot--) | ریشه همزمانی را برمی‌گرداند. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


تعداد سلول‌ها در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


یک سلول را با توجه به موقعیت آن برمی‌گرداند. فقط خواندنی [Cell](../../com.aspose.slides/cell).

--------------------

یک شیء Cell می‌تواند برای چندین شاخص برگردانده شود در صورتی که سلول ادغام شده باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


یک iterator جاوا برای تمام مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


اسلاید والد CellCollection را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


ارائه والد CellCollection را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان است (امنیت‌پذیر). فقط خواندنی boolean.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشه همزمانی را برمی‌گرداند. فقط خواندنی Object.

**بازگشت:**
java.lang.Object