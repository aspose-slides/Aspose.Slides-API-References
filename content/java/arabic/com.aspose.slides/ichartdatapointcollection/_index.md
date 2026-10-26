---
title: IChartDataPointCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
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
| [get_Item(int index)](#get-Item-int-) | Returns the series data point by index (its serial number in this collection). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Return index (serial number in this collection) of data point in this collection. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specifies the type of values in ChartDataPoint.ErrorBarsCustomValues properties list. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | If collection already contains data point with index index then returns this data point. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the given index. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

يرجع نقطة بيانات السلسلة حسب الفهرس (رقمها التسلسلي في هذه المجموعة).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

يرجع الفهرس (رقم التسلسل في هذه المجموعة) لنقطة البيانات في هذه المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**الإرجاع:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPointEx.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

يحدد ما إذا كانت خاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن خاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

يحدد نوع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues. قراءة فقط [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**الإرجاع:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات بالفه index فإنها تُرجع هذه النقطة. إذا لم تحتوِ المجموعة على نقطة بيانات بالفه index==N (عندما يكون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تُضيف نقاط بيانات ناقصة وتُرجع الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، فهارس المجموعة هي {0, 1, 2}، والفهرس المطلوب هو 5. عندئذٍ تُضيف الطريقة نقاط البيانات الناقصة: {0, 1, 2, 3, 4, 5}. وتُرجع نقطة البيانات بالفه 5.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | long | الفهرس. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - تُرجع نقطة البيانات بالفه المطلوب.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلة التي يكون chartType أحد الأنواع الفرعية لـ Stock (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلة التي يكون chartType أحد الأنواع الفرعية لـ Stock (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChatDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلة التي يكون chartType أحد الأنواع الفرعية لـ Line (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلة التي يكون chartType أحد الأنواع الفرعية لـ Line (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلسلة التي يكون chartType أحد الأنواع الفرعية لـ Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Scatter (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Radar (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Radar (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Column أو Bar (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Column أو Bar (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeColumn(ChartType) و ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Area (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeArea(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Area (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeArea(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Pie (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypePie(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Pie (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypePie(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Doughnut (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Doughnut (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Surface (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Surface (انظر أيضًا طريقة ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Sunburst.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Waterfall.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها BoxAndWhisker.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Treemap.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Histogram.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Funnel.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chart type الخاص بها Map.

--------------------

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


**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع العناصر من المجموعة.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


يزيل القيمة المحددة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر عند الفهرس المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات التي سيتم إزالتها. |