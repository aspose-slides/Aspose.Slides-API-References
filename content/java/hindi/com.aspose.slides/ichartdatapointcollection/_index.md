---
title: IChartDataPointCollection
second_title: Aspose.Slides for Java API संदर्भ
description: एक श्रृंखला डेटा बिंदु का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartdatapointcollection/
---
**सभी लागू इंटरफ़ेस:**  
com.aspose.slides.IGenericCollection  
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

एक श्रृंखला डेटा बिंदु का संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | संग्रह में अनुक्रमणिका (क्रमिक संख्या) द्वारा श्रृंखला डेटा बिंदु लौटाता है। |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | इस संग्रह में डेटा बिंदु की अनुक्रमणिका (क्रमिक संख्या) लौटाता है। |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | डेटा बिंदुओं के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | डेटा बिंदुओं के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | डेटा बिंदुओं के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | डेटा बिंदुओं के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | डेटा बिंदुओं के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | डेटा बिंदुओं के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | डेटा बिंदुओं के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | डेटा बिंदुओं के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार को निर्दिष्ट करता है। |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | यदि संग्रह में पहले से ही इंडेक्स index वाला डेटा बिंदु मौजूद है तो यह डेटा बिंदु लौटाता है। |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए अनुक्रमणिका पर तत्व को हटाता है। |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

संग्रह में अनुक्रमणिका (क्रमिक संख्या) द्वारा श्रृंखला डेटा बिंदु लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

डेटा बिंदु का अनुक्रमणिका (इस संग्रह में क्रमिक संख्या) लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**वापसी:**  
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

डेटा बिंदुओं के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**  
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceForXValues(int value)
```

डेटा बिंदुओं के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

डेटा बिंदुओं के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**  
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

डेटा बिंदुओं के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

डेटा बिंदुओं के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**  
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

डेटा बिंदुओं के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPointEx.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

डेटा बिंदुओं के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**  
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

डेटा बिंदुओं के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं निर्दिष्ट करता है। अन्य शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार को निर्दिष्ट करता है। केवल-पढ़ने [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)।

**वापसी:**  
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

यदि संग्रह में पहले से ही इंडेक्स index वाला डेटा बिंदु मौजूद है तो यह डेटा बिंदु लौटाता है। यदि संग्रह में index==N वाला डेटा बिंदु नहीं है (जब इस संग्रह में डेटा बिंदुओं की संख्या N से कम या बराबर है) तो अपूर्ण डेटा बिंदुओं को जोड़ता है और अंतिम (अनुरोधित इंडेक्स वाला) को लौटाता है। उदाहरण के लिए, संग्रह अनुक्रमणिकाएँ {0, 1, 2} हैं, और अनुरोधित अनुक्रमणिका 5 है। तब मेथड अपूर्ण डेटा बिंदुओं को जोड़ता है: {0, 1, 2, 3, 4, 5}। और अनुक्रमणिका 5 वाला डेटा बिंदु लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | long | अनुक्रमणिका। |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - अनुरोधित अनुक्रमणिका वाला डेटा बिंदु लौटाता है।

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्टॉक उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeStock(ChartType) मेथड)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु मान। |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा बिंदु।

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्टॉक उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeStock(ChartType) मेथड)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु मान। |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा बिंदु।

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType लाइन उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeLine(ChartType) मेथड)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु मान। |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा बिंदु।

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType लाइन उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeLine(ChartType) मेथड)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु मान। |

**वापसी:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा बिंदु।

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

नया डेटा बिंदु बनाता है और संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType स्कैटर उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
...
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Scatter उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | double | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Scatter उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Scatter उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Scatter उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | double | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Scatter उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeScatter(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Radar उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeRadar(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Radar उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeRadar(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Column या Bar उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeColumn(ChartType) और ChartTypeCharacterizer.IsChartTypeBar(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Column या Bar उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeColumn(ChartType) और ChartTypeCharacterizer.IsChartTypeBar(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Area उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeArea(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Area उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeArea(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Pie उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypePie(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Pie उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypePie(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Doughnut उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Doughnut उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double | डेटा बिंदु Value |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | double | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा बिंदु XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | double | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा बिंदु बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType Bubble उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा बिंदु XValue |
| yValue | double | डेटा बिंदु YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा बिंदु BubbleSize |

**रिटर्न:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType बबल उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeBubble(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType सतह उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeSurface(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chartType सतह उपप्रकारों में से एक है (देखें ChartTypeCharacterizer.IsChartTypeSurface(ChartType) मेथड)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type सनबर्स्ट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type वाटरफॉल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type बॉक्सएंडव्हिस्कर है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type ट्रीमैप है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type हिस्टोग्राम है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type फ़नल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

एक नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। यह उन श्रृंखलाओं के लिए लागू है जिनका chart type मैप है।

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


**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

निर्दिष्ट मान को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

दिए गए इंडेक्स पर मौजूद तत्व को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Index of a data point to remove. |