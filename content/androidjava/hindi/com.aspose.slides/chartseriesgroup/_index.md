---
title: ChartSeriesGroup
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: श्रृंखलाओं के समूह को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/chartseriesgroup/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

श्रृंखलाओं का समूह दर्शाता है।

--------------------

1) ChartSeriesGroupCollection वर्ग और CombinableSeriesTypesGroup एनम के सारांश और टिप्पणी देखें। 2) श्रृंखलाओं का समूह कुछ श्रृंखला गुणों को शामिल करता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties")। "Series group properties" ChartSeriesGroup वर्ग में पढ़ने/लिखने योग्य है। ChartSeries वर्ग में प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य प्रक्षेपण हो सकता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | इस श्रृंखला समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। |
| [getSeries()](#getSeries--) | श्रृंखलाओं का संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | Line- या Stock-चार्ट के up/down बार तक पहुंच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट_chart स्लाइस का कोण डिग्री में प्राप्त करता या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच)। |
| [getOverlap()](#getOverlap--) | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-D_chart में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल_chart में बबल आकार मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल_chart में बबल आकार मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | pie-of-pie या bar-of-pie चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | pie-of-pie या bar-of-pie चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। |
| [getPieSplitBy()](#getPieSplitBy--) | pie-of-pie या bar-of-pie चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | pie-of-pie या bar-of-pie_chart में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। |
| [isColorVaried()](#isColorVaried--) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने का निर्धारण करता है। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने का निर्धारण करता है। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines प्रारूप निर्दिष्ट करता है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल_chart के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल_chart के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | एक कस्टम विभाजन वाले pie-of-pie या बार-of-pie_chart के लिए कस्टम विभाजन जानकारी। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट_chart लौटाता है। |
| [getSlide()](#getSlide--) | FillFormat की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रस्तुति लौटाता है। |
### getType() {#getType--}
```
public final int getType()
```

इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)।

**रिटर्न:**
int
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**
boolean
### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

श्रृंखलाओं का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)।

**रिटर्न:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Line- या Stock-चार्ट के up/down बार तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)।

**रिटर्न:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें int।

**रिटर्न:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

बार या कॉलम क्लस्टर के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें int।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D_chart में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ें/लिखें int।

**रिटर्न:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D_chart में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ें/लिखें int।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

पहले पाई या डोनट_chart स्लाइस का कोण डिग्री में प्राप्त करता या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ें/लिखें int।

**रिटर्न:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

पहले पाई या डोनट_chart स्लाइस का कोण डिग्री में प्राप्त करता या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)。 पढ़ें/लिखें int।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

डोनट_chart में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच)。 पढ़ें/लिखें byte।

**रिटर्न:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

डोनट_chart में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच)。 पढ़ें/लिखें byte।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-D_chart में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)।
- -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)।
- 0%: बार बिना ओवरलैप या स्पेसिंग के साइड-बाय-साइड रखे जाते हैं।
- 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप)।
यह प्रॉपर्टी पढ़ें/लिखें byte।

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ओवरलैप को 55% पर सेट करें
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
byte
### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

2-D_chart में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)।
- -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)।
- 0%: बार बिना ओवरलैप या स्पेसिंग के साइड-बाय-साइड रखे जाते हैं।
- 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप)।
यह प्रॉपर्टी पढ़ें/लिखें byte।

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ओवरलैप को 55% पर सेट करें
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

pie-of-pie या bar-of-pie_chart में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)。 पढ़ें/लिखें int।

**रिटर्न:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

pie-of-pie या bar-of-pie_chart में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)। पढ़ें/लिखें int।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

बबल_chart में बबल आकार मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**रिटर्न:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

बबल_chart में बबल आकार मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

pie-of-pie या bar-of-pie_chart में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें double।

**रिटर्न:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

pie-of-pie या bar-of-pie_chart में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें double।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

pie-of-pie या bar-of-pie_chart में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला तरीका निर्दिष्ट करता है। पढ़ें/लिखें [PieSplitType](../../com.aspose.slides/piesplittype)।

**रिटर्न:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

pie-of-pie या bar-of-pie_chart में कौन से डेटा बिंदु दूसरे पाई या बार में होंगे, इसे निर्धारित करने के लिये उपयोग किया जाने वाला तरीका निर्दिष्ट करता है। पढ़ें/लिखें [PieSplitType](../../com.aspose.slides/piesplittype)।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने का निर्धारण करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने का निर्धारण करता है। पढ़ें/लिखें boolean।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। stacked bar और OfPie_chart पर लागू। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। stacked bar और OfPie_chart पर लागू। पढ़ें/लिखें boolean।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines प्रारूप निर्दिष्ट करता है। HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose_chart प्रकारों के साथ लागू होते हैं।

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

बबल_chart के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। पढ़ें/लिखें int।

**रिटर्न:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

बबल_chart के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। पढ़ें/लिखें int।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

एक कस्टम विभाजन वाले pie-of-pie या बार-of-pie_chart के लिए कस्टम विभाजन जानकारी। इसमें डेटा बिंदु होते हैं जिन्हें दूसरे पाई या बार में ड्रॉ किया जाना चाहिए। केवल-पढ़ने योग्य [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection)।

**रिटर्न:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
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

पैरेंट_chart लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)
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