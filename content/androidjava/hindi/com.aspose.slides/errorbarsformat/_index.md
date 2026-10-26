---
title: ErrorBarsFormat
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: चार्ट श्रृंखला के त्रुटि बार को दर्शाता है।
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

चार्ट श्रृंखला की त्रुटि बार को दर्शाता है। ErrorBars कस्टम मान IChartDataPointCollection में होते हैं ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) गुण में)।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | त्रुटि बार का प्रकार प्राप्त करता है या निर्धारित करता है। |
| [setType(int value)](#setType-int-) | त्रुटि बार का प्रकार प्राप्त करता है या निर्धारित करता है। |
| [getValueType()](#getValueType--) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। |
| [setValueType(int value)](#setValueType-int-) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। |
| [hasEndCap()](#hasEndCap--) | त्रुटि बार पर अंत कैप नहीं बनाया जाता, यह निर्दिष्ट करता है। |
| [setEndCap(boolean value)](#setEndCap-boolean-) | त्रुटि बार पर अंत कैप नहीं बनाया जाता, यह निर्दिष्ट करता है। |
| [getValue()](#getValue--) | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान प्राप्त करता है या निर्धारित करता है। |
| [setValue(float value)](#setValue-float-) | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान प्राप्त करता है या निर्धारित करता है। |
| [getFormat()](#getFormat--) | त्रुटि बार का फ़ॉर्मेट दर्शाता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | त्रुटि बार का फ़ॉर्मेट दर्शाता है। |
| [getChart()](#getChart--) | पैरेंट चार्ट लौटाता है। |
| [isVisible()](#isVisible--) | त्रुटि बार की दृश्यता प्राप्त करता है या निर्धारित करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | त्रुटि बार की दृश्यता प्राप्त करता है या निर्धारित करता है। |
| [getSlide()](#getSlide--) | FillFormat का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | FillFormat का पैरेंट प्रेज़ेंटेशन लौटाता है। |
### getType() {#getType--}
```
public final int getType()
```

त्रुटि बार का प्रकार प्राप्त करता है या निर्धारित करता है। पढ़ने/लिखने योग्य [ErrorBarType](../../com.aspose.slides/errorbartype)।

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

त्रुटि बार का प्रकार प्राप्त करता है या निर्धारित करता है। पढ़ने/लिखने योग्य [ErrorBarType](../../com.aspose.slides/errorbartype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public final int getValueType()
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) प्रॉपर्टी का उपयोग करें जो series के DataPoints कलेक्शन में विशिष्ट डेटा पॉइंट के लिए है। Fixed, Percentage या StandardDeviation वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिए Value प्रॉपर्टी का उपयोग करें। पढ़ने/लिखने योग्य [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**रिटर्न:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। कस्टम वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिये ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) प्रॉपर्टी का उपयोग करें जो series के DataPoints कलेक्शन में विशिष्ट डेटा पॉइंट के लिए है। Fixed, Percentage या StandardDeviation वैल्यू टाइप के मामले में मान निर्दिष्ट करने के लिये Value प्रॉपर्टी का उपयोग करें। पढ़ने/लिखने योग्य [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

त्रुटि बार पर अंत कैप नहीं बनाया जाता, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

त्रुटि बार पर अंत कैप नहीं बनाया जाता, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public final float getValue()
```

त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान प्राप्त करता है या निर्धारित करता है। अन्य किसी भी मामले में NaN लौटाएगा। पढ़ने/लिखने योग्य float।

**रिटर्न:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation वैल्यू टाइप के साथ उपयोग किया जाने वाला मान प्राप्त करता है या निर्धारित करता है। अन्य किसी भी मामले में NaN लौटाएगा। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

त्रुटि बार का फ़ॉर्मेट दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

त्रुटि बार का फ़ॉर्मेट दर्शाता है। पढ़ने/लिखने योग्य [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getChart() {#getChart--}
```
public final IChart getChart()
```

पैरेंट चार्ट लौटाता है। केवल पढ़ने योग्य [IChart](../../com.aspose.slides/ichart)।

**रिटर्न:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

त्रुटि बार की दृश्यता प्राप्त करता है या निर्धारित करता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

त्रुटि बार की दृश्यता प्राप्त करता है या निर्धारित करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**रिटर्न:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat का पैरेंट प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**रिटर्न:**
[IPresentation](../../com.aspose.slides/ipresentation)