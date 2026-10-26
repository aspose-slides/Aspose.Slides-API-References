---
title: IChartSeriesGroup
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सीरीज़ समूह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartseriesgroup/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

सीरीज़ समूह का प्रतिनिधित्व करता है।

--------------------

1) ChartSeriesGroupCollection class और CombinableSeriesTypesGroup enum के सारांश और टिप्पणी देखें। 2) सीरीज़ समूह में कुछ सीरीज़ गुण होते हैं जो समूह के प्रत्येक सीरीज़ के लिए सामान्य होते हैं ("series group properties")। "Series group properties" ChartSeriesGroup class में पढ़ें/लिखें हैं। प्रत्येक "series group properties" का एक केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries class में हो सकता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | इस श्रृंखला समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | यदि इस समूह की श्रृंखला द्वितीयक धुरी पर प्लॉट की गई है तो संकेत देता है। |
| [getSeries()](#getSeries--) | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | Line- या Stock-चार्ट की ऊपर/नीचे बार तक पहुँच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच का अंतर, मार्कर की चौड़ाई के प्रतिशत के रूप में, लौटाता या सेट करता है। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D चार्ट में डेटा श्रृंखलाओं के बीच का अंतर, मार्कर की चौड़ाई के प्रतिशत के रूप में, लौटाता या सेट करता है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक) प्राप्त करता या सेट करता है। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक) प्राप्त करता या सेट करता है। |
| [isColorVaried()](#isColorVaried--) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में श्रृंखला रेखाएं हैं तो सत्य। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में श्रृंखला रेखाएं हैं तो सत्य। |
| [getOverlap()](#getOverlap--) | 2-D चार्टों पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में (-100% से 100% तक) निर्दिष्ट करता है। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-D चार्टों पर बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में (-100% से 100% तक) निर्दिष्ट करता है। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच हो सकता है) निर्दिष्ट करता है। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच हो सकता है) निर्दिष्ट करता है। |
| [getPieSplitPosition()](#getPieSplitPosition--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, निर्धारित करने के लिए प्रयुक्त मान को निर्दिष्ट करता है। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, निर्धारित करने के लिए प्रयुक्त मान को निर्दिष्ट करता है। |
| [getPieSplitBy()](#getPieSplitBy--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम विभाजन के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छिद्र का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट_chart में छिद्र का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines प्रारूप निर्दिष्ट करता है। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। |

### getType() {#getType--}
```
public abstract int getType()
```

इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup)।

**वापसी:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

यदि इस समूह की श्रृंखला द्वितीयक धुरी पर प्लॉट की गई है तो संकेत देता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)।

**वापसी:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Line- या Stock-चार्ट की ऊपर/नीचे बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)।

**वापसी:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें int।

**वापसी:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

3D चार्ट में डेटा श्रृंखलाओं के बीच का अंतर, मार्कर की चौड़ाई के प्रतिशत के रूप में, लौटाता या सेट करता है। पढ़ें/लिखें int।

**वापसी:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

3D चार्ट में डेटा श्रृंखलाओं के बीच का अंतर, मार्कर की चौड़ाई के प्रतिशत के रूप में, लौटाता या सेट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक) प्राप्त करता या सेट करता है। पढ़ें/लिखें int।

**वापसी:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक) प्राप्त करता या सेट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

शृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**वापसी:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

शृंखला में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

यदि चार्ट में श्रृंखला रेखाएं हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट में लागू। पढ़ें/लिखें boolean।

**वापसी:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

यदि चार्ट में श्रृंखला रेखाएं हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट में लागू। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीट‍र | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

बार और कॉलम 2-D चार्टों पर कितनी ओवरलैप करेंगे, प्रतिशत में (-100% से 100% तक) निर्दिष्ट करता है। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)। - 0%: बार साइड-बाय-साइड बिना ओवरलैप या स्पेसिंग के। - 100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलैप करता है)। यह प्रॉपर्टी पढ़ें/लिखें byte।

--------------------

> ```markdown
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


**वापसी:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

बार और कॉलम 2-D चार्टों पर कितनी ओवरलैप करेंगे, प्रतिशत में (-100% से 100% तक) निर्दिष्ट करता है। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)। - 0%: बार साइड-बाय-साइड बिना ओवरलैप या स्पेसिंग के। - 100%: अधिकतम ओवरलैप (बार एक-दूसरे को पूरी तरह ओवरलैप करता है)। यह प्रॉपर्टी पढ़ें/लिखें byte।

--------------------

> ```markdown
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

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच) निर्दिष्ट करता है। पढ़ें/लिखें int।

**वापसी:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
``` 
public abstract void setSecondPieSize(int value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच) निर्दिष्ट करता है। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, निर्धारित करने के लिए प्रयुक्त मान को निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें double।

**वापसी:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, निर्धारित करने के लिए प्रयुक्त मान को निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें double।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ें/लिखें [PieSplitType](../../com.aspose.slides/piesplittype)।

**वापसी:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा बिंदु दूसरे पाई या बार में हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ें/लिखें [PieSplitType](../../com.aspose.slides/piesplittype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

कस्टम विभाजन के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। इसमें वे डेटा पॉइंट्स होते हैं जिन्हें दूसरे पाई या बार में ड्रॉ किया जाना चाहिए। केवल-पढ़ने योग्य [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)।

**वापसी:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

डोनट चार्ट में छिद्र का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। पढ़ें/लिखें byte।

**वापसी:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

डोनट चार्ट में छिद्र का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। पढ़ें/लिखें byte।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। पढ़ें/लिखें int।

**वापसी:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। पढ़ें/लिखें int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

HiLowLines प्रारूप निर्दिष्ट करता है। HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं।

**वापसी:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**वापसी:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
``` 
public abstract void setBubbleSizeRepresentation(int value)
```

बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। पढ़ें/लिखें [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |