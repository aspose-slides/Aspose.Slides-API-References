---
title: IChartDataPoint
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل نقطة بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/ichartdatapoint/
---
**كل الواجهات المنفذة:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

يمثل نقطة بيانات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | يحصل على قيمة x لنقطة بيانات المخطط. |
| [getYValue()](#getYValue--) | يحصل على قيمة y لنقطة بيانات المخطط. |
| [getBubbleSize()](#getBubbleSize--) | يحصل على حجم الفقاعة لنقطة بيانات المخطط. |
| [getValue()](#getValue--) | يحصل على قيمة نقطة بيانات المخطط. |
| [getCachedXValue()](#getCachedXValue--) | يحصل على قيمة X المؤقتة لنقطة بيانات المخطط. |
| [getCachedYValue()](#getCachedYValue--) | يحصل على قيمة Y المؤقتة لنقطة بيانات المخطط. |
| [getCachedValue()](#getCachedValue--) | يحصل على القيمة المؤقتة لنقطة بيانات المخطط. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | يحصل على حجم الفقاعة المؤقت لنقطة بيانات المخطط. |
| [getSizeValue()](#getSizeValue--) | يحصل على قيمة الحجم لنقطة بيانات المخطط. |
| [getColorValue()](#getColorValue--) | يحصل على قيمة اللون لنقطة بيانات المخطط. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة المخصص. |
| [getLabel()](#getLabel--) | يمثل تسمية نقطة بيانات المخطط. |
| [isBubble3D()](#isBubble3D--) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. |
| [getExplosion()](#getExplosion--) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل خصائص التنسيق. |
| [getMarker()](#getMarker--) | يحدد علامة بيانات. |
| [remove()](#remove--) | يزيل DataPoint من سلسلة المخطط. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | يرجي لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried، ونمط المخطط. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | يضبط نقطة البيانات كإجمالي. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | يضبط نقطة البيانات كإجمالي. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [getDataPointLevels()](#getDataPointLevels--) | يرجع حاوية مستويات نقطة البيانات. |
| [getIndex()](#getIndex--) | يحدد أي مجموعة من أطفال الوالد تنطبق عليها نقطة البيانات هذه. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

يحصل على قيمة x لنقطة بيانات المخطط. للقراءة فقط [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**الإرجاع:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

يحصل على قيمة y لنقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

يحصل على حجم الفقاعة لنقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

يحصل على قيمة نقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```

يحصل على قيمة X المؤقتة لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // طباعة جميع القيم X المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedYValue() {#getCachedYValue--}
```
public abstract ICachedChartValue getCachedYValue()
```

يحصل على قيمة Y المؤقتة لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // طباعة جميع القيم Y المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

يحصل على القيمة المؤقتة لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // طباعة جميع القيم المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```

يحصل على حجم الفقاعة المؤقت لنقطة بيانات المخطط. للقراءة فقط [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // طباعة جميع قيم حجم الفقاعة المخزنة لسلسلة المخطط.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

يحصل على قيمة الحجم لنقطة بيانات المخطط. يستخدم مع مخططي Treemap و Sunburst. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

يحصل على قيمة اللون لنقطة بيانات المخطط. يستخدم مع مخططي الخريطة. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الخطأ للسلسلة في حالة نوع القيمة المخصص. للقراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**الإرجاع:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

يمثل تسمية نقطة بيانات المخطط. للقراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. قراءة/كتابة int.

**الإرجاع:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. قراءة/كتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل خصائص التنسيق. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل خصائص التنسيق. قراءة/كتابة [IFormat](../../com.aspose.slides/iformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

يحدد علامة بيانات. للقراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

يزيل DataPoint من سلسلة المخطط.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

يرجع لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried، ونمط المخطط. هذا اللون يستخدم افتراضيًا إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

خصائص إدخال الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

يضبط نقطة البيانات كإجمالي. يُطبق لنوع سلسلة Waterfall فقط.

**الإرجاع:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

يضبط نقطة البيانات كإجمالي. يُطبق لنوع سلسلة Waterfall فقط.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

يرجع حاوية مستويات نقطة البيانات. يُطبق على سلاسل Treeamp و Sunburst. فهرسة مستويات نقطة البيانات تبدأ من الصفر.

**الإرجاع:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

يحدد أي مجموعة من أطفال الوالد تنطبق عليها نقطة البيانات هذه. قراءة long.

**الإرجاع:**
long