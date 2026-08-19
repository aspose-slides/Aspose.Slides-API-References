---
title: PieSplitCustomPointCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ مجموعه‌ای از نقاط برای نقطهٔ تقسیم در نمودار بار-از-پای یا پای-از-بار با تقسیم سفارشی.
type: docs
url: /fa/com.aspose.slides/piesplitcustompointcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | نقطه دادهٔ نمودار را برای ایندکس مشخص برمی‌گرداند. |
| [add(int dataPointIndex)](#add-int-) | نقطه داده را با ایندکس آن در مجموعهٔ نقاط سری والد اضافه می‌کند. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | نقطه داده را به مجموعه اضافه می‌کند. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | عنصری را از مجموعه حذف می‌کند. |
| [remove(int dataPointIndex)](#remove-int-) | عنصری را از مجموعه با ایندکس آن در مجموعهٔ نقاط سری والد حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک ایندکس خاص آرایه. |
| [size()](#size--) | تعداد نقاط دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

نقطه دادهٔ نمودار را برای ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس. |

**بازگشت:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطه دادهٔ نمودار.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

نقطه داده را با ایندکس آن در مجموعهٔ نقاط سری والد اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPointIndex | int | ایندکس نقطه داده در مجموعهٔ نقاط سری والد. |
### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

نقطه داده را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطه داده برای افزودن به. |
### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

عنصری را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | نقطه داده برای حذف. |

**بازگشت:**
boolean - در صورتی که عنصر با موفقیت حذف شود؛ در غیر این صورت، false. این متد همچنین false برمی‌گرداند اگر عنصر در System.Collections.Generic.List\{T\} یافت نشود.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

عنصری را از مجموعه با ایندکس آن در مجموعهٔ نقاط سری والد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| dataPointIndex | int | ایندکس نقطه داده در مجموعهٔ نقاط سری والد. |
### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.
### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | شیء برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - در صورتی که عنصر در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک ایندکس خاص آرایه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | آرایهٔ تک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی می‌شوند. آرایه باید ایندکس صفر-پایه داشته باشد. |
| arrayIndex | int | ایندکس صفر-پایه در آرایه که کپی از آن شروع می‌شود. |
### size() {#size--}
```
public final int size()
```

تعداد نقاط دادهٔ نمودار را برمی‌گرداند یا تنظیم می‌کند. int فقط-خواندنی.

**بازگشت:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است. boolean فقط-خواندنی.

**بازگشت:**
boolean - در صورتی که [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر این صورت، false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. boolean فقط-خواندنی.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط-خواندنی.

**بازگشت:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - یک java.util.Iterator برای کل مجموعه.