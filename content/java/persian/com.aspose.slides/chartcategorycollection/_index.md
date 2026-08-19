---
title: ChartCategoryCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایش مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/chartcategorycollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)  
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

نمایش مجموعه‌ای از [ChartCategory](../../com.aspose.slides/chartcategory)
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در شاخص مشخص شده قرار دارد برمی‌گرداند. |
| [getUseCells()](#getUseCells--) | اگر true باشد، کاربرگ برای ذخیره‌سازی دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | اگر true باشد، کاربرگ برای ذخیره‌سازی دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | تعداد سطوح گروه‌بندی دسته‌های استفاده‌شده را برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | اگر دسته در مجموعه وجود داشته باشد، آن را برمی‌گرداند. |
| [add(Object value)](#add-java.lang.Object-) | یک [ChartCategory](../../com.aspose.slides/chartcategory) جدید از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | [ChartCategory](../../com.aspose.slides/chartcategory) مشخص‌شده را جستجو می‌کند و اندیس پایه صفر اولین رخداد آن را در کل مجموعه برمی‌گرداند. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در شاخص داده شده قرار دارد حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر مجموعه را حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارشگر را برمی‌گرداند که در مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [size()](#size--) | تعداد عناصری را در مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به List همگام‌سازی شده است (ایمن برای چندنخ). |
| [getSyncRoot()](#getSyncRoot--) | یک شیء را برمی‌گرداند که می‌تواند برای همگام‌سازی دسترسی به مجموعه استفاده شود. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

عنصری را که در شاخص مشخص شده قرار دارد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - عنصر در شاخص مشخص شده

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

اگر true باشد، کاربرگ برای ذخیره‌سازی دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر false باشد، کاربرگ برای ذخیره‌سازی مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی قابل خواندن/نوشتن.

**بازگشت:**  
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

اگر true باشد، کاربرگ برای ذخیره‌سازی دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر false باشد، کاربرگ برای ذخیره‌سازی مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولی قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

تعداد سطوح گروه‌بندی دسته‌های استفاده‌شده را برمی‌گرداند. برای دسته‌های چندسطحی بیشتر از یک است. عدد صحیح فقط خواندنی.

**بازگشت:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

اگر دسته در مجموعه وجود داشته باشد، آن را برمی‌گرداند. در غیر این صورت یک دسته نمودار جدید از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد می‌کند و به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | سلولی که برای ایجاد دسته نمودار استفاده می‌شود. |

**بازگشت:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - دسته اضافه‌شده یا موجود.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

یک [ChartCategory](../../com.aspose.slides/chartcategory) جدید از مقدار ایجاد می‌کند و آن را به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار.

--------------------

این روش یک کاربرگ با نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن قرار می‌دهد. اگر از [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده می‌کنید، مطمئن شوید که از این کاربرگ استفاده نمی‌کنید. حداکثر تعداد مقادیری که با استفاده از این روش اضافه می‌شوند نباید بیش از 16711680 باشد |

**بازگشت:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) اضافه شد.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

به دنبال [ChartCategory](../../com.aspose.slides/chartcategory) مشخص‌شده جستجو می‌کند و اندیس پایه صفر اولین رخداد آن را در کل مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | دسته نمودار. |

**بازگشت:**
int - اندیس پایه صفر اولین رخداد مقدار در کل CollectionBase، در صورتی که یافت شود؛ در غیر این صورت -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

مقدار مشخص‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | مقدار. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصری را که در شاخص داده شده قرار دارد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس دسته‌ای که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام عناصر مجموعه را حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

یک شمارشگر را برمی‌گرداند که در مجموعه تکرار می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - یک java.util.Iterator برای کل مجموعه.

### size() {#size--}
```
public final int size()
```

تعداد عناصری را در مجموعه برمی‌گرداند. عدد صحیح فقط خواندنی.

**بازگشت:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به List همگام‌سازی شده است (ایمن برای چندنخ). بولی فقط خواندنی.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک شیء را برمی‌گرداند که می‌تواند برای همگام‌سازی دسترسی به مجموعه استفاده شود. شیء فقط خواندنی.

یک ریشه همگام‌سازی را برمی‌گرداند. شیء فقط خواندنی.

**بازگشت:**
java.lang.Object