---
title: ChartSeries
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل سلسلة مخطط.
type: docs
url: /ar/com.aspose.slides/chartseries/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

يمثل سلسلة مخطط.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | يعيد المخطط الأب. |
| [getExplosion()](#getExplosion--) | المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. |
| [getSmooth()](#getSmooth--) | يمثل تنعيم المنحنى. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | يمثل تنعيم المنحنى. |
| [getName()](#getName--) | يعيد اسم السلسلة. |
| [getDataPoints()](#getDataPoints--) | يعيد مجموعة نقاط البيانات لهذه السلسلة. |
| [getType()](#getType--) | يعيد نوع هذه السلسلة. |
| [setType(int value)](#setType-int-) | يعيد نوع هذه السلسلة. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | يعيد تنسيق السلسلة. |
| [getOrder()](#getOrder--) | يعيد ترتيب السلسلة. |
| [setOrder(int value)](#setOrder-int-) | يعيد ترتيب السلسلة. |
| [getLabels()](#getLabels--) | يعيد Labels الخاصة بسلسلة. |
| [getTrendLines()](#getTrendLines--) | مجموعة خطوط الاتجاه للسلسلة. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | يمثل ErrorBars للسلسلة باتجاه X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | يمثل ErrorBars للسلسلة باتجاه Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | تمثّل مدخل وسيلة الإيضاح المتعلق بهذه السلسلة للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | يحدد شكل السلسلة في مخطط شريطي ثلاثي الأبعاد. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | يحدد شكل السلسلة في مخطط شريطي ثلاثي الأبعاد. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن سلسلة الشريط أو العمود أو الفقاعة يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن سلسلة الشريط أو العمود أو الفقاعة يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | يحدد عكس اللون الصلب للسلسلة. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | يعيد لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. |
| [getShowInnerPoints()](#getShowInnerPoints--) | يمثل النقاط الداخلية. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | يمثل النقاط الداخلية. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | يمثل نقاط القيم الشاذة. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | يمثل نقاط القيم الشاذة. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | يمثل علامات المتوسط. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | يمثل علامات المتوسط. |
| [getShowMeanLine()](#getShowMeanLine--) | يمثل خط المتوسط. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | يمثل خط المتوسط. |
| [getQuartileMethod()](#getQuartileMethod--) | يمثل طريقة الربعيات. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | يمثل طريقة الربعيات. |
| [getShowConnectorLines()](#getShowConnectorLines--) | يمثل خطوط الوصل. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | يمثل خطوط الوصل. |
| [getParentLabelLayout()](#getParentLabelLayout--) | يمثل تخطيط تسميات الفئة الأصلية. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | يمثل تخطيط تسميات الفئة الأصلية. |
| [hasUpDownBars()](#hasUpDownBars--) | يحدد ما إذا كان مخطط الخط أو السهم يحتوي على أشرطة صعود/هبوط. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض العمود أو الشريط. |
| [getGapDepth()](#getGapDepth--) | يعيد أو يعيّن المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحدد زاوية القطعة الأولى في مخطط الفطيرة أو الحلقة، بالدرجات (عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الثقب في مخطط الحلقة (يمكن أن يكون بين 10 و90 بالمائة من حجم مساحة الرسم). |
| [getOverlap()](#getOverlap--) | يحدد مدى تداخل الأشرطة والأعمدة في مخططات ذات بعدين، كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-فطيرة أو شريط-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمائة). |
| [hasSeriesLines()](#hasSeriesLines--) | يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل المرتبطة. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط بيانات تنتمي إلى الفطيرة أو الشريط الثاني في مخطط فطيرة-فطيرة أو شريط-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط بيانات تنتمي إلى الفطيرة أو الشريط الثاني في مخطط فطيرة-فطيرة أو شريط-فطيرة. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط فطيرة-فطيرة أو شريط-فطيرة مع انقسام مخصص. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمائة من الحجم الافتراضي). |
| [getSlide()](#getSlide--) | يعيد الشريحة الأم لـ FillFormat. |
| [getPresentation()](#getPresentation--) | يعيد العرض التقديمي الأم لـ FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**  
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

يعيد المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**  
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. قابل للقراءة والكتابة int.

**الإرجاع:**  
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

المسافة بين شريحة الفطيرة المفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. قابل للقراءة والكتابة int.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

يمثل تنعيم المنحنى. true إذا كان تنعيم المنحنى مفعّلاً لمخطط الخط أو المخطط المبعثر. ينطبق فقط على مخططات الخط والمبعثر المتصلة بخطوط. قابل للقراءة والكتابة boolean.

**الإرجاع:**  
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

يمثل تنعيم المنحنى. true إذا كان تنعيم المنحنى مفعّلاً لمخطط الخط أو المخطط المبعثر. ينطبق فقط على مخططات الخط والمبعثر المتصلة بخطوط. قابل للقراءة والكتابة boolean.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

يعيد اسم السلسلة. للقراءة فقط [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**الإرجاع:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

يعيد مجموعة نقاط البيانات لهذه السلسلة. للقراءة فقط [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**الإرجاع:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

يعيد نوع هذه السلسلة. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**الإرجاع:**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

يعيد نوع هذه السلسلة. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. قابل للقراءة والكتابة boolean.

**الإرجاع:**  
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور الثانوي. قابل للقراءة والكتابة boolean.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. للقراءة فقط [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**الإرجاع:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

يعيد تنسيق السلسلة. للقراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**  
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

يعيد ترتيب السلسلة. قابل للقراءة والكتابة int.

**الإرجاع:**  
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

يعيد ترتيب السلسلة. قابل للقراءة والكتابة int.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

يعيد Labels الخاصة بسلسلة. للقراءة فقط [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**الإرجاع:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

مجموعة خطوط الاتجاه للسلسلة. للقراءة فقط [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

توفر TrendLines (غير فارغة) لسلسلة البيانات في مخططات المنطقة، الشريط، العمود، الخط، السهم، xy (المبعثرة)، والفقاعات غير المتراكبة ثنائية الأبعاد. لا تتوفر خطوط الاتجاه لسلسلة البيانات في أي نوع مخطط يكون متراكبًا أو ثلاثي الأبعاد. كما أن خطوط الاتجاه غير متوفرة لمخططات الرادار، الفطيرة، السطح، أو الحلقة.

**الإرجاع:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

يمثل ErrorBars للسلسلة باتجاه X. للقراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

تتوفر ErrorBars باتجاه X للسلاسل من النوع المنطقة، الشريط، المبعثر والفقاعة. بالنسبة لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (بالخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

يمثل ErrorBars للسلسلة باتجاه Y. للقراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

تتوفر ErrorBars باتجاه Y للسلاسل من النوع المنطقة، الشريط، الخط، المبعثر والفقاعة. بالنسبة لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (بالخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

يمثّل مدخل وسيلة الإيضاح المتعلق بهذه السلسلة للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. قابل للقراءة والكتابة String.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. قابل للقراءة والكتابة String.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. قابل للقراءة والكتابة String.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. قابل للقراءة والكتابة String.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. للقراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**  
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

يحدد شكل السلسلة في مخطط شريطي ثلاثي الأبعاد. تغيير قيمة هذه الخاصية قد يؤدي إلى تغيير نوع السلسلة تلقائيًا. قابل للقراءة والكتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**الإرجاع:**  
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

يحدد شكل السلسلة في مخطط شريطي ثلاثي الأبعاد. تغيير قيمة هذه الخاصية قد يؤدي إلى تغيير نوع السلسلة تلقائيًا. قابل للقراءة والكتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

يحدد أن سلسلة الشريط أو العمود أو الفقاعة يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قابل للقراءة والكتابة boolean.

**الإرجاع:**  
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

يحدد أن سلسلة الشريط أو العمود أو الفقاعة يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قابل للقراءة والكتابة boolean.

**الوسائط:**  
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
يحدد لونًا صلبًا معكوسًا للسلسلة. لتطبيق إعداد اللون اضبط تنسيق السلسلة FillType إلى FillType.Solid. قراءة/كتابة [ColorFormat](../../com.aspose.slides/colorformat).

**القيمة المرتجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

يرجع لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يتم استخدام هذا اللون بشكل افتراضي إذا كان FillType يساوي NotDefined.

**القيمة المرتجعة:**
java.awt.Color - كائن java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

يمثل النقاط الداخلية. True إذا تم إظهار النقاط الداخلية على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**القيمة المرتجعة:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

يمثل النقاط الداخلية. True إذا تم إظهار النقاط الداخلية على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

يمثل نقاط الشذوذ. True إذا تم إظهار نقاط الشذوذ على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**القيمة المرتجعة:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

يمثل نقاط الشذوذ. True إذا تم إظهار نقاط الشذوذ على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

يمثل علامات المتوسط. True إذا تم إظهار علامات المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**القيمة المرتجعة:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

يمثل علامات المتوسط. True إذا تم إظهار علامات المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

يمثل خط المتوسط. True إذا تم إظهار خط المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**القيمة المرتجعة:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

يمثل خط المتوسط. True إذا تم إظهار خط المتوسط على مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker.

**القيمة المرتجعة:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

يمثل خطوط الموصل. ينطبق فقط على مخططات Waterfall.

**القيمة المرتجعة:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

يمثل خطوط الموصل. ينطبق فقط على مخططات Waterfall.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

يمثل تخطيط تسميات الفئات الأصلية. ينطبق فقط على مخططات Treemap.

**القيمة المرتجعة:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

يمثل تخطيط تسميات الفئات الأصلية. ينطبق فقط على مخططات Treemap.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

يحدد ما إذا كان مخطط الخط أو المخطط المالي يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. قراءة فقط boolean.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars.

**القيمة المرتجعة:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

يحدد المسافة بين مجموعات الأعمدة أو القضبان كنسبة مئوية من عرض العمود أو القضيب. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.GapWidth.

**القيمة المرتجعة:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

يرجع أو يضبط المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.GapDepth.

**القيمة المرتجعة:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.FirstSliceAngle.

**القيمة المرتجعة:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن تكون بين 10 و90 في المئة من حجم مساحة الرسم). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط byte.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.DoughnutHoleSize.

**القيمة المرتجعة:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

يحدد مقدار تداخل الأعمدة والقضبان في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية. هي إسقاط للخاصية المناسبة في مجموعة السلاسل الأصلية، وبالتالي هذه الخاصية قراءة فقط. لتغيير القيمة، استخدم الخاصية ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط byte.

--------------------

التداخل يحدد درجة التداخل أو الفاصل بين الأعمدة والقضبان كنسبة مئوية من عرضها: -100%: أقصى مسافة (الأعمدة منفصلة تمامًا). 0%: تُوضع الأعمدة جنبًا إلى جنب بدون تداخل أو مسافة. 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذا هو إسقاط الخاصية ParentSeriesGroup.Overlap.

**القيمة المرتجعة:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

يحدد حجم الفطيرة أو العمود الثاني في مخطط الفطيرة داخل الفطيرة أو الفطيرة داخل العمود كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن تكون بين 5 و200 في المئة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.SecondPieSize.

**القيمة المرتجعة:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

يحدد ما إذا كانت هناك خطوط سلاسل لهذا السلسل والسلاسل المرتبطة. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلاسل. قراءة فقط boolean.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.HasSeriesLines.

**القيمة المرتجعة:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.BubbleSizeRepresentation.

**القيمة المرتجعة:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

يحدد قيمة تستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط الفطيرة داخل الفطيرة أو الفطيرة داخل العمود. يستخدم مع الخاصية PieSplitBy. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط double.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitPosition.

**القيمة المرتجعة:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو العمود الثاني في مخطط الفطيرة داخل الفطيرة أو الفطيرة داخل العمود. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitBy. 2) إذا كانت قيمة الخاصية PieSplitType.Custom فستتمكن من تعريف معلومات تقسيم مخصصة باستخدام الخاصية ParentSeriesGroup.PieSplitCustomPoints.

**القيمة المرتجعة:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات التقسيم المخصصة لمخطط الفطيرة داخل الفطيرة أو الفطيرة داخل العمود مع تقسيم مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو العمود الثاني في مخطط الفطيرة داخل الفطيرة أو الفطيرة داخل العمود. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلاسل الأصلية – هي إسقاط لخاصية المجموعة المناسبة قراءة فقط [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitCustomPoints.

**القيمة المرتجعة:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة ولكن لجميع سلاسل مجموعة السلسلة الأصلية - هذه تمثيل لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.IsColorVaried للقراءة/الكتابة لتغيير القيمة. قيمة منطقية للقراءة فقط.

--------------------

هذا هو تمثيل الخاصية ParentSeriesGroup.IsColorVaried.

**القيمة المرجعة:**  
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المائة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة ولكن لجميع سلاسل مجموعة السلسلة الأصلية - هذه تمثيل لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم الخاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeScale للقراءة/الكتابة لتغيير القيمة.

--------------------

هذا هو تمثيل الخاصية ParentSeriesGroup.BubbleSizeScale.

**القيمة المرجعة:**  
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يرجع الشريحة الأصلية لـ FillFormat. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يرجع العرض التقديمي الأصلي لـ FillFormat. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)