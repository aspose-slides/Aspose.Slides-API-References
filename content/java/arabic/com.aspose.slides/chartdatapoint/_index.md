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

| الطريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | إرجاع قيمة الحجم لنقطة بيانات المخطط. |
| [getColorValue()](#getColorValue--) | إرجاع قيمة اللون لنقطة بيانات المخطط. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة المخصص. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. |
| [getExplosion()](#getExplosion--) | يحدد مقدار التحرك لنقطة البيانات من مركز الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | يحدد مقدار التحرك لنقطة البيانات من مركز الفطيرة. |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل خصائص التنسيق. |
| [getMarker()](#getMarker--) | يحدد علامة بيانات. |
| [getSetAsTotal()](#getSetAsTotal--) | يضبط نقطة البيانات كإجمالي. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | يضبط نقطة البيانات كإجمالي. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | يزيل DataPoint من سلسلة المخطط. |
| [getDataPointLevels()](#getDataPointLevels--) | إرجاع حاوية مستويات نقطة البيانات. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | إرجاع لون تلقائي لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [getCachedValue()](#getCachedValue--) | يحصل على القيمة المخزنة مؤقتًا لنقطة بيانات المخطط. |
| [getCachedXValue()](#getCachedXValue--) | يحصل على القيمة المخزنة مؤقتًا لـ X لنقطة بيانات المخطط. |
| [getCachedYValue()](#getCachedYValue--) | يحصل على القيمة المخزنة مؤقتًا لـ Y لنقطة بيانات المخطط. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | يحصل على حجم الفقاعة المخزن مؤقتًا لنقطة بيانات المخطط. |
| [getActualX()](#getActualX--) | يحدد الموقع الفعلي لـ x (اليسار) لعناصر المخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط. |
| [getActualY()](#getActualY--) | يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط. |
| [getActualWidth()](#getActualWidth--) | يحدد العرض الفعلي لعنصر المخطط. |
| [getActualHeight()](#getActualHeight--) | يحدد الارتفاع الفعلي لعنصر المخطط. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. للقراءة فقط [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**القيمة المرجعة:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

إرجاع قيمة الحجم لنقطة بيانات المخطط. يُستخدم مع مخططات Treemap و Sunburst. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

إرجاع قيمة اللون لنقطة بيانات المخطط. يُستخدم مع مخططات الخريطة. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**القيمة المرجعة:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة المخصص. للقراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**القيمة المرجعة:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. للقراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

**القيمة المرجعة:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة/الكتابة boolean.

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

يحدد مقدار التحرك لنقطة البيانات من مركز الفطيرة. قابل للقراءة/الكتابة int.

**القيمة المرجعة:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

يحدد مقدار التحرك لنقطة البيانات من مركز الفطيرة. قابل للقراءة/الكتابة int.

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يمثل خصائص التنسيق. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**القيمة المرجعة:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

يمثل خصائص التنسيق. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

يحدد علامة بيانات. للقراءة فقط [IMarker](../../com.aspose.slides/imarker).

**القيمة المرجعة:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

يضبط نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall.

**القيمة المرجعة:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

يضبط نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall.

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**القيمة المرجعة:**
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

إرجاع حاوية مستويات نقطة البيانات. يُطبق على سلاسل Treeamp و Sunburst. فهرسة مستويات نقطة البيانات تبدأ من الصفر.

**القيمة المرجعة:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**القيمة المرجعة:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

إرجاع لون تلقائي لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined.

**القيمة المرجعة:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة/الكتابة boolean.

**القيمة المرجعة:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة/الكتابة boolean.

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

يحصل على القيمة المخزنة مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // اطبع جميع القيم المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

يحصل على القيمة المخزنة مؤقتًا لـ X لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // اطبع جميع القيم المخزنة للمحور X لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

يحصل على القيمة المخزنة مؤقتًا لـ Y لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // اطبع جميع القيم المخزنة للمحور Y لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

يحصل على حجم الفقاعة المخزن مؤقتًا لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // اطبع جميع قيم حجم الفقاعات المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

يحدد الموقع الفعلي لـ x (اليسار) لعناصر المخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

يحدد الجزء العلوي الفعلي لعنصر المخطط بالنسبة إلى الزاوية العلوية اليسرى للمخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

يحدد العرض الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

يحدد الارتفاع الفعلي لعنصر المخطط. استدعِ الطريقة IChart.ValidateChartLayout() قبل الحصول على القيم الفعلية. قراءة float.

**القيمة المرجعة:**
float