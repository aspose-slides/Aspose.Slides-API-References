---
title: BehaviorCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از اثرات رفتار.
type: docs
url: /fa/com.aspose.slides/behaviorcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
``` 
public class BehaviorCollection implements IBehaviorCollection 
```

نمایانگر مجموعه‌ای از اثرات رفتار است.
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد رفتارها را در یک مجموعه برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را برمی‌گرداند که نشان می‌دهد [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | رفتار جدیدی را به یک مجموعه اضافه می‌کند. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | شاخص یک مورد خاص را در List تعیین می‌کند. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | رفتار جدیدی را در ایندکس مشخص به مجموعه وارد می‌کند. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک ایندکس خاص Array. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | رفتار مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | رفتار را از یک مجموعه در ایندکس مشخص حذف می‌کند. |
| [clear()](#clear--) | همه رفتارها را از یک مجموعه حذف می‌کند. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [get_Item(int index)](#get-Item-int-) | رفتار را در ایندکس مشخص برمی‌گرداند. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | رفتار را در ایندکس مشخص تنظیم می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |
### getCount() {#getCount--}
```
public final int getCount()
```


تعداد رفتارها را در یک مجموعه برمی‌گرداند. int فقط-خواندنی.

**بازگشت:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


مقداری را برمی‌گرداند که نشان می‌دهد [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است. boolean فقط-خواندنی.

**بازگشت:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر این صورت، false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


رفتار جدیدی را به یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای افزودن. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


شاخص یک مورد خاص را در List تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیء برای یافتن در List. |

**بازگشت:**
int - شاخص item اگر در لیست یافت شود؛ در غیر این صورت، -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


رفتار جدیدی را در ایندکس مشخص به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس که رفتار جدید باید در آن وارد شود. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای وارد کردن. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک ایندکس خاص Array.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Array تک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی شده‌اند. Array باید اندیس‌گذاری صفر-پایه داشته باشد. |
| arrayIndex | int | ایندکس صفر-پایه در array که کپی از آن آغاز می‌شود. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


رفتار مشخص‌شده را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای حذف. |

**بازگشت:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


رفتار را از یک مجموعه در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس رفتار برای حذف. |

### clear() {#clear--}
```
public final void clear()
```


همه رفتارها را از یک مجموعه حذف می‌کند.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیء برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - true اگر item در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```


رفتار را در ایندکس مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس رفتار برای برگرداندن. |

**بازگشت:**
[IBehavior](../../com.aspose.slides/ibehavior) - رفتار انیمیشن.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```


رفتار را در ایندکس مشخص تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس رفتار که باید تنظیم شود. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


یک enumerator برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - یک IGenericEnumerator که می‌توان برای پیمایش مجموعه استفاده کرد.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - یک java.util.Iterator برای کل مجموعه.