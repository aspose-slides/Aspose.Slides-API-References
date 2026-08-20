---
title: ChartDataPoint
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل نقطة بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/chartdatapoint/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

يمثل نقطة بيانات السلسلة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. للقراءة فقط [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**الإرجاع:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

يعيد قيمة الحجم لنقطة بيانات المخطط. يُستخدم مع مخططات Treemap و Sunburst. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

يعيد قيمة اللون لنقطة بيانات المخطط. يُستخدم مع مخططات Map. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة Custom. للقراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**الإرجاع:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. للقراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة والكتابة boolean.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. قراءة/كتابة int.

**الإرجاع:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. قراءة/كتابة int.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل خصائص التنسيق. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل خصائص التنسيق. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

يحدد مؤشر بيانات. للقراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

يضبط نقطة البيانات كإجمالي. يُطبق على نوع السلسلة Waterfall فقط.

**الإرجاع:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

يضبط نقطة البيانات كإجمالي. يُطبق على نوع السلسلة Waterfall فقط.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

خصائص مدخل الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

يزيل DataPoint من سلسلة المخطط.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

يعيد حاوية مستويات نقطة البيانات. يُطبق على سلسلة Treeamp و Sunburst. ترقيم مستويات نقطة البيانات يبدأ من الصفر.

**الإرجاع:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**الإرجاع:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

يعيد لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. يُستخدم هذا اللون بشكل افتراضي إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة والكتابة boolean.

**المعاملات:**
| معامل | نوع | وصف |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

يحدد الموقع الفعلي للمحور x (يسار) لعنصر المخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد أعلى العنصر الفعلي للمخطط نسبةً إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() مسبقًا للحصول على القيم الفعلية. قراءة float.

**الإرجاع:**
float