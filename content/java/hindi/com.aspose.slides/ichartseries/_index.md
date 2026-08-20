---
title: IChartSeries
second_title: Aspose.Slides for Java API संदर्भ
description: एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartseries/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getExplosion()](#getExplosion--) | एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [setExplosion(int value)](#setExplosion-int-) | एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [getSmooth()](#getSmooth--) | वक्र स्मूथिंग को दर्शाता है। |
| [setSmooth(boolean value)](#setSmooth-boolean-) | वक्र स्मूथिंग को दर्शाता है। |
| [getMarker()](#getMarker--) | श्रृंखला मार्कर लौटाता है। |
| [getBar3DShape()](#getBar3DShape--) | 3-D बार चार्ट की श्रृंखला के आकार को निर्दिष्ट करता है। |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D बार चार्ट की श्रृंखला के आकार को निर्दिष्ट करता है। |
| [getName()](#getName--) | श्रृंखला का नाम लौटाता है। |
| [getDataPoints()](#getDataPoints--) | इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। |
| [getType()](#getType--) | इस श्रृंखला का प्रकार लौटाता है। |
| [setType(int value)](#setType-int-) | इस श्रृंखला का प्रकार लौटाता है। |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | पैरेंट श्रृंखला समूह लौटाता है। |
| [getFormat()](#getFormat--) | एक श्रृंखला का फ़ॉर्मेट लौटाता है। |
| [getOrder()](#getOrder--) | एक श्रृंखला का क्रम लौटाता है। |
| [setOrder(int value)](#setOrder-int-) | एक श्रृंखला का क्रम लौटाता है। |
| [getLabels()](#getLabels--) | एक श्रृंखला के लेबल्स लौटाता है। |
| [getTrendLines()](#getTrendLines--) | श्रृंखला ट्रेंड लाइन्स का संग्रह केवल-पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)। |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | यदि यह श्रृंखला दूसरे वैल्यू अक्ष पर प्लॉट की गई है तो संकेत देता है। |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | यदि यह श्रृंखला दूसरे वैल्यू अक्ष पर प्लॉट की गई है तो संकेत देता है। |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | श्रृंखला मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | श्रृंखला मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | श्रृंखला X मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | श्रृंखला X मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | श्रृंखला Y मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | श्रृंखला Y मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | श्रृंखला बबल आकारों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | श्रृंखला बबल आकारों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक है तो बार, कॉलम या बबल श्रृंखला के रंग उलटे जाएँगे यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक है तो बार, कॉलम या बबल श्रृंखला के रंग उलटे जाएँगे यह निर्दिष्ट करता है। |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस श्रृंखला से संबंधित लेजेंड एंट्री को दर्शाता है केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | श्रृंखला इंडेक्स और चार्ट शैली के आधार पर स्वचालित रंग लौटाता है। |
| [getShowInnerPoints()](#getShowInnerPoints--) | आंतरिक बिंदुओं को दर्शाता है। |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | आंतरिक बिंदुओं को दर्शाता है। |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | आउटलेयर बिंदुओं को दर्शाता है। |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | आउटलेयर बिंदुओं को दर्शाता है। |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | औसत मार्कर्स को दर्शाता है। |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | औसत मार्कर्स को दर्शाता है। |
| [getShowMeanLine()](#getShowMeanLine--) | औसत मार्कर्स को दर्शाता है। |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | औसत मार्कर्स को दर्शाता है। |
| [getQuartileMethod()](#getQuartileMethod--) | क्वार्टाइल विधि को दर्शाता है। |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | क्वार्टाइल विधि को दर्शाता है। |
| [getShowConnectorLines()](#getShowConnectorLines--) | कनेक्टर लाइन्स को दर्शाता है। |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | कनेक्टर लाइन्स को दर्शाता है। |
| [getParentLabelLayout()](#getParentLabelLayout--) | पैरेंट श्रेणी लेबल्स की लेआउट को दर्शाता है। |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | पैरेंट श्रेणी लेबल्स की लेआउट को दर्शाता है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि लाइन या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर्स के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच, मार्कर चौड़ाई के प्रतिशत के रूप में दूरी लौटाता या सेट करता है। |
| [isColorVaried()](#isColorVaried--) | निर्धारित करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होगा। |
| [hasSeriesLines()](#hasSeriesLines--) | निर्धारित करता है कि इस श्रृंखला और संबंधित श्रृंखलाओं के लिए श्रृंखला लाइनें हैं या नहीं। |
| [getOverlap()](#getOverlap--) | 2-D चार्ट्स में बार और कॉलम ओवरलैप का प्रतिशत निर्दिष्ट करता है (-100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत के रूप में (5 से 200 प्रतिशत के बीच)। |
| [getPieSplitPosition()](#getPieSplitPosition--) | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं। |
| [getPieSplitBy()](#getPieSplitBy--) | निर्धारित करता है कि किस प्रकार निर्धारित किया जाए कि कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत के बीच)। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट पर बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, यह निर्दिष्ट करता है। |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ें/लिखें int.

**परिणाम:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

वक्र स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूधिंग चालू है तो true। केवल लाइनों द्वारा जुड़े लाइन और स्कैटर चार्ट्स पर लागू होता है। पढ़ें/लिखें boolean.

**परिणाम:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

वक्र स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूधिंग चालू है तो true। केवल लाइनों द्वारा जुड़े लाइन और स्कैटर चार्ट्स पर लागू होता है। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

श्रृंखला मार्कर लौटाता है। केवल-पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**परिणाम:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-D बार चार्ट की श्रृंखला के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी के मूल्य को बदलने से श्रृंखला का प्रकार स्वचालित रूप से बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**परिणाम:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-D बार चार्ट की श्रृंखला के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी के मूल्य को बदलने से श्रृंखला का प्रकार स्वचालित रूप से बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

श्रृंखला का नाम लौटाता है। केवल-पढ़ने योग्य [IStringChartValue](../../com.aspose.slides/istringchartvalue)।

**परिणाम:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)।

**परिणाम:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**परिणाम:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

पैरेंट श्रृंखला समूह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)।

**परिणाम:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

एक श्रृंखला का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**परिणाम:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

एक श्रृंखला का क्रम लौटाता है। पढ़ें/लिखें int।

**परिणाम:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

एक श्रृंखला का क्रम लौटाता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

एक श्रृंखला के लेबल्स लौटाता है। केवल-पढ़ने योग्य [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)।

**परिणाम:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

श्रृंखला ट्रेंड लाइन्स का संग्रह केवल-पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)।

**परिणाम:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

X दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

ErrorBars X दिशा में area, bar, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों (3D सहित) के लिए यह प्रॉपर्टी null लौटाती है। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**परिणाम:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Y दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

ErrorBars Y दिशा में area, bar, line, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों (3D सहित) के लिए यह प्रॉपर्टी null लौटाती है। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**परिणाम:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

यदि यह श्रृंखला दूसरे वैल्यू अक्ष पर प्लॉट की गई है तो संकेत देता है। पढ़ें/लिखें boolean।

**परिणाम:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

यदि यह श्रृंखला दूसरे वैल्यू अक्ष पर प्लॉट की गई है तो संकेत देता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

श्रृंखला मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**परिणाम:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

श्रृंखला मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

श्रृंखला X मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**परिणाम:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

श्रृंखला X मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

श्रृंखला Y मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**परिणाम:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberOfValues(String value)
```

श्रृंखला Y मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

श्रृंखला बबल आकारों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**परिणाम:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

श्रृंखला बबल आकारों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ें/लिखें String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

यदि मान नकारात्मक है तो बार, कॉलम या बबल श्रृंखला के रंग उलटे जाएँगे यह निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**परिणाम:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक है तो बार, कॉलम या बबल श्रृंखला के रंग उलटे जाएँगे यह निर्दिष्ट करता है। पढ़ें/लिंखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। रंग सेटिंग लागू करने के लिए श्रृंखला फ़ॉर्मेट FillType को FillType.Solid पर सेट करें। पढ़ें/लिखें [IColorFormat](../../com.aspose.slides/icolorformat)।

**परिणाम:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

इस श्रृंखला से संबंधित लेजेंड एंट्री को दर्शाता है केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**परिणाम:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**रिटर्न:**
java.awt.Color - सीरीज़ का स्वचालित रंग java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

आंतरिक बिंदुओं को दर्शाता है। True यदि आंतरिक बिंदु BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhiskर charts पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

आंतरिक बिंदुओं को दर्शाता है। True यदि आंतरिक बिंदु BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

आउटलायर बिंदुओं को दर्शाता है। True यदि आउटलायर बिंदु BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

आउटलायर बिंदुओं को दर्शाता है। True यदि आउटलायर बिंदु BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

औसत मार्करों को दर्शाता है। True यदि औसत मार्कर BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

औसत मार्करों को दर्शाता है। True यदि औसत मार्कर BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

औसत रेखा को दर्शाता है। True यदि औसत रेखा BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

औसत रेखा को दर्शाता है। True यदि औसत रेखा BoxAndWhisker चार्ट पर दिखाए गए हों। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू।

**रिटर्न:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू।

**रिटर्न:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

पैरेंट कैटेगरी लेबल्स की लेआउट को दर्शाता है। केवल Treemap चार्ट पर लागू।

**रिटर्न:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

पैरेंट कैटेगरी लेबल्स की लेआउट को दर्शाता है। केवल Treemap चार्ट पर लागू।

**पैरामीटर:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें।

--------------------

यह ParentSeriesGroup.BubbleSizeScale प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

निर्धारित करता है कि Line- या Stock-चार्ट में अप/डाउन बार हैं या नहीं। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फॉर्मेटिंग के लिए ParentSeriesGroup.UpDownBars प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह ParentSeriesGroup.UpDownBars.HasUpDownBars प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

बार या कॉलम क्लस्टर्स के बीच की जगह को प्रतिशत के रूप में निर्दिष्ट करता है। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.GapWidth प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D चार्ट में डेटा सीरीज़ के बीच की दूरी को प्रतिशत के रूप में (मार्कर की चौड़ाई के प्रतिशत) निर्दिष्ट करता है। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.GapDepth प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

निर्दिष्ट करता है कि सीरीज़ में प्रत्येक डेटा मार्कर का रंग अलग हो। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह ParentSeriesGroup.IsColorVaried प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

निर्धारित करता है कि इस सीरीज़ और सम्बद्ध सीरीज़ के लिए सीरीज़ लाइन्स हैं या नहीं। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेटिंग के लिए ParentSeriesGroup.SeriesLinesFormat प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह ParentSeriesGroup.HasSeriesLines प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D चार्ट में बार और कॉलम के ओवरलैप को प्रतिशत के रूप में निर्दिष्ट करता है (-100% से 100% तक)। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte।

--------------------

ओवरलैप बार और कॉलम की चौड़ाई के प्रतिशत के रूप में ओवरलैप या स्पेसिंग की डिग्री को निर्दिष्ट करता है:
- -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)।
- 0%: बार बिना ओवरलैप या स्पेसिंग के बगल में रखे गए।
- 100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलेप)।

यह ParentSeriesGroup.Overlap प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरा पाई या बार का आकार निर्दिष्ट करता है, पहला पाई के आकार का प्रतिशत (5%-200% के बीच) के रूप में। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.SecondPieSize प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में यह निर्धारित करने के लिए उपयोग किया जाने वाला मान कि किन डेटा पॉइंट्स को दूसरे पाई या बार में रखा जाए, निर्दिष्ट करता है। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य double।

--------------------

यह ParentSeriesGroup.PieSplitPosition प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

निर्धारित करता है कि पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में किन डेटा पॉइंट्स को दूसरे पाई या बार में रखा जाए। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

--------------------

1) यह ParentSeriesGroup.PieSplitBy प्रॉपर्टी का प्रक्षेपण है। 2) यदि प्रॉपर्टी मान PieSplitType.Custom है तो आप ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी के साथ कस्टम स्प्लिट जानकारी परिभाषित कर सकते हैं।

**रिटर्न:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार का 10%-90% के बीच)। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte।

--------------------

यह ParentSeriesGroup.DoughnutHoleSize प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0-360 डिग्री)।

यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुंचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.FirstSliceAngle प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम स्प्लिट जानकारी पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कस्टम स्प्लिट के साथ होती है। इसमें डेटा पॉइंट्स होते हैं जिन्हें दूसरे पाई या बार में ड्रॉ किया जाना चाहिए। यह केवल इस सीरीज़ का नहीं, बल्कि पैरेंट सीरीज़ समूह के सभी सीरीज़ का प्रॉपर्टी प्रोजेक्शन है। केवल पढ़ने योग्य [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)।

--------------------

यह ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी का प्रक्षेपण है।

**रिटर्न:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
निर्दिष्ट करता है कि बबल चार्ट पर बबल आकार मान कैसे प्रदर्शित किए जाते हैं। यह प्रॉपर्टी न केवल इस श्रृंखला की है बल्कि पैरेंट सीरीज़ समूह की सभी श्रृंखलाओं की भी है - यह संबंधित समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य (read-only) है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation read/write प्रॉपर्टी का उपयोग करें।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.BubbleSizeRepresentation का प्रोजेक्शन है।

**रिटर्न:**  
int