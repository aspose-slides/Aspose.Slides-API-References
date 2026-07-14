---
title: IChartSeries
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getExplosion()](#getExplosion--) | एक खुले पाई स्लाइस की पाई चार्ट के केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [setExplosion(int value)](#setExplosion-int-) | एक खुले पाई स्लाइस की पाई चार्ट के केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। |
| [getSmooth()](#getSmooth--) | वक्र स्मूदिंग का प्रतिनिधित्व करता है। |
| [setSmooth(boolean value)](#setSmooth-boolean-) | वक्र स्मूदिंग का प्रतिनिधित्व करता है। |
| [getMarker()](#getMarker--) | श्रृंखला मार्कर लौटाता है। |
| [getBar3DShape()](#getBar3DShape--) | 3-D बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-D बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। |
| [getName()](#getName--) | श्रृंखला का नाम लौटाता है। |
| [getDataPoints()](#getDataPoints--) | इस श्रृंखला के डेटा बिंदुओं का संग्रह लौटाता है। |
| [getType()](#getType--) | इस श्रृंखला का प्रकार लौटाता है। |
| [setType(int value)](#setType-int-) | इस श्रृंखला का प्रकार लौटाता है। |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | पैरेंट श्रृंखला समूह लौटाता है। |
| [getFormat()](#getFormat--) | एक श्रृंखला का फ़ॉर्मेट लौटाता है। |
| [getOrder()](#getOrder--) | एक श्रृंखला का क्रम लौटाता है। |
| [setOrder(int value)](#setOrder-int-) | एक श्रृंखला का क्रम लौटाता है। |
| [getLabels()](#getLabels--) | एक श्रृंखला के लेबल लौटाता है। |
| [getTrendLines()](#getTrendLines--) | श्रृंखला ट्रेंड लाइनों का संग्रह केवल पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)। |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X दिशा वाले श्रृंखला की ErrorBars का प्रतिनिधित्व करता है। |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y दिशा वाले श्रृंखला की ErrorBars का प्रतिनिधित्व करता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | बताता है कि यह श्रृंखला द्वितीय मान अक्ष पर प्लॉट की गई है या नहीं। |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | बताता है कि यह श्रृंखला द्वितीय मान अक्ष पर प्लॉट की गई है या नहीं। |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | श्रृंखला मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | श्रृंखला मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | श्रृंखला X मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | श्रृंखला X मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | श्रृंखला Y मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | श्रृंखला Y मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | श्रृंखला बबल आकारों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | श्रृंखला बबल आकारों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | बार, कॉलम या बबल श्रृंखला का रंग नकारात्मक होने पर उलटा होना चाहिए, यह निर्धारित करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | बार, कॉलम या बबल श्रृंखला का रंग नकारात्मक होने पर उलटा होना चाहिए, यह निर्धारित करता है। |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | श्रृंखला के लिए इनवर्ट सॉलिड रंग निर्दिष्ट करता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस श्रृंखला से संबंधित लीजेंड एंट्री का प्रतिनिधित्व करता है केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | श्रृंखला सूचकांक और चार्ट शैली के आधार पर श्रृंखला का स्वचालित रंग लौटाता है। |
| [getShowInnerPoints()](#getShowInnerPoints--) | भीतर के बिंदुओं का प्रतिनिधित्व करता है। |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | भीतर के बिंदुओं का प्रतिनिधित्व करता है। |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | आउट्लायर बिंदुओं का प्रतिनिधित्व करता है। |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | आउट्लायर बिंदुओं का प्रतिनिधित्व करता है। |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | औसत मार्करों का प्रतिनिधित्व करता है। |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | औसत मार्करों का प्रतिनिधित्व करता है। |
| [getShowMeanLine()](#getShowMeanLine--) | औसत मार्करों का प्रतिनिधित्व करता है। |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | औसत मार्करों का प्रतिनिधित्व करता है। |
| [getQuartileMethod()](#getQuartileMethod--) | चतुर्थांश विधि का प्रतिनिधित्व करता है। |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | चतुर्थांश विधि का प्रतिनिधित्व करता है। |
| [getShowConnectorLines()](#getShowConnectorLines--) | कनेक्टर लाइनों का प्रतिनिधित्व करता है। |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | कनेक्टर लाइनों का प्रतिनिधित्व करता है। |
| [getParentLabelLayout()](#getParentLabelLayout--) | पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक हो सकता है)। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि लाइन या स्टॉक चार्ट में अप/डाउन बार है या नहीं। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर्स के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में प्राप्त या सेट करता है। |
| [isColorVaried()](#isColorVaried--) | निर्दिष्ट करता है कि श्रृंखला के प्रत्येक डेटा मार्कर का रंग अलग हो। |
| [hasSeriesLines()](#hasSeriesLines--) | निर्धारित करता है कि इस श्रृंखला और संबंधित श्रृंखलाओं के लिए श्रृंखला लाइनें हैं या नहीं। |
| [getOverlap()](#getOverlap--) | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप होते हैं, प्रतिशत में ( -100% से 100% तक) निर्धारित करता है। |
| [getSecondPieSize()](#getSecondPieSize--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से clockwise, 0 से 360 डिग्री)। |
| [getPieSplitPosition()](#getPieSplitPosition--) | एक मान निर्दिष्ट करता है जिसका उपयोग यह तय करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [getPieSplitBy()](#getPieSplitBy--) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत तक)। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से clockwise, 0 से 360 डिग्री)। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाए, यह निर्दिष्ट करता है। |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

एक खुले पाई स्लाइस की पाई चार्ट के केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

एक खुले पाई स्लाइस की पाई चार्ट के केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

वक्र स्मूदिंग का प्रतिनिधित्व करता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूदिंग चालू है तो true। केवल लाइन और स्कैटर, जो लाइनों से जुड़े हैं, पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

वक्र स्मूदिंग का प्रतिनिधित्व करता है। यदि लाइन चार्ट या स्कैटर चार्ट में वक्र स्मूदिंग चालू है तो true। केवल लाइन और स्कैटर, जो लाइनों से जुड़े हैं, पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

श्रृंखला मार्कर लौटाता है। केवल पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**रिटर्न:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

3-D बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी का मान बदलने से स्वचालित रूप से श्रृंखला का प्रकार बदल सकता है। पढ़ने/लिखने योग्य [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**रिटर्न:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

3-D बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी का मान बदलने से स्वचालित रूप से श्रृंखला का प्रकार बदल सकता है। पढ़ने/लिखने योग्य [ChartShapeType](../../com.aspose.slides/chartshapetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

श्रृंखला का नाम लौटाता है। केवल पढ़ने योग्य [IStringChartValue](../../com.aspose.slides/istringchartvalue)।

**रिटर्न:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

इस श्रृंखला के डेटा बिंदुओं का संग्रह लौटाता है। केवल पढ़ने योग्य [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)।

**रिटर्न:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public abstract int getType()
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ने/लिखने योग्य [ChartType](../../com.aspose.slides/charttype)।

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ने/लिखने योग्य [ChartType](../../com.aspose.slides/charttype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

पैरेंट श्रृंखला समूह लौटाता है। केवल पढ़ने योग्य [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)।

**रिटर्न:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

एक श्रृंखला का फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

एक श्रृंखला का क्रम लौटाता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

एक श्रृंखला का क्रम लौटाता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

एक श्रृंखला के लेबल लौटाता है। केवल पढ़ने योग्य [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)।

**रिटर्न:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

श्रृंखला ट्रेंड लाइनों का संग्रह केवल पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)।

**रिटर्न:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

X दिशा वाले श्रृंखला की ErrorBars का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

X दिशा वाले ErrorBars केवल area, bar, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**रिटर्न:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Y दिशा वाले श्रृंखला की ErrorBars का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

Y दिशा वाले ErrorBars केवल area, bar, line, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी के साथ)।

**रिटर्न:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

बताता है कि यह श्रृंखला द्वितीय मान अक्ष पर प्लॉट की गई है या नहीं। पढ़ने/लिखने योग्य बूलियान।

**रिटर्न:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

बताता है कि यह श्रृंखला द्वितीय मान अक्ष पर प्लॉट की गई है या नहीं। पढ़ने/लिखने योग्य बूलियान।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

श्रृंखला मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

श्रृंखला मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

श्रृंखला X मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

श्रृंखला X मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

श्रृंखला Y मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

श्रृंखला Y मानों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

श्रृंखला बबल आकारों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**रिटर्न:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

श्रृंखला बबल आकारों के लिए संख्या स्वरूप को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य String।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

बार, कॉलम या बबल श्रृंखला का रंग नकारात्मक होने पर उलटा होना चाहिए, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

बार, कॉलम या बबल श्रृंखला का रंग नकारात्मक होने पर उलटा होना चाहिए, यह निर्धारित करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

श्रृंखला के लिए इनवर्ट सॉलिड रंग निर्दिष्ट करता है। रंग सेटिंग लागू करने के लिए श्रृंखला फ़ॉर्मेट का FillType FillType.Solid पर सेट करें। पढ़ने/लिखने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

इस श्रृंखला से संबंधित लीजेंड एंट्री का प्रतिनिधित्व करता है केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

श्रृंखला सूचकांक और चार्ट शैली के आधार पर श्रृंखला का स्वचालित रंग लौटाता है। यह रंग डिफ़ॉल्ट रूप से उपयोग होता है यदि FillType NotDefined के बराबर है।

**रिटर्न:**
java.lang.Integer - Automatic color of series java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

भीतर के बिंदुओं का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में भीतर के बिंदु दिखाए जाते हैं तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

भीतर के बिंदुओं का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में भीतर के बिंदु दिखाए जाते हैं तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

आउटलायर बिंदुओं का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में आउट्लायर बिंदु दिखाए जाते हैं तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

आउटलायर बिंदुओं का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में आउट्लायर बिंदु दिखाए जाते हैं तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

औसत मार्करों का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में औसत मार्कर दिखाया जाए तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

औसत मार्करों का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में औसत मार्कर दिखाया जाए तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

औसत मार्करों का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में औसत लाइन दिखाया जाए तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

औसत मार्करों का प्रतिनिधित्व करता है। यदि BoxAndWhisker चार्ट में औसत लाइन दिखाया जाए तो true। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

चतुर्थांश विधि का प्रतिनिधित्व करता है। केवल BoxAndWhisker चार्ट पर लागू।

**रिटर्न:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

चतुर्थांश विधि का प्रतिनिधित्व करता है। केवल BoxAndWhisker चार्ट पर लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

कनेक्टर लाइनों का प्रतिनिधित्व करता है। केवल Waterfall चार्ट पर लागू।

**रिटर्न:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

कनेक्टर लाइनों का प्रतिनिधित्व करता है। केवल Waterfall चार्ट पर लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट पर लागू।

**रिटर्न:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट पर लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक हो सकता है)। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.BubbleSizeScale का प्रोजेक्शन है।

**रिटर्न:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

निर्धारित करता है कि लाइन या स्टॉक चार्ट में अप/डाउन बार है या नहीं। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेटिंग के लिए ParentSeriesGroup.UpDownBars प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.UpDownBars.HasUpDownBars का प्रोजेक्शन है।

**रिटर्न:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

बार या कॉलम क्लस्टर्स के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.GapWidth का प्रोजेक्शन है।

**रिटर्न:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में प्राप्त या सेट करता है। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.GapDepth का प्रोजेक्शन है।

**रिटर्न:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

निर्दिष्ट करता है कि श्रृंखला के प्रत्येक डेटा मार्कर का रंग अलग हो। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.IsColorVaried का प्रोजेक्शन है।

**रिटर्न:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

निर्धारित करता है कि इस श्रृंखला और संबंधित श्रृंखलाओं के लिए श्रृंखला लाइनें हैं या नहीं। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंच के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेटिंग के लिए ParentSeriesGroup.SeriesLinesFormat प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य बूलियन।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.HasSeriesLines का प्रोजेक्शन है।

**रिटर्न:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D चार्ट में बार और कॉलम कितनी ओवरलैप होते हैं, प्रतिशत में ( -100% से 100% तक) निर्धारित करता है। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है। यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है, इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte।

--------------------

ओवरलैप बार और कॉलम के बीच ओवरलैप या स्पेसिंग को उनके चौड़ाई के प्रतिशत में निर्दिष्ट करता है: -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)। 0%: बिना ओवरलैप या स्पेसिंग के साइड बाय साइड। 100%: अधिकतम ओवरलैप (बार पूरी तरह ओवरलैप)। यह प्रॉपर्टी ParentSeriesGroup.Overlap का प्रोजेक्शन है।

**रिटर्न:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से clockwise, 0 से 360 डिग्री)। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.SecondPieSize का प्रोजेक्शन है।

**रिटर्न:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

एक मान निर्दिष्ट करता है जिसका उपयोग यह तय करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य double।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.PieSplitPosition का प्रोजेक्शन है।

**रिटर्न:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

निर्दिष्ट करता है कि पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह कैसे तय किया जाए। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

--------------------

1) यह प्रॉपर्टी ParentSeriesGroup.PieSplitBy का प्रोजेक्शन है। 2) यदि प्रॉपर्टी मान PieSplitType.Custom है तो आप ParentSeriesGroup.PieSplitCustomPoints प्रॉपर्टी के साथ कस्टम स्प्लिट जानकारी परिभाषित कर सकते हैं।

**रिटर्न:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत तक)। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य byte।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.DoughnutHoleSize का प्रोजेक्शन है।

**रिटर्न:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से clockwise, 0 से 360 डिग्री)। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य int।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.FirstSliceAngle का प्रोजेक्शन है।

**रिटर्न:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। उन डेटा पॉइंट्स को शामिल करता है जिन्हें दूसरे पाई या बार में ड्रॉ किया जाना चाहिए। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है केवल पढ़ने योग्य [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.PieSplitCustomPoints का प्रोजेक्शन है।

**रिटर्न:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाए, यह निर्दिष्ट करता है। यह प्रॉपर्टी न केवल इस श्रृंखला की बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं की भी है - यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें।

--------------------

यह प्रॉपर्टी ParentSeriesGroup.BubbleSizeRepresentation का प्रोजेक्शन है।

**रिटर्न:**
int