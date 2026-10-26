---
title: IChartSeriesGroup
second_title: Aspose.Slides जावा API संदर्भ
description: श्रृंखलाओं का समूह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartseriesgroup/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

श्रृंखलाओं का समूह दर्शाता है।

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.
## विधियाँ

| Method | Description |
| --- | --- |
| [getType()](#getType--) | इस श्रृंखला समूह का प्रकार लौटाता है। |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। |
| [getSeries()](#getSeries--) | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [getUpDownBars()](#getUpDownBars--) | लाइन- या स्टॉक-चार्ट के अप/डाउन बार तक पहुंच प्रदान करता है। |
| [getGapWidth()](#getGapWidth--) | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [setGapWidth(int value)](#setGapWidth-int-) | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। |
| [getGapDepth()](#getGapDepth--) | 3D चार्ट में डेटा श्रृंखलाओं के बीच स्थिति को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [setGapDepth(int value)](#setGapDepth-int-) | 3D चार्ट में डेटा श्रृंखलाओं के बीच स्थिति को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। |
| [isColorVaried()](#isColorVaried--) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। |
| [hasSeriesLines()](#hasSeriesLines--) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो true। |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो true। |
| [getOverlap()](#getOverlap--) | 2-डी चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [setOverlap(byte value)](#setOverlap-byte-) | 2-डी चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| [getSecondPieSize()](#getSecondPieSize--) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5-200 % के बीच)। |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5-200 % के बीच)। |
| [getPieSplitPosition()](#getPieSplitPosition--) | मूल्य निर्दिष्ट करता है जो यह निर्धारित करता है कि किन डेटा पॉइंट्स को पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में रखा जाएगा। |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | मूल्य निर्दिष्ट करता है जो यह निर्धारित करता है कि किन डेटा पॉइंट्स को पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में रखा जाएगा। |
| [getPieSplitBy()](#getPieSplitBy--) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि किन डेटा पॉइंट्स को पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में रखा जाएगा। |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | यह निर्धारित करने का तरीका निर्दिष्ट करता है कि किन डेटा पॉइंट्स को पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में रखा जाएगा। |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | कस्टम स्प्लिट के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10-90 % के बीच)। |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10-90 % के बीच)। |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | बबल चार्ट में बबल आकार मान कैसे प्रस्तुत किए जाते हैं, यह निर्दिष्ट करता है। |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | बबल चार्ट में बबल आकार मान कैसे प्रस्तुत किए जाते हैं, यह निर्दिष्ट करता है। |
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


यदि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं तो दर्शाता है। केवल-पढ़ने योग्य boolean।

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


निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```


लाइन- या स्टॉक-चार्ट के अप/डाउन बार तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)।

**वापसी:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य int।

**वापसी:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```


3D चार्ट में डेटा श्रृंखलाओं के बीच स्थिति को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य int।

**वापसी:**
int
### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```


3D चार्ट में डेटा श्रृंखलाओं के बीच स्थिति को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```


पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ने-और-लिखने योग्य int।

**वापसी:**
int
### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```


पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```


सिरिज में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य boolean।

**वापसी:**
boolean
### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```


सिरिज में प्रत्येक डेटा मार्कर का रंग अलग होने को निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य boolean।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```


यदि चार्ट में श्रृंखला रेखाएँ हैं तो true। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने-और-लिखने योग्य boolean।

**वापसी:**
boolean
### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```


यदि चार्ट में श्रृंखला रेखाएँ हैं तो true। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने-और-लिखने योग्य boolean।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```


2-डी चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। - -100%: अधिकतम अंतराल (बार पूरी तरह अलग हैं)। - 0%: बार बगल में बिना ओवरलैप या अंतराल के रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप होते हैं)। यह प्रॉपर्टी पढ़ने-और-लिखने योग्य byte।

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


2-डी चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। - -100%: अधिकतम अंतराल (बार पूरी तरह अलग हैं)। - 0%: बार बगल में बिना ओवरलैप या अंतराल के रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप होते हैं)। यह प्रॉपर्टी पढ़ने-और-लिखने योग्य byte।

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


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```


पहले पाई के आकार के प्रतिशत के रूप में दूसरे पाई या बार का आकार निर्दिष्ट करता है (5-200 % के बीच)। पढ़ने-और-लिखने योग्य int।

**वापसी:**
int
### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```


पहले पाई के आकार के प्रतिशत के रूप में दूसरे पाई या बार का आकार निर्दिष्ट करता है (5-200 % के बीच)। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```


पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में किन डेटा पॉइंट्स को रखा जाए, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने-और-लिखने योग्य double।

**वापसी:**
double
### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```


पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में किन डेटा पॉइंट्स को रखा जाए, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने-और-लिखने योग्य double।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```


पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में किन डेटा पॉइंट्स को रखा जाए, यह निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

**वापसी:**
int
### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```


पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में किन डेटा पॉइंट्स को रखा जाए, यह निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य [PieSplitType](../../com.aspose.slides/piesplittype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```


कस्टम स्प्लिट के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम विभाजन जानकारी। इसमें वह डेटा पॉइंट्स शामिल हैं जो दूसरे पाई या बार में ड्रॉ किए जाएंगे। केवल-पढ़ने योग्य [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)।

**वापसी:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```


डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10-90 % के बीच)। पढ़ने-और-लिखने योग्य byte।

**वापसी:**
byte
### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```


डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10-90 % के बीच)। पढ़ने-और-लिखने योग्य byte।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```


बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। पढ़ने-और-लिखने योग्य int।

**वापसी:**
int
### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```


बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच)। पढ़ने-और-लिखने योग्य int।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```


HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है।

**वापसी:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```


बबल चार्ट में बबल आकार मान कैसे प्रस्तुत किए जाते हैं, यह निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**वापसी:**
int
### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```


बबल चार्ट में बबल आकार मान कैसे प्रस्तुत किए जाते हैं, यह निर्दिष्ट करता है। पढ़ने-और-लिखने योग्य [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype)।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |