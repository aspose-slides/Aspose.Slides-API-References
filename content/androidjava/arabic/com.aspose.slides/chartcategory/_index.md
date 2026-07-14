---
title: ChartCategory
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل فئات المخطط.
type: docs
url: /ar/com.aspose.slides/chartcategory/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject  
```
public class ChartCategory implements IChartCategory, IDOMObject
```

يمثل فئات المخطط.  
## الطرق

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | إذا كان true فإن خاصية AsCell هي الفعلية. |
| [getAsCell()](#getAsCell--) | يرجع أو يضبط كائن IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | يرجع أو يضبط كائن IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | يرجع أو يضبط كائن AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | يرجع أو يضبط كائن AsLiteral. |
| [getValue()](#getValue--) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | حاوية مُدارة لقيم مستويات تجميع فئات المخطط. |
| [remove()](#remove--) | يزيل الفئة من المخطط. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

إذا كان true فإن خاصية AsCell هي الفعلية. بمعنى آخر، يتم استخدام ورقة العمل لتخزين الفئة (هذه الحالة تدعم فئة متعددة المستويات). إذا كان false فإن خاصية AsLiteral هي الفعلية. بمعنى آخر، لا يتم استخدام ورقة العمل لتخزين الفئة (وهذه الحالة لا تدعم الفئات المتعددة المستويات). لقراءة فقط boolean.

--------------------

لتغيير قيمة هذه الخاصية (لكل الفئات في المجموعة) عيّن القيمة الجديدة لخاصية ChartCategoryCollection.UseCells property.

**الإرجاع:**  
boolean

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

يرجع أو يضبط كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن الكائن IChartDataCell المستخدم للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**الإرجاع:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

يرجع أو يضبط كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن الكائن IChartDataCell المستخدم للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

يرجع أو يضبط كائن AsLiteral. قراءة/كتابة Object.

**الإرجاع:**  
java.lang.Object

### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

يرجع أو يضبط كائن AsLiteral. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**الإرجاع:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

إذا كان UseCell true فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell false فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

حاوية مُدارة لقيم مستويات تجميع فئات المخطط. الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد. فهرسة مستويات التجميع تبدأ من الصفر. لقراءة فقط [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**الإرجاع:**  
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)

### remove() {#remove--}
```
public final void remove()
```

يزيل الفئة من المخطط.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يرجع كائن Parent_Immediate. لقراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject