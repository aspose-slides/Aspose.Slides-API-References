---
title: BehaviorCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش مجموعه‌ای از اثرات رفتار.
type: docs
url: /fa/com.aspose.slides/behaviorcollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

نمایش مجموعه‌ای از اثرات رفتار.

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد رفتارها در یک مجموعه را برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را بر می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | یک رفتار جدید را به مجموعه اضافه می‌کند. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | شاخص یک مورد خاص در لیست را تعیین می‌کند. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | یک رفتار جدید را در یک مجموعه در شاخص مشخص درج می‌کند. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک شاخص آرایه خاص. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | رفتار مشخص‌شده را از یک مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | رفتار را از یک مجموعه در شاخص مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام رفتارها را از یک مجموعه حذف می‌کند. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [get_Item(int index)](#get-Item-int-) | یک رفتار را در شاخص مشخص برمی‌گرداند. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | یک رفتار را در شاخص مشخص تنظیم می‌کند. |
| [iterator()](#iterator--) | یک enumerator را برمی‌گرداند که در مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک java iterator برای کل مجموعه برمی‌گرداند. |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد رفتارها در یک مجموعه را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری را بر می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. فقط‌خواندنی boolean.

**بازگشت:**  
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی باشد؛ در غیر این صورت false.

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

یک رفتار جدید را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای افزودن. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

شاخص یک مورد خاص را در لیست تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیئی که در لیست باید یافت شود. |

**بازگشت:**  
int - شاخص مورد اگر در لیست یافت شود؛ در غیر این صورت -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

یک رفتار جدید را در یک مجموعه در شاخص مشخص درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخصی که رفتار جدید باید در آن درج شود. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | رفتار برای درج. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک شاخص آرایه خاص.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | آرایهٔ یک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی شده‌اند. آرایه باید دارای ایندکس صفر مبنا باشد. |
| arrayIndex | int | ایندکس صفر مبنا در آرایه که کپی از آن شروع می‌شود. |

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

رفتار را از یک مجموعه در شاخص مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص رفتار برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام رفتارها را از یک مجموعه حذف می‌کند.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | شیئی که در [IGenericCollection](../../com.aspose.slides/igenericcollection) باید یافت شود. |

**بازگشت:**  
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

یک رفتار را در شاخص مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص رفتار برای برگرداندن. |

**بازگشت:**  
[IBehavior](../../com.aspose.slides/ibehavior) - رفتار انیمیشن.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

یک رفتار را در شاخص مشخص تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص رفتار برای برگرداندن. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

یک enumerator را برمی‌گرداند که در مجموعه تکرار می‌کند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

یک java iterator برای کل مجموعه برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - یک java.util.Iterator برای کل مجموعه.