---
title: IChartDataPointCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مجموعة من نقاط بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/ichartdatapointcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

يمثل مجموعة من نقاط بيانات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد نقطة بيانات السلسلة بحسب الفهرس (رقمها المتسلسل في هذه المجموعة). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | يعيد الفهرس (الرقم المتسلسل في هذه المجموعة) لنقطة البيانات في هذه المجموعة. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية XValue لنقاط البيانات. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية XValue لنقاط البيانات. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية YValue لنقاط البيانات. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية YValue لنقاط البيانات. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية BubbleSize لنقاط البيانات. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية BubbleSize لنقاط البيانات. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية Value لنقاط البيانات. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية Value لنقاط البيانات. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | يحدد نوع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات بالفهرس index، فتعيد هذه النقطة. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

**الإرجاع:**
يعيد نقطة بيانات السلسلة بحسب الفهرس (رقمها المتسلسل في هذه المجموعة).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

**الإرجاع:**
يعيد الفهرس (الرقم المتسلسل في هذه المجموعة) لنقطة البيانات في هذه المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**القيمة المرجعة:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPointEx.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

**الإرجاع:**
يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

**الإرجاع:**
يحدد ما وإذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble فعّالة في كائن خاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة الخاصة بـ ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

**الإرجاع:**
يحدد نوع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues. للقراءة فقط [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**القيمة المرجعة:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

**الإرجاع:**
إذا كانت المجموعة تحتوي على نقطة بيانات بالفهرس index فإنها تعيد هذه النقطة. إذا لم تحتوِ المجموعة على نقطة بيانات بالفهرس index==N (عندما يكون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تضيف نقاط بيانات مفقودة وتعيد الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، الفهارس في المجموعة هي {0, 1, 2}، والفهرس المطلوب هو 5. عندئذٍ تضيف الطريقة نقاط البيانات المفقودة: {0, 1, 2, 3, 4, 5}. وتعيد نقطة البيانات ذات الفهرس 5.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | long | الفهرس. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - يعيد نقطة البيانات ذات الفهرس المطلوب.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Stock الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Stock الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Line الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Line الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Scatter الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Radar الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Radar الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Column أو Bar الفرعية (انظر أيضًا الطريقتين ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Column أو Bar الفرعية (انظر أيضًا الطريقتين ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Area الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Area الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Pie الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Pie الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Doughnut الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Doughnut الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

**الإرجاع:**
ينشؤ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Bubble الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | double | قيمة BubbleSize لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Surface الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها أحد أنواع Surface الفرعية (انظر أيضًا الطريقة ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Sunburst.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة SizeValue لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Waterfall.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها BoxAndWhisker.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Treemap.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة SizeValue لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Histogram.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

**الإرجاع:**
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Funnel.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. صالح للسلاسل التي يكون نوع المخطط الخاص بها Map.

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة ColorValue لنقطة البيانات |

**القيمة المرجعية:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### clear() {#clear--}
```
public abstract void clear()
```

**الإرجاع:**
يزيل جميع العناصر من المجموعة.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

**الإرجاع:**
يزيل القيمة المحددة.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

**الإرجاع:**
يزيل العنصر في الفهرس المحدد.

**المعاملات::
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات المراد إزالتها. |