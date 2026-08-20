---
title: IPortionCollection
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل مجموعة من الأجزاء.
type: docs
url: /ar/com.aspose.slides/iportioncollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

يمثل مجموعة من الأجزاء.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | يضيف جزءًا إلى نهاية المجموعة. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | يحدد فهرس جزء محدد في المجموعة. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | يدخل جزءًا في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | يزيل أول حدث لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```


يحصل على عدد العناصر الفعلية الموجودة في المجموعة. int للقراءة فقط.

**Returns:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```


يضيف جزءًا إلى نهاية المجموعة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | الجزء الذي سيُضاف إلى نهاية المجموعة. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```


يحدد فهرس جزء محدد في المجموعة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الجزء لتحديد موقعه في المجموعة. |

**Returns:**
int - فهرس العنصر إذا وجد في المجموعة؛ وإلا -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```


يدخل جزءًا في المجموعة عند الفهرس المحدد.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدخال الجزء عنده. |
| value | [IPortion](../../com.aspose.slides/iportion) | الجزء الذي سيُدخل. |

### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع العناصر من المجموعة.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```


يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن لتحديد موقعه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - صحيح إذا وجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا خطأ.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```


يزيل أول حدث لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن لإزالته من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - صحيح إذا تم إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا خطأ. تُعيد هذه الطريقة أيضًا خطأ إذا لم يُعثر على العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection) الأصلي.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد من المجموعة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |