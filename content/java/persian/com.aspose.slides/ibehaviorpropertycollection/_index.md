---
title: IBehaviorPropertyCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایندهٔ خواص زمان‌بندی برای رفتار اثر است.
type: docs
url: /fa/com.aspose.slides/ibehaviorpropertycollection/
---
**تمام واسط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

نمایندهٔ خواص زمان‌بندی برای رفتار اثر است.

## متدها

| متد | توضیح |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | یک خاصیت جدید به مجموعه اضافه می‌کند. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | شاخص یک مورد خاص را بر اساس مقدار خاصیت در لیست تعیین می‌کند. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | یک خاصیت جدید (با مقدار خاصیت مشخص شده) را در مجموعه در شاخص مشخص شده وارد می‌کند. |
| [remove(String propertyValue)](#remove-java.lang.String-) | خاصیت مشخص‌شده را از مجموعه حذف می‌کند. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |

### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

یک خاصیت جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار خاصیتی که باید اضافه شود. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

شاخص یک مورد خاص را بر اساس مقدار خاصیت در لیست تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار خاصیت |

**بازگشت:**
int - شاخص خاصیت با مقدار مشخص شده

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

یک خاصیت جدید (با مقدار خاصیت مشخص شده) را در مجموعه در شاخص مشخص شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخصی که خاصیت جدید باید در آن وارد شود. |
| propertyValue | java.lang.String | مقدار خاصیتی که باید اضافه شود. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

خاصیت مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار خاصیتی که باید حذف شود. |

**بازگشت:**
boolean - True اگر خاصیتی با مقدار propertyValue حذف شده باشد

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار خاصیتی که باید در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود. |

**بازگشت:**
boolean - true اگر propertyValue در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت false.