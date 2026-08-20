---
title: IRowCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة صفوف الجدول.
type: docs
url: /ar/com.aspose.slides/irowcollection/
---
**جميع الواجهات التي تم تنفيذها:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

يمثل مجموعة صفوف الجدول.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل صفًا في الموضع المحدد من جدول. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


ينشئ نسخة من صف القالب المحدد ويُدرجها في أسفل جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | true لنسخ جميع الصفوف المرفقة بصف القالب أيضًا. |

**القيمة المرجعة:**
com.aspose.slides.IRow[] - Added rows.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


ينشئ نسخة من صف القالب المحدد ويُدرجها في الموضع المحدد داخل جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الصف الجديد. |
| templ | [IRow](../../com.aspose.slides/irow) | الصف الذي يُستخدم كقالب. |
| withAttachedRows | boolean | true لنسخ جميع الصفوف المرفقة بصف القالب أيضًا. |

**القيمة المرجعة:**
com.aspose.slides.IRow[] - Inserted rows.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


يزيل صفًا في الموضع المحدد من جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| firstRowIndex | int | فهرس الصف المراد حذفه. |
| withAttachedRows | boolean | true لحذف جميع الصفوف المرفقة أيضًا. |