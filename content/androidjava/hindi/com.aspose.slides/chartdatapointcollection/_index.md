---
title: ChartDataPointCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक श्रृंखला डेटा पॉइंट का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartdatapointcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

एक श्रृंखला डेटा पॉइंट का संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इस संग्रह में क्रमांक (सीरियल नंबर) द्वारा श्रृंखला डेटा पॉइंट लौटाता है। |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | इस संग्रह में डेटा पॉइंट का अनुक्रमणिका (सीरियल नंबर) लौटाता है। |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टीज़ सूची में मानों के प्रकार निर्दिष्ट करता है। |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | यदि संग्रह में पहले से ही वही अनुक्रमणिका वाला डेटा पॉइंट मौजूद है तो वह डेटा पॉइंट लौटाता है। |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | यह दर्शाता है कि क्या संग्रह तक पहुँच समकालिक (थ्रेड-सुरक्षित) है। |
| [getSyncRoot()](#getSyncRoot--) | एक समकालिक मूल लौटाता है। |
| [iterator()](#iterator--) | वह एन्यूमेरेटर लौटाता है जो संग्रह को इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गये अनुक्रमणिका पर तत्व को हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

इस संग्रह में क्रमांक (सीरियल नंबर) द्वारा श्रृंखला डेटा पॉइंट लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

इस संग्रह में डेटा पॉइंट का अनुक्रमणिका (सीरियल नंबर) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**रिटर्न मान:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। केवल-पढ़ने-योग्य [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न मान:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। केवल-पढ़ने-योग्य [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न मान:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। केवल-पढ़ने-योग्य [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न मान:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न मान:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। अन्य शब्दों में, यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टीज़ सूची में मानों के प्रकार निर्दिष्ट करता है। केवल-पढ़ने-योग्य [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)।

**रिटर्न मान:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

यदि संग्रह में पहले से ही वही अनुक्रमणिका वाला डेटा पॉइंट मौजूद है तो वह डेटा पॉइंट लौटाता है। यदि संग्रह में अनुक्रमणिका index==N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N या उससे कम है) तो कमी वाले डेटा पॉइंट्स जोड़ता है और अंतिम (जिसका अनुरोधित अनुक्रमणिका है) लौटाता है। उदाहरण के लिए, संग्रह अनुक्रमणिकाएँ {0, 1, 2} हैं, और अनुरोधित अनुक्रमणिका 5 है। तब मेथड कमी वाले डेटा पॉइंट्स जोड़ता है: {0, 1, 2, 3, 4, 5}। और अनुक्रमणिका 5 वाले डेटा पॉइंट को लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | long | अनुक्रमणिका। |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - अनुरोधित अनुक्रमणिका वाला डेटा पॉइंट लौटाता है।

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने-योग्य int।

**रिटर्न मान:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | कॉपी करने के लिये एरे। |
| arrayIndex | int | कॉपी शुरू करने की अनुक्रमणिका। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

यह दर्शाता है कि क्या संग्रह तक पहुँच समकालिक (थ्रेड-सेफ़) है। केवल-पढ़ने-योग्य boolean।

**रिटर्न मान:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समकालिक मूल लौटाता है। केवल-पढ़ने-योग्य Object।

**रिटर्न मान:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

एक एन्यूमेरेटर लौटाता है जो संग्रह को इटररेट करता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - एक IGenericEnumerator जिसे संग्रह को इटररेट करने के लिये उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

पूरे संग्रह के लिये एक जावा इटेरेटर लौटाता है।

**रिटर्न मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - पूरे संग्रह के लिये एक java.util.Iterator।

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Stock उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू। |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Stock उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू। |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Line उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू। |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Line उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू। |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Scatter उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Radar उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Radar उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Column या Bar उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) और [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Column या Bar उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) और [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Area उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Area उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Pie उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Pie उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Doughnut उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Doughnut उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Bubble उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Surface उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनकी chartType Surface उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Sunburst है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```




I love you

```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Treemap है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type BoxAndWhisker है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Waterfall है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Histogram है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Funnel है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट वैल्यू |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और संग्रह के अंत में जोड़ता है। उन श्रृंखलाओं के लिये लागू है जिनका chart type Map है।

---

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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट ColorValue |

**रिटर्न मान:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### clear() {#clear--}
```
public final void clear()
```

सभी तत्वों को संग्रह से हटाता है।

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

निर्दिष्ट मान को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | वह मान। |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

दिए गये अनुक्रमणिका पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले डेटा पॉइंट की अनुक्रमणिका। |