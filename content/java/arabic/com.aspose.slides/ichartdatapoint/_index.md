---
title: IChartDataPoint
second_title: مرجع API Aspose.Slides لجافا
description: يمثل نقطة بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/ichartdatapoint/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

يمثل نقطة بيانات السلسلة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getXValue()](#getXValue--) | يرجم قيمة x لنقطة بيانات المخطط. |
| [getYValue()](#getYValue--) | يرجم قيمة y لنقطة بيانات المخطط. |
| [getBubbleSize()](#getBubbleSize--) | يرجم حجم الفقاعة لنقطة بيانات المخطط. |
| [getValue()](#getValue--) | يرجم قيمة نقطة بيانات المخطط. |
| [getSizeValue()](#getSizeValue--) | يرجم قيمة الحجم لنقطة بيانات المخطط. |
| [getColorValue()](#getColorValue--) | يرجم قيمة اللون لنقطة بيانات المخطط. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | يمثل قيم أشرطة الخطأ للسلسلة في حال نوع القيمة مخصص. |
| [getLabel()](#getLabel--) | يمثل التسمية لنقطة بيانات المخطط. |
| [isBubble3D()](#isBubble3D--) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. |
| [getExplosion()](#getExplosion--) | يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. |
| [getFormat()](#getFormat--) | يمثل خصائص التنسيق. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | يمثل خصائص التنسيق. |
| [getMarker()](#getMarker--) | يحدد علامة بيانات. |
| [remove()](#remove--) | يزيل DataPoint من سلسلة المخطط. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | يرجع لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | خصائص إدخال وسيلة الإيضاح المقابلة في حالة نوع المخطط من القائمة التالية: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | يعيّن نقطة البيانات كإجمالي. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | يعيّن نقطة البيانات كإجمالي. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية. |
| [getDataPointLevels()](#getDataPointLevels--) | يرجع الحاوية لمستويات نقطة البيانات. |
| [getIndex()](#getIndex--) | يحدد أي مجموعة من مجموعة الأطفال الخاصة بالأب ينتمي إليها نقطة البيانات. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

يرجع قيمة x لنقطة بيانات المخطط. للقراءة فقط [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**الإرجاع:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

يرجع قيمة y لنقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

يرجع حجم الفقاعة لنقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

يرجع قيمة نقطة بيانات المخطط. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

يرجع قيمة الحجم لنقطة بيانات المخطط. يُستخدم مع مخططي Treemap و Sunburst. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

يرجع قيمة اللون لنقطة بيانات المخطط. يُستخدم مع مخططي الخريطة. للقراءة فقط [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**الإرجاع:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

يمثل قيم أشرطة الخطأ للسلسلة في حال نوع القيمة مخصص. للقراءة فقط [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**الإرجاع:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

يمثل التسمية لنقطة بيانات المخطط. للقراءة فقط [IDataLabel](../../com.aspose.slides/idatalabel).

**الإرجاع:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة/الكتابة من نوع boolean.

**الإرجاع:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

يحدد أن الفقاعات لها تأثير ثلاثي الأبعاد مطبق عليها. قابل للقراءة/الكتابة من نوع boolean.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. قابل للقراءة/الكتابة من نوع int.

**الإرجاع:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

يحدد مقدار التحريك لنقطة البيانات من مركز الفطيرة. قابل للقراءة/الكتابة من نوع int.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يمثل خصائص التنسيق. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

يمثل خصائص التنسيق. قابل للقراءة/الكتابة [IFormat](../../com.aspose.slides/iformat).

**المعلمات:**
| معامل | نوع | الوصف |
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

يرجع لونًا تلقائيًا لنقطة البيانات بناءً على فهرس السلسلة، فهرس نقطة البيانات، خاصية ParentSeriesGroup.IsColorVaried ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.awt.Color - اللون التلقائي لنقطة البيانات java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

خصائص إدخال وسيلة الإيضاح المقابلة في حالة نوع المخطط من القائمة التالية: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

يعيّن نقطة البيانات كإجمالي. يُطبق على نوع السلسلة Waterfall فقط.

**الإرجاع:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

يعيّن نقطة البيانات كإجمالي. يُطبق على نوع السلسلة Waterfall فقط.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة/الكتابة من نوع boolean.

**الإرجاع:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

يحدد أن نقطة البيانات ستعكس ألوانها إذا كانت القيمة سلبية. قابل للقراءة/الكتابة من نوع boolean.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

يرجع الحاوية لمستويات نقطة البيانات. يُطبق على سلسلتي Treeamp و Sunburst. فهرسة مستويات نقطة البيانات تبدأ من الصفر.

**الإرجاع:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

يحدد أي مجموعة من مجموعة الأطفال الخاصة بالأب ينتمي إليها نقطة البيانات. للقراءة من نوع long.

**الإرجاع:**
long