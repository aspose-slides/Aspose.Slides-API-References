---
title: ChartCategory
second_title: Aspose.Slides لجافا - مرجع API
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

| الطريقة | الوصف |
| --- | --- |
| [getUseCell()](#getUseCell--) | إذا كان صحيحًا فإن خاصية AsCell هي الفعلية. |
| [getAsCell()](#getAsCell--) | يرجع أو يضبط كائن IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | يرجع أو يضبط كائن IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | يرجع أو يضبط كائن AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | يرجع أو يضبط كائن AsLiteral. |
| [getValue()](#getValue--) | إذا كان UseCell صحيحًا فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | إذا كان UseCell صحيحًا فإن هذه الخاصية تمثل خاصية AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | حاوية مُدارة لقيم مستويات تجميع فئات المخطط. |
| [remove()](#remove--) | يزيل الفئة من المخطط. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

إذا كان صحيحًا فإن خاصية AsCell هي الفعلية. بعبارة أخرى، يتم استخدام ورقة العمل لتخزين الفئة (هذا المثال يدعم فئة متعددة المستويات). إذا كان خاطئًا فإن خاصية AsLiteral هي الفعلية. بعبارة أخرى، لا يتم استخدام ورقة العمل لتخزين الفئة (وهذا المثال لا يدعم فئات متعددة المستويات). قراءة فقط من نوع boolean.

--------------------

لتغيير قيمة هذه الخاصية (لكل الفئات في المجموعة) عيّن القيمة الجديدة لخاصية ChartCategoryCollection.UseCells property.

**القيمة المرجعة:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

يرجع أو يضبط كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن كائن IChartDataCell يُستخدم للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**القيمة المرجعة:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

يرجع أو يضبط كائن IChartDataCell. إذا كانت الفئة متعددة المستويات فإن كائن IChartDataCell يُستخدم للمستوى "0". قراءة/كتابة [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

يرجع أو يضبط كائن AsLiteral. قراءة/كتابة Object.

**القيمة المرجعة:**
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

إذا كان UseCell صحيحًا فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell خاطئًا فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**القيمة المرجعة:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

إذا كان UseCell صحيحًا فإن هذه الخاصية تمثل خاصية AsCell.Value. إذا كان UseCell خاطئًا فإن هذه الخاصية تمثل خاصية AsLiteral. قراءة/كتابة Object.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

حاوية مُدارة لقيم مستويات تجميع فئات المخطط. الفئة متعددة المستويات تحتوي على أكثر من مستوى تجميع واحد. فهرسة مستويات التجميع تبدأ من الصفر. قراءة فقط [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**القيمة المرجعة:**
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

يرجع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject