---
title: ISequenceCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من السلاسل التفاعلية.
type: docs
url: /ar/com.aspose.slides/isequencecollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

يمثل مجموعة من السلاسل التفاعلية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | إرجاع عدد العناصر في مجموعة غير قابل للكتابة int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | إضافة سلسلة تفاعلية جديدة. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | إزالة السلسلة المحددة من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة السلسلة في الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع السلاسل من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع سلسلة عند الفهرس المحدد. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


إرجاع عدد العناصر في مجموعة غير قابل للكتابة int.

**الإرجاع:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


إضافة سلسلة تفاعلية جديدة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence) - سلسلة جديدة [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


إزالة السلسلة المحددة من مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | السلسلة لإزالتها. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


إزالة السلسلة في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في المجموعة int |

### clear() {#clear--}
```
public abstract void clear()
```


إزالة جميع السلاسل من مجموعة.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


إرجاع سلسلة عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[ISequence](../../com.aspose.slides/isequence) - الكائن [ISequence](../../com.aspose.slides/isequence).