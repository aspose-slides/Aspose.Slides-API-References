---
title: IChartDataPointCollection
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक श्रृंखला डेटा पॉइंट का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartdatapointcollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

श्रृंखला डेटा पॉइंट का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा श्रृंखला डेटा पॉइंट लौटाता है (इस संग्रह में इसका क्रम संख्या)। |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | डेटा पॉइंट का इंडेक्स (इस संग्रह में इसका क्रम संख्या) लौटाता है। |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार को निर्दिष्ट करता है। |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | यदि संग्रह में पहले से ही इंडेक्स index वाला डेटा पॉइंट मौजूद है तो यह डेटा पॉइंट लौटाता है। |
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
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | निर्दिष्ट मान को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | दिए गए इंडेक्स पर तत्व को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

इंडेक्स द्वारा श्रृंखला डेटा पॉइंट लौटाता है (इस संग्रह में इसका क्रम संख्या)।

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

डेटा पॉइंट का इंडेक्स (इस संग्रह में इसका क्रम संख्या) लौटाता है।

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

डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

डेटा पॉइंट्स के XValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.XValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

डेटा पॉइंट्स के YValue प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.YValue.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

डेटा पॉइंट्स के BubbleSize प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPointEx.BubbleSize.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**वापसी:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

डेटा पॉइंट्स के Value प्रॉपर्टी ऑब्जेक्ट में AsCell या AsLiteralString या AsLiteralDouble प्रॉपर्टी वास्तविक है या नहीं, निर्दिष्ट करता है। दूसरे शब्दों में यह ChartDataPoint.Value.Data प्रॉपर्टी के मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [DataSourceType](../../com.aspose.slides/datasourcetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ChartDataPoint.ErrorBarsCustomValues प्रॉपर्टी सूची में मानों के प्रकार को निर्दिष्ट करता है। केवल-पढ़ने योग्य [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)।

**वापसी:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

यदि संग्रह में पहले से ही इंडेक्स index वाला डेटा पॉइंट मौजूद है तो यह डेटा पॉइंट लौटाता है। यदि संग्रह में इंडेक्स index==N वाला डेटा पॉइंट नहीं है (जब इस संग्रह में डेटा पॉइंट्स की संख्या N से कम या बराबर है) तो कमी वाले डेटा पॉइंट्स जोड़ता है और अंतिम (जिसका अनुरोधित इंडेक्स है) लौटाता है। उदाहरण के लिए, संग्रह के सूचकांक {0, 1, 2} हैं, और अनुरोधित सूचकांक 5 है। तब यह विधि कमी वाले डेटा पॉइंट्स जोड़ती है: {0, 1, 2, 3, 4, 5} और सूचकांक 5 वाला डेटा पॉइंट लौटाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | long | सूचकांक। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - अनुरोधित सूचकांक वाला डेटा पॉइंट लौटाता है।
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Stock उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeStock(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Stock उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeStock(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Line उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeLine(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Line उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeLine(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value। |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Scatter उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeScatter(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Radar उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeRadar(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Radar उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeRadar(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Column या Bar उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeColumn(ChartType) और ChartTypeCharacterizer.IsChartTypeBar(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Column या Bar उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeColumn(ChartType) और ChartTypeCharacterizer.IsChartTypeBar(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Area उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeArea(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Area उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeArea(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Pie उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypePie(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Pie उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypePie(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Doughnut उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Doughnut उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | double | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Bubble उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeBubble(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| xValue | java.lang.String | डेटा पॉइंट XValue |
| yValue | double | डेटा पॉइंट YValue |
| bubbleSize | double | डेटा पॉइंट BubbleSize |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Surface उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeSurface(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chartType Surface उपप्रकार में से एक है (देखेँ ChartTypeCharacterizer.IsChartTypeSurface(ChartType) विधि)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Sunburst है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Waterfall है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type BoxAndWhisker है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट Value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Treemap है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट SizeValue |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Histogram है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Funnel है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | डेटा पॉइंट value |

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

नया डेटा पॉइंट बनाता है और इसे संग्रह के अंत में जोड़ता है। उस श्रृंखला के लिए लागू है जिसका chart type Map है।

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

**वापसी:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - नया डेटा पॉइंट।
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | मान। |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

दिए गए इंडेक्स पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाने हेतु डेटा पॉइंट का सूचकांक। |