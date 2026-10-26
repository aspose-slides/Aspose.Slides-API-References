---
title: ChartDataPointCollection
second_title: Aspose.Slides لـ Android عبر مرجع API Java
description: يمثل مجموعة من نقاط بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/chartdatapointcollection/
---
**الوراثة:**  
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

يمثل مجموعة من نقاط البيانات لسلسلة.

## الطرق

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يُرجِع نقطة البيانات السلسلة حسب الفهرس (رقمها التسلسلي في هذه المجموعة). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | يُرجِع الفهرس (الرقم التسلسلي) لنقطة البيانات في هذه المجموعة. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | يحدد أنواع القيم في قائمة الخصائص ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | إذا كانت المجموعة تحتوي مسبقًا على نقطة بيانات بالفهرس المحدد فإنها تُرجِع هذه النقطة. |
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يُرجِع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن متعدد الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يُرجِع جذر التزامن. |
| [iterator()](#iterator--) | يُرجِع عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يُرجِع عدّاد جافا للمجموعة بأكملها. |
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
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

يُرجِع نقطة البيانات السلسلة حسب الفهرس (رقمها التسلسلي في هذه المجموعة).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

يُرجِع الفهرس (الرقم التسلسلي) لنقطة البيانات في هذه المجموعة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**القيمة المرجعة:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceForXValues(int value)
```

يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

يحدد ما إذا كانت الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

يحدد ما إذا كانت الخاصةية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

يحدد ما إذا كانت الخاصةية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

يحدد ما إذا كانت الخاصةية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

يحدد ما إذا كانت الخاصةية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**القيمة المرجعة:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

يحدد ما إذا كانت الخاصةية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع قيمة خاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

يحدد أنواع القيم في قائمة الخصائص ChartDataPoint.ErrorBarsCustomValues. قراءة فقط [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**القيمة المرجعة:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

إذا كانت المجموعة تحتوي مسبقًا على نقطة بيانات بالفهرس المحدد فإنها تُرجِع هذه النقطة. إذا لم تكن المجموعة تحتوي على نقطة بيانات بالفهرس index==N (عند كون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تضيف نقاط بيانات ناقصة وتُرجِع الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، فهارس المجموعة هي {0, 1, 2}، والفهرس المطلوب هو 5. عندها تُضيف الطريقة نقاطًا ناقصة: {0, 1, 2, 3, 4, 5}. وتُرجِع نقطة البيانات بالفهرس 5.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long | الفهرس. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - يُرجِع نقطة البيانات بالفهرس المطلوب.

### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. قراءة فقط int.

**القيمة المرجعة:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

نسخ إلى المصفوفة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة التي سيُنسخ إليها. |
| arrayIndex | int | الفهرس الذي يبدأ النسخ منه. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يُرجِع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن متعدد الخيوط). قراءة فقط boolean.

**القيمة المرجعة:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يُرجِع جذر التزامن. قراءة فقط Object.

**القيمة المرجعة:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

يُرجِع عدّادًا يتنقل عبر المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

يُرجِع عدّاد جافا للمجموعة بأكملها.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator للمجموعة بأكملها.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Stock (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Stock (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Line (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Line (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Radar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Radar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Column أو Bar (انظر أيضًا طريقتي [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و[ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Column أو Bar (انظر أيضًا طريقتي [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و[ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Area (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Area (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Pie (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Pie (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Doughnut (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Doughnut (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات::
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | XValue نقطة البيانات |
| yValue | double | YValue نقطة البيانات |
| bubbleSize | double | BubbleSize نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Surface (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها أحد أنواع Surface (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Sunburst.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Treemap.

**المعلمات::
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها BoxAndWhisker.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Waterfall.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Histogram.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Funnel.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. يُطبق على السلاسل التي يكون نوع المخطط فيها Map.

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


**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue نقطة البيانات |

**القيمة المرجعة:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

يزيل القيمة المحددة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات التي تُزال. |