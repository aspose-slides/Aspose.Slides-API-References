---
title: IPortionCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل مجموعة من الأجزاء.
type: docs
url: /ar/com.aspose.slides/iportioncollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

يمثل مجموعة من الأجزاء.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | يضيف جزءًا إلى نهاية المجموعة. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | يحدد فهرس جزء معين في المجموعة. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | يدخل جزءًا في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | يزيل أول حدوث لكائن معين من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قيمة للقراءة فقط int.

**القيمة المرجعة:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

يضيف جزءًا إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | الجزء الذي سيُضاف إلى نهاية المجموعة. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

يحدد فهرس جزء معين في المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الجزء للعثور عليه في المجموعة. |

**القيمة المرجعة:**
int - فهرس العنصر إذا وجد في المجموعة؛ وإلا -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

يدخل جزءًا في المجموعة عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر الذي يجب إدخال الجزء عنده. |
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

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن للعثور عليه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - true إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

يزيل أول حدوث لكائن معين من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن للإزالة من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في الأصل [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر الذي سيُزال. |