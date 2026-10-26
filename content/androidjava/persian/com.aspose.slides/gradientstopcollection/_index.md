---
title: GradientStopCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک مجموعه از نقاط گرادیان را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/gradientstopcollection/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

یک مجموعه از نقاط گرادیان را نشان می‌دهد.
## متدها

| متد | توصیف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | نقطه گرادیان را بر اساس شاخص برمی‌گرداند. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | نقطه گرادیان را در شاخص مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام نقاط گرادیان را از یک مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (امنیت رشته‌ای). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازمی‌گرداند:**
long

### size() {#size--}
```
public final int size()
```

تعداد نقاط گرادیان در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**بازمی‌گرداند:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

نقطه گرادیان را بر اساس شاخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

نقطه گرادیان جدید را ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| color | java.lang.Integer | رنگ نقطه گرادیان جدید. |

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
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| presetColor | int | رنگ نقطه گرادیان جدید. |

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
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| schemeColor | int | رنگ نقطه گرادیان جدید. |

**بازمی‌گرداند:**
[IGradientStop](../../com.aspose.slides/igradientstop) - شاخص نقطه گرادیان جدید در مجموعه.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه که در آن نقطه گرادیان جدید وارد می‌شود. |
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| color | java.lang.Integer | رنگ نقطه گرادیان جدید. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه که در آن نقطه گرادیان جدید وارد می‌شود. |
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| presetColor | int | رنگ نقطه گرادیان جدید. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

نقطه گرادیان جدید را ایجاد کرده و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه که در آن نقطه گرادیان جدید وارد می‌شود. |
| position | float | محل قرارگیری نقطه گرادیان جدید. |
| schemeColor | int | رنگ نقطه گرادیان جدید. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

نقطه گرادیان را در شاخص مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص نقطه گرادیان که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام نقاط گرادیان را از یک مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | شاخص شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (امنیت رشته‌ای). فقط خواندنی boolean.

**بازمی‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**بازمی‌گرداند:**
java.lang.Object