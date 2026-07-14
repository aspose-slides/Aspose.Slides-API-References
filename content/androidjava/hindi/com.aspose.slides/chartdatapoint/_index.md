---
title: ChartDataPoint
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdatapoint/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | चार्ट डेटा पॉइंट का आकार मान लौटाता है। |
| [getColorValue()](#getColorValue--) | चार्ट डेटा पॉइंट का रंग मान लौटाता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम वैल्यू प्रकार के मामले में सीरीज़ एरर बार मानों का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | निर्देशित करता है कि बबल्स पर 3-D प्रभाव लागू किया गया है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | निर्देशित करता है कि बबल्स पर 3-D प्रभाव लागू किया गया है। |
| [getExplosion()](#getExplosion--) | निर्देशित करता है कि डेटा पॉइंट को पाई के केंद्र से कितना दूर ले जाया जाना चाहिए। |
| [setExplosion(int value)](#setExplosion-int-) | निर्देशित करता है कि डेटा पॉइंट को पाई के केंद्र से कितना दूर ले जाया जाना चाहिए। |
| [getFormat()](#getFormat--) | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। |
| [getMarker()](#getMarker--) | एक डेटा मार्कर निर्दिष्ट करता है। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस सूची में से चार्ट प्रकार के मामले में समानांतर लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | चार्ट सीरीज़ से DataPoint हटाता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | निर्देशित करता है कि यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट दे। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | निर्देशित करता है कि यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट दे। |
| [getActualX()](#getActualX--) | चार्ट एलिमेंट के वास्तविक x स्थान (बाएं) को चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट एलिमेंट के वास्तविक शीर्ष स्थान को चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट एलिमेंट की वास्तविक चौड़ाई निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट एलिमेंट की वास्तविक ऊँचाई निर्दिष्ट करता है। |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. केवल पढ़ने योग्य [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**वापसी:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

चार्ट डेटा पॉइंट का रंग मान लौटाता है। Map चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम वैल्यू प्रकार के मामले में सीरीज़ एरर बार मानों का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**वापसी:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. केवल पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel).

**वापसी:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

निर्देशित करता है कि बबल्स पर 3-D प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

निर्देशित करता है कि बबल्स पर 3-D प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

डेटा पॉइंट को पाई के केंद्र से कितना दूरी ले जाना है, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**वापसी:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

डेटा पॉइंट को पाई के केंद्र से कितना दूरी ले जाना है, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat).

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

एक डेटा मार्कर निर्दिष्ट करता है। केवल पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker).

**वापसी:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**वापसी:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

समानांतर लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**वापसी:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

चार्ट सीरीज़ से DataPoint हटाता है।

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखला के लिए लागू। डेटा पॉइंट लेवल्स की इंडेक्सिंग शून्य-आधारित है।

**वापसी:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**वापसी:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```

सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट तौर पर उपयोग किया जाता है।

**वापसी:**
java.lang.Integer

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

निर्देशित करता है कि यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट दे। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

निर्देशित करता है कि यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट दे। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट एलिमेंट के वास्तविक x स्थान (बाएं) को चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने से पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float।

**वापसी:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट एलिमेंट के वास्तविक शीर्ष स्थान को चार्ट के बाएं शीर्ष कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने से पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float।

**वापसी:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट एलिमेंट की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने से पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float।

**वापसी:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट एलिमेंट की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने से पहले IChart.ValidateChartLayout() मेथड को कॉल करें। पढ़ें float।

**वापसी:**
float