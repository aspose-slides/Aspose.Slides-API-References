---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک مجموعه از نقاط برای نقطه تقسیم در نمودار bar-of-pie یا pie-of-pie با تقسیم سفارشی.
type: docs
url: /fa/com.aspose.slides/piesplitcustompointcollection/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

نمایش یک مجموعه از نقاط برای نقطه تقسیم در نمودار bar-of-pie یا pie-of-pie با تقسیم سفارشی.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک نقطه داده نمودار را برای اندیس مشخص شده برمی‌گرداند. |
| [add(int dataPointIndex)](#add-int-) | نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | نقطه داده را به مجموعه اضافه می‌کند. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | آیتم را از مجموعه حذف می‌کند. |
| [remove(int dataPointIndex)](#remove-int-) | آیتم را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند. |
| [clear()](#clear--) | تمام آیتم‌ها را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک اندیس خاص Array. |
| [size()](#size--) | تعداد نقاط داده نمودار را برمی‌گرداند یا تنظیم می‌کند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا خیر. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (امن در برابر نخ) است یا خیر. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک Enumerator را برمی‌گرداند که بر مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

یک نقطه داده نمودار را برای اندیس مشخص شده برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه داده نمودار.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

نقطه داده را بر اساس اندیس آن در مجموعه نقاط سری والد اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

نقطه داده را به مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطه داده‌ای که به آن اضافه می‌شود. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

آیتم را از مجموعه حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطه داده‌ای که از آن حذف می‌شود. |

**بازگشت:**
boolean - true اگر آیتم با موفقیت حذف شود؛ در غیر اینصورت false. این متد همچنین false بر می‌گرداند اگر آیتم در System.Collections.Generic.List{T} یافت نشود.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

آیتم را از مجموعه بر اساس اندیس آن در مجموعه نقاط سری والد حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataPointIndex | int | اندیس نقطه داده در مجموعه نقاط سری والد. |

### clear() {#clear--}
```
public final void clear()
```

تمام آیتم‌ها را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | شیء برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - true اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر اینصورت false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک اندیس خاص Array.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IChartDataPoint[]](../../com.aspose.slides/ichartdatapoint) | آرایهٔ یک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی می‌شوند. آرایه باید ایندکس صفرپایه داشته باشد. |
| arrayIndex | int | ایندکس صفرپایه در آرایه که کپی از آن آغاز می‌شود. |

### size() {#size--}
```
public final int size()
```

تعداد نقاط داده نمودار را برمی‌گرداند یا تنظیم می‌کند. فقط-خواندنی int.

**بازگشت:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر اینصورت false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (امن در برابر نخ) است یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

یک Enumerator را برمی‌گرداند که بر مجموعه تکرار می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint] - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint] - An java.util.Iterator for the entire collection.