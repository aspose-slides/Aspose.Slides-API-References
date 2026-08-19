---
title: ChartSeriesCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/chartseriescollection/
---
**وراثت:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

نمایش مجموعه‌ای از [ChartSeries](../../com.aspose.slides/chartseries)
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در فهرست مشخص شده است دریافت می‌کند. |
| [size()](#size--) | تعداد اشیاء موجود در مجموعه را برمی‌گرداند. |
| [add(int type)](#add-int-) | یک سری نمودار جدید ایجاد می‌کند و به مجموعه اضافه می‌نماید. |
| [insert(int index, int type)](#insert-int-int-) | یک سری نمودار جدید ایجاد می‌کند و در مجموعه درج می‌کند. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | یک سری نمودار جدید از [ChartDataCell](../../com.aspose.slides/chartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | یک سری نمودار جدید از [ChartCellCollection](../../com.aspose.slides/chartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(String name, int type)](#add-java.lang.String-int-) | یک سری نمودار جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | برای [ChartSeries](../../com.aspose.slides/chartseries) مشخص شده جستجو می‌کند و اندیس صفر-محور نخستین رخداد را در کل مجموعه برمی‌گرداند. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | مقدار مشخص شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک کنترل ActiveX ذخیره‌شده در موقعیت مشخص را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام کنترل‌ها را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (امن از نظر رشته) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

عنصری را که در فهرست مشخص شده است دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - عنصر در فهرست مشخص شده.

### size() {#size--}
```
public final int size()
```

تعداد اشیاء موجود در مجموعه را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

یک سری نمودار جدید ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار جدید.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

یک سری نمودار جدید ایجاد می‌کند و در مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

یک سری نمودار جدید از [ChartDataCell](../../com.aspose.slides/chartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که نام سری را شامل می‌شود. |
| type | int | نوع تنظیم شده برای سری |

--------------------

اگر سری نمودار از همان سلول قبلاً در مجموعه وجود داشته باشد، متد هیچ چیزی اضافه نمی‌کند و اندیس آن را برمی‌گرداند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری‌ای که پیش از این در مجموعه وجود داشته است.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

یک سری نمودار جدید از [ChartCellCollection](../../com.aspose.slides/chartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | سلول‌هایی که نام سری را شامل می‌شوند. |
| type | int | نوع تنظیم شده برای سری |

--------------------

اگر سری نمودار از همان سلول قبلاً در مجموعه وجود داشته باشد، متد هیچ چیزی اضافه نمی‌کند و اندیس آن را برمی‌گرداند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری‌ای که پیش از این در مجموعه وجود داشته است.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

یک سری نمودار جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام سری. |
| type | int | نوع تنظیم شده برای سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

برای [ChartSeries](../../com.aspose.slides/chartseries) مشخص شده جستجو می‌کند و اندیس صفر-محور نخستین رخداد را در کل مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار سری نمودار. |

**بازگشت:**
int - اندیس صفر-محور نخستین رخداد مقدار در کل CollectionBase، اگر یافت شود؛ در غیر این صورت -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

مقدار مشخص شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک کنترل ActiveX ذخیره‌شده در موقعیت مشخص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس کنترل برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام کنترل‌ها را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

یک enumerator که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه از آن استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

کل مجموعه را به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف |
| index | int | اندیس در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (امن از نظر رشته) است یا نه. فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**
java.lang.Object