---
title: Chart
second_title: Aspose.Slides لمرجع API جافا
description: يمثل مخططًا رسوميًا على شريحة.
type: docs
url: /ar/com.aspose.slides/chart/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)  
```
public class Chart extends GraphicalObject implements IChart
```

يمثل مخططًا رسوميًا على الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | يحسب القيم الفعلية لعناصر المخطط. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | يحدد ما إذا كانت الخلايا المرئية فقط هي التي يتم تمثيلها. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | يحدد ما إذا كانت الخلايا المرئية فقط هي التي يتم تمثيلها. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | يعيد أو يضبط طريقة تمثيل الخلايا الفارغة في المخطط. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | يعيد أو يضبط طريقة تمثيل الخلايا الفارغة في المخطط. |
| [getChartData()](#getChartData--) | يعيد معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بمخطط. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمخطط عنوان مرئي. |
| [getChartTitle()](#getChartTitle--) | يعيد أو يضبط عنوان المخطط. |
| [hasDataTable()](#hasDataTable--) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [hasLegend()](#hasLegend--) | يحدد ما إذا كان للمخطط مفتاح شرح. |
| [setLegend(boolean value)](#setLegend-boolean-) | يحدد ما إذا كان للمخطط مفتاح شرح. |
| [getLegend()](#getLegend--) | يعيد أو يضبط مفتاح شرح للمخطط. |
| [getChartDataTable()](#getChartDataTable--) | يعيد جدول بيانات للمخطط. |
| [getStyle()](#getStyle--) | يعيد أو يضبط نمط المخطط. |
| [setStyle(int value)](#setStyle-int-) | يعيد أو يضبط نمط المخطط. |
| [getType()](#getType--) | يعيد أو يضبط نوع المخطط. |
| [setType(int value)](#setType-int-) | يعيد أو يضبط نوع المخطط. |
| [getPlotArea()](#getPlotArea--) | يمثل مساحة الرسم للمخطط. |
| [getRotation3D()](#getRotation3D--) | يعيد دورانًا ثلاثي الأبعاد للمخطط. |
| [getBackWall()](#getBackWall--) | يعيد كائنًا يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. |
| [getSideWall()](#getSideWall--) | يعيد كائنًا يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. |
| [getFloor()](#getFloor--) | يعيد كائنًا يتيح تغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. |
| [getTextFormat()](#getTextFormat--) | يعيد تنسيق نص المخطط. |
| [createThemeEffective()](#createThemeEffective--) | يعيد سمة فعالة لهذا المخطط. |
| [getThemeManager()](#getThemeManager--) | يعيد مدير السمات. |
| [getUserShapes()](#getUserShapes--) | حدد الأشكال المرسومة أعلى المخطط. |
| [getAxes()](#getAxes--) | وفر الوصول إلى محاور المخطط. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | يحدد أن تُعرض تسميات البيانات فوق الحد الأقصى للمخطط. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | يحدد أن تُعرض تسميات البيانات فوق الحد الأقصى للمخطط. |
| [hasRoundedCorners()](#hasRoundedCorners--) | يحدد أن تكون مساحة المخطط ذات زوايا مستديرة. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | يحدد أن تكون مساحة المخطط ذات زوايا مستديرة. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

يحسب القيم الفعلية لعناصر المخطط. تشمل القيم الفعلية موضع العناصر التي تنفذ واجهة IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

يحدد ما إذا كانت الخلايا المرئية فقط هي التي يتم تمثيلها. false لتمثيل كل من الخلايا المرئية والمخفية. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

يحدد ما إذا كانت الخلايا المرئية فقط هي التي يتم تمثيلها. false لتمثيل كل من الخلايا المرئية والمخفية. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

يعيد أو يضبط طريقة تمثيل الخلايا الفارغة في المخطط. قابلة للقراءة والكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**القيمة المرجعة:**  
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

يعيد أو يضبط طريقة تمثيل الخلايا الفارغة في المخطط. قابلة للقراءة والكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

يعيد معلومات حول البيانات المرتبطة أو المدمجة المرتبطة بمخطط. للقراءة فقط [IChartData](../../com.aspose.slides/ichartdata).

**القيمة المرجعة:**  
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

يحدد ما إذا كان للمخطط عنوان مرئي. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

يحدد ما إذا كان للمخطط عنوان مرئي. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

يعيد أو يضبط عنوان المخطط. للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**القيمة المرجعة:**  
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

يحدد ما إذا كان للمخطط جدول بيانات. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

يحدد ما إذا كان للمخطط جدول بيانات. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

يحدد ما إذا كان للمخطط مفتاح شرح. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

يحدد ما إذا كان للمخطط مفتاح شرح. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

يعيد أو يضبط مفتاح شرح للمخطط. للقراءة فقط [ILegend](../../com.aspose.slides/ilegend).

**القيمة المرجعة:**  
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

يعيد جدول بيانات للمخطط. للقراءة فقط [IDataTable](../../com.aspose.slides/idatatable).

**القيمة المرجعة:**  
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

يعيد أو يضبط نمط المخطط. قابلة للقراءة والكتابة [StyleType](../../com.aspose.slides/styletype).

**القيمة المرجعة:**  
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

يعيد أو يضبط نمط المخطط. قابلة للقراءة والكتابة [StyleType](../../com.aspose.slides/styletype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

يعيد أو يضبط نوع المخطط. قابلة للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**القيمة المرجعة:**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يعيد أو يضبط نوع المخطط. قابلة للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

يمثل مساحة الرسم للمخطط. للقراءة فقط [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**القيمة المرجعة:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

يعيد دورانًا ثلاثي الأبعاد للمخطط. للقراءة فقط [IRotation3D](../../com.aspose.slides/irotation3d).

**القيمة المرجعة:**  
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

يعيد كائنًا يتيح تغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

يعيد كائنًا يتيح تغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

يعيد كائنًا يتيح تغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**القيمة المرجعة:**  
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يعيد تنسيق نص المخطط. الخاصية غير قابلة للتطبيق على الأنواع التالية: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). للقراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**القيمة المرجعة:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يعيد سمة فعالة لهذا المخطط.

**القيمة المرجعة:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

يعيد مدير السمات. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**القيمة المرجعة:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

حدد الأشكال المرسومة أعلى المخطط. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**القيمة المرجعة:**  
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

وفر الوصول إلى محاور المخطط. للقراءة فقط [IAxesManager](../../com.aspose.slides/iaxesmanager).

**القيمة المرجعة:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

يحدد أن تُعرض تسميات البيانات فوق الحد الأقصى للمخطط. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

يحدد أن تُعرض تسميات البيانات فوق الحد الأقصى للمخطط. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

يحدد أن تكون مساحة المخطط ذات زوايا مستديرة. قابلة للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

يحدد أن تكون مساحة المخطط ذات زوايا مستديرة. قابلة للقراءة والكتابة boolean.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**القيمة المرجعة:**  
[IChart](../../com.aspose.slides/ichart)