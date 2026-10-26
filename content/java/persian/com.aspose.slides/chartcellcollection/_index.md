---
title: ChartCellCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش مجموعه‌ای از سلول‌ها با داده.
type: docs
url: /fa/com.aspose.slides/chartcellcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

نمایش یک مجموعه از سلول‌ها با داده.
## متدها

| متد | توضیح |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | آدرس مجموعه سلول‌ها در کتاب کار را برمی‌گرداند. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | رشته ترکیبی از تمام مقادیر رشته‌ای سلول‌ها. |
| [get_Item(int index)](#get-Item-int-) | یک سلول (IChartDataCell) را بر اساس ایندکس برمی‌گرداند. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | سلول جدیدی به مجموعه اضافه می‌کند. |
| [add(Object value)](#add-java.lang.Object-) | [ChartDataCell](../../com.aspose.slides/chartdatacell) را از مقدار مشخص شده ایجاد کرده و به مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک سلول را از مجموعه بر اساس ایندکس حذف می‌کند. |
| [getCount()](#getCount--) | تعداد سلول‌های موجود در مجموعه را دریافت می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

آدرس مجموعه سلول‌ها در کتاب کار را برمی‌گرداند.

**باز می‌گردد:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

رشته ترکیبی از تمام مقادیر رشته‌ای سلول‌ها.

**باز می‌گردد:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

یک سلول (IChartDataCell) را بر اساس ایندکس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس سلول. |

**باز می‌گردد:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - سلول با داده.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

سلول جدیدی به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلول جدید برای اضافه کردن. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

[ChartDataCell](../../com.aspose.slides/chartdatacell) را از مقدار مشخص شده ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار. |

--------------------

این متد یک worksheet با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) برای اضافه یا ویرایش مقادیر Cell استفاده کنید، مطمئن شوید که از این worksheet استفاده نکنید. حداکثر تعداد مقادیری که با این متد اضافه می‌شود نباید از ۱۶۷۱۱۶۸۰ بیشتر باشد |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک سلول را از مجموعه بر اساس ایندکس حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس سلول برای حذف. |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد سلول‌های موجود در مجموعه را دریافت می‌کند. فقط-خواندنی int.

**باز می‌گردد:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - یک java.util.Iterator برای کل مجموعه.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**باز می‌گردد:**
com.aspose.slides.IDOMObject