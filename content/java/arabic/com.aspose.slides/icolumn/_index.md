---
title: IColumn
second_title: مرجع API الخاص بـ Aspose.Slides للغة Java
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

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | تُرجِع أو تُعيِّن عرض العمود. |
| [setWidth(double value)](#setWidth-double-) | تُرجِع أو تُعيِّن عرض العمود. |
| [getColumnFormat()](#getColumnFormat--) | تُرجِع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

تُرجِع أو تُعيِّن عرض العمود. قراءة/كتابة double.

**الإرجاع:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

تُرجِع أو تُعيِّن عرض العمود. قراءة/كتابة double.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

تُرجِع كائن ColumnFormat الذي يحتوي على خصائص التنسيق لهذا العمود. للقراءة فقط [IColumnFormat](../../com.aspose.slides/icolumnformat).

**الإرجاع:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)