---
title: LayoutSlideCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: يمثل فئة أساسية لمجموعة من شرائح التخطيط.
type: docs
url: /ar/com.aspose.slides/layoutslidecollection/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

يمثل فئة أساسية لمجموعة من شرائح التخطيط.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [size()](#size--) | Returns the number of layout slides in a collection. |
| [get_Item(int index)](#get-Item-int-) | Returns the layout slide by index. |
| [getByType(byte type)](#getByType-byte-) | Returns the first layout slide of specified type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Removes a layout from the collection. |
| [removeUnused()](#removeUnused--) | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

يرجع عدد شرائح التخطيط في مجموعة. للقراءة فقط int.

**القيمة المرجعة:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

يرجع شريحة التخطيط حسب الفهرس. للقراءة فقط [LayoutSlide](../../com.aspose.slides/layoutslide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

يرجع أول شريحة تخطيط من النوع المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| type | byte | نوع شريحة التخطيط للبحث عنها. |

**القيمة المرجعة:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) بالنوع المحدد أو null إذا لم يتم العثور على تخطيطات.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

يزيل تخطيطًا من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | شريحة التخطيط التي سيتم إزالتها من المجموعة.

--------------------

1) لتجنب رمي PptxEditException تحقق من خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام طريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الكود. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides لها false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

يرجع كائن تعداد يتنقل عبر المجموعة.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

يرجع مكرِّر java للمجموعة بأكملها.

**القيمة المرجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة المستهدفة. |
| index | int | الفهرس الابتدائي في المصفوفة المستهدفة. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخلThreads). للقراءة فقط boolean.

**القيمة المرجعة:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. للقراءة فقط Object.

**القيمة المرجعة:**  
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject