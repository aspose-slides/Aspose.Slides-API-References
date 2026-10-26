---
title: IChartSeries
second_title: مرجع Aspose.Slides for Java API
description: يمثل سلسلة مخطط.
type: docs
url: /ar/com.aspose.slides/ichartseries/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

يمثل سلسلة مخطط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getExplosion()](#getExplosion--) | المسافة بين قطعة فطيرة مفتوحة ومركز مخطط الفطيرة معبر عنها كنسبة مئوية من قطر الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | المسافة بين قطعة فطيرة مفتوحة ومركز مخطط الفطيرة معبر عنها كنسبة مئوية من قطر الفطيرة. |
| [getSmooth()](#getSmooth--) | يمثل تنعيم المنحنى. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | يمثل تنعيم المنحنى. |
| [getMarker()](#getMarker--) | إرجاع علامة السلسلة. |
| [getBar3DShape()](#getBar3DShape--) | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. |
| [getName()](#getName--) | إرجاع اسم السلسلة. |
| [getDataPoints()](#getDataPoints--) | إرجاع مجموعة نقاط البيانات لهذه السلسلة. |
| [getType()](#getType--) | إرجاع نوع هذه السلسلة. |
| [setType(int value)](#setType-int-) | إرجاع نوع هذه السلسلة. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | إرجاع مجموعة السلسلة الأصلية. |
| [getFormat()](#getFormat--) | إرجاع تنسيق السلسلة. |
| [getOrder()](#getOrder--) | إرجاع ترتيب السلسلة. |
| [setOrder(int value)](#setOrder-int-) | إرجاع ترتيب السلسلة. |
| [getLabels()](#getLabels--) | إرجاع تسميات السلسلة. |
| [getTrendLines()](#getTrendLines--) | مجموعة خطوط الاتجاه للسلسلة قراءة فقط [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | يمثل أشرطة الخطأ للسلسلة باتجاه X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | يمثل أشرطة الخطأ للسلسلة باتجاه Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا تم رسم هذه السلسلة على المحور القيمي الثاني. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | يشير إلى ما إذا تم رسم هذه السلسلة على المحور القيمي الثاني. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | إرجاع أو تعيين تنسيق الأرقام لقيم السلسلة. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | إرجاع أو تعيين تنسيق الأرقام لقيم السلسلة. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | إرجاع أو تعيين تنسيق الأرقام لقيم X للسلسلة. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | إرجاع أو تعيين تنسيق الأرقام لقيم X للسلسلة. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | إرجاع أو تعيين تنسيق الأرقام لقيم Y للسلسلة. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | إرجاع أو تعيين تنسيق الأرقام لقيم Y للسلسلة. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | إرجاع أو تعيين تنسيق الأرقام لأحجام الفقاعات في السلسلة. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | إرجاع أو تعيين تنسيق الأرقام لأحجام الفقاعات في السلسلة. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن السلسلة الشريطية أو العامودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن السلسلة الشريطية أو العامودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سالبة. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | يحدد عكس اللون الصلب للسلسلة. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل مدخل المفتاح المتعلق بهذه السلسلة قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | إرجاع لون تلقائي للسلسلة بناءً على فهرس السلسلة ونمط المخطط. |
| [getShowInnerPoints()](#getShowInnerPoints--) | يمثل النقاط الداخلية. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | يمثل النقاط الداخلية. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | يمثل نقاط القيم المتطرفة. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | يمثل نقاط القيم المتطرفة. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | يمثل علامات المتوسط. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | يمثل علامات المتوسط. |
| [getShowMeanLine()](#getShowMeanLine--) | يمثل علامات المتوسط. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | يمثل علامات المتوسط. |
| [getQuartileMethod()](#getQuartileMethod--) | يمثل طريقة الربع. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | يمثل طريقة الربع. |
| [getShowConnectorLines()](#getShowConnectorLines--) | يمثل الخطوط الوصل. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | يمثل الخطوط الوصل. |
| [getParentLabelLayout()](#getParentLabelLayout--) | يمثل تخطيط تسميات الفئة الأصلية. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | يمثل تخطيط تسميات الفئة الأصلية. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمئة من الحجم الافتراضي). |
| [hasUpDownBars()](#hasUpDownBars--) | يحدد ما إذا كان مخطط الخط أو المخطط المالي يحتوي على أشرطة صعود/نزول. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض الشريط أو العمود. |
| [getGapDepth()](#getGapDepth--) | إرجاع أو تعيين المسافة كنسبة مئوية من عرض العلامة بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | يحدد ما إذا كانت هناك خطوط سلسلة لهذه السلسلة والسلاسل المرتبطة. |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد كنسبة مئوية (من -100% إلى 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو الشريط داخل الفطيرة كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمئة). |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تقع في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو الشريط داخل الفطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد طريقة تحديد أي نقاط البيانات تقع في الفطيرة أو الشريط الثاني في مخطط الفطيرة داخل الفطيرة أو الشريط داخل الفطيرة. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الشكل الدائري (يمكن أن يكون بين 10 و90 بالمئة من حجم مساحة الرسم). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحدد زاوية شريحة الفطيرة أو الشكل الدائري الأولى بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصصة لمخطط الفطيرة داخل الفطيرة أو الشريط داخل الفطيرة مع انقسام مخصص. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

المسافة بين قطعة فطيرة مفتوحة ومركز مخطط الفطيرة معبر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة int.

**الإرجاع:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

المسافة بين قطعة فطيرة مفتوحة ومركز مخطط الفطيرة معبر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التبعثر. ينطبق فقط على مخططات الخط والتبعثر المتصلة بالخطوط. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

يمثل تنعيم المنحنى. صحيح إذا تم تشغيل تنعيم المنحنى لمخطط الخط أو مخطط التبعثر. ينطبق فقط على مخططات الخط والتبعثر المتصلة بالخطوط. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

إرجاع علامة السلسلة. قراءة فقط [IMarker](../../com.aspose.slides/imarker).

**الإرجاع:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. تغيير قيمة هذا الخاصية قد يسبب تغيير نوع السلسلة تلقائياً. قراءة/كتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**الإرجاع:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. تغيير قيمة هذا الخاصية قد يسبب تغيير نوع السلسلة تلقائياً. قراءة/كتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

إرجاع اسم السلسلة. قراءة فقط [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**الإرجاع:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

إرجاع مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**الإرجاع:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

إرجاع نوع هذه السلسلة. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**الإرجاع:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

إرجاع نوع هذه السلسلة. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

إرجاع مجموعة السلسلة الأصلية. قراءة فقط [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**الإرجاع:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

إرجاع تنسيق السلسلة. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

إرجاع ترتيب السلسلة. قراءة/كتابة int.

**الإرجاع:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

إرجاع ترتيب السلسلة. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

إرجاع تسميات السلسلة. قراءة فقط [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**الإرجاع:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

مجموعة خطوط الاتجاه للسلسلة قراءة فقط [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**الإرجاع:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

يمثل أشرطة الخطأ للسلسلة باتجاه X. قراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

أشرطة الخطأ باتجاه X متاحة لسلاسل نوع area، bar، scatter و bubble. بالنسبة لأي نوع مخطط آخر تُرجع هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

يمثل أشرطة الخطأ للسلسلة باتجاه Y. قراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

أشرطة الخطأ باتجاه Y متاحة لسلاسل نوع area، bar، line، scatter و bubble. بالنسبة لأي نوع مخطط آخر تُرجع هذه الخاصية null (بما في ذلك المخططات ثلاثية الأبعاد). في حالة القيم المخصصة استخدم مجموعة DataPoints لتحديد القيمة (مع الخاصية ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**الإرجاع:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا تم رسم هذه السلسلة على المحور القيمي الثاني. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

يشير إلى ما إذا تم رسم هذه السلسلة على المحور القيمي الثاني. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

إرجاع أو تعيين تنسيق الأرقام لقيم السلسلة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

إرجاع أو تعيين تنسيق الأرقام لقيم السلسلة. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

إرجاع أو تعيين تنسيق الأرقام لقيم X للسلسلة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

إرجاع أو تعيين تنسيق الأرقام لقيم X للسلسلة. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

إرجاع أو تعيين تنسيق الأرقام لقيم Y للسلسلة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

إرجاع أو تعيين تنسيق الأرقام لقيم Y للسلسلة. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

إرجاع أو تعيين تنسيق الأرقام لأحجام الفقاعات في السلسلة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

إرجاع أو تعيين تنسيق الأرقام لأحجام الفقاعات في السلسلة. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

يحدد أن السلسلة الشريطية أو العامودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

يحدد أن السلسلة الشريطية أو العامودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سالبة. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون اضبط Format السلسلة FillType إلى FillType.Solid. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

يمثل مدخل المفتاح المتعلق بهذه السلسلة قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
يعيد لونًا تلقائيًا للسلسلة بناءً على فهرس السلسلة ونمط المخطط. يُستخدم هذا اللون كقيمة افتراضية إذا كان FillType يساوي NotDefined.

**القيمة المرجعة:**  
java.awt.Color - اللون التلقائي للسلسلة java.awt.Color  

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

يمثل النقاط الداخلية. يُصبح ص true إذا تم عرض النقاط الداخلية في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**القيمة المرجعة:**  
boolean  

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

يمثل النقاط الداخلية. يُصبح ص true إذا تم عرض النقاط الداخلية في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

يمثل نقاط الشذوذ. يُصبح ص true إذا تم عرض نقاط الشذوذ في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**القيمة المرجعة:**  
boolean  

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

يمثل نقاط الشذوذ. يُصبح ص true إذا تم عرض نقاط الشذوذ في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

يمثل علامات المتوسط. يُصبح ص true إذا تم عرض علامات المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**القيمة المرجعة:**  
boolean  

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

يمثل علامات المتوسط. يُصبح ص true إذا تم عرض علامات المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

يمثل علامات المتوسط. يُصبح ص true إذا تم عرض خط المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**القيمة المرجعة:**  
boolean  

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

يمثل علامات المتوسط. يُصبح ص true إذا تم عرض خط المتوسط في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قابل للقراءة/الكتابة Boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

يمثل طريقة الربع. يُطبق فقط على مخططات BoxAndWhisker.

**القيمة المرجعة:**  
int  

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

يمثل طريقة الربع. يُطبق فقط على مخططات BoxAndWhisker.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

يمثل خطوط الاتصال. يُطبق فقط على مخططات Waterfall.

**القيمة المرجعة:**  
boolean  

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

يمثل خطوط الاتصال. يُطبق فقط على مخططات Waterfall.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

يمثل تخطيط تسميات الفئة الأصلية. يُطبق فقط على مخططات Treemap.

**القيمة المرجعة:**  
int  

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

يمثل تخطيط تسميات الفئة الأصلية. يُطبق فقط على مخططات Treemap.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

يحدد معامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و300 بالمئة من الحجم الافتراضي). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeScale القابلة للقراءة/الكتابة لتغيير القيمة.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.BubbleSizeScale.

**القيمة المرجعة:**  
int  

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

يحدد ما إذا كان مخطط Line أو Stock يحتوي على أشرطة صعود/هبوط. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.UpDownBars.HasUpDownBars القابلة للقراءة/الكتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars لتنسيق أشرطة الصعود/الهبوط. Boolean للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.UpDownBars.HasUpDownBars.

**القيمة المرجعة:**  
boolean  

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

يحدد المسافة بين مجموعات الأعمدة أو الشرائط، كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapWidth القابلة للقراءة/الكتابة لتغيير القيمة. int للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.GapWidth.

**القيمة المرجعة:**  
int  

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

يعود أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapDepth القابلة للقراءة/الكتابة لتغيير القيمة. int للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.GapDepth.

**القيمة المرجعة:**  
int  

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

يحدد أن لكل مؤشر بيانات في السلسلة لونًا مختلفًا. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.IsColorVaried القابلة للقراءة/الكتابة لتغيير القيمة. Boolean للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.IsColorVaried.

**القيمة المرجعة:**  
boolean  

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

يحدد ما إذا كانت هناك خطوط سلسلة لهذا السلسلة والسلاسل المرتبطة بها. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.HasSeriesLines القابلة للقراءة/الكتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat لتنسيق خطوط السلسلة. Boolean للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.HasSeriesLines.

**القيمة المرجعة:**  
boolean  

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

يحدد مقدار تداخل الأعمدة والشرائط في المخططات الثنائية الأبعاد، كنسبة مئوية (من -100% إلى 100%). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية. إنها إسقاط للخاصية المناسبة في مجموعة السلسلة الأصلية، وبالتالي هذه الخاصية للقراءة فقط. لتغيير القيمة، استخدم خاصية ParentSeriesGroup.Overlap القابلة للقراءة/الكتابة. byte للقراءة فقط.

--------------------

يحدد Overlap درجة التداخل أو المسافة بين الأعمدة والشرائط كنسبة مئوية من عرضها: -100%: أقصى مسافة (الأعمدة منفصلة تمامًا). 0%: توضع الأعمدة جنبًا إلى جنب بدون تداخل أو مسافة. 100%: أقصى تداخل (الأعمدة تتداخل تمامًا). هذه هي إسقاط الخاصية ParentSeriesGroup.Overlap.

**القيمة المرجعة:**  
byte  

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و200 بالمئة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.SecondPieSize القابلة للقراءة/الكتابة لتغيير القيمة. int للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.SecondPieSize.

**القيمة المرجعة:**  
int  

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تتواجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. يُستخدم مع خاصية PieSplitBy. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitPosition القابلة للقراءة/الكتابة لتغيير القيمة. double للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.PieSplitPosition.

**القيمة المرجعة:**  
double  

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تتواجد في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitBy القابلة للقراءة/الكتابة لتغيير القيمة. [PieSplitType](../../com.aspose.slides/piesplittype) للقراءة فقط.

--------------------

1) هذه هي إسقاط الخاصية ParentSeriesGroup.PieSplitBy. 2) إذا كانت قيمة الخاصية PieSplitType.Custom يمكنك تعريف معلومات تقسيم مخصصة باستخدام خاصية ParentSeriesGroup.PieSplitCustomPoints.

**القيمة المرجعة:**  
int  

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونات (يمكن أن يكون بين 10 و90 بالمئة من حجم مساحة الرسم). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.DoughnutHoleSize القابلة للقراءة/الكتابة لتغيير القيمة. byte للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.DoughnutHoleSize.

**القيمة المرجعة:**  
byte  

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونات، بالدرجات (مع اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. وبالتالي هذه الخاصية للقراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.FirstSliceAngle القابلة للقراءة/الكتابة لتغيير القيمة. int للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.FirstSliceAngle.

**القيمة المرجعة:**  
int  

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات التقسيم المخصصة لمخطط pie-of-pie أو bar-of-pie مع تقسيم مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط pie-of-pie أو bar-of-pie. هذه الخاصية ليست خاصة بهذه السلسلة فقط بل بجميع سلاسل مجموعة السلسلة الأصلية – هي إسقاط للخاصية المناسبة في المجموعة. [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection) للقراءة فقط.

--------------------

هذه هي إسقاط الخاصية ParentSeriesGroup.PieSplitCustomPoints.

**القيمة المرجعة:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Specifies how the bubble size values are represented on the bubble chart. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeRepresentation read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**الإرجاع:**
int