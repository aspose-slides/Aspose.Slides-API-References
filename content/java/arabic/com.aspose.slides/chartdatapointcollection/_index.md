---
title: ChartDataPointCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة من نقاط بيانات السلسلة.
type: docs
url: /ar/com.aspose.slides/chartdatapointcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

يمثل مجموعة من نقاط بيانات السلسلة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع نقطه بيانات السلسلة حسب الفهرس (رقمها التسلسلي في هذه المجموعة). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | يرجع الفهرس (الرقم التسلسلي) لنقطة البيانات في هذه المجموعة. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | يحدد أنواع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات بالفهرس index فإنها تُعيد هذه النقطة. |
| [size()](#size--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمهام). |
| [getSyncRoot()](#getSyncRoot--) | يرجع جذر التزامن. |
| [iterator()](#iterator--) | يرجع تعدادًا (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يرجع مكرِّرًا (iterator) جافا للمجموعة بأكملها. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | يزيل القيمة المحددة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

يرجع نقطه بيانات السلسلة حسب الفهرس (رقمها التسلسلي في هذه المجموعة).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

يرجع الفهرس (الرقم التسلسلي) لنقطة البيانات في هذه المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**الإرجاع:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية XValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.XValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية YValue لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.YValue.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية BubbleSize لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.BubbleSize.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**الإرجاع:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

يحدد ما إذا كان الخاصية AsCell أو AsLiteralString أو AsLiteralDouble هي الفعلية في كائن الخاصية Value لنقاط البيانات. بعبارة أخرى يحدد نوع القيمة لخاصية ChartDataPoint.Value.Data. قراءة/كتابة [DataSourceType](../../com.aspose.slides/datasourcetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

يحدد أنواع القيم في قائمة خصائص ChartDataPoint.ErrorBarsCustomValues. قراءة فقط [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**الإرجاع:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

إذا كانت المجموعة تحتوي بالفعل على نقطة بيانات بالفهرس index فإنها تُعيد هذه النقطة. إذا لم تحتوِ المجموعة على نقطة بيانات بالفهرس index==N (عندما يكون عدد نقاط البيانات في هذه المجموعة أقل أو يساوي N) فإنها تُضيف نقاط بيانات ناقصة وتُعيد الأخيرة (التي لها الفهرس المطلوب). على سبيل المثال، فهارس المجموعة هي \{0, 1, 2\}، والفهرس المطلوب هو 5. ثم تُضيف الطريقة نقاط بيانات ناقصة: \{0, 1, 2, 3, 4, 5\}. وتُعيد نقطة البيانات بالفهرس 5.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | long | الفهرس. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - يُعيد نقطة البيانات بالفهرس المطلوب.
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

**الإرجاع:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

نسخ إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة للنسخ إليها. |
| arrayIndex | int | الفهرس لبدء النسخ. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يرجع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للمهام). قراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يرجع جذر التزامن. قراءة فقط Object.

**الإرجاع:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

يرجع تعدادًا (enumerator) يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

يرجع مكرِّرًا (iterator) جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

يخلق نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية Stock (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Stock (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Line (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Line (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات. |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Scatter (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Radar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Radar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Column أو Bar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Column أو Bar (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) و [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Area (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Area (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Pie (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Pie (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Doughnut (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Doughnut (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | قيمة نقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | حجم الفقاع لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | حجم الفقاع لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | قيمة X لنقطة البيانات |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | حجم الفقاع لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | حجم الفقاع لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | قيمة X لنقطة البيانات |
| yValue | double | قيمة Y لنقطة البيانات |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | حجم الفقاع لنقطة البيانات |

**الإرجاع:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة بيانات جديدة.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

ينشئ نقطة بيانات جديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType فيها أحد الأنواع الفرعية من Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | double | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Bubble (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| xValue | java.lang.String | نقطة البيانات XValue |
| yValue | double | نقطة البيانات YValue |
| bubbleSize | double | نقطة البيانات BubbleSize |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Surface (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون chartType الخاص بها أحد الأنواع الفرعية لـ Surface (انظر أيضًا طريقة [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Sunburst.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات SizeValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Treemap.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات SizeValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو BoxAndWhisker.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Waterfall.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Histogram.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Funnel.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات Value |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

ينشئ نقطة البيانات الجديدة ويضيفها إلى نهاية المجموعة. ينطبق على السلاسل التي يكون نوع المخطط الخاص بها هو Map.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | نقطة البيانات ColorValue |

**الإرجاع:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - نقطة البيانات الجديدة.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | القيمة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة البيانات التي تُزال. |