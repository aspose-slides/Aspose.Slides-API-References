---
title: BehaviorPropertyCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: يمثل خصائص التوقيت لسلوك التأثير.
type: docs
url: /ar/com.aspose.slides/behaviorpropertycollection/
---
**الإرث:**
java.lang.Object

**جميع الواجهات المطبقَة:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

يمثل خصائص التوقيت لسلوك التأثير.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد الخصائص المخزَّنة في المجموعة. |
| [isReadOnly()](#isReadOnly--) | الحصول على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | إضافة خاصية جديدة إلى المجموعة. |
| [add(String propertyValue)](#add-java.lang.String-) | إضافة خاصية جديدة إلى المجموعة. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | تحديد فهرس عنصر محدد في القائمة. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | تحديد فهرس عنصر محدد حسب قيمة الخاصية في القائمة. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | إدراج خاصية جديدة إلى المجموعة في الفهرس المحدد. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | إدراج خاصية جديدة (مع قيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | نسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | إزالة الخاصية المحددة من المجموعة. |
| [remove(String propertyValue)](#remove-java.lang.String-) | إزالة الخاصية المحددة من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | إزالة خاصية في الفهرس المحدد. |
| [clear()](#clear--) | إزالة جميع الخصائص من المجموعة. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [contains(String propertyValue)](#contains-java.lang.String-) | تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع خاصية في الفهرس المحدد. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | ضبط خاصية في الفهرس المحدد. |
| [iterator()](#iterator--) | إرجاع مُعدد (enumerator) يتنقل عبر المجموعة. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرِّر java للمجموعة بالكامل. |
### size() {#size--}
```
public final int size()
```


إرجاع عدد الخصائص المخزَّنة في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


الحصول على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط. boolean للقراءة فقط.

**الإرجاع:**
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) للقراءة فقط؛ وإلا false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


إضافة خاصية جديدة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية المراد إضافتها. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


إضافة خاصية جديدة إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية المراد إضافتها. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


تحديد فهرس عنصر محدد في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الكائن المراد locate في القائمة. |

**الإرجاع:**
int - فهرس العنصر إذا وجد في القائمة؛ وإلا -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


تحديد فهرس عنصر محدد حسب قيمة الخاصية في القائمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية |

**الإرجاع:**
int - فهرس الخاصية ذات القيمة المحددة
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


إدراج خاصية جديدة إلى المجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدراج خاصية جديدة. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية المراد إضافتها. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


إدراج خاصية جديدة (مع قيمة الخاصية المحددة) إلى المجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس حيث يجب إدراج خاصية جديدة. |
| propertyValue | java.lang.String | قيمة الخاصية المراد إضافتها. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


نسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | المصفوفة أحادية البعد التي هي وجهة العناصر المنقولة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس الصفري في المصفوفة حيث يبدأ النسخ. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


إزالة الخاصية المحددة من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية المراد إزالتها. |

**الإرجاع:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


إزالة الخاصية المحددة من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية المراد إزالتها. |

**الإرجاع:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


إزالة خاصية في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية التي يجب حذفها. |

### clear() {#clear--}
```
public final void clear()
```


إزالة جميع الخصائص من المجموعة.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | الخاصية المراد locate في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - true إذا وجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


تحديد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| propertyValue | java.lang.String | قيمة الخاصية المراد locate في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - true إذا وُجدت propertyValue في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


إرجاع خاصية في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية المراد إرجاعها. |

**الإرجاع:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - خاصية سلوك الرسوم المتحركة.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


ضبط خاصية في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الخاصية المراد إرجاعها. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


إرجاع مُعدد (enumerator) يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**الإرجاع:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**الإرجاع:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**الإرجاع:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


إرجاع مكرِّر java للمجموعة بالكامل.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - java.util.Iterator للمجموعة بالكامل.