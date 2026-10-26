---
title: BaseSlideHeaderFooterManager
second_title: Aspose.Slides for Java API संदर्भ
description: सभी स्लाइड प्रकारों के लिए फुटर, तारीख-समय और पेज नंबर प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/baseslideheaderfootermanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

सभी स्लाइड प्रकारों के लिए फुटर, तारीख-समय, पेज नंबर प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | फ़ुटर प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | पेज नंबर प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। |
| [isDateTimeVisible()](#isDateTimeVisible--) | तारीख-समय प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | स्लाइड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | स्लाइड तारीख-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | स्लाइड फ़ुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है। |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | स्लाइड तारीख-समय प्लेसहोल्डर के लिए टेक्स्ट सेट करता है। |
### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

फ़ुटर प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ता है।

**रिटर्न:**  
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

पेज नंबर प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ता है।

**रिटर्न:**  
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

तारीख-समय प्लेसहोल्डर मौजूद है यह दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ता है।

**रिटर्न:**  
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

स्लाइड फ़ुटर प्लेसहोल्डर की दृश्यता बदलता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ुटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपा देता है। |
### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपा देता है। |
### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

स्लाइड तारीख-समय प्लेसहोल्डर की दृश्यता बदलता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - तारीख-समय प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपा देता है। |
### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

स्लाइड फ़ुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |
### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

स्लाइड तारीख-समय प्लेसहोल्डर के लिए टेक्स्ट सेट करता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिये टेक्स्ट। |