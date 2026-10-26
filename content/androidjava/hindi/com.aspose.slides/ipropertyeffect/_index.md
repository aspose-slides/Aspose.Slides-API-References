---
title: IPropertyEffect
second_title: Java API संदर्भ के माध्यम से Android के लिए Aspose.Slides
description: प्रॉपर्टी इफ़ेक्ट व्यवहार का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ipropertyeffect/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

प्रॉपर्टी प्रभाव व्यवहार का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFrom()](#getFrom--) | एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। |
| [setFrom(String value)](#setFrom-java.lang.String-) | एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। |
| [getTo()](#getTo--) | एनिमेशन के समाप्ति मान को निर्दिष्ट करता है। |
| [setTo(String value)](#setTo-java.lang.String-) | एनिमेशन के समाप्ति मान को निर्दिष्ट करता है। |
| [getBy()](#getBy--) | एनिमेशन शुरू होने से पहले उसकी स्थिति के सापेक्ष एक सापेक्ष ऑफ़सेट मान को निर्दिष्ट करता है। |
| [setBy(String value)](#setBy-java.lang.String-) | एनिमेशन शुरू होने से पहले उसकी स्थिति के सापेक्ष एक सापेक्ष ऑफ़सेट मान को निर्दिष्ट करता है। |
| [getValueType()](#getValueType--) | प्रॉपर्टी मान के प्रकार को निर्दिष्ट करता है। |
| [setValueType(int value)](#setValueType-int-) | प्रॉपर्टी मान के प्रकार को निर्दिष्ट करता है। |
| [getCalcMode()](#getCalcMode--) | एनिमेशन के लिए इंटरपोलेशन मोड को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | एनिमेशन के लिए इंटरपोलेशन मोड को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | एनिमेशन के बिंदुओं को निर्दिष्ट करता है। |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | एनिमेशन के बिंदुओं को निर्दिष्ट करता है। |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

एनिमेशन का प्रारंभिक मान निर्दिष्ट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getTo() {#getTo--}
```
public abstract String getTo()
```

एनिमेशन के समाप्ति मान को निर्दिष्ट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

एनिमेशन के समाप्ति मान को निर्दिष्ट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getBy() {#getBy--}
```
public abstract String getBy()
```

एनिमेशन शुरू होने से पहले उसकी स्थिति के सापेक्ष एक सापेक्ष ऑफ़सेट मान को निर्दिष्ट करता है। पढ़ें/लिखें String.

**वापसी:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

एनिमेशन शुरू होने से पहले उसकी स्थिति के सापेक्ष एक सापेक्ष ऑफ़सेट मान को निर्दिष्ट करता है। पढ़ें/लिखें String.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

प्रॉपर्टी मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**वापसी:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

प्रॉपर्टी मान के प्रकार को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

एनिमेशन के लिए इंटरपोलेशन मोड को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**वापसी:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

एनिमेशन के लिए इंटरपोलेशन मोड को निर्दिष्ट करता है। पढ़ें/लिखें [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

एनिमेशन के बिंदुओं को निर्दिष्ट करता है। पढ़ें/लिखें [IPointCollection](../../com.aspose.slides/ipointcollection).

**वापसी:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

एनिमेशन के बिंदुओं को निर्दिष्ट करता है। पढ़ें/लिखें [IPointCollection](../../com.aspose.slides/ipointcollection).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |