---
title: IColumnCollection
second_title: Aspose.Slides للـ Android عبر مرجع API لجافا
description: يمثل مجموعة من الأعمدة في جدول.
type: docs
url: /ar/com.aspose.slides/icolumncollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

يمثل مجموعة من الأعمدة في جدول.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the column at the specified index. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template row and inserts it at the bottom of a table. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Creates a copy of the specified template column and insert it at the specified position in a table. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Removes a column at the specified position from a table. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

إرجاع العمود عند الفهرس المحدد. للقراءة فقط [IColumn](../../com.aspose.slides/icolumn).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

إنشاء نسخة من صف القالب المحدد وإدراجها في أسفل جدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | العمود المستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بصف القالب أيضاً. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المضافة.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

إنشاء نسخة من العمود القالب المحدد وإدراجها في الموضع المحدد داخل جدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود الجديد. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | العمود المستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بعمود القالب أيضاً. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المدخلة.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

إزالة عمود في الموضع المحدد من جدول.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| firstColumnIndex | int | فهرس العمود المراد حذفه. |
| withAttachedRows | boolean | صحيح لحذف جميع الأعمدة المرتبطة أيضاً. |