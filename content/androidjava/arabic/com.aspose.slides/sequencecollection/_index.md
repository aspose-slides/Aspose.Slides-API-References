---
title: SequenceCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من السلاسل التفاعلية.
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

يمثل مجموعة من السلاسل التفاعلية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يعيد عدد العناصر في مجموعة عدد صحيح للقراءة فقط. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | إضافة سلسلة تفاعلية جديدة. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | يزيل السلسلة المحددة من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل السلسلة في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع السلاسل من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد تسلسلًا في الفهرس المحدد. |
| [iterator()](#iterator--) | يعيد مُعددًا يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر java للمجموعة بأكملها. |
### getCount() {#getCount--}
```
public final int getCount()
```


يعيد عدد العناصر في مجموعة عدد صحيح للقراءة فقط.

**القيمة المرتجعة:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


إضافة سلسلة تفاعلية جديدة. قابل للقراءة والكتابة [Sequence](../../com.aspose.slides/sequence).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**القيمة المرتجعة:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


يزيل السلسلة المحددة من مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | السلسلة التي سيتم إزالتها. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


يزيل السلسلة في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلسلة التي يجب حذفها. |

### clear() {#clear--}
```
public final void clear()
```


يزيل جميع السلاسل من مجموعة.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


يعيد تسلسلًا في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**القيمة المرتجعة:**
[ISequence](../../com.aspose.slides/isequence) - الكائن [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


يعيد مُعددًا يمر عبر المجموعة.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator يمكن استخدامه للمرور عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


يعيد مكرّر java للمجموعة بأكملها.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator للمجموعة بأكملها.