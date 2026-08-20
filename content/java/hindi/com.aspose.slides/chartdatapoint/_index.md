---
title: ChartDataPoint
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: श्रृंखला डेटा बिंदु का प्रतिनिधित्व करता है।
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

श्रृंखला डेटा बिंदु का प्रतिनिधित्व करता है।
## विधियाँ

| Method | विवरण |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | चार्ट डेटा बिंदु का आकार मान लौटाता है। |
| [getColorValue()](#getColorValue--) | चार्ट डेटा बिंदु का रंग मान लौटाता है। |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | कस्टम मान प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | बबल्स पर 3-डी प्रभाव लागू होने को निर्दिष्ट करता है। |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | बबल्स पर 3-डी प्रभाव लागू होने को निर्दिष्ट करता है। |
| [getExplosion()](#getExplosion--) | पाई के केंद्र से डेटा बिंदु को स्थानांतरित करने की मात्रा निर्दिष्ट करता है। |
| [setExplosion(int value)](#setExplosion-int-) | पाई के केंद्र से डेटा बिंदु को स्थानांतरित करने की मात्रा निर्दिष्ट करता है। |
| [getFormat()](#getFormat--) | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। |
| [getMarker()](#getMarker--) | डेटा मार्कर को निर्दिष्ट करता है। |
| [getSetAsTotal()](#getSetAsTotal--) | डेटा बिंदु को कुल के रूप में सेट करता है। |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | डेटा बिंदु को कुल के रूप में सेट करता है। |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | इस सूची में से चार्ट प्रकार के लिए संबंधित लेजेंड एंट्री के गुण: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | चार्ट श्रृंखला से DataPoint को हटाता है। |
| [getDataPointLevels()](#getDataPointLevels--) | डेटा बिंदु स्तरों का कंटेनर लौटाता है। |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | श्रृंखला सूचकांक, डेटा बिंदु सूचकांक, ParentSeriesGroup.IsColorVaried गुण और चार्ट शैली के आधार पर डेटा बिंदु का स्वचालित रंग लौटाता है। |
| [getInvertIfNegative()](#getInvertIfNegative--) | यदि मान नकारात्मक है तो डेटा बिंदु अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | यदि मान नकारात्मक है तो डेटा बिंदु अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। |
| [getActualX()](#getActualX--) | चार्ट तत्व की वास्तविक X स्थिति (बाएँ) को चार्ट के बाएँ-ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualY()](#getActualY--) | चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ-ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। |
| [getActualWidth()](#getActualWidth--) | चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। |
| [getActualHeight()](#getActualHeight--) | चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। |

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

चार्ट डेटा बिंदु का आकार मान लौटाता है। Treemap और Sunburst चार्ट में उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

चार्ट डेटा बिंदु का रंग मान लौटाता है। Map चार्ट में उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**वापसी:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

कस्टम मान प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

बबल्स पर 3-डी प्रभाव लागू होने को निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

बबल्स पर 3-डी प्रभाव लागू होने को निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

पाई के केंद्र से डेटा बिंदु को स्थानांतरित करने की मात्रा निर्दिष्ट करता है। पढ़ने/लिखने योग्य इंट।

**वापसी:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

पाई के केंद्र से डेटा बिंदु को स्थानांतरित करने की मात्रा निर्दिष्ट करता है। पढ़ने/लिखने योग्य इंट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**वापसी:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

डेटा मार्कर को निर्दिष्ट करता है। केवल पढ़ने योग्य [IMarker](../../com.aspose.slides/imarker)।

**वापसी:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

डेटा बिंदु को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू।

**वापसी:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

डेटा बिंदु को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

इस सूची में से चार्ट प्रकार के लिए संबंधित लेजेंड एंट्री के गुण: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. केवल पढ़ने योग्य [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)।

**वापसी:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```

चार्ट श्रृंखला से DataPoint को हटाता है।

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

डेटा बिंदु स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखला के लिए लागू। डेटा बिंदु स्तरों का अनुक्रमण शून्य-आधारित है।

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
public final Color getAutomaticDataPointColor()
```

श्रृंखला सूचकांक, डेटा बिंदु सूचकांक, ParentSeriesGroup.IsColorVaried गुण और चार्ट शैली के आधार पर डेटा बिंदु का स्वचालित रंग लौटाता है। यदि FillType NotDefined है तो यह डिफ़ॉल्ट रूप से उपयोग होता है।

**वापसी:**
java.awt.Color
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

यदि मान नकारात्मक है तो डेटा बिंदु अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**वापसी:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

यदि मान नकारात्मक है तो डेटा बिंदु अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```

चार्ट तत्व की वास्तविक X स्थिति (बाएँ) को चार्ट के बाएँ-ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() को पहले कॉल करें। पढ़ने योग्य फ्लोट।

**वापसी:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```

चार्ट तत्व के वास्तविक शीर्ष को चार्ट के बाएँ-ऊपरी कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() को पहले कॉल करें। पढ़ने योग्य फ्लोट।

**वापसी:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

चार्ट तत्व की वास्तविक चौड़ाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() को पहले कॉल करें। पढ़ने योग्य फ्लोट।

**वापसी:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

चार्ट तत्व की वास्तविक ऊँचाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए IChart.ValidateChartLayout() को पहले कॉल करें। पढ़ने योग्य फ्लोट।

**वापसी:**
float