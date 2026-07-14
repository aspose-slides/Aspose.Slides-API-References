---
title: ChartCategoryCollection
second_title: مرجع API جاوا برای Aspose.Slides در اندروید
description: نمایش مجموعه‌ای از
type: docs
url: /fa/com.aspose.slides/chartcategorycollection/
---
**وراثت:**
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
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص شده دریافت می‌کند. |
| [getUseCells()](#getUseCells--) | اگر مقدار true باشد، کاربرگ برای ذخیره دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | اگر مقدار true باشد، کاربرگ برای ذخیره دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | تعداد سطوح گروه‌بندی دسته‌ها را برمی‌گرداند. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | اگر دسته در مجموعه موجود باشد، آن را برمی‌گرداند. |
| [add(Object value)](#add-java.lang.Object-) | یک [ChartCategory](../../com.aspose.slides/chartcategory) جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌نماید. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | برای [ChartCategory](../../com.aspose.slides/chartcategory) مشخص‌شده جستجو می‌کند و ایندکس صفر-پایه اولین وقوع را در کل مجموعه برمی‌گرداند. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | مقدار مشخص‌شده را حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در ایندکس داده‌شده را حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارشگر که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک ایتراتور جاوا برای کل مجموعه برمی‌گرداند. |
| [size()](#size--) | تعداد عناصری در مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار را که نشان می‌دهد دسترسی به لیست همگام‌سازی شده است (ایمن برای چندنخیه) برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | یک شیء که می‌توان از آن برای همگام‌سازی دسترسی به مجموعه استفاده کرد را برمی‌گرداند. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

عنصر را در اندیس مشخص شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - عنصر در اندیس مشخص شده.

### getUseCells() {#getUseCells--}}
```
public final boolean getUseCells()
```

اگر مقدار true باشد، کاربرگ برای ذخیره دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، کاربرگ برای ذخیره مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولین قابل خواندن/نوشتن.

**بازگشت:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

اگر مقدار true باشد، کاربرگ برای ذخیره دسته‌ها استفاده می‌شود (این حالت از دسته‌های چندسطحی پشتیبانی می‌کند). اگر مقدار false باشد، کاربرگ برای ذخیره مقادیر استفاده نمی‌شود (و این حالت از دسته‌های چندسطحی پشتیبانی نمی‌کند). بولین قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}}
```
public final int getGroupingLevelCount()
```

تعداد سطوح گروه‌بندی دسته‌ها را برمی‌گرداند. برای دسته‌های چندسطحی بیشتر از یک است. عدد فقط خواندنی.

**بازگشت:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

اگر دسته در مجموعه موجود باشد، آن را برمی‌گرداند. در غیر این صورت یک دسته نمودار جدید از [IChartDataCell](../../com.aspose.slides/ichartdatacell) ایجاد کرده و به مجموعه اضافه می‌کند.

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

یک [ChartCategory](../../com.aspose.slides/chartcategory) جدید از مقدار ایجاد می‌کند و به مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Object | مقدار. |

--------------------

این متد یک کاربرگ به نام AUTO_DATA اضافه می‌کند و تمام مقادیر را در آن می‌گذارد. اگر از [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) برای افزودن یا ویرایش مقادیر سلول استفاده کنید، مطمئن شوید که از این کاربرگ استفاده نمی‌کنید. حداکثر تعداد مقادیری که با این متد اضافه می‌شوند نباید از 16711680 بیش تر باشد.

**بازگشت:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - [IChartCategory](../../com.aspose.slides/ichartcategory) اضافه شد.

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

برای [ChartCategory](../../com.aspose.slides/chartcategory) مشخص‌شده جستجو می‌کند و ایندکس صفر-پایه اولین وقوع را در کل مجموعه برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | دسته نمودار. |

**بازگشت:**
int - ایندکس صفر-پایه اولین وقوع مقدار در کل CollectionBase، اگر یافت شد؛ در غیر این صورت -1.

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

عنصر در ایندکس داده‌شده را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس دسته‌ای که باید حذف شود. |

### clear() {#clear--}}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### iterator() {#iterator--}}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

یک شمارشگر که از مجموعه عبور می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

یک ایتراتور جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - یک java.util.Iterator برای کل مجموعه.

### size() {#size--}}
```
public final int size()
```

تعداد عناصر موجود در مجموعه را برمی‌گرداند. عدد فقط خواندنی.

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
| index | int | ایندکس شروع در آرایه. |

### isSynchronized() {#isSynchronized--}}
```
public final boolean isSynchronized()
```

مقداری که نشان می‌دهد دسترسی به List همگام‌سازی شده است (ایمن برای چندنخیه) را برمی‌گرداند. بولین فقط خواندنی.

**بازگشت:**
boolean

### getSyncRoot() {#getSyncRoot--}}
```
public final Object getSyncRoot()
```

یک شیء که می‌توان از آن برای همگام‌سازی دسترسی به مجموعه استفاده کرد را برمی‌گرداند. شیء فقط خواندنی.  
یک ریشه همگام‌سازی را برمی‌گرداند. شیء فقط خواندنی.

**بازگشت:**
java.lang.Object