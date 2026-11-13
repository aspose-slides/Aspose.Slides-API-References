---
title: IChartSeriesGroup
second_title: Aspose.Slides के लिए Java API संदर्भ
description: श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartseriesgroup/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

श्रृंखला का समूह दर्शाता है।

--------------------

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एनम के लिए सारांश और टिप्पणी देखें। 2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह की प्रत्येक श्रृंखला में सामान्य होते हैं ("series group properties")। ChartSeriesGroup क्लास में "Series group properties" पढ़ने/लिखने योग्य हैं। "Series group properties" में से प्रत्येक का ChartSeries क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | इस श्रृंखला समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | निर्देश करता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर चित्रित होती हैं या नहीं। |
| [getSeries()](#getSeries--) | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | Line- या Stock-चार्ट के ऊपर/नीचे बार तक पहुँच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच की जगह प्राप्त करता है या सेट करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच की जगह प्राप्त करता है या सेट करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी प्राप्त करता है या सेट करता है, मार्कर की चौड़ाई के प्रतिशत के रूप में। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी प्राप्त करता है या सेट करता है, मार्कर की चौड़ाई के प्रतिशत के रूप में। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। |
| [isColorVaried()](#isColorVaried--) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। |
| [getOverlap()](#getOverlap--) | 2-D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई चार्ट या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच हो सकता है)। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | पाई-ऑफ़-पाई चार्ट या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच हो सकता है)। |
| [getPieSplitPosition()](#getPieSplitPosition--) | एक मूल्य निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | एक मूल्य निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [getPieSplitBy()](#getPieSplitBy--) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | एक कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल कारक निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल चार्ट के लिए स्केल कारक निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट पर बबल आकार मूल्यों का प्रतिनिधित्व कैसे किया जाता है, निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल चार्ट पर बबल आकार मूल्यों का प्रतिनिधित्व कैसे किया जाता है, निर्दिष्ट करता है। |

### getType() {#getType--}
```
public abstract int getType()
```

इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)।

**रिटर्न:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

निर्देश करता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर चित्रित होती हैं या नहीं। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)।

**रिटर्न:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Line- या Stock-चार्ट के ऊपर/नीचे बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)।

**रिटर्न:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच की जगह प्राप्त करता है या सेट करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

यह गुण निम्न प्रकार की श्रृंखलाओं पर लागू होता है: सभी बार और कॉलम उपप्रकार, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)।

**रिटर्न:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

बार या कॉलम क्लस्टर के बीच की जगह प्राप्त करता है या सेट करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

यह गुण निम्न प्रकार की श्रृंखलाओं पर लागू होता है: सभी बार और कॉलम उपप्रकार, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी प्राप्त करता है या सेट करता है, मार्कर की चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

यह गुण निम्न प्रकार की श्रृंखलाओं पर लागू होता है: 3D बार और कॉलम उपप्रकार, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)।

**रिटर्न:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी प्राप्त करता है या सेट करता है, मार्कर की चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

यह गुण निम्न प्रकार की श्रृंखलाओं पर लागू होता है: 3D बार और कॉलम उपप्रकार, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

2-D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह से अलग होते हैं)। - 0%: बार बिना ओवरलैप या स्पेसिंग के साइड बाय साइड रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह से एक-दूसरे पर ओवरलैप होते हैं)। यह गुण पढ़ने/लिखने योग्य बाइट है।

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ओवरलैप को 55% पर सेट करें
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

2-D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह से अलग होते हैं)। - 0%: बार बिना ओवरलैप या स्पेसिंग के साइड बाय साइड रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह से एक-दूसरे पर ओवरलैप होते हैं)। यह गुण पढ़ने/लिखने योग्य बाइट है।

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


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

पाई-ऑफ़-पाई चार्ट या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

पाई-ऑफ़-पाई चार्ट या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

एक मूल्य निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। PieSplitBy गुण के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double।

**रिटर्न:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

एक मूल्य निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। PieSplitBy गुण के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

कैसे निर्धारित किया जाए कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

**रिटर्न:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

कैसे निर्धारित किया जाए कि कौन से डेटा पॉइंट्स पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

एक कस्टम स्प्लिट वाले पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। इस चार्ट में दूसरे पाई या बार में खींचे जाने वाले डेटा पॉइंट्स को शामिल करता है। केवल-पढ़ने योग्य [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)।

**रिटर्न:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य byte।

**रिटर्न:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य byte।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल कारक निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

बबल चार्ट के लिए स्केल कारक निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं।

**रिटर्न:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

बबल चार्ट पर बबल आकार मूल्यों का प्रतिनिधित्व कैसे किया जाता है, निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**रिटर्न:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

बबल चार्ट पर बबल आकार मूल्यों का प्रतिनिधित्व कैसे किया जाता है, निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |