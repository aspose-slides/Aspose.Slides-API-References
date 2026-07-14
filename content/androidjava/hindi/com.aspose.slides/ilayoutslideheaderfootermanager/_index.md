---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: लेआउट स्लाइड फ़ूटर, तिथि-समय, पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले प्रबंधक को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

लेआउट स्लाइड फ़ूटर, तिथि-समय, पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड प्लेसहोल्डर के व्यवहार को धारण करने वाले मैनेजर को दर्शाता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | लेआउट स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर में टेक्स्ट सेट करता है। |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें मास्टर स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - फ़ूटर प्लेसहोल्डर को दिखाई देता है, अन्यथा उन्हें छिपा देता है। |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

लेआउट स्लाइड पृष्ठ संख्या प्लेसहोल्डर और सभी चाइल्ड पृष्ठ संख्या प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - पृष्ठ संख्या प्लेसहोल्डर को दिखाई देता है, अन्यथा उन्हें छिपा देता है। |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर की दृश्यता बदलता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| isVisible | boolean | true - तिथि-समय प्लेसहोल्डर को दिखाई देता है, अन्यथा उन्हें छिपा देता है। |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

लेआउट स्लाइड फ़ूटर प्लेसहोल्डर और सभी चाइल्ड फ़ूटर प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

लेआउट स्लाइड तिथि-समय प्लेसहोल्डर और सभी चाइल्ड तिथि-समय प्लेसहोल्डर में टेक्स्ट सेट करता है। चाइल्ड प्लेसहोल्डर का अर्थ है कि प्लेसहोल्डर निर्भर स्लाइडों में समाहित होते हैं। निर्भर स्लाइडें लेआउट स्लाइड का उपयोग करती हैं और उस पर निर्भर होती हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | सेट करने के लिए टेक्स्ट। |