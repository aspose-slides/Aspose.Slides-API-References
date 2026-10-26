---
title: IColumnCollection
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
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
| [get_Item(int index)](#get-Item-int-) | إرجاع العمود عند الفهرس المحدد. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | ينشئ نسخة من صف القالب المحدد ويُدخلها في أسفل الجدول. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | ينشئ نسخة من عمود القالب المحدد ويُدخلها في الموضع المحدد داخل جدول. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | يزيل عمودًا من الموضع المحدد في جدول. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

إرجاع العمود عند الفهرس المحدد. للقراءة فقط [IColumn](../../com.aspose.slides/icolumn).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

ينشئ نسخة من صف القالب المحدد ويُدخلها في أسفل جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | العمود المستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بصف القالب أيضًا. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المضافة.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

ينشئ نسخة من عمود القالب المحدد ويُدخلها في الموضع المحدد داخل جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العمود الجديد. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | العمود المستخدم كقالب. |
| withAttachedColumns | boolean | صحيح لنسخ جميع الأعمدة المرتبطة بعمود القالب أيضًا. |

**القيمة المرجعة:**
com.aspose.slides.IColumn[] - الأعمدة المدخلة.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

يزيل عمودًا من الموضع المحدد في جدول.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| firstColumnIndex | int | فهرس العمود المراد حذفه. |
| withAttachedRows | boolean | صحيح لحذف جميع الأعمدة المرفقة أيضًا. |