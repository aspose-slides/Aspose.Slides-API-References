---
title: IChartSeries
second_title: مرجع API لجافا لـ Aspose.Slides لنظام Android
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
| [getExplosion()](#getExplosion--) | المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. |
| [setExplosion(int value)](#setExplosion-int-) | المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. |
| [getSmooth()](#getSmooth--) | يمثل تنعيم المنحنى. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | يمثل تنعيم المنحنى. |
| [getMarker()](#getMarker--) | إرجاع علامة السلسلة. |
| [getBar3DShape()](#getBar3DShape--) | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. |
| [getName()](#getName--) | إرجاع اسم السلسلة. |
| [getDataPoints()](#getDataPoints--) | يرجع مجموعة نقاط البيانات لهذه السلسلة. |
| [getType()](#getType--) | يرجع نوعًا لهذه السلسلة. |
| [setType(int value)](#setType-int-) | يرجع نوعًا لهذه السلسلة. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | يرجع مجموعة السلسلة الأصلية. |
| [getFormat()](#getFormat--) | يرجع تنسيق السلسلة. |
| [getOrder()](#getOrder--) | يرجع ترتيب السلسلة. |
| [setOrder(int value)](#setOrder-int-) | يرجع ترتيب السلسلة. |
| [getLabels()](#getLabels--) | يرجع التسميات الخاصة بالسلسلة. |
| [getTrendLines()](#getTrendLines--) | مجموعة خطوط الاتجاه للسلسلة قراءة فقط [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | يمثل أشرطة الخطأ للسلسلة باتجاه X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | يمثل أشرطة الخطأ للسلسلة باتجاه Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور القيمي الثانوي. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور القيمي الثانوي. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | يرجع أو يضبط تنسيق الرقم لقيم السلسلة. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | يرجع أو يضبط تنسيق الرقم لقيم السلسلة. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | يرجع أو يضبط تنسيق الرقم لقيم X الخاصة بالسلسلة. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | يرجع أو يضبط تنسيق الرقم لقيم X الخاصة بالسلسلة. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | يرجع أو يضبط تنسيق الرقم لقيم Y الخاصة بالسلسلة. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | يرجع أو يضبط تنسيق الرقم لقيم Y الخاصة بالسلسلة. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | يرجع أو يضبط تنسيق الرقم لأحجام الفقاعات في السلسلة. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | يرجع أو يضبط تنسيق الرقم لأحجام الفقاعات في السلسلة. |
| [getInvertIfNegative()](#getInvertIfNegative--) | يحدد أن السلسلة الشريطية أو العمودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | يحدد أن السلسلة الشريطية أو العمودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سلبية. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | يحدد عكس اللون الصلب للسلسلة. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | يمثل مدخل المفتاح المرتبط بهذه السلسلة قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | يرجع لونًا تلقائيًا للسلسلة استنادًا إلى فهرس السلسلة ونمط المخطط. |
| [getShowInnerPoints()](#getShowInnerPoints--) | يمثل النقاط الداخلية. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | يمثل النقاط الداخلية. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | يمثل نقاط القيم المتطرفة. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | يمثل نقاط القيم المتطرفة. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | يمثل علامات المتوسط. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | يمثل علامات المتوسط. |
| [getShowMeanLine()](#getShowMeanLine--) | يمثل علامات المتوسط. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | يمثل علامات المتوسط. |
| [getQuartileMethod()](#getQuartileMethod--) | يمثل طريقة الربعيات. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | يمثل طريقة الربعيات. |
| [getShowConnectorLines()](#getShowConnectorLines--) | يمثل خطوط الوصل. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | يمثل خطوط الوصل. |
| [getParentLabelLayout()](#getParentLabelLayout--) | يمثل تخطيط تسميات الفئة الأصلية. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | يمثل تخطيط تسميات الفئة الأصلية. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المائة من الحجم الافتراضي). |
| [hasUpDownBars()](#hasUpDownBars--) | يحدد ما إذا كان مخطط الخط أو مخطط الأسهم يحتوي على أشرطة صعود/نزول. |
| [getGapWidth()](#getGapWidth--) | يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض العمود أو الشريط. |
| [getGapDepth()](#getGapDepth--) | يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. |
| [isColorVaried()](#isColorVaried--) | يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. |
| [hasSeriesLines()](#hasSeriesLines--) | يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل المرتبطة. |
| [getOverlap()](#getOverlap--) | يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). |
| [getSecondPieSize()](#getSecondPieSize--) | يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المائة). |
| [getPieSplitPosition()](#getPieSplitPosition--) | يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة. |
| [getPieSplitBy()](#getPieSplitBy--) | يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | يحدد حجم الفتحة في مخطط الدونت (يمكن أن يكون بين 10 و 90 في المائة من حجم مساحة الرسم). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونت، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | معلومات الانقسام المخصص لمخطط فطيرة-في-فطيرة أو شريط-في-فطيرة مع انقسام مخصص. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة int.

**الإرجاع:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

المسافة بين شريحة فطيرة مفتوحة ومركز مخطط الفطيرة تُعبّر عنها كنسبة مئوية من قطر الفطيرة. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

يمثل تنعيم المنحنى. صحيح إذا كان تنعيم المنحنى مفعلاً لمخطط الخط أو مخطط التبعثر. يُطبق فقط على مخططات الخط والتبعثر المتصلة بالخطوط. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

يمثل تنعيم المنحنى. صحيح إذا كان تنعيم المنحنى مفعلاً لمخطط الخط أو مخطط التبعثر. يُطبق فقط على مخططات الخط والتبعثر المتصلة بالخطوط. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
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

يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. قد يتسبب تغيير قيمة هذه الخاصية في تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**الإرجاع:**  
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

يحدد شكل سلسلة مخطط شريطي ثلاثي الأبعاد. قد يتسبب تغيير قيمة هذه الخاصية في تغيير نوع السلسلة تلقائيًا. قراءة/كتابة [ChartShapeType](../../com.aspose.slides/chartshapetype).

**المعلمات:**
| المعامل | النوع | الوصف |
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

يرجع مجموعة نقاط البيانات لهذه السلسلة. قراءة فقط [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**الإرجاع:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

يرجع نوعًا لهذه السلسلة. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**الإرجاع:**  
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

يرجع نوعًا لهذه السلسلة. قراءة/كتابة [ChartType](../../com.aspose.slides/charttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

يرجع مجموعة السلسلة الأصلية. قراءة فقط [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**الإرجاع:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

يرجع تنسيق السلسلة. قراءة فقط [IFormat](../../com.aspose.slides/iformat).

**الإرجاع:**  
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

يرجع ترتيب السلسلة. قراءة/كتابة int.

**الإرجاع:**  
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

يرجع ترتيب السلسلة. قراءة/كتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

يرجع التسميات الخاصة بالسلسلة. قراءة فقط [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

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

ErrorBars with X direction are avalible for series of type area, bar, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**الإرجاع:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

يمثل أشرطة الخطأ للسلسلة باتجاه Y. قراءة فقط [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars with Y direction are avalible for series of type area, bar, line, scatter and bubble. For any other types of chart this property returns null (including 3D charts). In case of custom values use DataPoints collection to specify value (with ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) property).

**الإرجاع:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور القيمي الثانوي. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

يشير إلى ما إذا كانت هذه السلسلة مرسومة على المحور القيمي الثانوي. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

يرجع أو يضبط تنسيق الرقم لقيم السلسلة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

يرجع أو يضبط تنسيق الرقم لقيم السلسلة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

يرجع أو يضبط تنسيق الرقم لقيم X الخاصة بالسلسلة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

يرجع أو يضبط تنسيق الرقم لقيم X الخاصة بالسلسلة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

يرجع أو يضبط تنسيق الرقم لقيم Y الخاصة بالسلسلة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

يرجع أو يضبط تنسيق الرقم لقيم Y الخاصة بالسلسلة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

يرجع أو يضبط تنسيق الرقم لأحجام الفقاعات في السلسلة. قراءة/كتابة String.

**الإرجاع:**  
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

يرجع أو يضبط تنسيق الرقم لأحجام الفقاعات في السلسلة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

يحدد أن السلسلة الشريطية أو العمودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

يحدد أن السلسلة الشريطية أو العمودية أو الفقاعية يجب أن تعكس ألوانها إذا كانت القيمة سلبية. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

يحدد عكس اللون الصلب للسلسلة. لتطبيق إعداد اللون اضبط Format FillType للسلسلة إلى FillType.Solid. قراءة/كتابة [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

يمثل مدخل المفتاح المرتبط بهذه السلسلة قراءة فقط [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**الإرجاع:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

يرجع لونًا تلقائيًا للسلسلة استنادًا إلى فهرس السلسلة ونمط المخطط. هذا اللون يُستخدم بشكل افتراضي إذا كان FillType يساوي NotDefined.

**الإرجاع:**  
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

يمثل النقاط الداخلية. صحيح إذا كانت النقاط الداخلية معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

يمثل النقاط الداخلية. صحيح إذا كانت النقاط الداخلية معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

يمثل نقاط القيم المتطرفة. صحيح إذا كانت نقاط القيم المتطرفة معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

يمثل نقاط القيم المتطرفة. صحيح إذا كانت نقاط القيم المتطرفة معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

يمثل علامات المتوسط. صحيح إذا كانت علامات المتوسط معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

يمثل علامات المتوسط. صحيح إذا كانت علامات المتوسط معروضة في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

يمثل علامات المتوسط. صحيح إذا كان خط المتوسط معروضًا في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**الإرجاع:**  
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

يمثل علامات المتوسط. صحيح إذا كان خط المتوسط معروضًا في مخطط BoxAndWhisker. يُطبق فقط على مخططات BoxAndWhisker. قراءة/كتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

يمثل طريقة الربعيات. يُطبق فقط على مخططات BoxAndWhisker.

**الإرجاع:**  
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

يمثل طريقة الربعيات. يُطبق فقط على مخططات BoxAndWhisker.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

يمثل خطوط الوصل. يُطبق فقط على مخططات Waterfall.

**الإرجاع:**  
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

يمثل خطوط الوصل. يُطبق فقط على مخططات Waterfall.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

يمثل تخطيط تسميات الفئة الأصلية. يُطبق فقط على مخططات Treemap.

**الإرجاع:**  
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

يحدد عامل المقياس لمخطط الفقاعات (يمكن أن يكون بين 0 و 300 في المائة من الحجم الافتراضي). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeScale قراءة/كتابة لتغيير القيمة.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**الإرجاع:**  
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

يحدد ما إذا كان مخطط الخط أو مخطط الأسهم يحتوي على أشرطة صعود/نزول. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.UpDownBars.HasUpDownBars قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.UpDownBars للتهيئة. قراءة فقط boolean.

--------------------

This is the projection of the property ParentSeriesGroup.UpDownBars.HasUpDownBars.

**الإرجاع:**  
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

يحدد المسافة بين مجموعات الأشرطة أو الأعمدة كنسبة مئوية من عرض العمود أو الشريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapWidth قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

This is the projection of the property ParentSeriesGroup.GapWidth.

**الإرجاع:**  
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

يرجع أو يضبط المسافة، كنسبة مئوية من عرض العلامة، بين سلاسل البيانات في مخطط ثلاثي الأبعاد. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.GapDepth قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

This is the projection of the property ParentSeriesGroup.GapDepth.

**الإرجاع:**  
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

يحدد أن كل علامة بيانات في السلسلة لها لون مختلف. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.IsColorVaried قراءة/كتابة لتغيير القيمة. قراءة فقط boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**الإرجاع:**  
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

يحدد ما إذا كانت هناك خطوط سلاسل لهذه السلسلة والسلاسل المرتبطة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.HasSeriesLines قراءة/كتابة لتغيير القيمة. استخدم خاصية ParentSeriesGroup.SeriesLinesFormat للتهيئة. قراءة فقط boolean.

--------------------

This is the projection of the property ParentSeriesGroup.HasSeriesLines.

**الإرجاع:**  
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

يحدد مقدار تداخل الأشرطة والأعمدة في المخططات ثنائية الأبعاد، كنسبة مئوية (من -100٪ إلى 100٪). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية. هي إسقاط للخاصية المناسبة في مجموعة السلسلة الأصلية، وبالتالي هذه الخاصية قراءة فقط. لتغيير القيمة، استخدم خاصية ParentSeriesGroup.Overlap قراءة/كتابة. قراءة فقط byte.

--------------------

Overlap specifies the degree of overlap or spacing between bars and columns as a percentage of their width: - -100%: Maximum spacing (bars are completely separated). - 0%: Bars are placed side by side without overlap or spacing. - 100%: Maximum overlap (bars completely overlap each other). This is a projection of the property ParentSeriesGroup.Overlap.

**الإرجاع:**  
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

يحدد حجم الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة، كنسبة مئوية من حجم الفطيرة الأولى (يمكن أن يكون بين 5 و 200 في المائة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.SecondPieSize قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

This is the projection of the property ParentSeriesGroup.SecondPieSize.

**الإرجاع:**  
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

يحدد قيمة تُستخدم لتحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة. يُستخدم مع خاصية PieSplitBy. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitPosition قراءة/كتابة لتغيير القيمة. قراءة فقط double.

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitPosition.

**الإرجاع:**  
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

يحدد كيفية تحديد أي نقاط البيانات تكون في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-فطيرة. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.PieSplitBy قراءة/كتابة لتغيير القيمة. قراءة فقط [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) This is the projection of the property ParentSeriesGroup.PieSplitBy. 2) If property value is PieSplitType.Custom then you can define custom split information with ParentSeriesGroup.PieSplitCustomPoints property.

**الإرجاع:**  
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

يحدد حجم الفتحة في مخطط الدونت (يمكن أن يكون بين 10 و 90 في المائة من حجم مساحة الرسم). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.DoughnutHoleSize قراءة/كتابة لتغيير القيمة. قراءة فقط byte.

--------------------

This is the projection of the property ParentSeriesGroup.DoughnutHoleSize.

**الإرجاع:**  
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

يحدد زاوية الشريحة الأولى في مخطط الفطيرة أو الدونت، بالدرجات (في اتجاه عقارب الساعة من الأعلى، من 0 إلى 360 درجة). هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup للوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.FirstSliceAngle قراءة/كتابة لتغيير القيمة. قراءة فقط int.

--------------------

This is the projection of the property ParentSeriesGroup.FirstSliceAngle.

**الإرجاع:**  
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

معلومات الانقسام المخصص لمخطط فطيرة-في-فطيرة أو شريط-في-شريط مع انقسام مخصص. يحتوي على نقاط البيانات التي يجب رسمها في الفطيرة أو الشريط الثاني في مخطط فطيرة-في-فطيرة أو شريط-في-شريط. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة قراءة فقط [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

This is the projection of the property ParentSeriesGroup.PieSplitCustomPoints.

**الإرجاع:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

يحدد كيفية تمثيل قيم حجم الفقاعات في مخطط الفقاعات. هذه الخاصية ليست فقط لهذه السلسلة بل لجميع سلاسل مجموعة السلسلة الأصلية - هي إسقاط للخاصية المناسبة للمجموعة. وبالتالي هذه الخاصية قراءة فقط. استخدم خاصية ParentSeriesGroup لالوصول إلى مجموعة السلسلة الأصلية. استخدم خاصية ParentSeriesGroup.BubbleSizeRepresentation قراءة/كتابة لتغيير القيمة.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeRepresentation.

**الإرجاع:**  
int