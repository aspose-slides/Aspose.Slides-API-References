---
title: IChart
second_title: Aspose.Slides لـ Android عبر مرجع واجهة برمجة التطبيقات Java
description: يمثل مخططًا رسوميًا على شريحة.
type: docs
url: /ar/com.aspose.slides/ichart/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

يمثل مخططًا رسوميًا على شريحة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | يعيد أو يضبط طريقة رسم الخلايا الفارغة على المخطط. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | يعيد أو يضبط طريقة رسم الخلايا الفارغة على المخطط. |
| [getChartData()](#getChartData--) | يعيد معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بمخطط. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [getChartTitle()](#getChartTitle--) | يعيد أو يضبط عنوان المخطط للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [hasLegend()](#hasLegend--) | يحدد ما إذا كان للمخطط مفتاح إيضاح. |
| [setLegend(boolean value)](#setLegend-boolean-) | يحدد ما إذا كان للمخطط مفتاح إيضاح. |
| [getLegend()](#getLegend--) | يعيد أو يضبط مفتاح إيضاح للمخطط. |
| [getChartDataTable()](#getChartDataTable--) | يعيد جدول بيانات للمخطط. |
| [getStyle()](#getStyle--) | يعيد أو يضبط نمط المخطط. |
| [setStyle(int value)](#setStyle-int-) | يعيد أو يضبط نمط المخطط. |
| [getType()](#getType--) | يعيد أو يضبط نوع المخطط. |
| [setType(int value)](#setType-int-) | يعيد أو يضبط نوع المخطط. |
| [getPlotArea()](#getPlotArea--) | يمثل مساحة الرسم للمخطط. |
| [getRotation3D()](#getRotation3D--) | يعيد دورانًا ثلاثيًا الأبعاد للمخطط. |
| [getBackWall()](#getBackWall--) | يعيد كائنًا يسمح بتغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. |
| [getSideWall()](#getSideWall--) | يعيد كائنًا يسمح بتغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. |
| [getFloor()](#getFloor--) | يعيد كائنًا يسمح بتغيير تنسيق أرضية مخطط ثلاثي الأبعاد. |
| [getUserShapes()](#getUserShapes--) | حدِد الأشكال المرسومة فوق المخطط. |
| [getAxes()](#getAxes--) | وفر الوصول إلى محاور المخطط. |
| [validateChartLayout()](#validateChartLayout--) | يحسب القيم الفعلية لعناصر المخطط. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | يحدد أن تسميات البيانات فوق الحد الأقصى للمخطط يجب أن تُظهر. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | يحدد أن تسميات البيانات فوق الحد الأقصى للمخطط يجب أن تُظهر. |
| [hasRoundedCorners()](#hasRoundedCorners--) | يحدد أن مساحة المخطط يجب أن تكون بزوايا مدورة. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | يحدد أن مساحة المخطط يجب أن تكون بزوايا مدورة. |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. False لرسم كل من الخلايا الظاهرة والمخفية. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. False لرسم كل من الخلايا الظاهرة والمخفية. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

يعيد أو يضبط طريقة رسم الخلايا الفارغة على المخطط. قابل للقراءة والكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**القيمة المرجعة:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

يعيد أو يضبط طريقة رسم الخلايا الفارغة على المخطط. قابل للقراءة والكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

يعيد معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بمخطط. للقراءة فقط [IChartData](../../com.aspose.slides/ichartdata).

**القيمة المرجعة:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

يحدد ما إذا كان للمخطط عنوان مرئي. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

يحدد ما إذا كان للمخطط عنوان مرئي. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

يعيد أو يضبط عنوان المخطط للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**القيمة المرجعة:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

يحدد ما إذا كان للمخطط جدول بيانات. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

يحدد ما إذا كان للمخطط جدول بيانات. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

يحدد ما إذا كان للمخطط مفتاح إيضاح. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

يحدد ما إذا كان للمخطط مفتاح إيضاح. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

يعيد أو يضبط مفتاح إيضاح للمخطط. للقراءة فقط [ILegend](../../com.aspose.slides/ilegend).

**القيمة المرجعة:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

يعيد جدول بيانات للمخطط. للقراءة فقط [IDataTable](../../com.aspose.slides/idatatable).

**القيمة المرجعة:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

يعيد أو يضبط نمط المخطط. قابل للقراءة والكتابة [StyleType](../../com.aspose.slides/styletype).

**القيمة المرجعة:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

يعيد أو يضبط نمط المخطط. قابل للقراءة والكتابة [StyleType](../../com.aspose.slides/styletype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

يعيد أو يضبط نوع المخطط. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**القيمة المرجعة:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يعيد أو يضبط نوع المخطط. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

يمثل مساحة الرسم للمخطط. للقراءة فقط [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**القيمة المرجعة:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

يعيد دورانًا ثلاثيًا الأبعاد للمخطط. للقراءة فقط [IRotation3D](../../com.aspose.slides/irotation3d).

**القيمة المرجعة:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

يعيد كائنًا يسمح بتغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

يعيد كائنًا يسمح بتغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

يعيد كائنًا يسمح بتغيير تنسيق أرضية مخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

حدد الأشكال المرسومة فوق المخطط. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

وفر الوصول إلى محاور المخطط. للقراءة فقط [IAxesManager](../../com.aspose.slides/iaxesmanager).

**القيمة المرجعة:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

يحسب القيم الفعلية لعناصر المخطط. تشمل القيم الفعلية موضع العناصر التي تنفذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

يحدد أنه يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

يحدد أنه يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

يحدد أن مساحة المخطط يجب أن تكون بزوايا مدورة. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

يحدد أن مساحة المخطط يجب أن تكون بزوايا مدورة. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |