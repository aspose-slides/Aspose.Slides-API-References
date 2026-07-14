---
title: RowCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد الصفوف الموجودة فعليًا في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع الصف في الفهرس المحدد. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل صفًا في الموضع المحدد من جدول. |
| [iterator()](#iterator--) | إرجاع تعداد يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مُكرّر جافا للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للقراءات المتعددة). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المزامنة. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد الصفوف الموجودة فعليًا في المجموعة. قابل للقراءة فقط int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

إرجاع الصف في الفهرس المحدد. قابل للقراءة فقط [Row](../../com.aspose.slides/row).

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | True لنسخ أيضًا جميع الصفوف المرفقة بصف القالب. |

**Returns:**
com.aspose.slides.IRow[] - الصفوف المضافة.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف الجديد. |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | True لنسخ أيضًا جميع الصفوف المرفقة بصف القالب. |

**Returns:**
com.aspose.slides.IRow[] - الصفوف المُدرجة.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

يزيل صفًا في الموضع المحدد من جدول.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstRowIndex | int | فهرس الصف المراد حذفه. |
| withAttachedRows | boolean | True لحذف أيضًا جميع الصفوف المرفقة. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

إرجاع تعداد يتنقل عبر المجموعة.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

إرجاع مُكرّر جافا للمجموعة بأكملها.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | مصفوفة الهدف. |
| index | int | فهرس البدء في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للقراءات المتعددة). قابل للقراءة فقط boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المزامنة. قابل للقراءة فقط Object.

**Returns:**
java.lang.Object