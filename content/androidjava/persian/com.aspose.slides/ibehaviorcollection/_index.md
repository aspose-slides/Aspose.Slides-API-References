---
title: IBehaviorCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از اثرات رفتار.
type: docs
url: /fa/com.aspose.slides/ibehaviorcollection/
---
**همهٔ رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

نمایش‌دهندهٔ مجموعه‌ای از اثرات رفتار.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک رفتار را در اندیس مشخص شده برمی‌گرداند. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | یک رفتار را در اندیس مشخص شده برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد رفتارها در یک مجموعه را برمی‌گرداند. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | رفتار جدیدی را به یک مجموعه اضافه می‌کند. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | اندیس یک مورد خاص را در List تعیین می‌کند. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | رفتار جدید را در اندیس مشخص شده به مجموعه وارد می‌کند. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | رفتار مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | رفتار را در اندیس مشخص شده از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام رفتارها را از یک مجموعه حذف می‌کند. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

یک رفتار را در اندیس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس رفتاری که باید برگردانده شود. |

**بازگشت:**
[IBehavior](../../com.aspose.slides/ibehavior) - رفتار Animation.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

یک رفتار را در اندیس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس رفتاری که باید برگردانده شود. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد رفتارها در یک مجموعه را برمی‌گرداند. int فقط‌خواندنی.

**بازگشت:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

رفتار جدیدی را به یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای افزودن. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

اندیس یک مورد خاص را در List تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیئی که در List پیدا شود. |

**بازگشت:**
int - اندیس مورد اگر در لیست یافت شود؛ در غیر این صورت -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

رفتار جدید را در اندیس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس که رفتار جدید باید در آن وارد شود. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای وارد کردن. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

رفتار مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای حذف. |

**بازگشت:**
boolean - True اگر رفتار با موفقیت حذف شود boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

رفتار را در اندیس مشخص شده از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس رفتاری که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام رفتارها را از یک مجموعه حذف می‌کند.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیئی که در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود. |

**بازگشت:**
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود؛ در غیر این صورت false.