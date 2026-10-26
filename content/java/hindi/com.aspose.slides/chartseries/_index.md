---
title: ChartSeries
second_title: Aspose.Slides for Java API संदर्भ
description: एक चार्ट सीरीज़ को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartseries/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

एक चार्ट श्रृंखला को दर्शाता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट चार्ट को लौटाता है। |
| [getExplosion()](#getExplosion--) | पाई चार्ट के एक खुले स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [setExplosion(int value)](#setExplosion-int-) | पाई चार्ट के एक खुले स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [getSmooth()](#getSmooth--) | वक्र स्मूथिंग को दर्शाता है। |
| [setSmooth(boolean value)](#setSmooth-boolean-) | वक्र स्मूथिंग को दर्शाता है। |
| [getName()](#getName--) | सीरीज़ नाम लौटाता है। |
| [getDataPoints()](#getDataPoints--) | इस सीरीज़ के डेटा पॉइंट्स का संग्रह लौटाता है। |
| [getType()](#getType--) | इस सीरीज़ का प्रकार लौटाता है। |
| [setType(int value)](#setType-int-) | इस सीरीज़ का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | निर्दिष्ट करता है कि यह सीरीज़ द्वितीयक अक्ष पर प्लॉट किया गया है या नहीं। |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | निर्दिष्ट करता है कि यह सीरीज़ द्वितीयक अक्ष पर प्लॉट किया गया है या नहीं। |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup। |
| [getFormat()](#getFormat--) | एक सीरीज़ का फॉर्मेट लौटाता है। |
| [getOrder()](#getOrder--) | एक सीरीज़ का क्रम लौटाता है। |
| [setOrder(int value)](#setOrder-int-) | एक सीरीज़ का क्रम लौटाता है। |
| [getLabels()](#getLabels--) | एक सीरीज़ के लेबल्स लौटाता है। |
| [getTrendLines()](#getTrendLines--) | सीरीज़ ट्रेंड लाइनों का संग्रह। |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस सीरीज़ से संबंधित लेजेंड एंट्री को दर्शाता है। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues। |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues। |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues। |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues। |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues। |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues। |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes। |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes। |
| [getMarker()](#getMarker--) | Marker। |
| [getBar3DShape()](#getBar3DShape--) | 3-D बार चार्ट की एक सीरीज़ के आकार को निर्दिष्ट करता है। |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D बार चार्ट की एक सीरीज़ के आकार को निर्दिष्ट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | बार, कॉलम या बबल सीरीज़ को नकारात्मक मान होने पर उसके रंग उलटने के लिए निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | बार, कॉलम या बबल सीरीज़ को नकारात्मक मान होने पर उसके रंग उलटने के लिए निर्धारित करता है। |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | सीरीज़ के लिए उलटा ठोस रंग निर्दिष्ट करता है। |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | सीरीज़ के इंडेक्स और चार्ट शैली के आधार पर स्वचलित रंग लौटाता है। |
| [getShowInnerPoints()](#getShowInnerPoints--) | आंतरिक बिंदुओं को दर्शाता है। |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | आंतरिक बिंदुओं को दर्शाता है। |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | बहिर्प्रमुख बिंदुओं को दर्शाता है। |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | बहिर्प्रमुख बिंदुओं को दर्शाता है। |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | औसत मार्कर को दर्शाता है। |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | औसत मार्कर को दर्शाता है। |
| [getShowMeanLine()](#getShowMeanLine--) | औसत रेखा को दर्शाता है। |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | औसत रेखा को दर्शाता है। |
| [getQuartileMethod()](#getQuartileMethod--) | चतुर्थांश विधि को दर्शाता है। |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | चतुर्थांश विधि को दर्शाता है। |
| [getShowConnectorLines()](#getShowConnectorLines--) | कनेक्टर लाइनों को दर्शाता है। |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | कनेक्टर लाइनों को दर्शाता है। |
| [getParentLabelLayout()](#getParentLabelLayout--) | पैरेंट श्रेणी लेबल्स की लेआउट को दर्शाता है। |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | पैरेंट श्रेणी लेबल्स की लेआउट को दर्शाता है। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि लाइन या स्टॉक चार्ट में ऊपर/नीचे बार हैं या नहीं। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर्स के बीच अंतर को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा सीरीज़ के बीच दूरी को मार्कर की चौड़ाई के प्रतिशत में लौटाता या सेट करता है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत के बीच)। |
| [getOverlap()](#getOverlap--) | 2-D चार्ट में बार और कॉलम के ओवरलैप को प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)। |
| [hasSeriesLines()](#hasSeriesLines--) | निर्धारित करता है कि इस सीरीज़ और संबंधित सीरीज़ के लिए सीरीज़ लाइन्स हैं या नहीं। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट में बबल आकार मानों को कैसे प्रस्तुत किया जाए, इसे निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौनसे डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने के लिए उपयोग होने वाला मान निर्दिष्ट करता है। |
| [getPieSplitBy()](#getPieSplitBy--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौनसे डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने की विधि को निर्दिष्ट करता है। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। |
| [isColorVaried()](#isColorVaried--) | निर्दिष्ट करता है कि सीरीज़ के प्रत्येक डेटा मार्कर का अलग रंग है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। |
| [getSlide()](#getSlide--) | FillFormat की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रस्तुति लौटाता है। |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**रिटर्न:**  
com.aspose.slides.IDOMObject  

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट को लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)  

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

पाई चार्ट के एक खुले स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ें/लिखें int।

**रिटर्न:**  
int  

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

पाई चार्ट के एक खुले स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

वक्र स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूथिंग चालू है तो true होता है। केवल लाइन और स्कैटर (लाइन से जुड़ी) चार्ट पर लागू होता है। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean  

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

वक्र स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूथिंग चालू है तो true होता है। केवल लाइन और स्कैटर (लाइन से जुड़ी) चार्ट पर लागू होता है। पढ़ें/लिखें boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

सीरीज़ नाम लौटाता है। केवल-पढ़ने योग्य [IStringChartValue](../../com.aspose.slides/istringchartvalue)।

**रिटर्न:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)  

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

इस सीरीज़ के डेटा पॉइंट्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)।

**रिटर्न:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  

### getType() {#getType--}
```
public final int getType()
```

इस सीरीज़ का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**रिटर्न:**  
int  

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

इस सीरीज़ का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

निर्देश करता है कि यह सीरीज़ द्वितीयक अक्ष पर प्लॉट किया गया है या नहीं। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean  

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

निर्देश करता है कि यह सीरीज़ द्वितीयक अक्ष पर प्लॉट किया गया है या नहीं। पढ़ें/लिखें boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup। केवल-पढ़ने योग्य [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)।

**रिटर्न:**  
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)  

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

एक सीरीज़ का फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**  
[IFormat](../../com.aspose.slides/iformat)  

### getOrder() {#getOrder--}
```
public final int getOrder()
```

एक सीरीज़ का क्रम लौटाता है। पढ़ें/लिखें int।

**रिटर्न:**  
int  

### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

एक सीरीज़ का क्रम लौटाता है। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

एक सीरीज़ के लेबल्स लौटाता है। केवल-पढ़ने योग्य [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)।

**रिटर्न:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

सीरीज़ ट्रेंड लाइनों का संग्रह। केवल-पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)।

--------------------

ट्रेंड लाइन्स अनस्टैक्ड 2-D एरिया, बार, कॉलम, लाइन, स्टॉक, XY (स्कैटर), और बबल चार्ट में डेटा सीरीज़ के लिए उपलब्ध (null नहीं) हैं। स्टैक्ड या 3-D चार्ट प्रकार में ट्रेंडलाइन उपलब्ध नहीं है। रडार, पाई, सरफेस, या डोनट चार्ट में भी ट्रेंडलाइन उपलब्ध नहीं है।

**रिटर्न:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

X दिशा वाले ErrorBars एरिया, बार, स्कैटर और बबल प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**रिटर्न:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

Y दिशा वाले ErrorBars एरिया, बार, लाइन, स्कैटर और बबल प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**रिटर्न:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

इस सीरीज़ से संबंधित लेजेंड एंट्री को दर्शाता है। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**रिटर्न:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)  

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String  

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String  

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String  

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes। पढ़ें/लिखें String।

**रिटर्न:**  
java.lang.String  

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes। पढ़ें/लिखें String।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker। केवल-पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**रिटर्न:**  
[IMarker](../../com.aspose.slides/imarker)  

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

3-D बार चार्ट की एक सीरीज़ के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी का मान बदलने से स्वचालित रूप से सीरीज़ का Type बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**रिटर्न:**  
int  

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3-D बार चार्ट की एक सीरीज़ के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी का मान बदलने से स्वचालित रूप से सीरीज़ का Type बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

बार, कॉलम या बबल सीरीज़ को नकारात्मक मान होने पर उसके रंग उलटने के लिए निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean  

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

बार, कॉलम या बबल सीरीज़ को नकारात्मक मान होने पर उसके रंग उलटने के लिए निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. पढ़ें/लिखें [ColorFormat](../../com.aspose.slides/colorformat).

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

सीरीज़ की इंडेक्स और चार्ट शैली के आधार पर सीरीज़ का स्वचालित रंग लौटाता है। यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है यदि FillType NotDefined के बराबर है।

**वापसी:**
java.awt.Color - The java.awt.Color ऑब्जेक्ट।
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

आंतरिक बिंदुओं को दर्शाता है। True यदि आंतरिक बिंदु BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

आंतरिक बिंदुओं को दर्शाता है। True यदि आंतरिक बिंदु BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

बाहरी बिंदुओं को दर्शाता है। True यदि बाहरी बिंदु BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

बाहरी बिंदुओं को दर्शाता है। True यदि बाहरी बिंदु BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

औसत मार्करों को दर्शाता है। True यदि औसत मार्कर BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

औसत मार्करों को दर्शाता है। True यदि औसत मार्कर BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

औसत रेखा को दर्शाता है। True यदि औसत रेखा BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**वापसी:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

औसत रेखा को दर्शाता है। True यदि औसत रेखा BoxAndWhisker चार्ट पर दिखाए जाते हैं। केवल BoxAndWhisker चार्ट पर लागू होता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू होता है।

**वापसी:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू होता है।

**वापसी:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

पैरेंट श्रेणी लेबल की लेआउट को दर्शाता है। केवल Treemap चार्ट पर लागू होता है।

**वापसी:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

पैरेंट श्रेणी लेबल की लेआउट को दर्शाता है। केवल Treemap चार्ट पर लागू होता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

निर्धारित करता है कि Line- या Stock-चार्ट में अप/डाउन बार हैं या नहीं। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। अप/डाउन बार को फॉर्मेट करने के लिए ParentSeriesGroup.UpDownBars प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य boolean.

--------------------

यह ParentSeriesGroup.UpDownBars.HasUpDownBars प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच की जगह को प्रतिशत के रूप में निर्दिष्ट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int.

--------------------

यह ParentSeriesGroup.GapWidth प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D चार्ट में डेटा सीरीज़ के बीच दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता या सेट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int.

--------------------

यह ParentSeriesGroup.GapDepth प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस के कोण को डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int.

--------------------

यह ParentSeriesGroup.FirstSliceAngle प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

डोनट चार्ट में होल का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10% से 90% तक)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte.

--------------------

यह ParentSeriesGroup.DoughnutHoleSize प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-D चार्ट में बार और कॉलम के ओवरलैप को प्रतिशत के रूप में निर्दिष्ट करता है ( -100% से 100% तक)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है। यह पैरेंट सीरीज़ समूह में उपयुक्त प्रॉपर्टी का प्रोजेक्शन है, इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte.

--------------------

ओवरलैप बार और कॉलम के बीच ओवरलैप या स्पेसिंग की डिग्री को उनके चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है: -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)। 0%: बार साइड बाय साइड बिना ओवरलैप या स्पेसिंग के रखे। 100%: अधिकतम ओवरलैप (बार एक दूसरे के ऊपर पूरी तरह)। यह ParentSeriesGroup.Overlap प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार के आकार को पहले पाई के आकार के प्रतिशत के रूप में निर्दिष्ट करता है (5% से 200% तक)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int.

--------------------

यह ParentSeriesGroup.SecondPieSize प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

निर्धारित करता है कि इस सीरीज़ और संबंधित सीरीज़ के लिए सीरीज़ लाइन्स हैं या नहीं। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। सीरीज़ लाइन्स को फॉर्मेट करने के लिए ParentSeriesGroup.SeriesLinesFormat प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य boolean.

--------------------

यह ParentSeriesGroup.HasSeriesLines प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रतिनिधित्व किया जाता है, यह निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ें/लिखें प्रॉपर्टी का उपयोग करें।

--------------------

यह ParentSeriesGroup.BubbleSizeRepresentation प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य double.

--------------------

यह ParentSeriesGroup.PieSplitPosition प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ें/लिखें प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) यह ParentSeriesGroup.PieSplitBy प्रॉपर्टी का प्रोजेक्शन है। 2) यदि प्रॉपर्टी मान PieSplitType.Custom है तो आप ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी के साथ कस्टम स्प्लिट जानकारी परिभाषित कर सकते हैं।

**वापसी:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी जो कस्टम स्प्लिट के साथ है। इसमें वे डेटा पॉइंट्स होते हैं जिन्हें दूसरे पाई या बार में ड्रॉ किया जाना चाहिए। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ की है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। केवल पढ़ने योग्य [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

यह ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी का प्रोजेक्शन है।

**वापसी:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
निर्देशित करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृंखलाओं का है - यह उपयुक्त समूह गुण का प्रोजेक्शन है। और इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ें/लिखें गुण का उपयोग करें। केवल-पढ़ने योग्य बूलियन।

--------------------

यह ParentSeriesGroup.IsColorVaried गुण का प्रोजेक्शन है।

**रिटर्न:**  
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृंखलाओं का है - यह उपयुक्त समूह गुण का प्रोजेक्शन है। और इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ें/लिखें गुण का उपयोग करें।

--------------------

यह ParentSeriesGroup.BubbleSizeScale गुण का प्रोजेक्शन है।

**रिटर्न:**  
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)