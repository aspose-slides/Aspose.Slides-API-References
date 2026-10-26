---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides برای Java مرجع API
description: نمایش یک مجموعه از اشیاء GradientStopData.
type: docs
url: /fa/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

نمایش یک مجموعه از اشیاء GradientStopData.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد توقف‌های گرادیان در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | توقف گرادیان را بر اساس اندیس برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که بر مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه‌ی مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندرشته). |
| [getSyncRoot()](#getSyncRoot--) | یک ریشه‌ی همگام‌سازی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد توقف‌های گرادیان در یک مجموعه را برمی‌گرداند. عدد صحیح فقط-خواندنی.

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

توقف گرادیان را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

یک شمارنده که بر مجموعه تکرار می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - یک IGenericEnumerator که می‌تواند برای تکرار مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه‌ی مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (ایمن برای چندرشته). بولی فقط-خواندنی.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشه‌ی همگام‌سازی را برمی‌گرداند. شیء فقط-خواندنی.

**بازگشت:**
java.lang.Object