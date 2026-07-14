---
title: BehaviorPropertyCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: ویژگی‌های زمان‌بندی رفتار افکت را نمایندگی می‌کند.
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

نمایش می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد ویژگی‌های ذخیره‌شده در مجموعه را باز می‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقداری را باز می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | یک ویژگی جدید را به مجموعه اضافه می‌کند. |
| [add(String propertyValue)](#add-java.lang.String-) | یک ویژگی جدید را به مجموعه اضافه می‌کند. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | اندیس یک مورد خاص را در لیست تعیین می‌کند. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | اندیس یک مورد خاص را بر اساس مقدار ویژگی در لیست تعیین می‌کند. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | یک ویژگی جدید را در اندیس مشخص شده به مجموعه وارد می‌کند. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | ویژگی جدید (با مقدار ویژگی مشخص شده) را در اندیس مشخص شده به مجموعه وارد می‌کند. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک اندیس خاص آرایه. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | ویژگی مشخص‌شده را از مجموعه حذف می‌کند. |
| [remove(String propertyValue)](#remove-java.lang.String-) | ویژگی مشخص‌شده را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | ویژگی را در اندیس مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام ویژگی‌ها را از مجموعه حذف می‌کند. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است. |
| [get_Item(int index)](#get-Item-int-) | ویژگی را در اندیس مشخص‌شده باز می‌گرداند. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | ویژگی را در اندیس مشخص‌شده تنظیم می‌کند. |
| [iterator()](#iterator--) | یک enumerator که در مجموعه تکرار می‌کند را باز می‌گرداند. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه باز می‌گرداند. |

### size() {#size--}
```
public final int size()
```


تعداد ویژگی‌های ذخیره‌شده در مجموعه را باز می‌گرداند. فقط‌خواندنی int.

**باز می‌گرداند:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


مقداری را باز می‌گرداند که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی است. فقط‌خواندنی boolean.

**باز می‌گرداند:**
boolean - اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌خواندنی باشد true؛ در غیر این صورت false.

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


اندیس یک مورد خاص را در لیست تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | شیء برای یافتن در لیست. |

**باز می‌گرداند:**
int - اندیس مورد اگر در لیست یافت شود؛ در غیر این صورت، -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


اندیس یک مورد خاص را بر اساس مقدار ویژگی در لیست تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی |

**باز می‌گرداند:**
int - اندیس ویژگی با مقدار مشخص‌شده

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


یک ویژگی جدید را در اندیس مشخص‌شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس که ویژگی جدید باید در آن وارد شود. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای افزودن. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


ویژگی جدید (با مقدار ویژگی مشخص شده) را در اندیس مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس که ویژگی جدید باید در آن وارد شود. |
| propertyValue | java.lang.String | مقدار ویژگی برای افزودن. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک آرایه کپی می‌کند، شروع از یک اندیس خاص آرایه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | آرایه تک‌بعدی که مقصد عناصری است که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی می‌شوند. آرایه باید دارای اندیس صفر-پایه باشد. |
| arrayIndex | int | اندیس صفر-پایه در آرایه که از آن کپی شروع می‌شود. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


ویژگی مشخص‌شده را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | ویژگی برای حذف. |

**باز می‌گرداند:**
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

**باز می‌گرداند:**
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

**باز می‌گرداند:**
boolean - اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود true؛ در غیر این صورت false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| propertyValue | java.lang.String | مقدار ویژگی برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**باز می‌گرداند:**
boolean - اگر propertyValue در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود true؛ در غیر این صورت false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


ویژگی را در اندیس مشخص‌شده باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ویژگی برای بازگشت. |

**باز می‌گرداند:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - ویژگی رفتار انیمیشن.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


ویژگی را در اندیس مشخص‌شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس ویژگی برای تنظیم. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


یک enumerator که در مجموعه تکرار می‌کند را باز می‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**باز می‌گرداند:**
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

**باز می‌گرداند:**
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

**باز می‌گرداند:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


یک iterator جاوا برای کل مجموعه باز می‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - یک java.util.Iterator برای کل مجموعه.