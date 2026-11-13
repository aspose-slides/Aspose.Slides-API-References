---
title: ChartSeriesGroup
second_title: Aspose.Slides के लिए Java API संदर्भ
description: श्रृंखला समूह का प्रतिनिधित्व करता है।
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

श्रृंखलाओं का समूह प्रदर्शित करता है।

--------------------

1) देखें सारांश और टिप्पणी के लिए ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एन्नुम। 2) श्रृंखलाओं का समूह कुछ श्रृंखला गुणों को समेटता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties")। "Series group properties" ChartSeriesGroup क्लास में पढ़ने/लिखने योग्य है। प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | इस श्रृंखला समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। |
| [getSeries()](#getSeries--) | श्रृंखलाओं का संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | Line- या Stock-चार्ट के अप/डाउन बार तक पहुँच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच अंतराल प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच अंतराल प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई का प्रतिशत है। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई का प्रतिशत है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोन डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट चार्ट स्लाइस का कोन डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। |
| [getOverlap()](#getOverlap--) | 2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ-पाई या बार-ऑफ-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार का प्रतिशत निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | पाई-ऑफ-पाई या बार-ऑफ-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार का प्रतिशत निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा बिंदु पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा बिंदु पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। |
| [getPieSplitBy()](#getPieSplitBy--) | पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [isColorVaried()](#isColorVaried--) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है, यह निर्दिष्ट करता है। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है, यह निर्दिष्ट करता है। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines स्वरूप निर्दिष्ट करता है। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट के साथ पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | माता चार्ट लौटाता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat की पैरेंट प्रस्तुति लौटाता है। |

### getType() {#getType--}
```
public final int getType()
```

इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**रिटर्न:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

निर्देशित करता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। केवल-पढ़ने योग्य boolean.

**रिटर्न:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

श्रृंखलाओं का संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**रिटर्न:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Line- या Stock-चार्ट के अप/डाउन बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**रिटर्न:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच अंतराल प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है। मान 0 और 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int.

यह प्रॉपर्टी निम्नलिखित प्रकार की श्रृंखलाओं पर लागू होती है: Bar उपप्रकार ([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें), Column उपप्रकार ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) मेथड देखें), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)।

**रिटर्न:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

बार या कॉलम क्लस्टर के बीच अंतराल प्राप्त करता है या सेट करता है, जो बार या कॉलम की चौड़ाई का प्रतिशत है। मान 0 और 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int.

यह प्रॉपर्टी निम्नलिखित प्रकार की श्रृंखलाओं पर लागू होती है: Bar उपप्रकार ([ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) मेथड देखें), Column उपप्रकार ([ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) मेथड देखें), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall)।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई का प्रतिशत है। मान 0 और 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int.

यह प्रॉपर्टी निम्नलिखित प्रकार की श्रृंखलाओं पर लागू होती है: 3D bar and column subtypes ([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) मेथड देखें), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)।

**रिटर्न:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी प्राप्त करता है या सेट करता है, जो मार्कर की चौड़ाई का प्रतिशत है। मान 0 और 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य int.

यह प्रॉपर्टी निम्नलिखित प्रकार की श्रृंखलाओं पर लागू होती है: 3D bar and column subtypes ([ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) मेथड देखें), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D)।

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोन डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

पहले पाई या डोनट चार्ट स्लाइस का कोन डिग्री में प्राप्त करता है या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ने/लिखने योग्य int.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
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

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्धारित करता है (-100% से 100% तक)। --100%: अधिकतम अंतर (बार पूरी तरह अलग)। - 0%: बार बिना ओवरलैप या अंतर के साथ-साथ रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप)। यह प्रॉपर्टी पढ़ने/लिखने योग्य byte है।

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

2-डी चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्धारित करता है (-100% से 100% तक)। --100%: अधिकतम अंतर (बार पूरी तरह अलग)। - 0%: बार बिना ओवरलैप या अंतर के साथ-साथ रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप)। यह प्रॉपर्टी पढ़ने/लिखने योग्य byte है।

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


**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

पाई-ऑफ-पाई या बार-ऑफ-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार का प्रतिशत निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

पाई-ऑफ-पाई या बार-ऑफ-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार का प्रतिशत निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। पढ़ने/लिखने योग्य int.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**रिटर्न:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा बिंदु पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double.

**रिटर्न:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा बिंदु पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में हैं। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य double.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype).

**रिटर्न:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने/लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype).

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य boolean.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

यदि चार्ट में श्रृंखला रेखाएँ हैं तो True। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य boolean.

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines स्वरूप निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है।

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

**पैरामीटर्स:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम स्प्लिट के साथ पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। इसमें डेटा बिंदु होते हैं जो पाई-ऑफ-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में दर्शाए जाने चाहिए। केवल-पढ़ने योग्य [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

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

माता चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart).

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

FillFormat की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)