---
title: ChartSeries
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | إرجاع المخطط الأب. |
| [getExplosion()](#getExplosion--) | المسافة بين قطعة فطيرة مفتوحة ومركز المخطط الفطري تُعبَّر عنها كنسبة مئوية من قطر الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | المسافة بين قطعة فطيرة مفتوحة ومركز المخطط الفطري تُعبَّر عنها كنسبة مئوية من قطر الفطيرة. |
| [getSmooth()](#getSmooth--) | يمثل تنعيم المنحنى. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | يمثل تنعيم المنحنى. |
| [getName()](#getName--) | إرجاع اسم السلسلة. |
| [getDataPoints()](#getDataPoints--) | إرجاع مجموعة نقاط البيانات لهذه السلسلة. |
| [getType()](#getType--) | إرجاع نوع هذه السلسلة. |
| [setType(int value)](#setType-int-) | إرجاع نوع هذه السلسلة. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا تم رسم هذه السلسلة على المحور الثانوي. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | يشير إلى ما إذا تم رسم هذه السلسلة على المحور الثانوي. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | إرجاع تنسيق السلسلة. |
| [getOrder()](#getOrder--) | إرجاع ترتيب السلسلة. |
| [setOrder(int value)](#setOrder-int-) | إرجاع ترتيب السلسلة. |
| [getLabels()](#getLabels--) | إرجاع تسميات السلسلة. |
| [getTrendLines()](#getTrendLines--) | مجموعة خطوط الاتجاه للسلسلة. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | يمثل أشرطة الأخطاء للسلسلة باتجاه X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | يمثل أشرطة الأخطاء للسلسلة باتجاه Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل عنصر الأسطورة المتعلق بهذه السلسلة للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | يحدد شكل سلسلة من مخطط شريط ثلاثي الأبعاد. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | يحدد شكل سلسلة من مخطط شريط ثلاثي الأبعاد. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن الشريط أو العمود أو سلسلة الفقاعات يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن الشريط أو العمود أو سلسلة الفقاعات يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | يحدد عكس اللون الصلب للسلسلة. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | إرجاع لون تلقائي للسلسلة بناءً على فهرس السلسلة ونمط المخطط. |
| [getShowInnerPoints()](#getShowInnerPoints--) | يمثل النقاط الداخلية. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | يمثل النقاط الداخلية. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | يمثل نقاط القيم المتطرفة. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | يمثل نقاط القيم المتطرفة. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | يمثل علامات المتوسط. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | يمثل علامات المتوسط. |
| [getShowMeanLine()](#getShowMeanLine--) | يمثل خط المتوسط. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | يمثل خط المتوسط. |
| [getQuartileMethod()](#getQuartileMethod--) | يمثل طريقة الربع. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | يمثل طريقة الربع. |
| [getShowConnectorLines()](#getShowConnectorLines--) | يمثل خطوط الوصل. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | يمثل خطوط الوصل. |
| [getParentLabelLayout()](#getParentLabelLayout--) | يمثل تخطيط تسميات الفئة الأب. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | يمثل تخطيط تسميات الفئة الأب. |
| [hasUpDownBars()](#hasUpDownBars--) | يحدد ما إذا كان مخطط الخط أو الأسهم يحتوي على أشرطة صعود/هبوط. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [getGapDepth()](#getGapDepth--) | إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحدد زاوية القطعة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10% و90% من حجم منطقة الرسم). |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5% و200%). |
| [hasSeriesLines()](#hasSeriesLines--) | يحدد ما إذا كانت هناك خطوط سلسلة لهذا السلسلة والسلاسل المرتبطة. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيف يتم تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة مع انقسام مخصص. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0% و300% من الحجم الافتراضي). |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأصلية لتنسيق التعبئة. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصل لتنسيق التعبئة. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. للقراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

إرجاع المخطط الأب. للقراءة فقط [IChart](../../com.aspose.slides/ichart).

**الإرجاع:**
[IChart](../../com.aspose.slides/ichart)

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

المسافة بين قطعة الفطيرة المفتوحة ومركز المخطط الفطري تُعبَّر عنها كنسبة مئوية من قطر الفطيرة. قابل للقراءة والكتابة int.

**الإرجاع:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

المسافة بين قطعة الفطيرة المفتوحة ومركز المخطط الفطري تُعبَّر عنها كنسبة مئوية من قطر الفطيرة. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التشتت. ينطبق فقط على مخططات الخط والتشتت المتصلة بالخطوط. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التشتت. ينطبق فقط على مخططات الخط والتشتت المتصلة بالخطوط. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

إرجاع اسم السلسلة. للقراءة فقط [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**الإرجاع:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

إرجاع مجموعة نقاط البيانات لهذه السلسلة. للقراءة فقط [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**الإرجاع:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

إرجاع نوع هذه السلسلة. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**الإرجاع:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

إرجاع نوع هذه السلسلة. قابل للقراءة والكتابة [ChartType](../../com.aspose.slides/charttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا تم رسم هذه السلسلة على المحور الثانوي. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

يشير إلى ما إذا تم رسم هذه السلسلة على المحور الثانوي. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
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

إرجاع تنسيق السلسلة. للقراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public final int getOrder()
```

إرجاع ترتيب السلسلة. قابل للقراءة والكتابة int.

**الإرجاع:**
int

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

إرجاع ترتيب السلسلة. قابل للقراءة والكتابة int.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

إرجاع تسميات السلسلة. للقراءة فقط [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**الإرجاع:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

مجموعة خطوط الاتجاه للسلسلة. للقراءة فقط [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

خطوط الاتجاه متوفرة (ليست null) للسلاسل في مخططات المنطقة، الشريط، العمود، الخط، الأسهم، xy (تشتت) والفقاعات غير المكدسة ثنائي الأبعاد. لا تتوفر خطوط الاتجاه للسلاسل في أي نوع مخطط مكدس أو ثلاثي الأبعاد. كما لا تتوفر خطوط الاتجاه لمخططات الرادار، الفطيرة، السطح، أو الدونات.

**الإرجاع:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

يمثل أشرطة الأخطاء للسلسلة باتجاه X. للقراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

أشرطة الأخطاء باتجاه X متوفرة للسلاسل من نوع المنطقة، الشريط، التشتت والفقاعة. لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع خاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

يمثل أشرطة الأخطاء للسلسلة باتجاه Y. للقراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

أشرطة الأخطاء باتجاه Y متوفرة للسلاسل من نوع المنطقة، الشريط، الخط، التشتت والفقاعة. لأي نوع مخطط آخر تُعيد هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع خاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

يمثل عنصر الأسطورة المتعلق بهذه السلسلة للقراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

**المعاملات:**
| المعامل | النوع | الوصف |
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

**المعاملات:**
| المعامل | النوع | الوصف |
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

**المعاملات:**
| المعامل | النوع | الوصف |
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

**المعاملات:**
| المعامل | النوع | الوصف |
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

يحدد شكل سلسلة من مخطط شريط ثلاثي الأبعاد. تغيير قيمة هذه الخاصية قد يؤدي إلى تغيير نوع السلسلة تلقائيًا. قابل للقراءة والكتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**الإرجاع:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

يحدد شكل سلسلة من مخطط شريط ثلاثي الأبعاد. تغيير قيمة هذه الخاصية قد يؤدي إلى تغيير نوع السلسلة تلقائيًا. قابل للقراءة والكتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

يحدد أن الشريط أو العمود أو سلسلة الفقاعات يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

يحدد أن الشريط أو العمود أو سلسلة الفقاعات يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون يجب ضبط FillType الخاص بالسلسلة إلى FillType.Solid. قابل للقراءة والكتابة [ColorFormat](../../com.aspose.slides/colorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

إرجاع لون تلقائي للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون افتراضيًا إذا كان FillType يساوي NotDefined.

**الإرجاع:**
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

يمثل النقاط الداخلية. صحيح إذا تم عرض النقاط الداخلية في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

يمثل النقاط الداخلية. صحيح إذا تم عرض النقاط الداخلية في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

يمثل نقاط القيم المتطرفة. صحيح إذا تم عرض نقاط القيم المتطرفة في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

يمثل نقاط القيم المتطرفة. صحيح إذا تم عرض نقاط القيم المتطرفة في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

يمثل علامات المتوسط. صحيح إذا تم عرض علامات المتوسط في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

يمثل علامات المتوسط. صحيح إذا تم عرض علامات المتوسط في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

يمثل خط المتوسط. صحيح إذا تم عرض خط المتوسط في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

يمثل خط المتوسط. صحيح إذا تم عرض خط المتوسط في مخطط BoxAndWhisker. ينطبق فقط على مخططات BoxAndWhisker. قابل للقراءة والكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker.

**الإرجاع:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

يمثل طريقة الربع. ينطبق فقط على مخططات BoxAndWhisker.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

يمثل خطوط الوصل. ينطبق فقط على مخططات Waterfall.

**الإرجاع:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

يمثل خطوط الوصل. ينطبق فقط على مخططات Waterfall.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

يمثل تخطيط تسميات الفئة الأب. ينطبق فقط على مخططات Treemap.

**الإرجاع:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

يمثل تخطيط تسميات الفئة الأب. ينطبق فقط على مخططات Treemap.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

يحدد ما إذا كان مخطط الخط أو الأسهم يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars القابلة للقراءة والكتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. قابل للقراءة فقط boolean.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars.

**الإرجاع:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapWidth القابلة للقراءة والكتابة لتغيير القيمة. قابل للقراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.GapWidth.

**الإرجاع:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

إرجاع أو تعيين المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.GapDepth القابلة للقراءة والكتابة لتغيير القيمة. قابل للقراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.GapDepth.

**الإرجاع:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

يحدد زاوية القطعة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.FirstSliceAngle القابلة للقراءة والكتابة لتغيير القيمة. قابل للقراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.FirstSliceAngle.

**الإرجاع:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10% و90% من حجم منطقة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.DoughnutHoleSize القابلة للقراءة والكتابة لتغيير القيمة. للقراءة فقط byte.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.DoughnutHoleSize.

**الإرجاع:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية. هي إسقاط للخاصية المناسبة في مجموعة السلاسل الأصلية، وبالتالي هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم الخاصية ParentSeriesGroup.Overlap القابلة للقراءة والكتابة. للقراءة فقط byte.

--------------------

تحدد Overlap درجة التداخل أو الفاصل بين الأشرطة والأعمدة كنسبة مئوية من عرضها: -100%: أقصى مسافة (الأشرطة منفصلة تمامًا). 0%: الأشرطة متجاورة بدون تداخل أو مسافة. 100%: أقصى تداخل (الأشرطة تتداخل تمامًا). هذا هو إسقاط الخاصية ParentSeriesGroup.Overlap.

**الإرجاع:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5% و200%). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.SecondPieSize القابلة للقراءة والكتابة لتغيير القيمة. للقراءة فقط int.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.SecondPieSize.

**الإرجاع:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

يحدد ما إذا كانت هناك خطوط سلسلة لهذا السلسلة والسلاسل المرتبطة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.HasSeriesLines القابلة للقراءة والكتابة لتغيير القيمة. استخدم الخاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. للقراءة فقط boolean.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.HasSeriesLines.

**الإرجاع:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

يحدد كيف يتم تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeRepresentation القابلة للقراءة والكتابة لتغيير القيمة.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.BubbleSizeRepresentation.

**الإرجاع:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

يحدد قيمة تستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. يستخدم مع الخاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitPosition القابلة للقراءة والكتابة لتغيير القيمة. للقراءة فقط double.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitPosition.

**الإرجاع:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

يحدد طريقة تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.PieSplitBy القابلة للقراءة والكتابة لتغيير القيمة. للقراءة فقط [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitBy. 2) إذا كانت قيمة الخاصية PieSplitType.Custom يمكنك تعريف معلومات الانقسام المخصص باستخدام الخاصية ParentSeriesGroup.PieSplitCustomPoints.

**الإرجاع:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط الفطيرة-في-فطيرة أو شريط-في-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة للقراءة فقط [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.PieSplitCustomPoints.

**الإرجاع:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.IsColorVaried القابلة للقراءة والكتابة لتغيير القيمة. للقراءة فقط boolean.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.IsColorVaried.

**الإرجاع:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0% و300% من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلاسل الأصلية - هي إسقاط لخاصية المجموعة المناسبة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلاسل الأصلية. استخدم الخاصية ParentSeriesGroup.BubbleSizeScale القابلة للقراءة والكتابة لتغيير القيمة.

--------------------

هذا هو إسقاط الخاصية ParentSeriesGroup.BubbleSizeScale.

**الإرجاع:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

إرجاع الشريحة الأصلية لتنسيق التعبئة. للقراءة فقط [BaseSlide](../../com.aspose.slides/baseslide).

**الإرجاع:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public         \`\`\`css
```

إرجاع العرض التقديمي الأصل لتنسيق التعبئة. للقراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[IPresentation](../../com.aspose.slides/ipresentation)