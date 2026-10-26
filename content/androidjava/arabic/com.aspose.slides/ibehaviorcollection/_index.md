---
title: IBehaviorCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة من تأثيرات السلوك.
type: docs
url: /ar/com.aspose.slides/ibehaviorcollection/
---
**جميع الواجهات المنفذة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

يمثل مجموعة من تأثيرات السلوك.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد سلوكًا في الفهرس المحدد. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | يعيد سلوكًا في الفهرس المحدد. |
| [getCount()](#getCount--) | يعيد عدد السلوكيات في مجموعة. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | إضافة سلوك جديد إلى مجموعة. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | يحدد فهرس عنصر معين في القائمة. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | يدخل سلوكًا جديدًا إلى مجموعة في الفهرس المحدد. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | يزيل السلوك المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل سلوكًا من مجموعة في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع السلوكيات من مجموعة. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

يعيد سلوكًا في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس سلوك لإرجاعه. |

**القيمة المرجعة:**
[IBehavior](../../com.aspose.slides/ibehavior) - سلوك الرسوم المتحركة.

### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

يعيد سلوكًا في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس سلوك لإرجاعه. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

يعيد عدد السلوكيات في مجموعة. int للقراءة فقط.

**القيمة المرجعة:**
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

يحدد فهرس عنصر معين في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن لتحديد موقعه في القائمة. |

**القيمة المرجعة:**
int - فهرس العنصر إذا وجد في القائمة؛ وإلا، -1.

### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

يدخل سلوكًا جديدًا إلى مجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الذي يجب إدراج السلوك الجديد فيه. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإدراجه. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

يزيل السلوك المحدد من مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإزالته. |

**القيمة المرجعة:**
boolean - صحيح إذا تمت إزالة سلوك بنجاح boolean

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل سلوكًا من مجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس سلوك لإزالته. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع السلوكيات من مجموعة.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن لتحديد موقعه في الـ [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - صحيح إذا تم العثور على العنصر في الـ [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا، خطأ.