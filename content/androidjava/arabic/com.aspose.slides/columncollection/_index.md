---
title: ColumnCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لل Java
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

| Method | Description |
| --- | --- |
| [size()](#size--) | يعيد عدد الأعمدة في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد العمود عند الفهرس المحدد. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | ينشئ نسخة من عمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل عمودًا في الموضع المحدد من جدول. |
| [iterator()](#iterator--) | يعيد مُعدِّدًا يمر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرِّر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر التزامن. |
### size() {#size--}
```
public final int size()
```

يعيد عدد الأعمدة في مجموعة. int للقراءة فقط.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

يعيد العمود عند الفهرس المحدد. [Column](../../com.aspose.slides/column) للقراءة فقط.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل الجدول.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | عمود يُستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بصف القالب أيضًا. |

**الإرجاع:**
com.aspose.slides.IColumn[] - الأعمدة المضافة.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

ينشئ نسخة من عمود القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس العمود الجديد. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | عمود يُستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بعمود القالب أيضًا. |

**الإرجاع:**
com.aspose.slides.IColumn[] - الأعمدة المدرجة.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

يزيل عمودًا في الموضع المحدد من جدول.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | فهرس العمود المراد حذفه. |
| withAttachedRows | boolean | صحيح لحذف جميع الأعمدة المرتبطة أيضًا. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

يعيد مُعدِّدًا يمر عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - مُعدِّد يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

يعيد مُكرِّر Java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمتعدد الخيوط). boolean للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر التزامن. java.lang.Object للقراءة فقط.

**الإرجاع:**
java.lang.Object