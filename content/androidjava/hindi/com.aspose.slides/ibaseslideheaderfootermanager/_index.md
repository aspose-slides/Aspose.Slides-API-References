---
title: IBaseSlideHeaderFooterManager
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सभी स्लाइड प्रकारों के फ़ूटर, तिथि-समय और पेज नंबर प्लेसहोल्डर के व्यवहार को रखने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ibaseslideheaderfootermanager/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IBaseSlideHeaderFooterManager extends IBaseHeaderFooterManager
```

सभी स्लाइड प्रकारों के फ़ूटर, तिथि-समय और पेज नंबर प्लेसहोल्डर के व्यवहार को रखे हुए प्रबंधक को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isFooterVisible()](#isFooterVisible--) | एक फ़ूटर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। |
| [isSlideNumberVisible()](#isSlideNumberVisible--) | एक पेज नंबर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। |
| [isDateTimeVisible()](#isDateTimeVisible--) | एक तिथि-समय प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। |
| [setFooterVisibility(boolean isVisible)](#setFooterVisibility-boolean-) | स्लाइड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberVisibility(boolean isVisible)](#setSlideNumberVisibility-boolean-) | स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeVisibility(boolean isVisible)](#setDateTimeVisibility-boolean-) | स्लाइड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterText(String text)](#setFooterText-java.lang.String-) | स्लाइड फ़ूटर प्लेसहोल्डर में पाठ सेट करता है। |
| [setDateTimeText(String text)](#setDateTimeText-java.lang.String-) | स्लाइड तिथि-समय प्लेसहोल्डर में पाठ सेट करता है। |
### isFooterVisible() {#isFooterVisible--}
```
public abstract boolean isFooterVisible()
```

फ़ूटर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें boolean।

**वापसी मान:**
boolean
### isSlideNumberVisible() {#isSlideNumberVisible--}
```
public abstract boolean isSlideNumberVisible()
```

पेज नंबर प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें boolean.

**वापसी मान:**
boolean
### isDateTimeVisible() {#isDateTimeVisible--}
```
public abstract boolean isDateTimeVisible()
```

तिथि-समय प्लेसहोल्डर मौजूद होने को दर्शाने वाला मान प्राप्त करता है। पढ़ें boolean.

**वापसी मान:**
boolean
### setFooterVisibility(boolean isVisible) {#setFooterVisibility-boolean-}
```
public abstract void setFooterVisibility(boolean isVisible)
```

स्लाइड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ूटर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा इसे छुपाता है। |

### setSlideNumberVisibility(boolean isVisible) {#setSlideNumberVisibility-boolean-}
```
public abstract void setSlideNumberVisibility(boolean isVisible)
```

स्लाइड पेज नंबर प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पेज नंबर प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा इसे छुपाता है। |

### setDateTimeVisibility(boolean isVisible) {#setDateTimeVisibility-boolean-}
```
public abstract void setDateTimeVisibility(boolean isVisible)
```

स्लाइड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - तिथि-समय प्लेसहोल्डर को दृश्यमान बनाता है, अन्यथा इसे छुपाता है। |

### setFooterText(String text) {#setFooterText-java.lang.String-}
```
public abstract void setFooterText(String text)
```

स्लाइड फ़ूटर प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |

### setDateTimeText(String text) {#setDateTimeText-java.lang.String-}
```
public abstract void setDateTimeText(String text)
```

स्लाइड तिथि-समय प्लेसहोल्डर में पाठ सेट करता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए पाठ। |