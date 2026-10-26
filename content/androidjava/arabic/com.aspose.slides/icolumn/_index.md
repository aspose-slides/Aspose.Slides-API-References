---
title: IColumn
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل عمودًا في جدول.
type: docs
url: /ar/com.aspose.slides/icolumn/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

يمثل عمودًا في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | إرجاع أو تعيين عرض العمود. |
| [setWidth(double value)](#setWidth-double-) | إرجاع أو تعيين عرض العمود. |
| [getColumnFormat()](#getColumnFormat--) | إرجاع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

إرجاع أو تعيين عرض العمود. قابل للقراءة/الكتابة double.

**القيمة المرجعة:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

إرجاع أو تعيين عرض العمود. قابل للقراءة/الكتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

إرجاع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. للقراءة فقط [IColumnFormat](../../com.aspose.slides/icolumnformat).

**القيمة المرجعة:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)