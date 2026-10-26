---
title: IBehaviorCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من تأثيرات السلوك.
type: docs
url: /ar/com.aspose.slides/ibehaviorcollection/
---
**جميع الواجهات المُنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

يمثل مجموعة من تأثيرات السلوك.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | إرجاع سلوك عند الفهرس المحدد. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | إرجاع سلوك عند الفهرس المحدد. |
| [getCount()](#getCount--) | إرجاع عدد السلوكيات في مجموعة. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | إضافة سلوك جديد إلى مجموعة. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | تحديد فهرس عنصر محدد في القائمة. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | إدراج سلوك جديد إلى مجموعة عند الفهرس المحدد. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | إزالة السلوك المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة سلوك من مجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع السلوكيات من مجموعة. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

إرجاع سلوك عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك المراد إرجاعه. |

**الإرجاع:**
[IBehavior](../../com.aspose.slides/ibehavior) - سلوك الرسوم المتحركة.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

إرجاع سلوك عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك المراد إرجاعه. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

إرجاع عدد السلوكيات في مجموعة. قراءة فقط int.

**الإرجاع:**
int

### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

إضافة سلوك جديد إلى مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإضافته. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

تحديد فهرس عنصر محدد في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن لتحديد موقعه في القائمة. |

**الإرجاع:**
int - فهرس العنصر إذا وجد في القائمة؛ وإلا -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

إدراج سلوك جديد إلى مجموعة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدراج السلوك الجديد. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإدراجه. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

إزالة السلوك المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإزالته. |

**الإرجاع:**
boolean - صحيح إذا تم إزالة السلوك بنجاح boolean

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

إزالة سلوك من مجموعة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك المراد إزالته. |

### clear() {#clear--}
```
public abstract void clear()
```

إزالة جميع السلوكيات من مجموعة.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن لتحديد موقعه في الـ [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - صحيح إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا، خطأ.