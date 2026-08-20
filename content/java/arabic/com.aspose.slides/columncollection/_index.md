---
title: ColumnCollection
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل مجموعة من الأعمدة في جدول.
type: docs
url: /ar/com.aspose.slides/columncollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

يمثل مجموعة من الأعمدة في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | إرجاع عدد الأعمدة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع العمود عند الفهرس المحدد. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | إنشاء نسخة من صف القالب المحدد وإدراجها في أسفل الجدول. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | إنشاء نسخة من عمود القالب المحدد وإدراجها في الموضع المحدد داخل الجدول. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | إزالة عمود من الموضع المحدد في جدول. |
| [iterator()](#iterator--) | إرجاع مُعدٍ (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مُتكرّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
### size() {#size--}
```
public final int size()
```


إرجاع عدد الأعمدة في المجموعة. للقراءة فقط int.

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


إرجاع العمود عند الفهرس المحدد. للقراءة فقط [Column](../../com.aspose.slides/column).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


إنشاء نسخة من صف القالب المحدد وإدراجها في أسفل الجدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | عمود يُستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ أيضًا جميع الأعمدة الملحقة بصف القالب. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المضافة.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


إنشاء نسخة من عمود القالب المحدد وإدراجها في الموضع المحدد داخل الجدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود الجديد. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | عمود يُستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ أيضًا جميع الأعمدة الملحقة بعمود القالب. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المُدخلة.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


إزالة عمود من الموضع المحدد في جدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstColumnIndex | int | فهرس العمود المراد حذفه. |
| withAttachedRows | boolean | صحيح لحذف أيضًا جميع الأعمدة المرفقة. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


إرجاع مُعدٍ (enumerator) يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator يمكن استخدامها للتجول عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


إرجاع مُتكرّر java للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخطوط). للقراءة فقط boolean.

**القيمة المرجعة:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


إرجاع جذر التزامن. للقراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object