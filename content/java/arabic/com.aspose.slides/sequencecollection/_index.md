---
title: SequenceCollection
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل مجموعة من التسلسلات التفاعلية.
type: docs
url: /ar/com.aspose.slides/sequencecollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

يمثل مجموعة من التسلسلات التفاعلية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يرجع عدد العناصر في مجموعة للقراءة فقط int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | أضف تسلسلًا تفاعليًا جديدًا. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | يزيل التسلسل المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل التسلسل في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع التسلسلات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يرجع تسلسلًا في الفهرس المحدد. |
| [iterator()](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرّر java للمجموعة بأكملها. |
### getCount() {#getCount--}
```
public final int getCount()
```

يرجع عدد العناصر في مجموعة للقراءة فقط int.

**الإرجاع:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

أضف تسلسلًا تفاعليًا جديدًا. للقراءة والكتابة [Sequence](../../com.aspose.slides/sequence).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

يزيل التسلسل المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | التسلسل المراد إزالته. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل التسلسل في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس التسلسل الذي يجب حذفه. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع التسلسلات من مجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

يرجع تسلسلًا في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence) - الكائن [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

يرجع مكرّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator للمجموعة بأكملها.