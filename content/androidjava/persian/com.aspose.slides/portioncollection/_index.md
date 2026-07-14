---
title: PortionCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نماینده یک مجموعه از بخش‌ها.
type: docs
url: /fa/com.aspose.slides/portioncollection/
---
**وارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

نماینده‌ی یک مجموعه از بخش‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصری را که در واقع در مجموعه موجود هستند، برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است یا خیر. |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده است، برمی‌گرداند. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | عنصری را که در ایندکس مشخص شده است، برمی‌گرداند. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | یک Portion را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | ایندکس یک آیتم خاص را در List تعیین می‌کند. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | یک Portion را در ایندکس مشخص شده به مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | تعیین می‌کند که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، از یک ایندکس آرایه مشخص شروع می‌شود. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در ایندکس مشخص شده از مجموعه است، حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که در طول مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصری را که در واقع در مجموعه موجود هستند، برمی‌گرداند. فقط‌خواندنی int.

**بازگرداندن:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. فقط‌خواندنی boolean.

**بازگرداندن:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی باشد؛ در غیر این صورت، false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

عنصری را که در ایندکس مشخص شده است، برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

عنصری را که در ایندکس مشخص شده است، برمی‌گرداند.

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
| value | [IPortion](../../com.aspose.slides/iportion) | Portionی که باید به انتهای مجموعه اضافه شود. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

ایندکس یک آیتم خاص را در List تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیء‌ای که باید در List جستجو شود. |

**بازگرداندن:**
int - ایندکس آیتم اگر در لیست یافت شود؛ در غیر این صورت، -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

یک Portion را در ایندکس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفرمبنی که Portion باید در آن قرار گیرد. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portionی که باید درج شود. |
### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

تعیین می‌کند که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیء‌ای که باید در [IGenericCollection](../../com.aspose.slides/igenericcollection) جستجو شود. |

**بازگرداندن:**
boolean - true اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، از یک ایندکس آرایه مشخص شروع می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | آرایهٔ تک‌بعدی که مقصد عناصر کپی شده از [IGenericCollection](../../com.aspose.slides/igenericcollection) است. آرایه باید ایندکس صفرمبنی داشته باشد. |
| arrayIndex | int | ایندکس صفرمبنی در آرایه که کپی از آنجا شروع می‌شود. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیء‌ای که باید از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شود. |

**بازگرداندن:**
boolean - true اگر آیتم با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شده باشد؛ در غیر این صورت، false. این متد همچنین false برمی‌گرداند اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصری را که در ایندکس مشخص شده از مجموعه است، حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفرمبنی عنصری که باید حذف شود. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

یک enumerator برمی‌گرداند که در طول مجموعه تکرار می‌کند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگرداندن:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - یک java.util.Iterator برای کل مجموعه.