---
title: ITable
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل جدولًا على شريحة.
type: docs
url: /ar/com.aspose.slides/itable/
---
**جميع الواجهات المنفذة:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)  
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

يمثل جدولاً على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | يعيد الخلية في الفهارس المحددة للعمود والصف. |
| [getRows()](#getRows--) | يعيد مجموعة الصفوف. |
| [getColumns()](#getColumns--) | يعيد مجموعة الأعمدة. |
| [getTableFormat()](#getTableFormat--) | يعيد كائن TableFormat الذي يحتوي على خصائص التنسيق لهذا الجدول. |
| [getStylePreset()](#getStylePreset--) | يحصل أو يعيّن نمط الجدول المدمج. |
| [setStylePreset(int value)](#setStylePreset-int-) | يحصل أو يعيّن نمط الجدول المدمج. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. |
| [getFirstRow()](#getFirstRow--) | يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. |
| [getFirstCol()](#getFirstCol--) | يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. |
| [getLastRow()](#getLastRow--) | يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. |
| [getLastCol()](#getLastCol--) | يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. |
| [getHorizontalBanding()](#getHorizontalBanding--) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. |
| [getVerticalBanding()](#getVerticalBanding--) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | يدمج الخلايا المجاورة. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

يعيد الخلية في الفهارس المحددة للعمود والصف. قراءة فقط [ICell](../../com.aspose.slides/icell).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**الإرجاع:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

يعيد مجموعة الصفوف. قراءة فقط [IRowCollection](../../com.aspose.slides/irowcollection).

**الإرجاع:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

يعيد مجموعة الأعمدة. قراءة فقط [IColumnCollection](../../com.aspose.slides/icolumncollection).

**الإرجاع:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

يعيد كائن TableFormat الذي يحتوي على خصائص التنسيق لهذا الجدول. قراءة فقط [ITableFormat](../../com.aspose.slides/itableformat).

**الإرجاع:**
[ITableFormat](../../com.aspose.slides/itableformat)

### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

يحصل أو يعيّن نمط الجدول المدمج. قراءة/كتابة [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**الإرجاع:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

يحصل أو يعيّن نمط الجدول المدمج. قراءة/كتابة [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة-كتابة boolean.

**الإرجاع:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة-كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

يحدد ما إذا كان يجب رسم الصف الأول للجدول بتنسيق خاص. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

يحدد ما إذا كان يجب رسم العمود الأول للجدول بتنسيق خاص. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

يحدد ما إذا كان يجب رسم الصف الأخير للجدول بتنسيق خاص. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

يحدد ما إذا كان يجب رسم العمود الأخير للجدول بتنسيق خاص. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة/كتابة boolean.

**الإرجاع:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

يدمج الخلايا المجاورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | الخلية للدمج. |
| cell2 | [ICell](../../com.aspose.slides/icell) | الخلية للدمج. |
| allowSplitting | boolean | صحيح للسماح بتقسيم الخلايا. |

**الإرجاع:**
[ICell](../../com.aspose.slides/icell) - خلية مدمجة.