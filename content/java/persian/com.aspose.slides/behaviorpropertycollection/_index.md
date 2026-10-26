---
title: BehaviorPropertyCollection
second_title: Aspose.Slides برای Java مرجع API
description: نماینده ویژگی‌های زمان‌بندی برای رفتار اثر.
type: docs
url: /fa/com.aspose.slides/behaviorpropertycollection/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

نمایش‌دهنده ویژگی‌های زمان‌بندی برای رفتار اثر.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد ویژگی‌های ذخیره‌شده در مجموعه را برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | یک مقدار دریافت می‌کند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط خواندنی است. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | یک ویژگی جدید به مجموعه اضافه می‌کند. |
| [add(String propertyValue)](#add-java.lang.String-) | یک ویژگی جدید به مجموعه اضافه می‌کند. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | اندیس یک مورد خاص در List را تعیین می‌کند. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | اندیس یک مورد خاص را بر اساس مقدار ویژگی در List تعیین می‌کند. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | یک ویژگی جدید را در مجموعه در اندیس مشخص شده درج می‌کند. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | یک ویژگی جدید (با مقدار ویژگی مشخص‌شده) را در مجموعه در اندیس مشخص شده درج می‌کند. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، آغاز از یک اندیس خاص آرایه. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | ویژگی مشخص‌شده را از مجموعه حذف می‌کند. |
| [remove(String propertyValue)](#remove-java.lang.String-) | ویژگی مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | ویژگی را در اندیس مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام ویژگی‌ها را از مجموعه حذف می‌کند. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [get_Item(int index)](#get-Item-int-) | یک ویژگی را در اندیس مشخص‌شده برمی‌گرداند. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | یک ویژگی را در اندیس مشخص‌شده تنظیم می‌کند. |
| [iterator()](#iterator--) | یک شمارنده (enumerator) که مجموعه را پیمایش می‌کند را برمی‌گرداند. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد ویژگی‌های ذخیره‌شده در مجموعه را برمی‌گرداند. int فقط خواندنی.

**بازگشت:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

یک مقدار دریافت می‌کند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط خواندنی است. boolean فقط خواندنی.

**بازگشت:**
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی باشد؛ در غیر این صورت، false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

یک ویژگی جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای افزودن. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

یک ویژگی جدید به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای افزودن. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

اندیس یک مورد خاص در List را تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | شی برای یافتن در List. |

**بازگشت:**
int - اندیس مورد اگر در لیست یافت شود؛ در غیر این صورت، -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

اندیس یک مورد خاص را بر اساس مقدار ویژگی در List تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی |

**بازگشت:**
int - اندیس ویژگی با مقدار مشخص‌شده
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

یک ویژگی جدید را در مجموعه در اندیس مشخص شده درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس که ویژگی جدید باید در آن درج شود. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای افزودن. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

یک ویژگی جدید (با مقدار ویژگی مشخص‌شده) را در مجموعه در اندیس مشخص شده درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس که ویژگی جدید باید در آن درج شود. |
| propertyValue | java.lang.String | مقدار ویژگی برای افزودن. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، آغاز از یک اندیس خاص آرایه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | آرایه یک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی شده‌اند. آرایه باید ایندکس صفر-پایه داشته باشد. |
| arrayIndex | int | ایندکس صفر-پایه در آرایه که کپی از آن شروع می‌شود. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

ویژگی مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای حذف. |

**بازگشت:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

ویژگی مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای حذف. |

**بازگشت:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ویژگی را در اندیس مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ویژگی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```

تمام ویژگی‌ها را از مجموعه حذف می‌کند.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - true اگر propertyValue در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت، false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

یک ویژگی را در اندیس مشخص‌شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ویژگی برای بازگرداندن. |

**بازگشت:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - ویژگی رفتار انیمیشن.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

یک ویژگی را در اندیس مشخص‌شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ویژگی برای بازگرداندن. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

یک شمارنده (enumerator) که مجموعه را پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**بازگشت:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**بازگشت:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**بازگشت:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - یک java.util.Iterator برای کل مجموعه.