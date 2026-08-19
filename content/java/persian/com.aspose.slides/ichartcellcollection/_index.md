---
title: IChartCellCollection
second_title: Aspose.Slides برای جاوا - مرجع API
description: نمایش مجموعه‌ای از سلول‌ها با داده.
type: docs
url: /fa/com.aspose.slides/ichartcellcollection/
---
**همه رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

نمایش مجموعه‌ای از سلول‌ها با داده.
## متدها

| متد | توضیح |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | آدرس مجموعه سلول‌ها در کتاب کاری را برمی‌گرداند. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | رشتهٔ ترکیبی از مقادیر رشته‌ای تمام سلول‌ها. |
| [get_Item(int index)](#get-Item-int-) | یک سلول (IChartDataCell) را بر اساس ایندکس برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | یک سلول جدید به مجموعه اضافه می‌کند. |
| [add(Object value)](#add-java.lang.Object-) | یک [IChartDataCell](../../com.aspose.slides/ichartdatacell) از مقدار مشخص شده ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید. |
| [removeAt(int index)](#removeAt-int-) | یک سلول را از مجموعه بر اساس ایندکس حذف می‌کند. |
| [getCount()](#getCount--) | تعداد سلول‌های موجود در مجموعه را به‌دست می‌آورد. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

آدرس مجموعه سلول‌ها در کتاب کاری را برمی‌گرداند.

**بازگشت:**
java.lang.String - آدرس مجموعه سلول‌ها در کتاب کاری String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

رشتهٔ ترکیبی از مقادیر رشته‌ای تمام سلول‌ها.

**بازگشت:**
java.lang.String - رشتهٔ نتیجه String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

یک سلول (IChartDataCell) را بر اساس ایندکس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس یک سلول. |

**بازگشت:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - سلول با داده.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

یک سلول جدید را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلول جدید برای اضافه شدن. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

یک [IChartDataCell](../../com.aspose.slides/ichartdatacell) از مقدار مشخص شده ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار. |

--------------------

این روش یک ورک‌شیت با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن افزودن می‌کند. اگر از [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، اطمینان حاصل کنید که از این ورک‌شیت استفاده نکنید حداکثر تعداد مقادیری که با استفاده از این روش اضافه می‌شود نباید بیش از 16711680 باشد |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک سلول را از مجموعه بر اساس ایندکس حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس سلولی که باید حذف شود. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد سلول‌های موجود در مجموعه را به‌دست می‌آورد. فقط خواندنی int.

**بازگشت:**
int