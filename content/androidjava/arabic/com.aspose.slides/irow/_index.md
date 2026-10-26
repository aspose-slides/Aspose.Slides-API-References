---
title: IRow
second_title: Aspose.Slides for Android عبر Java API Reference
description: يمثل صفًا في جدول.
type: docs
url: /ar/com.aspose.slides/irow/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

يمثل صفًا في جدول.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الصف. |
| [getMinimalHeight()](#getMinimalHeight--) | إرجاع أو ضبط الحد الأدنى الممكن لارتفاع الصف. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | إرجاع أو ضبط الحد الأدنى الممكن لارتفاع الصف. |
| [getRowFormat()](#getRowFormat--) | إرجاع كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

إرجاع ارتفاع الصف. قراءة فقط double.

**إرجاع:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

إرجاع أو ضبط الحد الأدنى الممكن لارتفاع الصف. قراءة/كتابة double.

**إرجاع:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

إرجاع أو ضبط الحد الأدنى الممكن لارتفاع الصف. قراءة/كتابة double.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

إرجاع كائن RowFormat الذي يحتوي على خصائص التنسيق لهذا الصف. للقراءة فقط [IRowFormat](../../com.aspose.slides/irowformat).

**إرجاع:**
[IRowFormat](../../com.aspose.slides/irowformat)