---
title: ISequenceCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش‌دهنده مجموعه‌ای از توالی‌های تعاملی.
type: docs
url: /fa/com.aspose.slides/isequencecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

نمایش‌دهنده مجموعه‌ای از توالی‌های تعاملی.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر در یک مجموعه را برمی‌گرداند int فقط-خواندنی. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | دنباله تعاملی جدیدی اضافه می‌کند. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | دنباله مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | دنباله را در ایندکس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام دنباله‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | دنباله‌ای را در ایندکس مشخص برمی‌گرداند. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصر در یک مجموعه را برمی‌گرداند int فقط-خواندنی.

**بازگشت:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

دنباله تعاملی جدیدی اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | شیء شکل [IShape](../../com.aspose.slides/ishape) |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence) - دنباله جدید [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

دنباله مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | دنباله‌ای که باید حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

دنباله را در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر در مجموعه int |

### clear() {#clear--}
```
public abstract void clear()
```

تمام دنباله‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

دنباله‌ای را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس عنصر. |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence) - شیء [ISequence](../../com.aspose.slides/isequence).