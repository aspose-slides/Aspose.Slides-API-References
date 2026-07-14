---
title: Chart
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
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

يمثل مخططًا رسوميًا على شريحة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | يحسب القيم الفعلية لعناصر المخطط. |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | يرجع أو يضبط طريقة رسم الخلايا الفارغة على المخطط. |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | يرجع أو يضبط طريقة رسم الخلايا الفارغة على المخطط. |
| [getChartData()](#getChartData--) | يرجع معلومات حول البيانات المرتبطة أو المضمنة المرتبطة بمخطط. |
| [hasTitle()](#hasTitle--) | يحدد ما إذا كان للمخطط عنوان ظاهر. |
| [setTitle(boolean value)](#setTitle-boolean-) | يحدد ما إذا كان للمخطط عنوان ظاهر. |
| [getChartTitle()](#getChartTitle--) | يرجع أو يضبط عنوان المخطط. |
| [hasDataTable()](#hasDataTable--) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [setDataTable(boolean value)](#setDataTable-boolean-) | يحدد ما إذا كان للمخطط جدول بيانات. |
| [hasLegend()](#hasLegend--) | يحدد ما إذا كان للمخطط وسيلة إيضاح. |
| [setLegend(boolean value)](#setLegend-boolean-) | يحدد ما إذا كان للمخطط وسيلة إيضاح. |
| [getLegend()](#getLegend--) | يرجع أو يضبط وسيلة إيضاح للمخطط. |
| [getChartDataTable()](#getChartDataTable--) | يرجع جدول بيانات للمخطط. |
| [getStyle()](#getStyle--) | يرجع أو يضبط نمط المخطط. |
| [setStyle(int value)](#setStyle-int-) | يرجع أو يضبط نمط المخطط. |
| [getType()](#getType--) | يرجع أو يضبط نوع المخطط. |
| [setType(int value)](#setType-int-) | يرجع أو يضبط نوع المخطط. |
| [getPlotArea()](#getPlotArea--) | يمثل منطقة الرسم للمخطط. |
| [getRotation3D()](#getRotation3D--) | يرجع دورانًا ثلاثيًا للأبعاد للمخطط. |
| [getBackWall()](#getBackWall--) | يرجع كائنًا يسمح بتغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. |
| [getSideWall()](#getSideWall--) | يرجع كائنًا يسمح بتغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. |
| [getFloor()](#getFloor--) | يرجع كائنًا يسمح بتغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. |
| [getTextFormat()](#getTextFormat--) | يرجع تنسيق نص المخطط. |
| [createThemeEffective()](#createThemeEffective--) | يرجع سمة فعّالة لهذا المخطط. |
| [getThemeManager()](#getThemeManager--) | يرجع مدير السمة. |
| [getUserShapes()](#getUserShapes--) | حدد الأشكال المرسومة فوق المخطط. |
| [getAxes()](#getAxes--) | يوفر الوصول إلى محاور المخطط. |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | يحدد ما إذا كان يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | يحدد ما إذا كان يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. |
| [hasRoundedCorners()](#hasRoundedCorners--) | يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

يحسب القيم الفعلية لعناصر المخطط. تشمل القيم الفعلية موضع العناصر التي تُنفِّذ واجهة IActualLayout (IActualLayout.ActualX، IActualLayout.ActualY، IActualLayout.ActualWidth، IActualLayout.ActualHeight) وقيم المحاور الفعلية (IAxis.ActualMaxValue، IAxis.ActualMinValue، IAxis.ActualMajorUnit، IAxis.ActualMinorUnit، IAxis.ActualMajorUnitScale، IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. ضع false لرسم كل من الخلايا الظاهرة والمخفية. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

يحدد ما إذا كانت الخلايا الظاهرة فقط هي التي تم رسمها. ضع false لرسم كل من الخلايا الظاهرة والمخفية. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

يرجع أو يضبط طريقة رسم الخلايا الفارغة على المخطط. قابل للقراءة/الكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**الإرجاع:**  
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

يرجع أو يضبط طريقة رسم الخلايا الفارغة على المخطط. قابل للقراءة/الكتابة [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

يرجع معلومات حول البيانات المرتبطة أو المضمنة المرتبطة بمخطط. للقراءة فقط [IChartData](../../com.aspose.slides/ichartdata).

**الإرجاع:**  
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

يحدد ما إذا كان للمخطط عنوان ظاهر. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

يحدد ما إذا كان للمخطط عنوان ظاهر. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

يرجع أو يضبط عنوان المخطط. للقراءة فقط [IChartTitle](../../com.aspose.slides/icharttitle).

**الإرجاع:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

يحدد ما إذا كان للمخطط جدول بيانات. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

يحدد ما إذا كان للمخطط جدول بيانات. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

يحدد ما إذا كان للمخطط وسيلة إيضاح. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

يحدد ما إذا كان للمخطط وسيلة إيضاح. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

يرجع أو يضبط وسيلة إيضاح للمخطط. للقراءة فقط [ILegend](../../com.aspose.slides/ilegend).

**الإرجاع:**  
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

يرجع جدول بيانات للمخطط. للقراءة فقط [IDataTable](../../com.aspose.slides/idatatable).

**الإرجاع:**  
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public final int getStyle()
```

يرجع أو يضبط نمط المخطط. قابل للقراءة/الكتابة [StyleType](../../com.aspose.slides/styletype).

**الإرجاع:**  
int

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

يرجع أو يضبط نمط المخطط. قابل للقراءة/الكتابة [StyleType](../../com.aspose.slides/styletype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

يرجع أو يضبط نوع المخطط. قابل للقراءة/الكتابة [ChartType](../../com.aspose.slides/charttype).

**الإرجاع:**  
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يرجع أو يضبط نوع المخطط. قابل للقراءة/الكتابة [ChartType](../../com.aspose.slides/charttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

يمثل منطقة الرسم للمخطط. للقراءة فقط [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**الإرجاع:**  
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

يرجع دورانًا ثلاثيًا للأبعاد للمخطط. للقراءة فقط [IRotation3D](../../com.aspose.slides/irotation3d).

**الإرجاع:**  
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

يرجع كائنًا يسمح بتغيير تنسيق الجدار الخلفي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**الإرجاع:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

يرجع كائنًا يسمح بتغيير تنسيق الجدار الجانبي لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**الإرجاع:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

يرجع كائنًا يسمح بتغيير تنسيق الأرضية لمخطط ثلاثي الأبعاد. للقراءة فقط [IChartWall](../../com.aspose.slides/ichartwall).

**الإرجاع:**  
[IChartWall](../../com.aspose.slides/ichartwall)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

يرجع تنسيق نص المخطط. الخاصية غير قابلة للتطبيق على الأنواع التالية: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). للقراءة فقط [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**الإرجاع:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

يرجع سمة فعّالة لهذا المخطط.

**الإرجاع:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

يرجع مدير السمة. للقراءة فقط [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**الإرجاع:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

حدد الأشكال المرسومة فوق المخطط. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

يوفر الوصول إلى محاور المخطط. للقراءة فقط [IAxesManager](../../com.aspose.slides/iaxesmanager).

**الإرجاع:**  
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

يحدد ما إذا كان يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

يحدد ما إذا كان يجب إظهار تسميات البيانات فوق الحد الأقصى للمخطط. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. قابل للقراءة/الكتابة من النوع boolean.

**الإرجاع:**  
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

يحدد أن منطقة المخطط يجب أن تكون ذات زوايا مستديرة. قابل للقراءة/الكتابة من النوع boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

يرجع المخطط. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)