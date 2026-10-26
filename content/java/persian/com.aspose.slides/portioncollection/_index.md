---
title: PortionCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک مجموعه از بخش‌ها است.
type: docs
url: /fa/com.aspose.slides/portioncollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

نمایانگر یک مجموعه از بخش‌ها است.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصری که واقعا در مجموعه موجود است را برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا خیر. |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | یک Portion را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | ایندکس یک مورد خاص در List را تعیین می‌کند. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | یک Portion را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص شده از مجموعه را حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری که واقعا در مجموعه موجود است را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر این صورت false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

یک Portion را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionی که به انتهای مجموعه اضافه خواهد شد. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

ایندکس یک مورد خاص در List را تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیئی که در List جستجو می‌شود. |

**بازگشت:**
int - ایندکس مورد اگر در لیست یافت شود؛ در غیر این صورت -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

یک Portion را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که Portion باید در آن وارد شود. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion برای درج. |
### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیئی که در [IGenericCollection](../../com.aspose.slides/igenericcollection) جستجو می‌شود. |

**بازگشت:**
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | آرایهٔ یک-بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی می‌شوند. آرایه باید ایندکس صفر-پایه داشته باشد. |
| arrayIndex | int | ایندکس صفر-پایه در آرایه که از آن کپی آغاز می‌شود. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیئی که از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌شود. |

**بازگشت:**
boolean - true اگر مورد با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شده باشد؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای عنصری که باید حذف شود. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

یک enumerator که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - An java.util.Iterator for the entire collection.