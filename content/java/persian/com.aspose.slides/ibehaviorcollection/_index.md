---
title: IBehaviorCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از اثرات رفتاری.
type: docs
url: /fa/com.aspose.slides/ibehaviorcollection/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

نمایش‌دهندهٔ مجموعه‌ای از اثرات رفتاری.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک رفتار را در فهرست مشخص شده برمی‌گرداند. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | یک رفتار را در فهرست مشخص شده برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد رفتارها در یک مجموعه را برمی‌گرداند. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | رفتار جدیدی را به یک مجموعه اضافه می‌کند. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | شاخص یک مورد خاص را در لیست تعیین می‌کند. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | رفتار جدیدی را در فهرست مشخص شده به مجموعه وارد می‌کند. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | رفتار مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | رفتار را از یک مجموعه در فهرست مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام رفتارها را از یک مجموعه حذف می‌کند. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

یک رفتار را در فهرست مشخص شده برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شاخص رفتاری که باید بازگردانده شود. |

**Returns:**
[IBehavior](../../com.aspose.slides/ibehavior) - رفتار انیمیشن.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

یک رفتار را در فهرست مشخص شده برمی‌گرداند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شاخص رفتاری که باید بازگردانده شود. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد رفتارها در یک مجموعه را برمی‌گرداند. فقط-خواندنی int.

**Returns:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

یک رفتار جدید به یک مجموعه اضافه می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتاری که باید اضافه شود. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

شاخص یک مورد خاص را در لیست تعیین می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیء مورد جستجو در لیست. |

**Returns:**
int - شاخص مورد اگر در لیست یافت شود؛ در غیر این صورت -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

رفتار جدیدی را در فهرست مشخص شده به مجموعه وارد می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شاخصی که رفتار جدید باید در آن درج شود. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتاری که باید وارد شود. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

رفتار مشخص‌شده را از یک مجموعه حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتاری که باید حذف شود. |

**Returns:**
boolean - True اگر رفتار با موفقیت حذف شود boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

رفتار را از یک مجموعه در فهرست مشخص شده حذف می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | شاخص رفتاری که باید حذف شود. |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیء مورد جستجو در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت false.