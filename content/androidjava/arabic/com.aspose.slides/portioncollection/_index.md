---
title: PortionCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأجزاء.
type: docs
url: /ar/com.aspose.slides/portioncollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)  
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

يمثل مجموعة من الأجزاء.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | يحصل على العنصر في الفهرس المحدد. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | يضيف Portion إلى نهاية المجموعة. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | يحدد الفهرس لعنصر محدد في القائمة. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | يدخل Portion في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة محدد. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | يزيل أول ظهور لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [iterator()](#iterator--) | يرجع تعدادًا يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع معدّد java للمجموعة بأكملها. |
### getCount() {#getCount--}
```
public final int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**  
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. boolean للقراءة فقط.

**القيمة المرجعة:**  
boolean - صحيح إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا خطأ.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**  
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

يحصل على العنصر في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

يضيف Portion إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | الـ Portion لإضافته إلى نهاية المجموعة. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

يحدد الفهرس لعنصر محدد في القائمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن لتحديد موقعه في القائمة. |

**القيمة المرجعة:**  
int - فهرس العنصر إذا وجد في القائمة؛ وإلا -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

يدخل Portion في المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم عنده إدخال Portion. |
| value | [IPortion](../../com.aspose.slides/iportion) | الـ Portion لإدخاله. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن لتحديد موقعه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**  
boolean - صحيح إذا تم العثور على العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا خطأ.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة محدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | المصفوفة الأحادية الأبعاد التي هي وجهة العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس الصفري في المصفوفة الذي يبدأ عنده النسخ. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

يزيل أول ظهور لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | الكائن لإزالته من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**  
boolean - صحيح إذا تمت إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا خطأ. كما أن هذه الطريقة تُعيد خطأ إذا لم يُعثر على العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection) الأصلي.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

يرجع تعدادًا يمر عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator يمكن استخدامه للمرور عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

يرجع معدّد java للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator للمجموعة بأكملها.