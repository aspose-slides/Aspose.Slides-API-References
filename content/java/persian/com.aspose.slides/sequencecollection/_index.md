---
title: SequenceCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر مجموعه‌ای از توالی‌های تعاملی است.
type: docs
url: /fa/com.aspose.slides/sequencecollection/
---
**وارثی:**  
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی شده:**  
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)  
```
public class SequenceCollection implements ISequenceCollection
```

نمایانگر مجموعه‌ای از توالی‌های تعاملی است.

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر موجود در یک مجموعه را برمی‌گرداند فقط‌خواندنی int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | یک توالی تعاملی جدید اضافه می‌کند. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | توالی مشخص شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | توالی را در ایندکس مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام توالی‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | دنباله‌ای را در ایندکس مشخص شده برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده (enumerator) که در مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر موجود در یک مجموعه را برمی‌گرداند فقط‌خواندنی int.

**بازگشت:**  
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

یک توالی تعاملی جدید اضافه می‌کند. قابل‌خواندن/قابل‌نوشتن [Sequence](../../com.aspose.slides/sequence).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

توالی مشخص شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | دنباله‌ای که باید حذف شود. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

توالی را در ایندکس مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس توالی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام توالی‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

دنباله‌ای را در ایندکس مشخص شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عنصر. |

**بازگشت:**
[ISequence](../../com.aspose.slides/isequence) - شی [ISequence](../../com.aspose.slides/isequence)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

یک شمارنده (enumerator) که در مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - یک java.util.Iterator برای کل مجموعه.