---
title: IChartCellCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ مجموعه‌ای از سلول‌ها با داده‌ها.
type: docs
url: /fa/com.aspose.slides/ichartcellcollection/
---
**همه رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

نمایانگر مجموعه‌ای از سلول‌ها با داده است.
## متدها

| متد | توضیح |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | آدرس مجموعهٔ سلول‌ها را در کتاب‌کار برمی‌گرداند. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | رشتهٔ ترکیبی از تمام مقادیر رشته‌ای سلول‌ها. |
| [get_Item(int index)](#get-Item-int-) | سلولی (IChartDataCell) را بر اساس اندیس برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | سلول جدیدی به مجموعه اضافه می‌کند. |
| [add(Object value)](#add-java.lang.Object-) | از مقدار مشخص [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌نماید. |
| [removeAt(int index)](#removeAt-int-) | سلولی را از مجموعه بر اساس اندیس حذف می‌کند. |
| [getCount()](#getCount--) | تعداد سلول‌های موجود در مجموعه را دریافت می‌کند. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


آدرس مجموعهٔ سلول‌ها را در کتاب‌کار برمی‌گرداند.

**بازگشت:**
java.lang.String - آدرس مجموعهٔ سلول‌ها در کتاب‌کار String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


رشتهٔ ترکیبی از تمام مقادیر رشته‌ای سلول‌ها.

**بازگشت:**
java.lang.String - رشتهٔ حاصل String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


سلولی (IChartDataCell) را بر اساس اندیس برمی‌گرداند.

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


سلول جدیدی به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلول جدید برای اضافه شدن. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


از مقدار مشخص [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار.

--------------------

این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن می‌گذارد. اگر از [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) برای اضافه یا ویرایش مقادیر Cell استفاده می‌کنید، اطمینان حاصل کنید که از این کاربرگ استفاده نکنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید از 16711680 عبور کند.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


سلولی را از مجموعه بر اساس اندیس حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس یک سلول برای حذف. |

### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد سلول‌های موجود در مجموعه را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**
int