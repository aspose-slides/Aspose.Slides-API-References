---
title: BaseSlideHeaderFooterManager
second_title: Android के लिए Aspose.Slides, Java API संदर्भ द्वारा
description: एक प्रबंधक का प्रतिनिधित्व करता है जो सभी स्लाइड प्रकारों के लिए फुटर, डेट-टाइम और पेज नंबर प्लेसहोल्डर्स के व्यवहार को धारण करता है।
type: docs
url: /hi/com.aspose.slides/baseslideheaderfootermanager/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager)  
```
public abstract class BaseSlideHeaderFooterManager extends BaseHeaderFooterManager
```

एक प्रबंधक को दर्शाता है जो सभी स्लाइड प्रकारों के लिए फुटर, डेट-टाइम, पेज नंबर प्लेसहोल्डर्स के व्यवहार को धारण करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | एक फुटर प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | एक पेज नंबर प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। |
| [isDateTimeVisible()](#isDateTimeVisible--) | एक डेट-टाइम प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | स्लाइड फुटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | स्लाइड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | स्लाइड फुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है। |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | स्लाइड डेट-टाइम प्लेसहोल्डर के लिए टेक्स्ट सेट करता है। |

### isFooterVisible() {#isFooterVisible--}
```
public final boolean isFooterVisible()
```

एक फुटर प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ें।

**वापसी मान:**  
boolean

### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public final boolean isSlideNumberVisible()
```

एक पेज नंबर प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ें।

**वापसी मान:**  
boolean

### isDateTimeVisible() {#isDateTimeVisible--}
```
public final boolean isDateTimeVisible()
```

एक डेट-टाइम प्लेसहोल्डर की उपस्थिति दर्शाने वाला मान प्राप्त करता है। बूलियन पढ़ें।

**वापसी मान:**  
boolean

### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public final void setFooterVisibility(boolean isVisible)
```

स्लाइड फुटर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक फुटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपाता है। |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public final void setSlideNumberVisibility(boolean isVisible)
```

स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपाता है। |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public final void setDateTimeVisibility(boolean isVisible)
```

स्लाइड डेट-टाइम प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - एक डेट-टाइम प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा - इसे छिपाता है। |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public final void setFooterText(String text)
```

स्लाइड फुटर प्लेसहोल्डर के लिए टेक्स्ट सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public final void setDateTimeText(String text)
```

स्लाइड डेट-टाइम प्लेसहोल्डर के लिए टेक्स्ट सेट करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |