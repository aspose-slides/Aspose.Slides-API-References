---
title: ErrorBarsFormat
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: चार्ट श्रृंखला के त्रुटि बार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/errorbarsformat/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)  
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

चार्ट श्रृंखला के त्रुटि बार का प्रतिनिधित्व करता है। ErrorBars कस्टम मान IChartDataPointCollection ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) प्रॉपर्टी में होते हैं।

## मेथड्स

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। |
| [setType(int value)](#setType-int-) | त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। |
| [getValueType()](#getValueType--) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीके का प्रतिनिधित्व करता है। |
| [setValueType(int value)](#setValueType-int-) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीके का प्रतिनिधित्व करता है। |
| [hasEndCap()](#hasEndCap--) | निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं खींचा जाता है। |
| [setEndCap(boolean value)](#setEndCap-boolean-) | निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं खींचा जाता है। |
| [getValue()](#getValue--) | वह मान प्राप्त करता है या सेट करता है जिसका उपयोग Fixed, Percentage और StandardDeviation मान प्रकारों के साथ त्रुटि बार की लंबाई निर्धारित करने के लिए किया जाता है। |
| [setValue(float value)](#setValue-float-) | वह मान प्राप्त करता है या सेट करता है जिसका उपयोग Fixed, Percentage और StandardDeviation मान प्रकारों के साथ त्रुटि बार की लंबाई निर्धारित करने के लिए किया जाता है। |
| [getFormat()](#getFormat--) | त्रुटि बार के स्वरूप का प्रतिनिधित्व करता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | त्रुटि बार के स्वरूप का प्रतिनिधित्व करता है। |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [isVisible()](#isVisible--) | त्रुटि बार की दृश्यमानता को प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | त्रुटि बार की दृश्यमानता को प्राप्त करता है या सेट करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रस्तुति लौटाता है। |

### getType() {#getType--}
```
public final int getType()
```

त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ErrorBarType](../../com.aspose.slides/errorbartype)।

**रिटर्न:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ErrorBarType](../../com.aspose.slides/errorbartype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीके का प्रतिनिधित्व करता है। कस्टम मान प्रकार के मामले में, मान निर्दिष्ट करने के लिए श्रृंखला के DataPoints संग्रह में विशिष्ट डेटा बिंदु की ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) प्रॉपर्टी का उपयोग करें। Fixed, Percentage या StandardDeviation मान प्रकार के मामले में, मान निर्दिष्ट करने के लिए Value प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**रिटर्न:**
int

### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीके का प्रतिनिधित्व करता है। कस्टम मान प्रकार के मामले में, मान निर्दिष्ट करने के लिए श्रृंखला के DataPoints संग्रह में विशिष्ट डेटा बिंदु की ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) प्रॉपर्टी का उपयोग करें। Fixed, Percentage या StandardDeviation मान प्रकार के मामले में, मान निर्दिष्ट करने के लिए Value प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं खींचा जाता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं खींचा जाता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है ताकि त्रुटि बार की लंबाई निर्धारित हो सके। अन्य सभी मामलों में NaN लौटाता है। पढ़ें/लिखें float।

**रिटर्न:**
float

### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है ताकि त्रुटि बार की लंबाई निर्धारित हो सके। अन्य सभी मामलों में NaN लौटाता है। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

त्रुटि बार के स्वरूप का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

त्रुटि बार के स्वरूप का प्रतिनिधित्व करता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

त्रुटि बार की दृश्यमानता को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

त्रुटि बार की दृश्यमानता को प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)