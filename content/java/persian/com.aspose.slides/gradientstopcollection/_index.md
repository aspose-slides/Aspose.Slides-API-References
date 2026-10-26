---
title: GradientStopCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: یک مجموعه از نقاط گرادیان را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/gradientstopcollection/
---
**ارث-بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

نمایش یک مجموعه از نقاط گرادیان.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه گرادیان را بر اساس اندیس برمی‌گرداند. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نقطه گرادیان را در اندیس مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام نقاط گرادیان را از یک مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن در برابر ریسه‌ها) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازمی‌گرداند:**
long

### size() {#size--}
```
public final int size()
```

تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. فقط‌خواندنی int .

**بازمی‌گرداند:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

نقطه گرادیان را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```

نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت نقطه گرادیان جدید. |
| color | java.awt.Color | رنگ نقطه گرادیان جدید. |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop) - شاخص نقطه گرادیان جدید در مجموعه.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت نقطه گرادیان جدید. |
| presetColor | int | رنگ پیش‌فرض نقطه گرادیان جدید. |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop) - شاخص نقطه گرادیان جدید در مجموعه.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت نقطه گرادیان جدید. |
| schemeColor | int | رنگ طرح نقطه گرادیان جدید. |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop) - شاخص نقطه گرادیان جدید در مجموعه.

### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```

نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که نقطه گرادیان جدید در آن درج می‌شود. |
| position | float | موقعیت نقطه گرادیان جدید. |
| color | java.awt.Color | رنگ نقطه گرادیان جدید. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که نقطه گرادیان جدید در آن درج می‌شود. |
| position | float | موقعیت نقطه گرادیان جدید. |
| presetColor | int | رنگ پیش‌فرض نقطه گرادیان جدید. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

نقطه گرادیان جدید را ایجاد کرده و در اندیس مشخص شده در مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که نقطه گرادیان جدید در آن درج می‌شود. |
| position | float | موقعیت نقطه گرادیان جدید. |
| schemeColor | int | رنگ طرح نقطه گرادیان جدید. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

نقطه گرادیان را در اندیس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس نقطه گرادیان که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام نقاط گرادیان را از یک مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (امن در برابر ریسه‌ها) است. فقط‌خواندنی boolean .

**بازمی‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object.

**بازمی‌گرداند:**
java.lang.Object