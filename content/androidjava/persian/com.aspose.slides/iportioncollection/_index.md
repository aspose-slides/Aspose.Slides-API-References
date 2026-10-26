---
title: IPortionCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از بخش‌ها.
type: docs
url: /fa/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

نمایانگر مجموعه‌ای از بخش‌ها.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در ایندکس مشخص‌شده دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر واقعی موجود در مجموعه را دریافت می‌کند. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | یک Portion را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | ایندکس یک Portion خاص را در مجموعه تعیین می‌کند. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | یک Portion را در ایندکس مشخص‌شده در مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

عنصر را در ایندکس مشخص‌شده دریافت می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصر واقعی موجود در مجموعه را دریافت می‌کند. int فقط-خواندنی.

**بازگشت:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

یک Portion را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionی که باید به انتهای مجموعه اضافه شود. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

ایندکس یک Portion خاص را در مجموعه تعیین می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portionی که باید در مجموعه پیدا شود. |

**بازگشت:**
int - ایندکس آیتم اگر در مجموعه یافت شود؛ در غیر اینصورت، -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

یک Portion را در ایندکس مشخص‌شده در مجموعه وارد می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنایی که Portion باید در آن وارد شود. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionی که باید وارد شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیئی که باید در [IGenericCollection](../../com.aspose.slides/igenericcollection) پیدا شود. |

**بازگشت:**
boolean - true اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر اینصورت، false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیئی که باید از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود. |

**بازگشت:**
boolean - true اگر آیتم با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود؛ در غیر اینصورت، false. این متد همچنین false برمی‌گرداند اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در ایندکس مشخص‌شده از مجموعه حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنایی عنصری که باید حذف شود. |