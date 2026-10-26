---
title: Table
second_title: Aspose.Slides لأجهزة Android عبر مرجع API Java
description: يمثل جدولًا على شريحة.
type: docs
url: /ar/com.aspose.slides/table/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

يمثل جدولًا على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | يعيد الخلية عند الفهرسين المحددين للعمود والصف. |
| [getRows()](#getRows--) | يعيد مجموعة الصفوف. |
| [getColumns()](#getColumns--) | يعيد مجموعة الأعمدة. |
| [getTableFormat()](#getTableFormat--) | يعيد كائن TableFormat الذي يحتوي على خصائص التنسيق لهذا الجدول. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | يدمج الخلايا المجاورة. |
| [getStylePreset()](#getStylePreset--) | يحصل أو يضبط نمط الجدول المدمج. |
| [setStylePreset(int value)](#setStylePreset-int-) | يحصل أو يضبط نمط الجدول المدمج. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. |
| [getFirstRow()](#getFirstRow--) | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. |
| [getFirstCol()](#getFirstCol--) | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. |
| [getLastRow()](#getLastRow--) | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. |
| [getLastCol()](#getLastCol--) | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. |
| [getHorizontalBanding()](#getHorizontalBanding--) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. |
| [getVerticalBanding()](#getVerticalBanding--) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | يضبط خصائص تنسيق الجزء المعرفة لجميع أجزاء خلايا الجدول. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | يضبط خصائص تنسيق الفقرة المعرفة لجميع فقرات خلايا الجدول. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | يضبط خصائص تنسيق إطار النص المعرفة لجميع إطارات النص في خلايا الجدول. |
| [getFillFormat()](#getFillFormat--) | يعيد كائن TableFormat.FillFormat يحتوي على تنسيق التعبئة للجدول. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

يعيد الخلية عند الفهرسين المحددين للعمود والصف. للقراءة فقط [Cell](../../com.aspose.slides/cell).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

يعيد مجموعة الصفوف. للقراءة فقط [IRowCollection](../../com.aspose.slides/irowcollection).

**القيمة المرجعة:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

يعيد مجموعة الأعمدة. للقراءة فقط [IColumnCollection](../../com.aspose.slides/icolumncollection).

**القيمة المرجعة:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

يعيد كائن TableFormat الذي يحتوي على خصائص التنسيق لهذا الجدول. للقراءة فقط [ITableFormat](../../com.aspose.slides/itableformat).

**القيمة المرجعية:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

يدمج الخلايا المجاورة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | خلية للدمج. |
| cell2 | [ICell](../../com.aspose.slides/icell) | خلية للدمج. |
| allowSplitting | boolean | True للسماح بتقسيم الخلايا. |

**القيمة المرجعة:**
[ICell](../../com.aspose.slides/icell) - خلية مدمجة.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

يحصل أو يضبط نمط الجدول المدمج. قراءة/كتابة [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**القيمة المرجعة:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

يحصل أو يضبط نمط الجدول المدمج. قراءة/كتابة [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

يحدد ما إذا كان للجدول ترتيب قراءة من اليمين إلى اليسار. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

يحدد ما إذا كان يجب رسم الصف الأول من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

يحدد ما إذا كان يجب رسم العمود الأول من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

يحدد ما إذا كان يجب رسم الصف الأخير من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

يحدد ما إذا كان يجب رسم العمود الأخير من الجدول بتنسيق خاص. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

يحدد ما إذا كان يجب رسم الصفوف الزوجية بتنسيق مختلف. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة-كتابة  boolean .

**القيمة المرجعة:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

يحدد ما إذا كان يجب رسم الأعمدة الزوجية بتنسيق مختلف. قراءة-كتابة  boolean .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

يضبط خصائص تنسيق الجزء المعرفة لجميع أجزاء خلايا الجدول.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | كائن IPortionFormat مع الخصائص المطلوبة مضبوطة. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

يضبط خصائص تنسيق الفقرة المعرفة لجميع فقرات خلايا الجدول.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | كائن IParagraphFormat مع الخصائص المطلوبة مضبوطة. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

يضبط خصائص تنسيق إطار النص المعرفة لجميع إطارات النص في خلايا الجدول.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | كائن ITextFrameFormat مع الخصائص المطلوبة مضبوطة. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

يعيد كائن TableFormat.FillFormat يحتوي على تنسيق التعبئة للجدول. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**القيمة المرجعة:**
[IFillFormat](../../com.aspose.slides/ifillformat)