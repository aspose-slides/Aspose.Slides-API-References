---
title: IRowCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل مجموعة صفوف الجدول.
type: docs
url: /ar/com.aspose.slides/irowcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

يمثل مجموعة صفوف الجدول.
## الطرق

| طريقة | وصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب العنصر عند الفهرس المحدد. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويضعها في أسفل الجدول. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | ينشئ نسخة من صف القالب المحدد ويضعها في الموضع المحدد داخل الجدول. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل صفًا في الموضع المحدد من جدول. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

يجلب العنصر عند الفهرس المحدد.

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويضعها في أسفل الجدول.

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Row التي تُستخدم كقالب. |
| withAttachedRows | boolean | True لنسخ أيضًا جميع الصفوف المرتبطة بRow القالب. |

**القيمة المرجعة:**
com.aspose.slides.IRow[] - الصفوف المضافة.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

ينشئ نسخة من صف القالب المحدد ويضعها في الموضع المحدد داخل جدول.

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| index | int | فهرس الصف الجديد. |
| templ | [IRow](../../com.aspose.slides/irow) | Row التي تُستخدم كقالب. |
| withAttachedRows | boolean | True لنسخ أيضًا جميع الصفوف المرتبطة بRow القالب. |

**القيمة المرجعة:**
com.aspose.slides.IRow[] - الصفوف المُدرجة.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

يزيل صفًا في الموضع المحدد من جدول.

**المعلمات:**
| معلمة | نوع | وصف |
| --- | --- | --- |
| firstRowIndex | int | فهرس الصف المراد حذفه. |
| withAttachedRows | boolean | True لحذف أيضًا جميع الصفوف المرتبطة. |