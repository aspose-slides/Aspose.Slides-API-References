---
title: BehaviorCollection
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من تأثيرات السلوك.
type: docs
url: /ar/com.aspose.slides/behaviorcollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

يمثل مجموعة من تأثيرات السلوك.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCount()](#getCount--) | يعيد عدد السلوكيات في المجموعة. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | يضيف سلوكًا جديدًا إلى المجموعة. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | يحدد فهرس عنصر محدد في القائمة. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | يدرج سلوكًا جديدًا في مجموعة عند الفهرس المحدد. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | يزيل السلوك المحدد من مجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل السلوك من المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع السلوكيات من المجموعة. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
| [get_Item(int index)](#get-Item-int-) | يعيد سلوكًا عند الفهرس المحدد. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | يضبط سلوكًا عند الفهرس المحدد. |
| [iterator()](#iterator--) | يعيد عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرر Java للمجموعة بأكملها. |
### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد السلوكيات في المجموعة. عدد صحيح للقراءة فقط.

**القيمة المرجعة:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. قيمة منطقية للقراءة فقط.

**القيمة المرجعة:**
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

يضيف سلوكًا جديدًا إلى المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإضافته. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

يحدد فهرس عنصر محدد في القائمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن للبحث عنه في القائمة. |

**القيمة المرجعة:**
int - فهرس العنصر إذا وجد في القائمة؛ وإلا -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

يدرج سلوكًا جديدًا في مجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدراج السلوك الجديد. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك للإدراج. |

### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | المصفوفة أحادية البُعد التي تكون وجهة العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس الصفري في المصفوفة حيث يبدأ النسخ. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

يزيل السلوك المحدد من مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | السلوك لإزالته. |

**القيمة المرجعة:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل السلوك من المجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك الذي سيتم إزالته. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع السلوكيات من مجموعة.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | الكائن للبحث عنه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - true إذا وجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

يعيد سلوكًا عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك الذي سيتم إرجاعه. |

**القيمة المرجعة:**
[IBehavior](../../com.aspose.slides/ibehavior) - سلوك حركة.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

يضبط سلوكًا عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس السلوك الذي سيتم إرجاعه. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

يعيد عدّادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - عدّاد يمكن استخدامها للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

يعيد مكرر Java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - java.util.Iterator للمجموعة بأكملها.