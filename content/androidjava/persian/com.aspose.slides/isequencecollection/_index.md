---
title: ISequenceCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مجموعه‌ای از توالی‌های تعاملی را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/isequencecollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

مجموعه‌ای از توالی‌های تعاملی را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر در یک مجموعه را برمی‌گرداند فقط-خواندنی int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | یک توالی تعاملی جدید اضافه می‌کند. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | توالی مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | توالی را در ایندکس مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام توالی‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | توالی را در ایندکس مشخص شده برمی‌گرداند. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد عناصر در یک مجموعه را برمی‌گرداند فقط-خواندنی int.

**بازگشت:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


یک توالی تعاملی جدید اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | شی Shape [IShape](../../com.aspose.slides/ishape) |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence) - دنباله جدید [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


توالی مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | دنباله برای حذف |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


توالی را در ایندکس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصر در مجموعه int |

### clear() {#clear--}
```
public abstract void clear()
```


تمام توالی‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


توالی را در ایندکس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصر |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence) - شی [ISequence](../../com.aspose.slides/isequence)