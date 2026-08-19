---
title: IChartSeriesCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش دهنده مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/ichartseriescollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IGenericCollection  
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

نمایش مجموعه‌ای از [IChartSeries](../../com.aspose.slides/ichartseries)
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده است دریافت می‌کند. |
| [add(int type)](#add-int-) | یک سری جدید نمودار ایجاد می‌کند و به مجموعه اضافه می‌نماید. |
| [insert(int index, int type)](#insert-int-int-) | یک سری جدید نمودار ایجاد می‌کند و در مجموعه وارد می‌کند. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | یک سری جدید نمودار از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | یک سری جدید نمودار از [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(String name, int type)](#add-java.lang.String-int-) | یک سری جدید نمودار از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | به دنبال [IChartSeries](../../com.aspose.slides/ichartseries) مشخص شده جستجو می‌کند و شاخص صفر مبنا اولین رخداد را در کل مجموعه برمی‌گرداند. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | مقدار مشخص شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در اندیس مشخص شده را حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر (از جمله سبک نمودار) را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

عنصری را که در اندیس مشخص شده است دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - عنصر در اندیس مشخص شده.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

یک سری جدید نمودار ایجاد می‌کند و به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری جدید نمودار.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

یک سری جدید نمودار ایجاد می‌کند و در مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برای درج |
| type | int | نوع نمودار [ChartType](../../com.aspose.slides/charttype) |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری جدید نمودار [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

یک سری جدید نمودار از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که اسم سری را شامل می‌شود. |
| type | int | نوع سری را تعیین می‌کند. |

--------------------

اگر سری نمودار از همان سلول که پیش از این در مجموعه وجود دارد، ایجاد شود، متد هیچ چیزی اضافه نمی‌کند و شاخص آن را باز می‌گرداند.

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری‌ای که پیش از این در مجموعه موجود بود.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

یک سری جدید نمودار از [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | سلول‌هایی که اسم سری را شامل می‌شوند. |
| type | int | نوع سری را تعیین می‌کند. |

--------------------

اگر سری نمودار از همان سلول که پیش از این در مجموعه وجود دارد، ایجاد شود، متد هیچ چیزی اضافه نمی‌کند و شاخص آن را باز می‌گرداند.

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری‌ای که پیش از این در مجموعه موجود بود.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

یک سری جدید نمودار از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام سری. |
| type | int | نوع سری را تعیین می‌کند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

به دنبال [IChartSeries](../../com.aspose.slides/ichartseries) مشخص شده جستجو می‌کند و شاخص صفر مبنا اولین رخداد را در کل مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار سری نمودار. |

**بازگشت:**
int - شاخص صفر مبنا اولین رخداد مقدار در کل CollectionBase، اگر یافت شود؛ در غیر این صورت -۱.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

مقدار مشخص شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر در اندیس مشخص شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر (از جمله سبک نمودار) را از مجموعه حذف می‌کند.