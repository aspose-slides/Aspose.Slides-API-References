---
title: IRow
second_title: مرجع API ل Aspose.Slides للغة Java
description: يمثل صفًا في جدول.
type: docs
url: /ar/com.aspose.slides/irow/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

يمثل صفًا في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeight()](#getHeight--) | يعيد ارتفاع الصف. |
| [getMinimalHeight()](#getMinimalHeight--) | يعيد أو يحدد الحد الأدنى الممكن لارتفاع الصف. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | يعيد أو يحدد الحد الأدنى الممكن لارتفاع الصف. |
| [getRowFormat()](#getRowFormat--) | يعيد كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


يعيد ارتفاع الصف. للقراءة فقط double.

**القيمة المرجعة:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


يعيد أو يحدد الحد الأدنى الممكن لارتفاع الصف. قابل للقراءة والكتابة double.

**القيمة المرجعة:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


يعيد أو يحدد الحد الأدنى الممكن لارتفاع الصف. قابل للقراءة والكتابة double.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


يعيد كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. للقراءة فقط [IRowFormat](../../com.aspose.slides/irowformat).

**القيمة المرجعة:**
[IRowFormat](../../com.aspose.slides/irowformat)