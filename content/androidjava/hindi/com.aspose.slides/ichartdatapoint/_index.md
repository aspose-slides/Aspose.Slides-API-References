---
title: IChartDataPoint
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ichartdatapoint/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

सीरिज डेटा पॉइंट का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | चार्ट डेटा पॉइंट का x मान लौटाता है। |
| [getYValue()](#getYValue--) | चार्ट डेटा पॉइंट का y मान लौटाता है। |
| [getBubbleSize()](#getBubbleSize--) | चार्ट डेटा पॉइंट का बबल आकार लौटाता है। |
| [getValue()](#getValue--) | चार्ट डेटा पॉइंट का मान लौटाता है। |
| [getSizeValue()](#getSizeValue--) | चार्ट डेटा पॉइंट का आकार मान लौटाता है। |
| [getColorValue()](#getColorValue--) | चार्ट डेटा पॉइंट का रंग मान लौटाता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम वैल्यू प्रकार के मामले में सीरिज एरर बार मानों का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | चार्ट डेटा पॉइंट का लेबल दर्शाता है। |
| [isBubble3D()](#isBubble3D--) | निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू है। |
| [getExplosion()](#getExplosion--) | पाई के केंद्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। |
| [setExplosion(int value)](#setExplosion-int-) | पाई के केंद्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। |
| [getMarker()](#getMarker--) | डेटा मार्कर निर्दिष्ट करता है। |
| [remove()](#remove--) | डेटा पॉइंट को चार्ट सीरिज से हटाता है। |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | सीरिज इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस सूची में से चार्ट प्रकार के लिए संबंधित लीजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा पॉइंट को कुल के रूप में सेट करता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट देगा, यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट देगा, यह निर्दिष्ट करता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) | निर्धारित करता है कि इस डेटा पॉइंट का लागू होना पैरेंट के चाइल्ड कलेक्शन में कौनसे पर है। |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```

चार्ट डेटा पॉइंट का x मान लौटाता है। केवल-पढ़ने योग्य [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**वापसी:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```

चार्ट डेटा पॉइंट का y मान लौटाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```

चार्ट डेटा पॉइंट का बबल आकार लौटाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```

चार्ट डेटा पॉइंट का मान लौटाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```

डेटा पॉइंट का आकार मान लौटाता है। ट्रीमैप और सनबर्स्ट चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```

डेटा पॉइंट का रंग मान लौटाता है। मैप चार्ट्स के साथ उपयोग किया जाता है। केवल-पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम वैल्यू प्रकार के मामले में सीरिज एरर बार मानों का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**वापसी:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```

चार्ट डेटा पॉइंट का लेबल दर्शाता है। केवल-पढ़ने योग्य [IDataLabel](../../com.aspose.slides/idatalabel).

**वापसी:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```

निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू है। पढ़ने/लिखने योग्य बूलियन.

**वापसी:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```

निर्दिष्ट करता है कि बबल्स पर 3-डी प्रभाव लागू है। पढ़ने/लिखने योग्य बूलियन.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

पाई के केंद्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य इंट।

**वापसी:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

पाई के केंद्र से डेटा पॉइंट को कितनी दूरी पर ले जाया जाएगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य इंट।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat).

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat).

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

डेटा मार्कर निर्दिष्ट करता है। केवल-पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker).

**वापसी:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```

डेटा पॉइंट को चार्ट सीरिज से हटाता है।

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```

सीरिज इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है।

**वापसी:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

इस सूची में से चार्ट प्रकार के लिए संबंधित लीजेंड एंट्री की प्रॉपर्टीज़: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie। केवल-पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**वापसी:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरिज प्रकार के लिए लागू।

**वापसी:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```

डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरिज प्रकार के लिए लागू।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन.

**वापसी:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक है तो डेटा पॉइंट अपने रंग उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन.

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```

डेटा पॉइंट लेवल्स का कंटेनर लौटाता है। ट्रीएम्प और सनबर्स्ट सीरिज के लिए लागू। डेटा पॉइंट लेवल्स का इंडेक्स शून्य-आधारित होता है।

**वापसी:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```

निर्धारित करता है कि इस डेटा पॉइंट का लागू होना पैरेंट के चाइल्ड कलेक्शन में कौनसे पर है। केवल-लॉन्ग पढ़ने योग्य।

**वापसी:**
long