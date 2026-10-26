---
title: IChartDataPoint
second_title: Aspose.Slides لأجهزة Android عبر مرجع Java API
description: يمثل نقطة بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/ichartdatapoint/
---
**All Implemented Interfaces:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

يمثل نقطة بيانات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | يعيد قيمة x لنقطة بيانات المخطط. |
| [getYValue()](#getYValue--) | يعيد قيمة y لنقطة بيانات المخطط. |
| [getBubbleSize()](#getBubbleSize--) | يعيد حجم الفقاعة لنقطة بيانات المخطط. |
| [getValue()](#getValue--) | يعيد القيمة لنقطة بيانات المخطط. |
| [getSizeValue()](#getSizeValue--) | يعيد قيمة الحجم لنقطة بيانات المخطط. |
| [getColorValue()](#getColorValue--) | يعيد قيمة اللون لنقطة بيانات المخطط. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | يمثل قيم أشرطة الخطأ للسلسلة في حالة النوع المخصص. |
| [getLabel()](#getLabel--) | يمثل تسمية نقطة بيانات المخطط. |
| [isBubble3D()](#isBubble3D--) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. |
| [getExplosion()](#getExplosion--) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | يحدد مقدار تحريك نقطة البيانات من مركز الفطيرة. |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل خصائص التنسيق. |
| [getMarker()](#getMarker--) | يحدد علامة بيانات. |
| [remove()](#remove--) | يزيل DataPoint من سلسلة المخطط. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | يعيد لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried، ونمط المخطط. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خصائص مدخل الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | يحدد نقطة البيانات كإجمالي. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | يحدد نقطة البيانات كإجمالي. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن نقطة البيانات يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [getDataPointLevels()](#getDataPointLevels--) | يعيد الحاوية لمستويات نقطة البيانات. |
| [getIndex()](#getIndex--) | يحدد أي مجموعة من أطفال الأصل تنطبق عليها نقطة البيانات هذه. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

يعيد قيمة x لنقطة بيانات المخطط. قراءة فقط [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**الإرجاع:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

يعيد قيمة y لنقطة بيانات المخطط. قراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

يعيد حجم الفقاعة لنقطة بيانات المخطط. قراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

يعيد القيمة لنقطة بيانات المخطط. قراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

يعيد قيمة الحجم لنقطة بيانات المخطط. يُستخدم مع مخططات Treemap و Sunburst. قراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

يعيد قيمة اللون لنقطة بيانات المخطط. يُستخدم مع مخططات الخريطة. قراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الخطأ للسلسلة في حالة النوع المخصص. قراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**الإرجاع:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

يمثل تسمية نقطة بيانات المخطط. قراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

يحدد أن الفقاعات لديها تأثير ثلاثي الأبعاد مطبق عليها. قراءة/كتابة boolean.

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

يحدد علامة بيانات. قراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

يزيل DataPoint من سلسلة المخطط.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

يعيد لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried، ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

خصائص مدخل الأسطورة المقابل في حالة نوع المخطط من هذه القائمة: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

يحدد نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall.

**الإرجاع:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

يحدد نقطة البيانات كإجمالي. يُطبق فقط على نوع السلسلة Waterfall.

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

يعيد الحاوية لمستويات نقطة البيانات. يُطبق على سلاسل Treeamp و Sunburst. فهرسة مستويات نقطة البيانات تبدأ من الصفر.

**الإرجاع:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

يحدد أي مجموعة من أطفال الأصل تنطبق عليها نقطة البيانات هذه. قراءة long.

**الإرجاع:**
long