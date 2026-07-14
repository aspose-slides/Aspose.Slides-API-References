---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نماینده ویژگی‌های زمان‌بندی برای رفتار اثر.
type: docs
url: /fa/com.aspose.slides/ibehaviorpropertycollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

نمایندهٔ ویژگی‌های زمان‌بندی برای رفتار اثر.

## متدها

| متد | توضیح |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | یک ویژگی جدید را به مجموعه اضافه می‌کند. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | ایندکس یک مورد خاص را بر اساس مقدار ویژگی در لیست تعیین می‌کند. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | یک ویژگی جدید (با مقدار ویژگی مشخص شده) را در ایندکس مشخص شده به مجموعه وارد می‌کند. |
| [remove(String propertyValue)](#remove-java.lang.String-) | ویژگی مشخص شده را از مجموعه حذف می‌کند. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تشخیص می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |

### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

یک ویژگی جدید را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای اضافه شدن. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

ایندکس یک مورد خاص را بر اساس مقدار ویژگی در لیست تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی |

**بازگرداندن:**
int - ایندکس ویژگی با مقدار مشخص شده

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

یک ویژگی جدید (با مقدار ویژگی مشخص شده) را در ایندکس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس که ویژگی جدید باید در آن وارد شود. |
| propertyValue | java.lang.String | مقدار ویژگی برای اضافه شدن. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

ویژگی مشخص شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای حذف. |

**بازگرداندن:**
boolean - True اگر ویژگی با موفقیت حذف شد boolean

### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

تشخیص می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگرداندن:**
boolean - true اگر propertyValue در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.