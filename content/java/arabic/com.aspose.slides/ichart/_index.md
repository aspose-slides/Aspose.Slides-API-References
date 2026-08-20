---
title: IChart
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مخططًا رسوميًا على شريحة.
type: docs
url: /ar/com.aspose.slides/ichart/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

يمثل مخططًا رسوميًا على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | يحدد ما إذا كانت الخلايا المرئية فقط هي المُرسَمة. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | يحدد ما إذا كانت الخلايا المرئية فقط هي المُرسَمة. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | إرجاع أو تعيين الطريقة المستخدمة لرسم الخلايا الفارغة في المخطط. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | إرجاع أو تعيين الطريقة المستخدمة لرسم الخلايا الفارغة في المخطط. |
| [getChartData()](#getChartData--) | إرجاع معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بالمخطط. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [getChartTitle()](#getChartTitle--) | إرجاع أو تعيين عنوان المخطط للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle). |
| [hasDataTable()](#hasDataTable--) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [hasLegend()](#hasLegend--) | يحدد ما إذا كان للمخطط مفتاح توضيحي. |
| [setLegend(boolean value)](#setLegend-boolean-) | يحدد ما إذا كان للمخطط مفتاح توضيحي. |
| [getLegend()](#getLegend--) | إرجاع أو تعيين مفتاح توضيحي للمخطط. |
| [getChartDataTable()](#getChartDataTable--) | إرجاع جدول بيانات للمخطط. |
| [getStyle()](#getStyle--) | إرجاع أو تعيين نمط المخطط. |
| [setStyle(int value)](#setStyle-int-) | إرجاع أو تعيين نمط المخطط. |
| [getType()](#getType--) | إرجاع أو تعيين نوع المخطط. |
| [setType(int value)](#setType-int-) | إرجاع أو تعيين نوع المخطط. |
| [getPlotArea()](#getPlotArea--) | يمثل منطقة الرسم للمخطط. |
| [getRotation3D()](#getRotation3D--) | إرجاع تدوير ثلاثي الأبعاد للمخطط. |
| [getBackWall()](#getBackWall--) | إرجاع كائن يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. |
| [getSideWall()](#getSideWall--) | إرجاع كائن يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. |
| [getFloor()](#getFloor--) | إرجاع كائن يتيح تغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. |
| [getUserShapes()](#getUserShapes--) | تحديد الأشكال المرسومة فوق المخطط. |
| [getAxes()](#getAxes--) | توفير الوصول إلى محاور المخطط. |
| [validateChartLayout()](#validateChartLayout--) | حساب القيم الفعلية لعناصر المخطط. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | تحديد عرض تسميات البيانات فوق الحد الأقصى للمخطط. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | تحديد عرض تسميات البيانات فوق الحد الأقصى للمخطط. |
| [hasRoundedCorners()](#hasRoundedCorners--) | تحديد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | تحديد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

يحدد ما إذا كانت الخلايا المرئية فقط هي المُرسَمة. False لرسمة كلٍ من الخلايا المرئية والمخفية. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

يحدد ما إذا كانت الخلايا المرئية فقط هي المُرسَمة. False لرسمة كلٍ من الخلايا المرئية والمخفية. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

إرجاع أو تعيين الطريقة المستخدمة لرسم الخلايا الفارغة في المخطط. قراءة/كتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**القيمة المرجعة:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

إرجاع أو تعيين الطريقة المستخدمة لرسم الخلايا الفارغة في المخطط. قراءة/كتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

إرجاع معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بالمخطط. للقراءة فقط [IChartData](../../com.aspose.slides/ichartdata).

**القيمة المرجعة:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

يحدد ما إذا كان للمخطط عنوان مرئي. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

يحدد ما إذا كان للمخطط عنوان مرئي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

إرجاع أو تعيين عنوان المخطط للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**القيمة المرجعة:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

يحدد ما إذا كان للمخطط جدول بيانات. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

يحدد ما إذا كان للمخطط جدول بيانات. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

يحدد ما إذا كان للمخطط مفتاح توضيحي. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

يحدد ما إذا كان للمخطط مفتاح توضيحي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

إرجاع أو تعيين مفتاح توضيحي للمخطط. للقراءة فقط [ILegend](../../com.aspose.slides/ilegend).

**القيمة المرجعة:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

إرجاع جدول بيانات للمخطط. للقراءة فقط [IDataTable](../../com.aspose.slides/idatatable).

**القيمة المرجعة:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

إرجاع أو تعيين نمط المخطط. قراءة/كتابة [StyleType](../../com.aspose.slides/styletype).

**القيمة المرجعة:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

إرجاع أو تعيين نمط المخطط. قراءة/كتابة [StyleType](../../com.aspose.slides/styletype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

إرجاع أو تعيين نوع المخطط. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**القيمة المرجعة:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

إرجاع أو تعيين نوع المخطط. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

يمثل منطقة الرسم للمخطط. للقراءة فقط [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**القيمة المرجعة:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

إرجاع تدوير ثلاثي الأبعاد للمخطط. للقراءة فقط [IRotation3D](../../com.aspose.slides/irotation3d).

**القيمة المرجعة:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

إرجاع كائن يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

إرجاع كائن يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

إرجاع كائن يتيح تغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

تحديد الأشكال المرسومة فوق المخطط. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

توفر الوصول إلى محاور المخطط. للقراءة فقط [IAxesManager](../../com.aspose.slides/iaxesmanager).

**القيمة المرجعة:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

حساب القيم الفعلية لعناصر المخطط. القيم الفعلية تشمل موضع العناصر التي تنفذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

تحديد عرض تسميات البيانات فوق الحد الأقصى للمخطط. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

تحديد عرض تسميات البيانات فوق الحد الأقصى للمخطط. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

تحديد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

تحديد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |