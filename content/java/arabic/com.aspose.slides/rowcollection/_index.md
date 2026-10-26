---
title: RowCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة صفوف الجدول.
type: docs
url: /ar/com.aspose.slides/rowcollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)  
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

يمثل مجموعة صفوف الجدول.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد الصفوف الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد الصف في الفهرس المحدد. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويدرجها في أسفل الجدول. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويدرجها في الموضع المحدد داخل الجدول. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل صفًا في الموضع المحدد من جدول. |
| [iterator()](#iterator--) | يعيد عدّادًا يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرِّر جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن من الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |

### size() {#size--}
```
public final int size()
```

يحصل على عدد الصفوف الموجودة فعليًا في المجموعة. للقراءة فقط int.

**القيمة المرتجعة:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

يعيد الصف في الفهرس المحدد. للقراءة فقط [Row](../../com.aspose.slides/row).

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**  
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويدرجها في أسفل الجدول.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | true لنسخ جميع الصفوف المرتبطة بصف القالب أيضًا. |

**القيمة المرتجعة:**  
com.aspose.slides.IRow[] - الصفوف المضافة.

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويدرجها في الموضع المحدد داخل جدول.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف الجديد. |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | true لنسخ جميع الصفوف المرتبطة بصف القالب أيضًا. |

**القيمة المرتجعة:**  
com.aspose.slides.IRow[] - الصفوف التي تم إدراجها.

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

يزيل صفًا في الموضع المحدد من جدول.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| firstRowIndex | int | فهرس الصف المراد حذفه. |
| withAttachedRows | boolean | true لحذف جميع الصفوف المرتبطة أيضًا. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

يعيد عدّادًا يتكرر عبر المجموعة.

**القيمة المرتجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - مُعدِّد يمكن استخدامه لتكرار المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

يعيد مكرِّر جافا للمجموعة بأكملها.

**القيمة المرتجعة:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator للمجموعة بأكملها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن من الخيوط). للقراءة فقط boolean.

**القيمة المرتجعة:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. للقراءة فقط Object.

**القيمة المرتجعة:**  
java.lang.Object