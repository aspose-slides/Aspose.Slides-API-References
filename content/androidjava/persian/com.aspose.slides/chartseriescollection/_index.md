---
title: ChartSeriesCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/chartseriescollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

نمایشگر مجموعه‌ای از [ChartSeries](../../com.aspose.slides/chartseries)

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر مورد نظر در شاخص مشخص شده را دریافت می‌کند. |
| [size()](#size--) | تعداد اشیاء در مجموعه را برمی‌گرداند. |
| [add(int type)](#add-int-) | یک سری جدید نمودار می‌سازد و به مجموعه اضافه می‌کند. |
| [insert(int index, int type)](#insert-int-int-) | یک سری جدید نمودار می‌سازد و در مجموعه وارد می‌کند. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | یک سری جدید نمودار از [ChartDataCell](../../com.aspose.slides/chartdatacell) می‌سازد و به مجموعه اضافه می‌کند. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | یک سری جدید نمودار از [ChartCellCollection](../../com.aspose.slides/chartcellcollection) می‌سازد و به مجموعه اضافه می‌کند. |
| [add(String name, int type)](#add-java.lang.String-int-) | یک سری جدید نمودار از مقدار می‌سازد و به مجموعه اضافه می‌کند. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | برای [ChartSeries](../../com.aspose.slides/chartseries) مشخص شده جستجو می‌کند و شاخص صفر-پایه اولین رخداد در کل مجموعه را برمی‌گرداند. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | مقدار مشخص شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک کنترل ActiveX که در موقعیت مشخص ذخیره شده را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام کنترل‌ها را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده‌ای را برمی‌گرداند که در مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | کل مجموعه را به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا نه. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

عنصری را که در شاخص مشخص شده است دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - عنصر در شاخص مشخص شده.

### size() {#size--}
```
public final int size()
```

تعداد اشیاء در مجموعه را برمی‌گرداند. عدد فقط-خواندنی.

**بازگشت:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

یک سری جدید نمودار می‌سازد و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری جدید نمودار.

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

یک سری جدید نمودار می‌سازد و در مجموعه وارد می‌کند.

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

یک سری جدید نمودار از [ChartDataCell](../../com.aspose.slides/chartdatacell) می‌سازد و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که نام سری را شامل می‌شود. |
| type | int | نوعی که نوع سری را تعیین می‌کند. |

اگر سری نمودار از سلول یکسانی که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ‌چیزی اضافه نمی‌کند و شاخص آن را برمی‌گرداند.

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه شده یا سری‌ای که قبلاً در مجموعه موجود است.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

یک سری جدید نمودار از [ChartCellCollection](../../com.aspose.slides/chartcellcollection) می‌سازد و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | سلول‌هایی که نام سری را شامل می‌شوند. |
| type | int | نوعی که نوع سری را تعیین می‌کند. |

اگر سری نمودار از سلول یکسانی که قبلاً در مجموعه وجود دارد ایجاد شده باشد، متد هیچ‌چیزی اضافه نمی‌کند و شاخص آن را برمی‌گرداند.

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه شده یا سری‌ای که قبلاً در مجموعه موجود است.

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

یک سری جدید نمودار از مقدار می‌سازد و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام سری. |
| type | int | نوعی که نوع سری را تعیین می‌کند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه شده.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

برای [ChartSeries](../../com.aspose.slides/chartseries) مشخص شده جستجو می‌کند و شاخص صفر-پایه اولین رخداد مقدار در کل CollectionBase، اگر یافت شد؛ در غیر این صورت -1 را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار سری نمودار. |

**بازگشت:**
int - شاخص صفر-پایه اولین رخداد مقدار در کل CollectionBase، اگر یافت شد؛ در غیر این صورت -1.

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

یک کنترل ActiveX که در موقعیت مشخص ذخیره شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص کنترلی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام کنترل‌ها را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

یک شمارنده‌ای را برمی‌گرداند که در مجموعه تکرار می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.

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
| index | int | شاخص در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده (thread-safe) است یا نه. مقدار فقط-خواندنی boolean.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. مقدار فقط-خواندنی Object.

**بازگشت:**
java.lang.Object