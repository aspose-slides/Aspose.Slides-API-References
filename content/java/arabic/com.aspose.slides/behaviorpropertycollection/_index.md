---
title: BehaviorPropertyCollection
second_title: Aspose.Slides للغة Java مرجع API
description: يمثل خصائص التوقيت لسلوك التأثير.
type: docs
url: /ar/com.aspose.slides/behaviorpropertycollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المطبقة:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

يمثل خصائص التوقيت لسلوك التأثير.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد الخصائص المخزنة في المجموعة. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | يضيف خاصية جديدة إلى المجموعة. |
| [add(String propertyValue)](#add-java.lang.String-) | يضيف خاصية جديدة إلى المجموعة. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | يحدد فهرس عنصر محدد في القائمة. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | يحدد فهرس عنصر محدد حسب قيمة الخاصية في القائمة. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | يقوم بإدراج خاصية جديدة إلى المجموعة عند الفهرس المحدد. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | يقوم بإدراج خاصية جديدة (مع قيمة الخاصية المحددة) إلى المجموعة عند الفهرس المحدد. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | يزيل الخاصية المحددة من المجموعة. |
| [remove(String propertyValue)](#remove-java.lang.String-) | يزيل الخاصية المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل الخاصية عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع الخصائص من المجموعة. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [contains(String propertyValue)](#contains-java.lang.String-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع خاصية عند الفهرس المحدد. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | يضبط خاصية عند الفهرس المحدد. |
| [iterator()](#iterator--) | إرجاع عداد يتنقل عبر المجموعة. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرر جافا للمجموعة بأكملها. |

### size() {#size--}
```
public final int size()
```

إرجاع عدد الخصائص المخزنة في المجموعة. عدد للقراءة فقط.

**القيمة المرجعة:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. منطقي للقراءة فقط.

**القيمة المرجعة:**
boolean - صحيح إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا، خطأ.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

يضيف خاصية جديدة إلى المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية التي سيتم إضافتها. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

يضيف خاصية جديدة إلى المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إضافتها. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

يحدد فهرس عنصر محدد في القائمة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الكائن الذي يُبحث عنه في القائمة. |

**القيمة المرجعة:**
int - فهرس العنصر إذا وجد في القائمة؛ وإلا، -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

يحدد فهرس عنصر محدد حسب قيمة الخاصية في القائمة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية |

**القيمة المرجعة:**
int - فهرس الخاصية ذات القيمة المحددة

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

يقوم بإدراج خاصية جديدة إلى المجموعة عند الفهرس المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الذي يجب إدراج الخاصية الجديدة فيه. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية التي سيتم إضافتها. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

يقوم بإدراج خاصية جديدة (مع قيمة الخاصية المحددة) إلى المجموعة عند الفهرس المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الذي يجب إدراج الخاصية الجديدة فيه. |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إضافتها. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | المصفوفة أحادية البعد التي تكون وجهة العناصر المنسوخة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة تبدأ من الصفر. |
| arrayIndex | int | الفهرس الصفرى في المصفوفة الذي يبدأ عنده النسخ. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

يزيل الخاصية المحددة من المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية التي سيتم إزالتها. |

**القيمة المرجعة:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

يزيل الخاصية المحددة من المجموعة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية التي سيتم إزالتها. |

**القيمة المرجعة:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل الخاصية عند الفهرس المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية التي يجب حذفها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع الخصائص من المجموعة.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية التي يُبحث عنها في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - صحيح إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا، خطأ.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية التي يُبحث عنها في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**القيمة المرجعة:**
boolean - صحيح إذا وُجد propertyValue في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا، خطأ.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

إرجاع خاصية عند الفهرس المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية التي يجب إرجاعها. |

**القيمة المرجعة:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - خاصية سلوك الرسوم المتحركة.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

يضبط خاصية عند الفهرس المحدد.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية التي يجب إرجاعها. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

إرجاع عداد يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**القيمة المرجعة:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**القيمة المرجعة:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**القيمة المرجعة:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

إرجاع مكرر جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator للمجموعة بأكملها.