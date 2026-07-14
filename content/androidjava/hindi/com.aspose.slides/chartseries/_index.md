---
title: ChartSeries
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartseries/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject  
```
public class ChartSeries implements IChartSeries, IDOMObject
```

एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [getExplosion()](#getExplosion--) | एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत में व्यक्त किया जाता है। |
| [setExplosion(int value)](#setExplosion-int-) | एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत में व्यक्त किया जाता है। |
| [getSmooth()](#getSmooth--) | कर्व स्मूदिंग को दर्शाता है। |
| [setSmooth(boolean value)](#setSmooth-boolean-) | कर्व स्मूदिंग को दर्शाता है। |
| [getName()](#getName--) | श्रृंखला का नाम लौटाता है। |
| [getDataPoints()](#getDataPoints--) | इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। |
| [getType()](#getType--) | इस श्रृंखला का प्रकार लौटाता है। |
| [setType(int value)](#setType-int-) | इस श्रृंखला का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | दर्शाता है कि यह श्रृंखला द्वितीयक अक्ष पर प्लॉट हुई है या नहीं। |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | दर्शाता है कि यह श्रृंखला द्वितीयक अक्ष पर प्लॉट हुई है या नहीं। |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup। |
| [getFormat()](#getFormat--) | श्रृंखला का फॉर्मेट लौटाता है। |
| [getOrder()](#getOrder--) | श्रृंखला का क्रम लौटाता है। |
| [setOrder(int value)](#setOrder-int-) | श्रृंखला का क्रम लौटाता है। |
| [getLabels()](#getLabels--) | श्रृंखला के लेबल लौटाता है। |
| [getTrendLines()](#getTrendLines--) | श्रृंखला ट्रेंड लाइनों का संग्रह। |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | X दिशा के साथ श्रृंखला की ErrorBars को दर्शाता है। |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Y दिशा के साथ श्रृंखला की ErrorBars को दर्शाता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस श्रृंखला से संबंधित लेजेंड एंट्री को दर्शाता है, केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)। |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues। |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues। |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues। |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues। |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues। |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues। |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes। |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes। |
| [getMarker()](#getMarker--) | Marker। |
| [getBar3DShape()](#getBar3DShape--) | 3-डी बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। |
| [setBar3DShape(int value)](#setBar3DShape-int-) | 3-डी बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | बार, कॉलम या बबल श्रृंखला को नकारात्मक मान होने पर रंग उलटना चाहिए, यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | बार, कॉलम या बबल श्रृंखला को नकारात्मक मान होने पर रंग उलटना चाहिए, यह निर्दिष्ट करता है। |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | श्रृंखला की इंडेक्स और चार्ट शैली के आधार पर स्वचालित रंग लौटाता है। |
| [getShowInnerPoints()](#getShowInnerPoints--) | आंतरिक बिंदुओं को दर्शाता है। |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | आंतरिक बिंदुओं को दर्शाता है। |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | अपवर्जन बिंदुओं को दर्शाता है। |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | अपवर्जन बिंदुओं को दर्शाता है। |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | औसत मार्करों को दर्शाता है। |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | औसत मार्करों को दर्शाता है। |
| [getShowMeanLine()](#getShowMeanLine--) | औसत रेखा को दर्शाता है। |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | औसत रेखा को दर्शाता है। |
| [getQuartileMethod()](#getQuartileMethod--) | क्वार्टाइल विधि को दर्शाता है। |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | क्वार्टाइल विधि को दर्शाता है। |
| [getShowConnectorLines()](#getShowConnectorLines--) | कनेक्टर लाइनों को दर्शाता है। |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | कनेक्टर लाइनों को दर्शाता है। |
| [getParentLabelLayout()](#getParentLabelLayout--) | पैरेंट श्रेणी लेबल्स के लेआउट को दर्शाता है। |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | पैरेंट श्रेणी लेबल्स के लेआउट को दर्शाता है। |
| [hasUpDownBars()](#hasUpDownBars--) | निर्धारित करता है कि लाइन-या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच की जगह को प्रतिशत में निर्धारित करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखला के बीच की दूरी को प्रतिशत में निर्धारित करता है (मार्कर चौड़ाई के अनुसार)। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहला पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्धारित करता है (ऊपर से घड़ी की दिशा में, 0-360)। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्धारित करता है (प्लॉट क्षेत्र के 10-90 % के बीच)। |
| [getOverlap()](#getOverlap--) | 2-डी चार्ट में बार और कॉलम के ओवरलैप को प्रतिशत में निर्धारित करता है (-100 % से 100 %)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार प्रथम पाई के आकार के प्रतिशत में निर्धारित करता है (5-200 %)। |
| [hasSeriesLines()](#hasSeriesLines--) | निर्धारित करता है कि इस श्रृंखला और सम्बद्ध श्रृंखलाओं के लिए श्रृंखला रेखाएँ हैं या नहीं। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, यह निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। |
| [getPieSplitBy()](#getPieSplitBy--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह निर्धारित करने की विधि को निर्दिष्ट करता है। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम विभाजन जानकारी जो पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कस्टम विभाजन के साथ उपयोग की जाती है। |
| [isColorVaried()](#isColorVaried--) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के स्केल फैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रस्तुति लौटाता है। |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

केवल-पढ़ने योग्य IDOMObject।  
**रिटर्न:**  
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।  
**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत में व्यक्त किया जाता है। पढ़ें/लिखें int।  
**रिटर्न:**  
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

एक खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत में व्यक्त किया जाता है। पढ़ें/लिखें int।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

कर्व स्मूदिंग को दर्शाता है। लाइन चार्ट या स्कैटर चार्ट के लिए यदि कर्व स्मूदिंग चालू है तो true। केवल-लाइन और स्कैटर-लाइन-कनेक्टेड चार्ट पर लागू। पढ़ें/लिखें boolean।  
**रिटर्न:**  
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

कर्व स्मूदिंग को दर्शाता है। लाइन चार्ट या स्कैटर चार्ट के लिए यदि कर्व स्मूदिंग चालू है तो true। केवल-लाइन और स्कैटर-लाइन-कनेक्टेड चार्ट पर लागू। पढ़ें/लिखें boolean।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

श्रृंखला का नाम लौटाता है। केवल-पढ़ने योग्य [IStringChartValue](../../com.aspose.slides/istringchartvalue)।  
**रिटर्न:**  
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)।  
**रिटर्न:**  
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।  
**रिटर्न:**  
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

इस श्रृंखला का प्रकार लौटाता है। पढ़ें/लिखें [ChartType](../../com.aspose.slides/charttype)।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

निर्दिष्ट करता है कि यह श्रृंखला द्वितीयक अक्ष पर प्लॉट हुई है या नहीं। पढ़ें/लिखें boolean।  
**रिटर्न:**  
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

निर्दिष्ट करता है कि यह श्रृंखला द्वितीयक अक्ष पर प्लॉट हुई है या नहीं। पढ़ें/लिखें boolean।  

**पैरामीटर्स:**  
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

एक श्रृंखला का फॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IFormat](../../com.aspose.slides/iformat)।  
**रिटर्न:**  
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

एक श्रृंखला का क्रम लौटाता है। पढ़ें/लिखें int।  
**रिटर्न:**  
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

एक श्रृंखला का क्रम लौटाता है। पढ़ें/लिखें int।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

एक श्रृंखला के लेबल लौटाता है। केवल-पढ़ने योग्य [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)।  
**रिटर्न:**  
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

श्रृंखला ट्रेंड लाइनों का संग्रह। केवल-पढ़ने योग्य [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)।

--------------------

TrendLines अनस्टैक्ड 2-डी एरिया, बार, कॉलम, लाइन, स्टॉक, XY (स्कैटर) और बबल चार्ट में उपलब्ध हैं। स्टैक्ड या 3-डी चार्ट में उपलब्ध नहीं हैं। रडार, पाई, सर्फेस या डोनट चार्ट में भी उपलब्ध नहीं हैं।

**रिटर्न:**  
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

X दिशा के साथ श्रृंखला की ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

X दिशा वाले ErrorBars एरिया, बार, स्कैटर और बबल प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों में यह गुण null लौटाता है (3D सहित)। कस्टम मानों के लिए DataPoints संग्रह में ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) गुण के साथ मान निर्दिष्ट करें।

**रिटर्न:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Y दिशा के साथ श्रृंखला की ErrorBars को दर्शाता है। केवल-पढ़ने योग्य [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)।

--------------------

Y दिशा वाले ErrorBars एरिया, बार, लाइन, स्कैटर और बबल प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों में यह गुण null लौटाता है (3D सहित)। कस्टम मानों के लिए DataPoints संग्रह में ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) गुण के साथ मान निर्दिष्ट करें।

**रिटर्न:**  
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

इस श्रृंखला से संबंधित लेजेंड एंट्री को दर्शाता है, केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।  
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

**पैरामीटर्स:**  
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

**पैरामीटर्स:**  
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

**पैरामीटर्स:**  
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

**पैरामीटर्स:**  
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

3-डी बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। इस गुण का मान बदलने से श्रृंखला का प्रकार स्वचालित रूप से बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।  
**रिटर्न:**  
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

3-डी बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। इस गुण का मान बदलने से श्रृंखला का प्रकार स्वचालित रूप से बदल सकता है। पढ़ें/लिखें [ChartShapeType](../../com.aspose.slides/chartshapetype)।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

यदि मान नकारात्मक हो तो बार, कॉलम या बबल श्रृंखला के रंग उलटने को निर्दिष्ट करता है। पढ़ें/लिखें boolean।  
**रिटर्न:**  
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक हो तो बार, कॉलम या बबल श्रृंखला के रंग उलटने को निर्दिष्ट करता है। पढ़ें/लिखें boolean।  

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। रंग सेट करने के लिए श्रृंखला फॉर्मेट का FillType FillType.Solid होना चाहिए। पढ़ें/लिखें [ColorFormat](../../com.aspose.slides/colorformat)।

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

श्रृंखला की इंडेक्स और चार्ट शैली के आधार पर स्वचालित रंग लौटाता है। यदि FillType NotDefined है तो यह रंग डिफ़ॉल्ट रूप से उपयोग होता है।

**रिटर्न:**  
java.lang.Integer - The java.lang.Integer object.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

आंतरिक बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट में आंतरिक बिंदु दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

आंतरिक बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट में आंतरिक बिंदु दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

अपवर्जन बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट में अपवर्जन बिंदु दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

अपवर्जन बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट में अपवर्जन बिंदु दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

औसत मार्करों को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत मार्कर दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

औसत मार्करों को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत मार्कर दिखाए गए हों तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

औसत रेखा को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत रेखा दिखाई गई हो तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**रिटर्न:**  
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

औसत रेखा को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत रेखा दिखाई गई हो तो true। केवल-BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें boolean।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

क्वार्टाइल विधि को दर्शाता है। केवल-BoxAndWhisker चार्ट पर लागू।

**रिटर्न:**  
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

क्वार्टाइल विधि को दर्शाता है। केवल-BoxAndWhisker चार्ट पर लागू।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

कनेक्टर लाइनों को दर्शाता है। केवल-Waterfall चार्ट पर लागू।

**रिटर्न:**  
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

कनेक्टर लाइनों को दर्शाता है। केवल-Waterfall चार्ट पर लागू।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

पैरेंट श्रेणी लेबल्स का लेआउट दर्शाता है। केवल-Treemap चार्ट पर लागू।

**रिटर्न:**  
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

पैरेंट श्रेणी लेबल्स का लेआउट दर्शाता है। केवल-Treemap चार्ट पर लागू।

**पैरामीटर्स:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

निर्धारित करता है कि लाइन-या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ें/लिखें गुण का प्रयोग करें। फॉर्मेटिंग के लिए ParentSeriesGroup.UpDownBars गुण का प्रयोग करें। केवल-पढ़ने योग्य boolean।

--------------------

यह ParentSeriesGroup.UpDownBars.HasUpDownBars गुण का प्रोजेक्शन है।

**रिटर्न:**  
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच की जगह को प्रतिशत में निर्धारित करता है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.GapWidth गुण का प्रोजेक्शन है।

**रिटर्न:**  
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D चार्ट में डेटा श्रृंखला के बीच की दूरी को प्रतिशत में (मार्कर चौड़ाई के अनुसार) निर्धारित करता या बदलता है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.GapDepth गुण का प्रोजेक्शन है।

**रिटर्न:**  
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्धारित करता है (ऊपर से घड़ी की दिशा में, 0-360)। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.FirstSliceAngle गुण का प्रोजेक्शन है।

**रिटर्न:**  
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

डोनट चार्ट में छेद का आकार निर्धारित करता है (प्लॉट क्षेत्र के 10-90 % के बीच)। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य byte।

--------------------

यह ParentSeriesGroup.DoughnutHoleSize गुण का प्रोजेक्शन है।

**रिटर्न:**  
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-डी चार्ट में बार और कॉलम के ओवरलैप को प्रतिशत में निर्धारित करता है (-100 % से 100 %)। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रोजेक्शन है। यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य byte।

--------------------

ओवरलैप बार और कॉलम की चौड़ाई के प्रतिशत के रूप में ओवरलैप या स्पेसिंग की डिग्री को दर्शाता है: -100 % → अधिकतम स्पेसिंग (बार पूरी तरह अलग), 0 % → कोई ओवरलैप या स्पेसिंग नहीं, 100 % → अधिकतम ओवरलैप (बार पूरी तरह ओवरलैप)। यह ParentSeriesGroup.Overlap गुण का प्रोजेक्शन है।

**रिटर्न:**  
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार के आकार को प्रथम पाई के आकार के प्रतिशत में निर्धारित करता है (5-200 %)। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य int।

--------------------

यह ParentSeriesGroup.SecondPieSize गुण का प्रोजेक्शन है।

**रिटर्न:**  
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

निर्धारित करता है कि इस श्रृंखला और सम्बद्ध श्रृंखलाओं के लिए श्रृंखला रेखाएँ उपलब्ध हैं या नहीं। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ें/लिखें गुण का प्रयोग करें। फ़ॉर्मेटिंग के लिए ParentSeriesGroup.SeriesLinesFormat गुण का प्रयोग करें। केवल-पढ़ने योग्य boolean।

--------------------

यह ParentSeriesGroup.HasSeriesLines गुण का प्रोजेक्शन है।

**रिटर्न:**  
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, यह निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ें/लिखें गुण का प्रयोग करें।

--------------------

यह ParentSeriesGroup.BubbleSizeRepresentation का प्रोजेक्शन है।

**रिटर्न:**  
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। यह PieSplitBy गुण के साथ उपयोग किया जाता है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य double।

--------------------

यह ParentSeriesGroup.PieSplitPosition का प्रोजेक्शन है।

**रिटर्न:**  
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह निर्धारित करने की विधि को निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

--------------------

1) यह ParentSeriesGroup.PieSplitBy गुण का प्रोजेक्शन है। 2) यदि गुण का मान PieSplitType.Custom है तो आप ParentSeriesGroup.PieSplitCustomPoints के साथ कस्टम विभाजन जानकारी परिभाषित कर सकते हैं।

**रिटर्न:**  
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम विभाजन जानकारी जो पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कस्टम विभाजन के साथ उपयोग की जाती है। उन डेटा पॉइंट्स को शामिल करता है जो दूसरे पाई या बार में ड्रॉ किए जाएंगे। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। केवल-पढ़ने योग्य [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)।

--------------------

यह ParentSeriesGroup.PieSplitCustomPoints का प्रोजेक्शन है।

**रिटर्न:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ें/लिखें गुण का प्रयोग करें। केवल-पढ़ने योग्य boolean।

--------------------

यह ParentSeriesGroup.IsColorVaried का प्रोजेक्शन है।

**रिटर्न:**  
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। यह गुण केवल इस श्रृंखला का नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का है – यह संबंधित समूह गुण का प्रोजेक्शन है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ें/लिखें गुण का प्रयोग करें।

--------------------

यह ParentSeriesGroup.BubbleSizeScale का प्रोजेक्शन है।

**रिटर्न:**  
int
### getSlide() {#getSlide--}
```
public  



....

```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)