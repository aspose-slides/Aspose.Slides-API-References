---
title: ISequenceCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل مجموعة من السلاسل التفاعلية.
type: docs
url: /ar/com.aspose.slides/isequencecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

يمثل مجموعة من السلاسل التفاعلية.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | إرجاع عدد العناصر في مجموعة (قراءة فقط) int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | إضافة تسلسل تفاعلي جديد. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | إزالة التسلسل المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة التسلسل عند الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع التسلسلات من مجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع تسلسل في الفهرس المحدد. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

إرجاع عدد العناصر في مجموعة (قراءة فقط) int.

**القيمة المرجعة:**
int

### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

إضافة تسلسل تفاعلي جديد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | كائن الشكل [IShape](../../com.aspose.slides/ishape) |

**القيمة المرجعة:**
[ISequence](../../com.aspose.slides/isequence) - تسلسل جديد [ISequence](../../com.aspose.slides/isequence)

### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

إزالة التسلسل المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | التسلسل لإزالته. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

إزالة التسلسل عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر في المجموعة int |

### clear() {#clear--}
```
public abstract void clear()
```

إزالة جميع التسلسلات من مجموعة.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

إرجاع تسلسل في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**القيمة المرجعة:**
[ISequence](../../com.aspose.slides/isequence) - الكائن [ISequence](../../com.aspose.slides/isequence).