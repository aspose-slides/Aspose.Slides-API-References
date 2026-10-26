---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: सभी स्लाइड प्रकारों के लिए फ़ुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर के व्यवहार को रखने वाले प्रबंधक का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibaseslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

एक प्रबंधक का प्रतिनिधित्व करता है जो सभी स्लाइड प्रकारों के लिए फ़ुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर के व्यवहार को रखता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | एक मान प्राप्त करता है जो दर्शाता है कि फ़ुटर प्लेसहोल्डर मौजूद है। |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | एक मान प्राप्त करता है जो दर्शाता है कि पेज नंबर प्लेसहोल्डर मौजूद है। |
| [isDateTimeVisible()](#isDateTimeVisible--) | एक मान प्राप्त करता है जो दर्शाता है कि डेट-टाइम प्लेसहोल्डर मौजूद है। |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | स्लाइड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | स्लाइड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | स्लाइड फ़ुटर प्लेसहोल्डर में पाठ सेट करता है। |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | स्लाइड डेट-टाइम प्लेसहोल्डर में पाठ सेट करता है। |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

एक मान प्राप्त करता है जो दर्शाता है कि फ़ुटर प्लेसहोल्डर मौजूद है। बूलियन पढ़ें।

**रिटर्न:**  
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

एक मान प्राप्त करता है जो दर्शाता है कि पेज नंबर प्लेसहोल्डर मौजूद है। बूलियन पढ़ें।

**रिटर्न:**  
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

एक मान प्राप्त करता है जो दर्शाता है कि डेट-टाइम प्लेसहोल्डर मौजूद है। बूलियन पढ़ें।

**रिटर्न:**  
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

स्लाइड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक फ़ुटर प्लेसहोल्डर को दृश्य बनाता है, अन्यथा - इसे छिपाता है। |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक पेज नंबर प्लेसहोल्डर को दृश्य बनाता है, अन्यथा - इसे छिपाता है। |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

स्लाइड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक डेट-टाइम प्लेसहोल्डर को दृश्य बनाता है, अन्यथा - इसे छिपाता है। |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

स्लाइड फ़ुटर प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

स्लाइड डेट-टाइम प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |