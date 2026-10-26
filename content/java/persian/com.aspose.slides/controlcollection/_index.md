---
title: ControlCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: یک مجموعه از کنترل‌های ActiveX.
type: docs
url: /fa/com.aspose.slides/controlcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

یک مجموعه از کنترل‌های ActiveX.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد اشیاء موجود در مجموعه را برمی‌گرداند. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | یک کنترل جدید ایجاد کرده و به مجموعه اضافه می‌کند. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | یک کنترل ActiveX را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | کنترل ActiveX ذخیره‌شده در موقعیت مشخص را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام کنترل‌ها را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | کنترل موجود در موقعیت مشخص را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایهٔ مشخص کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندنخی). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```


تعداد اشیاء موجود در مجموعه را برمی‌گرداند. int فقط-خواندنی.

**بازگشت:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```


یک کنترل جدید ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| controlType | int | نوع کنترل برای اضافه کردن. |
| x | float | مختصات X برای سمت چپ قاب شکل. |
| y | float | مختصات Y برای سمت بالای قاب شکل. |
| width | float | عرض قاب شکل. |
| height | float | ارتفاع قاب شکل. |

**بازگشت:**
[IControl](../../com.aspose.slides/icontrol) - کنترل ایجاد‌شده.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```


یک کنترل ActiveX را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | کنترلی برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


کنترل ActiveX ذخیره‌شده در موقعیت مشخص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شمارهٔ کنترل برای حذف. |

### clear() {#clear--}
```
public final void clear()
```


تمام کنترل‌ها را از مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```


کنترل موجود در موقعیت مشخص را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شمارهٔ کنترل. |

**بازگشت:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```


یک شمارشگر که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```


یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


کل مجموعه را به آرایهٔ مشخص کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایهٔ هدف |
| index | int | شماره در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندنخی). boolean فقط-خواندنی.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط-خواندنی.

**بازگشت:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را برمی‌گرداند. IDOMObject فقط-خواندنی.

**بازگشت:**
com.aspose.slides.IDOMObject