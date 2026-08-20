---
title: ChartSeriesGroup
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: सिरीज़ समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**  
विरासत:

java.lang.Object

**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Represents group of series.  
सिरीज़ समूह का प्रतिनिधित्व करता है।

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.  
1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एनीम के लिए सारांश और टिप्पणी देखें। 2) सिरीज़ समूह में कुछ सिरीज़ प्रॉपर्टीज़ होती हैं जो समूह में प्रत्येक सिरीज़ के लिए सामान्य हैं ("series group properties")। ChartSeriesGroup क्लास में "Series group properties" पढ़ने/लिखने योग्य है। प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getType()](#getType--) | इस सिरीज़ समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | यह दर्शाता है कि क्या इस समूह की सिरीज़ द्वितीयक अक्ष पर प्लॉट की गई है। |
| [getSeries()](#getSeries--) | सिरीज़ का संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | लाइन या स्टॉक-चार्ट की अप/डाउन बार तक पहुंच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच के अंतराल को, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच के अंतराल को, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3डी चार्ट में डेटा सिरीज़ के बीच की दूरी को, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3डी चार्ट में डेटा सिरीज़ के बीच की दूरी को, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (उपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (उपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। |
| [getOverlap()](#getOverlap--) | 2-डी चार्ट पर बार और कॉलम कितने ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-डी चार्ट पर बार और कॉलम कितने ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, इसे निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, इसे निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने के लिए उपयोग किए जाने वाले मान को निर्दिष्ट करता है। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, यह निर्धारित करने के लिए उपयोग किए जाने वाले मान को निर्दिष्ट करता है। |
| [getPieSplitBy()](#getPieSplitBy--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [isColorVaried()](#isColorVaried--) | यह निर्दिष्ट करता है कि सिरीज़ में प्रत्येक डेटा मार्कर का रंग अलग है। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | यह निर्दिष्ट करता है कि सिरीज़ में प्रत्येक डेटा मार्कर का रंग अलग है। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में सिरीज़ लाइन्स हैं तो सत्य। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में सिरीज़ लाइन्स हैं तो सत्य। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines का फॉर्मेट निर्दिष्ट करता है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। |

### getType() {#getType--}
```
public final int getType()
```

इस सिरीज़ समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**रिटर्न:**  
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

यह दर्शाता है कि क्या इस समूह की सिरीज़ द्वितीयक अक्ष पर प्लॉट की गई है। केवल-पढ़ने योग्य boolean.

**रिटर्न:**  
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

सिरीज़ का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**रिटर्न:**  
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

लाइन या स्टॉक-चार्ट की अप/डाउन बार तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**रिटर्न:**  
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच के अंतराल को, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ने/लिखने योग्य int.

**रिटर्न:**  
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

बार या कॉलम क्लस्टर के बीच के अंतराल को, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3डी चार्ट में डेटा सिरीज़ के बीच की दूरी को, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ने/लिखने योग्य int.

**रिटर्न:**  
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3डी चार्ट में डेटा सिरीज़ के बीच की दूरी को, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (उपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने/लिखने योग्य int.

**रिटर्न:**  
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (उपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। पढ़ने/लिखने योग्य byte.

**रिटर्न:**  
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। पढ़ने/लिखने योग्य byte.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-डी चार्ट पर बार और कॉलम कितने ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। -100%: अधिकतम अंतराल (बार पूरी तरह अलग)। -0%: बार बिना ओवरलैप या अंतराल के साइड बाय साइड। -100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलैप करते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ओवरलैप को 55% सेट करें
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

2-डी चार्ट पर बार और कॉलम कितने ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। -100%: अधिकतम अंतराल (बार पूरी तरह अलग)। -0%: बार बिना ओवरलैप या अंतराल के साइड बाय साइड। -100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलैप करते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ओवरलैप को 55% सेट करें
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**रिटर्न:**  
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**रिटर्न:**  
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

बबल चार्ट में बबल आकार मानों का प्रतिनिधित्व कैसे किया जाता है, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने के लिए उपयोग किए जाने वाले मान को निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**  
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने के लिए उपयोग किए जाने वाले मान को निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype).

**रिटर्न:**  
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype).

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

यह निर्दिष्ट करता है कि सिरीज़ में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**  
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

यह निर्दिष्ट करता है कि सिरीज़ में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

यदि चार्ट में सिरीज़ लाइन्स हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**  
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

यदि चार्ट में सिरीज़ लाइन्स हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines का फॉर्मेट निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है।

**रिटर्न:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**रिटर्न:**  
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। वह डेटा पॉइंट्स शामिल करता है जो पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में खींचे जाने चाहिए। केवल-पढ़ने योग्य [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**रिटर्न:**  
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject.

**रिटर्न:**  
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart).

**रिटर्न:**  
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide).

**रिटर्न:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पैरेंट प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**रिटर्न:**  
[IPresentation](../../com.aspose.slides/ipresentation)