---
title: IErrorBarsFormat
second_title: Aspose.Slides for Java API संदर्भ
description: चार्ट श्रृंखला के त्रुटि बार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

चार्ट श्रृंखला के त्रुटि बार को दर्शाता है। ErrorBars के कस्टम मान IChartDataPointCollection में होते हैं ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी में)।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getType()](#getType--) | त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। |
| [setType(int value)](#setType-int-) | त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। |
| [getValueType()](#getValueType--) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। |
| [setValueType(int value)](#setValueType-int-) | त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। |
| [hasEndCap()](#hasEndCap--) | निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं बनाया जाता है। |
| [setEndCap(boolean value)](#setEndCap-boolean-) | निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं बनाया जाता है। |
| [getValue()](#getValue--) | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है। |
| [setValue(float value)](#setValue-float-) | त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है। |
| [getFormat()](#getFormat--) | त्रुटि बार का फ़ॉर्मेट दर्शाता है। |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | त्रुटि बार का फ़ॉर्मेट दर्शाता है। |
| [isVisible()](#isVisible--) | त्रुटि बार की दृश्यता प्राप्त करता है या सेट करता है। |
| [setVisible(boolean value)](#setVisible-boolean-) | त्रुटि बार की दृश्यता प्राप्त करता है या सेट करता है। |
### getType() {#getType--}
```
public abstract int getType()
```

त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ErrorBarType](../../com.aspose.slides/errorbartype)।

**रिटर्न:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

त्रुटि बार का प्रकार प्राप्त करता है या सेट करता है। पढ़ें/लिखें [ErrorBarType](../../com.aspose.slides/errorbartype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। यदि कस्टम वैल्यू टाइप हो तो मान निर्धारित करने के लिए श्रृंखला के DataPoints संग्रह में विशिष्ट डेटा पॉइंट की [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**रिटर्न:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

त्रुटि बार की लंबाई निर्धारित करने के संभावित तरीकों को दर्शाता है। यदि कस्टम वैल्यू टाइप हो तो मान निर्धारित करने के लिए श्रृंखला के DataPoints संग्रह में विशिष्ट डेटा पॉइंट की [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं बनाया जाता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

निर्दिष्ट करता है कि त्रुटि बार पर अंत कैप नहीं बनाया जाता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getValue() {#getValue--}
```
public abstract float getValue()
```

त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

**रिटर्न:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

त्रुटि बार की लंबाई निर्धारित करने के लिए Fixed, Percentage और StandardDeviation मान प्रकारों के साथ उपयोग किए जाने वाले मान को प्राप्त करता है या सेट करता है। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

त्रुटि बार का फ़ॉर्मेट दर्शाता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

**रिटर्न:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

त्रुटि बार का फ़ॉर्मेट दर्शाता है। पढ़ें/लिखें [IFormat](../../com.aspose.slides/iformat)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

त्रुटि बार की दृश्यता प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

**रिटर्न:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

त्रुटि बार की दृश्यता प्राप्त करता है या सेट करता है। पढ़ें/लिखें boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |