---
title: IChartCategoryCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/ichartcategorycollection/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

نمایش مجموعه‌ای از [IChartCategory](../../com.aspose.slides/ichartcategory)
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده است دریافت می‌کند. |
| [getUseCells()](#getUseCells--) | اگر مقدار true باشد، کاربرگ برای ذخیرهٔ دسته‌ها استفاده می‌شود (در این حالت دسته‌های چندسطحی پشتیبانی می‌شوند). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | اگر مقدار true باشد، کاربرگ برای ذخیرهٔ دسته‌ها استفاده می‌شود (در این حالت دسته‌های چندسطحی پشتیبانی می‌شوند). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | تعداد سطوح گروه‌بندی دسته‌بندی استفاده شده را برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | اگر دسته در مجموعه موجود باشد، آن را برمی‌گرداند. |
| [add(Object value)](#add-java.lang.Object-) | یک [IChartCategory](../../com.aspose.slides/ichartcategory) جدید از مقدار ایجاد کرده و به مجموعه اضافه می‌کند. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | برای [IChartCategory](../../com.aspose.slides/ichartcategory) مشخص‌شده جستجو می‌کند و شاخص صفر-پایهٔ اولین رخداد در کل مجموعه را برمی‌گرداند. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در اندیس داده‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

عنصری را که در اندیس مشخص شده است دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - عنصر در اندیس مشخص شده

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

اگر مقدار true باشد، کاربرگ برای ذخیرهٔ دسته‌ها استفاده می‌شود (در این حالت دسته‌های چندسطحی پشتیبانی می‌شوند). اگر مقدار false باشد، کاربرگ برای ذخیرهٔ مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی با قابلیت خواندن/نوشتن.

**بازگرداندن:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

اگر مقدار true باشد، کاربرگ برای ذخیرهٔ دسته‌ها استفاده می‌شود (در این حالت دسته‌های چندسطحی پشتیبانی می‌شوند). اگر مقدار false باشد، کاربرگ برای ذخیرهٔ مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی با قابلیت خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

تعداد سطوح گروه‌بندی دسته‌بندی استفاده شده را برمی‌گرداند. برای دسته‌های چندسطحی بیش از یک است. int فقط-خواندنی.

**بازگرداندن:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

اگر دسته در مجموعه موجود باشد، آن را برمی‌گرداند. در غیر این صورت یک دسته نمودار جدید از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که برای ایجاد دسته‌ی نمودار استفاده می‌شود. |

**بازگرداندن:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - دسته اضافه‌شده یا موجود

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

یک [IChartCategory](../../com.aspose.slides/ichartcategory) جدید از مقدار ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار.

--------------------

این متد یک کاربرگ با نام AUTO\_DATA اضافه می‌کند و تمام مقادیر را در آن افزوده می‌نماید. اگر از [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده کنید، مطمئن شوید که از این کاربرگ استفاده نکنید. حداکثر تعداد مقادیری که با استفاده از این متد اضافه می‌شوند نباید بیش از 16711680 باشد. |

**بازگرداندن:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) اضافه شد.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

برای [IChartCategory](../../com.aspose.slides/ichartcategory) مشخص‌شده جستجو می‌کند و شاخص صفر-پایهٔ اولین رخداد در کل مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | دسته نمودار. |

**بازگرداندن:**
int - شاخص صفر-پایهٔ اولین رخداد مقدار در کل CollectionBase، اگر یافت شود؛ در غیر این صورت -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | مقدار.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر در اندیس داده‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس دسته‌ای که باید حذف شود.

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.