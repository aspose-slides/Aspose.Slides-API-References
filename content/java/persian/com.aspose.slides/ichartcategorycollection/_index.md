---
title: IChartCategoryCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/ichartcategorycollection/
---
**همه رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

نمایش‌دهندهٔ مجموعه‌ای از [IChartCategory](../../com.aspose.slides/ichartcategory)

## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص شده دریافت می‌کند. |
| [getUseCells()](#getUseCells--) | اگر مقدار true باشد، صفحه‌کار برای ذخیرهٔ دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | اگر مقدار true باشد، صفحه‌کار برای ذخیرهٔ دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | تعداد سطوح گروه‌بندی دسته‌بندی‌های استفاده‌شده را برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | اگر دسته در مجموعه موجود باشد، آن را برگردانید. |
| [add(Object value)](#add-java.lang.Object-) | یک [IChartCategory](../../com.aspose.slides/ichartcategory) جدید از مقدار ایجاد کرده و به مجموعه اضافه می‌کند. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | [IChartCategory](../../com.aspose.slides/ichartcategory) مشخص‌شده را جستجو می‌کند و اندیس صفر-مبنا برای اولین رخداد در کل Collection را برمی‌گرداند. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس داده‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

عنصر را در اندیس مشخص شده دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**بازگشت‌ها:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - عنصر در اندیس مشخص شده.

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

اگر مقدار true باشد، صفحه‌کار برای ذخیرهٔ دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، صفحه‌کار برای ذخیرهٔ مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی خواندنی/نوشتنی.

**بازگشت‌ها:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

اگر مقدار true باشد، صفحه‌کار برای ذخیرهٔ دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، صفحه‌کار برای ذخیرهٔ مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی خواندنی/نوشتنی.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

تعداد سطوح گروه‌بندی دسته‌بندی‌های استفاده‌شده را برمی‌گرداند. برای دسته‌های چندسطحی بیشتر از یک است. عدد صحیح فقط-خواندنی.

**بازگشت‌ها:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

اگر دسته در مجموعه موجود باشد، آن را برگردانید. در غیر این صورت، دستهٔ نمودار جدیدی از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که برای ایجاد دستهٔ نمودار استفاده می‌شود. |

**بازگشت‌ها:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - دستهٔ اضافه‌شده یا موجود.

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

[IChartCategory](../../com.aspose.slides/ichartcategory) جدیدی از مقدار ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | مقدار.

--------------------

این متد صفحه‌کاری با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، اطمینان حاصل کنید که از این صفحه‌کار استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید بیش از 16711680 باشد |

**بازگشت‌ها:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) اضافه‌شده.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

[IChartCategory](../../com.aspose.slides/ichartcategory) مشخص‌شده را جستجو می‌کند و اندیس صفرمبنا برای اولین رخداد در کل Collection را برمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | دستهٔ نمودار. |

**بازگشت‌ها:**
int - اندیس صفرمبنا برای اولین رخداد مقدار در کل CollectionBase، در صورت یافتن؛ در غیر این صورت -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در اندیس داده‌شده حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس دسته‌ای که حذف می‌شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.