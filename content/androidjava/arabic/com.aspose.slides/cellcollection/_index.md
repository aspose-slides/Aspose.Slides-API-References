---
title: CellCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من الخلايا.
type: docs
url: /ar/com.aspose.slides/cellcollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), com.aspose.slides.IDOMObject  
```
public abstract class CellCollection implements ICellCollection, IDOMObject
```

يمثل مجموعة من الخلايا.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | يرجع عدد الخلايا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع خلية بحسب موقعها. |
| [iterator()](#iterator--) | يرجع كائنًا متسلسلًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّرًا من نوع java للمجموعة بأكملها. |
| [getSlide()](#getSlide--) | يرجع الشريحة الأصلية لـ CellCollection. |
| [getPresentation()](#getPresentation--) | يرجع العرض التقديمي الأصلي لـ CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر المزامنة. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject

### size() {#size--}
```
public final int size()
```

يرجع عدد الخلايا في المجموعة. int للقراءة فقط.

**القيمة المرجعة:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```

يرجع خلية بحسب موقعها. [Cell](../../com.aspose.slides/cell) للقراءة فقط.

--------------------

يمكن إرجاع كائن Cell واحد لعدة مؤشرات في حالة دمج الخلية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```

يرجع كائنًا متسلسلًا يتنقل عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```

يرجع مكرّرًا من نوع java للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - java.util.Iterator للمجموعة بأكملها.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية لـ CellCollection. [IBaseSlide](../../com.aspose.slides/ibaseslide) للقراءة فقط.

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأصلي لـ CellCollection. [IPresentation](../../com.aspose.slides/ipresentation) للقراءة فقط.

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). boolean للقراءة فقط.

**القيمة المرجعة:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر المزامنة. Object للقراءة فقط.

**القيمة المرجعة:**  
java.lang.Object