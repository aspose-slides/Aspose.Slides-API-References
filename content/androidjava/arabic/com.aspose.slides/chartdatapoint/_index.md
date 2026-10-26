---
title: ChartDataPoint
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل نقطة بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/chartdatapoint/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

يمثل نقطة بيانات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | يرجع قيمة الحجم لنقطة بيانات المخطط. |
| [getColorValue()](#getColorValue--) | يرجع قيمة اللون لنقطة بيانات المخطط. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | يمثل قيم أشرطة الأخطاء للسلسلة في حالة نوع القيمة Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد يُطبق عليها. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد يُطبق عليها. |
| [getExplosion()](#getExplosion--) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل خصائص التنسيق. |
| [getMarker()](#getMarker--) | يحدد علامة بيانات. |
| [getSetAsTotal()](#getSetAsTotal--) | يضبط نقطة البيانات كمجموع. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | يضبط نقطة البيانات كمجموع. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | يزيل DataPoint من سلسلة المخطط. |
| [getDataPointLevels()](#getDataPointLevels--) | يرجع حاوية مستويات نقطة البيانات. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | يرجع لونًا تلقائيًا لنقطة البيانات استنادًا إلى فهرس السلسلة، فهرس نقطة البيانات، الخاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [getActualX()](#getActualX--) | يحدد الموقع الفعلي x (اليسار) لعنصر المخطط نسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualY()](#getActualY--) | يحدد الأعلى الفعلي لعنصر المخطط نسبة إلى الزاوية اليسرى العليا للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |

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

يرجع قيمة الحجم لنقطة بيانات المخطط. يستخدم مع مخططات Treemap و Sunburst. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

يرجع قيمة اللون لنقطة بيانات المخطط. يستخدم مع مخططات الخريطة. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الأخطاء للسلسلة في حالة نوع القيمة Custom. للقراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد يُطبق عليها. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد يُطبق عليها. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. قابل للقراءة والكتابة int.

**الإرجاع:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. قابل للقراءة والكتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل خصائص التنسيق. قابل للقراءة والكتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل خصائص التنسيق. قابل للقراءة والكتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

يحدد علامة بيانات. للقراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

يضبط نقطة البيانات كمجمع. يُطبق فقط على نوع السلسلة Waterfall.

**الإرجاع:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

يضبط نقطة البيانات كمجمع. يُطبق فقط على نوع السلسلة Waterfall.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

يرجع حاوية مستويات نقطة البيانات. يُطبق على سلاسل Treeamp و Sunburst. فهرسة مستويات نقطة البيانات صفرية.

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

يرجع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

يرجع لونًا تلقائيًا لنقطة البيانات استنادًا إلى فهرس السلسلة، فهرس نقطة البيانات، الخاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. يُستخدم هذا اللون بشكل افتراضي إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.lang.Integer
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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualY()
```

يحدد الموقع الفعلي x (اليسار) لعنصر المخطط نسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. للقراءة float.

**الإرجاع:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد الأعلى الفعلي لعنصر المخطط نسبة إلى الزاوية اليسرى العليا للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. للقراءة float.

**الإرجاع:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. للقراءة float.

**الإرجاع:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. للقراءة float.

**الإرجاع:**
float