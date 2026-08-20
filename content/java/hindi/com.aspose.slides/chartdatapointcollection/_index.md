---
title: ChartDataPointCollection
second_title: Aspose.Slides for Java API संदर्भ
description: एक श्रृंखला डेटा बिंदु का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartdatapointcollection/
---
**उत्पत्ति:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

एक श्रृंखला डेटा बिंदु का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | सीरीज डेटा पॉइंट को इंडेक्स द्वारा लौटाता है (इस संग्रह में इसका क्रमांक)। |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | डेटा पॉइंट का इंडेक्स (क्रमांक) इस संग्रह में लौटाता है। |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | निर्दिष्ट करता है कि डेटा पॉइंट के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | निर्दिष्ट करता है कि डेटा पॉइंट के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | निर्दिष्ट करता है कि डेटा पॉइंट के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | निर्दिष्ट करता है कि डेटा पॉइंट के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | निर्दिष्ट करता है कि डेटा पॉइंट के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | निर्दिष्ट करता है कि डेटा पॉइंट के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | निर्दिष्ट करता है कि डेटा पॉइंट के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | निर्दिष्ट करता है कि डेटा पॉइंट के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार निर्दिष्ट करता है। |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | यदि संग्रह में पहले से ही index इंडेक्स वाला डेटा पॉइंट मौजूद है तो यह डेटा पॉइंट लौटाता है। |
| [size()](#size--) | संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ़) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समक्रमण मूल (रूट) लौटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है। |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए इंडेक्स पर स्थित तत्व को हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

सीरीज डेटा पॉइंट को इंडेक्स द्वारा लौटाता है (इस संग्रह में इसका क्रमांक)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

डेटा पॉइंट का इंडेक्स (क्रमांक) इस संग्रह में लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**रिटर्न:**  
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

निर्दिष्ट करता है कि डेटा पॉइंट के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न:**  
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceForXValues(int value)
```

निर्दिष्ट करता है कि डेटा पॉइंट के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

निर्दिष्ट करता है कि डेटा पॉइंट के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न:**  
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

निर्दिष्ट करता है कि डेटा पॉइंट के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

निर्दिष्ट करता है कि डेटा पॉइंट के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न:**  
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

निर्दिष्ट करता है कि डेटा पॉइंट के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

निर्दिष्ट करता है कि डेटा पॉइंट के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**रिटर्न:**  
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

निर्दिष्ट करता है कि डेटा पॉइंट के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तव में मौजूद है या नहीं। अन्य शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार निर्दिष्ट करता है। केवल-पढ़ने योग्य [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)।

**रिटर्न:**  
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

यदि संग्रह में पहले से ही index इंडेक्स वाला डेटा पॉइंट मौजूद है तो यह डेटा पॉइंट लौटाता है। यदि संग्रह में index==N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट की संख्या N से कम या बराबर हो) तो यह अपर्याप्त डेटा पॉइंट जोड़ता है और अंतिम (जो अनुरोधित इंडेक्स है) लौटाता है। उदाहरण के लिए, संग्रह के इंडेक्स {0, 1, 2} हैं, और अनुरोधित इंडेक्स 5 है। तब मेथड अपर्याप्त डेटा पॉइंट जोड़ता है: {0, 1, 2, 3, 4, 5}। और इंडेक्स 5 वाला डेटा पॉइंट लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | long | इंडेक्स। |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - अनुरोधित इंडेक्स वाला डेटा पॉइंट लौटाता है।

### size() {#size--}
```
public final int size()
```

संग्रह में वास्तव में मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

निर्दिष्ट एरे में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | कॉपी करने के लिए एरे। |
| arrayIndex | int | कॉपी शुरू करने का इंडेक्स। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुंच समक्रमित (थ्रेड-सेफ़) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समक्रमण मूल (रूट) लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न:**  
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

पूरे संग्रह के लिए एक जावा इटेरेटर लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्टॉक उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) मेथड देखें)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान। |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्टॉक उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान। |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType लाइन उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान। |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType लाइन उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान। |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType स्कैटर उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType रडार उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType रडार उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType कॉलम या बार उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) और [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType कॉलम या बार उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) और [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType एरिया उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType एरिया उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType पाई उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType पाई उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType डोनट उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType डोनट उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट मान |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू होता है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType सतह उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType सतह उपप्रकारों में से एक है ([ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) मेथड को भी देखें)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type सनबर्स्ट है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type ट्रीमैप है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type बॉक्सएंडह्विस्कर है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type वाटरफ़ॉल है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type हिस्टोग्राम है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type फ़नल है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**रिटर्न:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type मैप है।

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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट ColorValue |

**रिटर्न:**  
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

निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने के लिए डेटा पॉइंट का इंडेक्स। |