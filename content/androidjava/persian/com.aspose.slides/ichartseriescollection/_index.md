---
title: IChartSeriesCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/ichartseriescollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

نمایش مجموعه‌ای از [IChartSeries](../../com.aspose.slides/ichartseries)
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص دریافت می‌کند. |
| [add(int type)](#add-int-) | یک سری جدید نمودار ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [insert(int index, int type)](#insert-int-int-) | یک سری جدید نمودار ایجاد می‌کند و در مجموعه درج می‌کند. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | یک سری جدید نمودار از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | یک سری جدید نمودار از [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [add(String name, int type)](#add-java.lang.String-int-) | یک سری جدید نمودار از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | به دنبال [IChartSeries](../../com.aspose.slides/ichartseries) مشخص جستجو می‌کند و اندیس صفرپایه اولین وقوع آن را در کل مجموعه برمی‌گرداند. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در ایندکس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر (از جمله سبک نمودار) را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

عنصر را در ایندکس مشخص دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - عنصر در ایندکس مشخص.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

یک سری جدید نمودار ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار جدید.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

یک سری جدید نمودار ایجاد می‌کند و در مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برای درج |
| type | int | نوع نمودار [ChartType](../../com.aspose.slides/charttype) |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار جدید [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

یک سری جدید نمودار از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که نام سری را شامل می‌شود. |
| type | int | نوع سری |

--------------------

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شود، متد چیزی اضافه نمی‌کند و اندیس آن را بر می‌گرداند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری که قبلاً در مجموعه وجود دارد.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

یک سری جدید نمودار از [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | سلول‌هایی که نام سری را شامل می‌شوند. |
| type | int | نوع سری |

--------------------

اگر سری نمودار از همان سلول که قبلاً در مجموعه وجود دارد ایجاد شود، متد چیزی اضافه نمی‌کند و اندیس آن را بر می‌گرداند. |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده یا سری که قبلاً در مجموعه وجود دارد.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

یک سری جدید نمودار از مقدار ایجاد می‌کند و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | java.lang.String | نام سری. |
| type | int | نوع سری |

**بازگشت:**
[IChartSeries](../../com.aspose.slides/ichartseries) - سری نمودار اضافه‌شده.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

به دنبال [IChartSeries](../../com.aspose.slides/ichartseries) مشخص جستجو می‌کند و اندیس صفرپایه اولین وقوع آن را در کل مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار سری نمودار. |

**بازگشت:**
int - اندیس صفرپایه اولین وقوع مقدار در کل CollectionBase، اگر یافت شود؛ در غیر این صورت، -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | مقدار. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس |
### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر (از جمله سبک نمودار) را از مجموعه حذف می‌کند.