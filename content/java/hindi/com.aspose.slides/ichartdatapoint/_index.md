---
title: IChartDataPoint
second_title: Aspose.Slides for Java API संदर्भ
description: सीरीज़ डेटा पॉइंट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ichartdatapoint/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

सीरीज़ डेटा पॉइंट को दर्शाता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getXValue()](#getXValue--) | चार्ट डेटा पॉइंट का x मान लौटाता है। |
| [getYValue()](#getYValue--) | चार्ट डेटा पॉइंट का y मान लौटाता है। |
| [getBubbleSize()](#getBubbleSize--) | चार्ट डेटा पॉइंट का बबल आकार लौटाता है। |
| [getValue()](#getValue--) | चार्ट डेटा पॉइंट का मान लौटाता है। |
| [getSizeValue()](#getSizeValue--) | चार्ट डेटा पॉइंट का आकार मान लौटाता है। |
| [getColorValue()](#getColorValue--) | चार्ट डेटा पॉइंट का रंग मान लौटाता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम वैल्यू प्रकार के मामलों में सीरीज़ एरर बार के मान दर्शाता है। |
| [getLabel()](#getLabel--) | चार्ट डेटा पॉइंट का लेबल दर्शाता है। |
| [isBubble3D()](#isBubble3D--) | निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू किया गया है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू किया गया है। |
| [getExplosion()](#getExplosion--) | डेटा पॉइंट को पाई के केंद्र से कितनी दूरी पर ले जाया जाना चाहिए, यह निर्दिष्ट करता है। |
| [setExplosion(int value)](#setExplosion-int-) | डेटा पॉइंट को पाई के केंद्र से कितनी दूरी पर ले जाया जाना चाहिए, यह निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। |
| [getMarker()](#getMarker--) | डेटा मार्कर निर्दिष्ट करता है। |
| [remove()](#remove--) | डेटा पॉइंट को चार्ट सीरीज़ से हटा देता है। |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वतः रंग लौटाता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस सूची के चार्ट प्रकारों के मामले में संबंधित लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) | निर्धारित करता है कि इस डेटा पॉइंट को माता के बच्चों के संग्रह में से कौन से पर लागू करना है। |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

चार्ट डेटा पॉइंट का x मान लौटाता है। केवल पढ़ने योग्य [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**रिटर्न:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

चार्ट डेटा पॉइंट का y मान लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**रिटर्न:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

चार्ट डेटा पॉइंट का बबल आकार लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**रिटर्न:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

चार्ट डेटा पॉइंट का मान लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**रिटर्न:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**रिटर्न:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

चार्ट डेटा पॉइंट का रंग मान लौटाता है। Map चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**रिटर्न:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम वैल्यू प्रकार के मामलों में सीरीज़ एरर बार के मान दर्शाता है। केवल पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**रिटर्न:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

चार्ट डेटा पॉइंट का लेबल दर्शाता है। केवल पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel).

**रिटर्न:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू किया गया है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

डेटा पॉइंट को पाई के केंद्र से कितनी दूरी पर ले जाया जाना चाहिए, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**रिटर्न:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

डेटा पॉइंट को पाई के केंद्र से कितनी दूरी पर ले जाया जाना चाहिए, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ को दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

डेटा मार्कर निर्दिष्ट करता है। केवल पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**रिटर्न:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

डेटा पॉइंट को चार्ट सीरीज़ से हटा देता है।

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```

सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वतः रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**रिटर्न:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

इस सूची के चार्ट प्रकारों के मामले में संबंधित लेजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**रिटर्न:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**रिटर्न:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst सीरीज़ के लिए लागू। डेटा पॉइंट स्तरों की इंडेक्सिंग शून्य-आधारित है।

**रिटर्न:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

निर्धारित करता है कि इस डेटा पॉइंट को माता के बच्चों के संग्रह में से कौन से पर लागू करना है। पढ़ने long।

**रिटर्न:**
long