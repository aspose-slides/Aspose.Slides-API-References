---
title: ChartCellCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از سلول‌ها با داده.
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

نمایش مجموعه‌ای از سلول‌ها با داده.

## متدها

| متد | توضیح |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | آدرس مجموعه سلول‌ها در کتاب کاری را باز می‌گرداند. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | رشتهٔ ترکیبی از تمام مقادیر سلول‌ها. |
| [get_Item(int index)](#get-Item-int-) | یک سلول (IChartDataCell) را بر اساس شاخص باز می‌گرداند. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | سلول جدیدی به مجموعه اضافه می‌کند. |
| [add(Object value)](#add-java.lang.Object-) | از مقدار مشخص شده [ChartDataCell](../../com.aspose.slides/chartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌گردد. |
| [removeAt(int index)](#removeAt-int-) | سلولی را از مجموعه بر اساس شاخص حذف می‌کند. |
| [getCount()](#getCount--) | تعداد سلول‌ها در مجموعه را دریافت می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که در مجموعه تکرار می‌شود را باز می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک تکرارگر جاوا برای کل مجموعه باز می‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

آدرس مجموعه سلول‌ها در کتاب کاری را باز می‌گرداند.

**بازگشت:**  
java.lang.String

### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

رشتهٔ ترکیبی از تمام مقادیر سلول‌ها.

**بازگشت:**  
java.lang.String

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

یک سلول (IChartDataCell) را بر اساس شاخص باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص سلول. |

**بازگشت:**  
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

از مقدار مشخص شده [ChartDataCell](../../com.aspose.slides/chartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌گردد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار. |

--------------------

این متد یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن اضافه می‌نماید. اگر از [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) برای اضافه یا ویرایش مقادیر Cell استفاده می‌کنید، مطمئن شوید که از این کاربرگ استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شود نباید بیشتر از 16711680 باشد |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

سلولی را از مجموعه بر اساس شاخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص سلول برای حذف. |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد سلول‌ها در مجموعه را دریافت می‌کند. فقط-خواندنی int.

**بازگشت:**  
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

یک شمارنده که در مجموعه تکرار می‌شود را باز می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - یک IGenericEnumerator که می‌توان برای تکرار در مجموعه استفاده کرد.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

یک تکرارگر جاوا برای کل مجموعه باز می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - یک java.util.Iterator برای کل مجموعه.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject