---
title: LayoutSlideCollection
second_title: مرجع API لـ Aspose.Slides للغة جافا
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

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد شرائح التخطيط في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد شريحة التخطيط حسب الفهرس. |
| [getByType(byte type)](#getByType-byte-) | يعيد أول شريحة تخطيط من النوع المحدد. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | يزيل تخطيطًا من المجموعة. |
| [removeUnused()](#removeUnused--) | يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides لها false). |
| [iterator()](#iterator--) | يعيد تعدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرِّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان وصول المجموعة متزامنًا (آمن للتعددية). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

يعيد عدد شرائح التخطيط في مجموعة. int للقراءة فقط.

**الإرجاع:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

يعيد شريحة التخطيط حسب الفهرس. [LayoutSlide](../../com.aspose.slides/layoutslide) للقراءة فقط.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

يعيد أول شريحة تخطيط من النوع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | byte | نوع شريحة التخطيط للبحث عنها. |

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) بالنوع المحدد أو null إذا لم يتم العثور على أي تخطيطات.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

يزيل تخطيطًا من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | شريحة التخطيط لإزالتها من المجموعة.

--------------------
1) لتجنب رمي استثناء PptxEditException، تحقق من خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام طريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الكود. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides لها false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

يعيد تعدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

يعيد مكرِّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان وصول المجموعة متزامنًا (آمن للتعددية). boolean للقراءة فقط.

**الإرجاع:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. Object للقراءة فقط.

**الإرجاع:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. IDOMObject للقراءة فقط.

**الإرجاع:**
com.aspose.slides.IDOMObject