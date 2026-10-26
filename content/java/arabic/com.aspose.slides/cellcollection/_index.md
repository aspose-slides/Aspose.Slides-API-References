---
title: CellCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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
## الطرق

| الدالة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [size()](#size--) | إرجاع عدد الخلايا في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع خلية بناءً على موقعها. |
| [iterator()](#iterator--) | إرجاع تعداد يتجول خلال المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع متكرر جافا للمجموعة بأكملها. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأصلية لـ CellCollection. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصلى لـ CellCollection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


إرجاع كائن Parent_Immediate. IDOMObject للقراءة فقط.

**إرجاع:**
com.aspose.slides.IDOMObject
### size() {#size--}
```
public final int size()
```


إرجاع عدد الخلايا في مجموعة. int للقراءة فقط.

**إرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICell get_Item(int index)
```


إرجاع خلية بناءً على موقعها. [Cell](../../com.aspose.slides/cell) للقراءة فقط.

--------------------

يمكن إرجاع كائن Cell واحد لعدة فهارس في حالة دمج الخلية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**إرجاع:**
[ICell](../../com.aspose.slides/icell)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iterator()
```


إرجاع تعداد يتجول خلال المجموعة.

**إرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICell> iteratorJava()
```


إرجاع متكرر جافا للمجموعة بأكملها.

**إرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICell> - An java.util.Iterator for the entire collection.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


إرجاع الشريحة الأصلية لـ CellCollection. [IBaseSlide](../../com.aspose.slides/ibaseslide) للقراءة فقط.

**إرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


إرجاع العرض التقديمي الأصلي لـ CellCollection. [IPresentation](../../com.aspose.slides/ipresentation) للقراءة فقط.

**إرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | الفهرس الابتدائي في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). boolean للقراءة فقط.

**إرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


إرجاع جذر التزامن. Object للقراءة فقط.

**إرجاع:**
java.lang.Object