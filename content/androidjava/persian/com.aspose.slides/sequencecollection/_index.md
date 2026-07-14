---
title: SequenceCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایندهٔ مجموعه‌ای از توالی‌های تعاملی.
type: docs
url: /fa/com.aspose.slides/sequencecollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

نماینده‌ی مجموعه‌ای از توالی‌های تعاملی است.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر موجود در یک مجموعه را بر می‌گرداند فقط-خواندنی int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | یک توالی تعاملی جدید را اضافه می‌کند. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | دنباله‌ی مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | دنباله را در شاخص مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام دنباله‌ها را از یک مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | دنباله‌ای را در شاخص مشخص‌شده بر می‌گرداند. |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه پیمایش می‌کند را بر می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه را بر می‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر موجود در یک مجموعه را بر می‌گرداند فقط-خواندنی int.

**باز می‌گردد:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

یک توالی تعاملی جدید را اضافه می‌کند. قابل-نوشتن [Sequence](../../com.aspose.slides/sequence).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**باز می‌گردد:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

دنباله‌ی مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | دنباله برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

دنباله را در شاخص مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص یک دنباله که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام دنباله‌ها را از یک مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

دنباله‌ای را در شاخص مشخص‌شده بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص عنصر. |

**باز می‌گردد:**
[ISequence](../../com.aspose.slides/isequence) - شیٔ [ISequence](../../com.aspose.slides/isequence).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

یک شمارشگر که در مجموعه پیمایش می‌کند را بر می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

یک java iterator برای کل مجموعه را بر می‌گرداند.

**باز می‌گردد:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - یک java.util.Iterator برای کل مجموعه.